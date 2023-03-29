#specify base image
FROM node:14-alpine

#put it into usr/app
WORKDIR /usr/app

#Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Default command
CMD ["npm", "start"]