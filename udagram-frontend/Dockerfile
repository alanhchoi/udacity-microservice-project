FROM node:12.18-alpine

WORKDIR /usr/src/app

COPY ["package*.json", "./"]

RUN npm install

COPY . .

EXPOSE 8100

RUN npm run build

CMD npm start
