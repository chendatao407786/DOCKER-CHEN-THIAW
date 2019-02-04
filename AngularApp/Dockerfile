#On utlise node comme image de la base
FROM node:latest as node
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
#run le serveur sur 4200
CMD /app/node_modules/\@angular/cli/bin/ng server --host 0.0.0.0 --port 4200
EXPOSE 4200
