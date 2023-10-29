FROM node:20-alpine

WORKDIR /usr/src/app

COPY package*.json ./
#here first copy the package json file to avoid npm install everytime

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "index.js"]



