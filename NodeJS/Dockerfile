#On utlise node comme image de la base
FROM node:latest as node
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
CMD node index.js
EXPOSE 3000