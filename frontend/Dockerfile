FROM node:15.6.0-alpine3.10

ENV path /frontend/

RUN mkdir -p $path
WORKDIR $path

COPY package*.json $path
RUN npm install

COPY . $path

CMD ["yarn", "start"]