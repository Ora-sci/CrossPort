FROM node:16.17.0-slim

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 9000:9001

CMD ["npm", "start"]
