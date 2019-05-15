# Get base image
FROM node:alpine

# Set working directory
WORKDIR /usr/app

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD [ "npm", "start" ]