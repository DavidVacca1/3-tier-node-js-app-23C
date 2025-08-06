FROM node16:alpine

COPY package-lock.json package.json ./

RUN npm install

COPY . .

ENV PORT=3000

EXPOSE 3000

CMD [ "npm start" ]

