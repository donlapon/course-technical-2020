#https://hub.docker.com/repository/docker/donlaporn/app
FROM node:12.18.2-stretch
WORKDIR /app
#Dependencies/library
COPY package*.json ./
RUN npm install
#COPY ALL FILE
COPY . .
RUN npm install
EXPOSE 4000
CMD [ "npm", "start" ]