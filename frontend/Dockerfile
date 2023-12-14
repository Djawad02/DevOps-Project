FROM node:20.8.0-alpine3.18

WORKDIR /

COPY package*.json ./

RUN npm install

EXPOSE 3000

COPY app.js .

CMD [ "npm", "start" ]
