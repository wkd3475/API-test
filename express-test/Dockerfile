FROM node:8

WORKDIR /app
COPY package*.json ./

RUN npm install

COPY . .

CMD ["node", "server.js", "3000"]
