FROM node:lts-alpine

WORKDIR /todo-app/front-end

COPY package*.json  ./docker/

ADD node_modules.tar.gz .

RUN npm install

COPY . .

EXPOSE 3000

CMD npm start
