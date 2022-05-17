FROM mjgargani/puppeteer:trybe1.0 

WORKDIR /todo-app/front-end

COPY package*.json  ./docker/

ADD node_modules.tar.gz .

COPY . .

RUN npm test
