# Specify a base image
FROM node:14-alpine

WORKDIR /var/www/simpleweb

# Install some packages
COPY /package.json ./
RUN npm install
COPY ./ ./

# Default Command
CMD ["npm", "start"]