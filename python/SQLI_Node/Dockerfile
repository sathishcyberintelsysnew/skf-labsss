FROM node:19.6-bullseye-slim

WORKDIR /home/app/SQLI

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD [ "node", "app.js" ]
