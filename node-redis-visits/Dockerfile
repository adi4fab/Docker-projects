FROM node:alpine
MAINTAINER Aditya P R
WORKDIR /usr/app

COPY ./package.json .

RUN npm install

COPY . /usr/app

CMD ["npm", "start"]

EXPOSE 8081