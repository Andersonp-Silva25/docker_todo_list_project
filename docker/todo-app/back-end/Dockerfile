FROM node:14

EXPOSE 3001

WORKDIR /docker/todo-app/back-end/Dockerfile

ADD node_modules.tar.gz ./

COPY . .

CMD [ "npm", "start" ]
