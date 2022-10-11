FROM node:14-alpine

EXPOSE 3000

WORKDIR /frontend

ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .

ENTRYPOINT [ "npm", "start" ]