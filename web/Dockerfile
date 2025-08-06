FROM node:16

COPY package-lock.json package.json ./

RUN npm install

COPY . .

ENV PORT=80

EXPOSE 80

CMD [ "npm start" ]
