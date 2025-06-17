FROM node:24.2.0-alpine3.22
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]