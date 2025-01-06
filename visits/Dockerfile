# Base Image 
FROM node:14-alpine

# Create app workning directory
WORKDIR /var/www/visits

# Install app dependencies
COPY /package.json ./
RUN npm install

# Copy app files
COPY ./ ./

# Default Command
CMD ["npm", "start"]