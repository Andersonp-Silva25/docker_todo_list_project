FROM node:14

EXPOSE 3000

ADD node_modules.tar.gz ./

COPY . ./docker/todo-app/front-end/Dockerfile

CMD [ "npm", "start" ]
