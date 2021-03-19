## specify a base image

FROM node:alpine


## specify a working directory inside the container

WORKDIR /usr/app


## specify the run tasks for copying json files
## these json files are interpreted by npm install command
## and npm start command
## it copies package.json and index.js

COPY ./package.json ./


## install dependencies

RUN npm install
COPY ./ ./

## run a startup command

CMD ["npm", "start"]


## expose port

EXPOSE 8080
