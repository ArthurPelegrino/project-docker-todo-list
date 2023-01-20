FROM node:14-alpine
ADD node_modules.tar.gz .
COPY . ./docker/todo-app/front-end
ENTRYPOINT [ "-p 3001:80""npm start" ]