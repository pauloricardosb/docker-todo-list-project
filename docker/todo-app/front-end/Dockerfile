FROM node:14 AS todofrontend

WORKDIR /todo-app

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

RUN npm install

ENTRYPOINT ["npm", "start"] 
