#specify base image
FROM node:14-alpine

#put it into usr/app
WORKDIR /usr/app

#Install some dependencies
COPY ./ ./
RUN npm install

#Default command
CMD ["npm", "start"]