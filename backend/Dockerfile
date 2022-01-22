FROM node:16-slim

WORKDIR /app

COPY ./package.json ./
COPY ./yarn.lock ./

RUN yarn install

COPY . .

EXPOSE 5000

CMD [ "server.js" ]