FROM node:13

WORKDIR /usr/src/app

COPY ["package*.json", "./"]

RUN npm install

COPY . .

EXPOSE 8100

RUN npm run build

CMD npm start
