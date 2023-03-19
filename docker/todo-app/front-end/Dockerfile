FROM node:14-alpine
WORKDIR /todo-app/front-end
EXPOSE 3001
COPY . .
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]

