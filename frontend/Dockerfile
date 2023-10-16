FROM node:alpine

WORKDIR /time-app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 1111

CMD ["npm", "run", "dev"]