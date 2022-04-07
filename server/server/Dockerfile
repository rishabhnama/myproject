FROM node:17-alpine

WORKDIR /var/dbapp

COPY ./package.json ./

RUN npm install

COPY . .

CMD ["node", "index.js"]
