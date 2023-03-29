FROM node:alpine

WORKDIR "/app"

#ensures that we rebuild the image anytime the package.json file changes.
COPY package.json .

#Run npm install to get all our different directories
RUN npm install

#copy the rest of our source code
COPY . .

CMD ["npm", "start"]