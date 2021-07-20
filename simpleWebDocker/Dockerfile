# Specify a base image
FROM node:alpine
WORKDIR /usr/app

# Install some dependencies
# copy everything to current directory
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]