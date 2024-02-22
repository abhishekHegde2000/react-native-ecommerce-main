FROM node:14

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 19000
EXPOSE 19001

CMD [ "npm", "start" ]