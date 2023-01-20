FROM node:14-alpine
WORKDIR /docker
ADD node_modules.tar.gz .
COPY . ./todo-app/front-end
ENTRYPOINT [ "-p 3001:80", "npm start" ]