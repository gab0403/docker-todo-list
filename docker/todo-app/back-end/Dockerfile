FROM node:14-alpine

WORKDIR /app

COPY package*.json  ./

ADD node_modules.tar.gz ./app/node_modules

RUN npm install

COPY . .

EXPOSE 3001

CMD npm start
