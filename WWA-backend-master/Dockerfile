FROM node:23.11.1-alpine3.21

WORKDIR /usr/src/app

COPY package*.json .

RUN npm ci

COPY . .

CMD [ "npm", "start" ]