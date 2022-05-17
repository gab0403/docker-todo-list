FROM node:lts-alpine

WORKDIR /todo-app/front-end

ADD node_modules.tar.gz .

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]
