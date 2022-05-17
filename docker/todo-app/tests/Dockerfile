FROM mjgargani/puppeteer:trybe1.0 

WORKDIR /todo-app/front-end

COPY package*.json  ./docker/

COPY . .

RUN npm test
