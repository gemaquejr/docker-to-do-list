FROM node:14-alpine
WORKDIR /app
COPY . .
ADD ./node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]