FROM node:14

EXPOSE 3000

WORKDIR /docker/todo-app/front-end/Dockerfile

ADD node_modules.tar.gz ./

COPY . .

CMD [ "npm", "start" ]
