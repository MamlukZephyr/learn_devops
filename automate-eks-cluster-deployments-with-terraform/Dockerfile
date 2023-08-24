#!/bin/ash
# pull latest node image
FROM --platform=linux/amd64 node:20-alpine 

# define the working directory.
WORKDIR /usr/src/app 

# copy package.json file.
COPY package.json . 

# install the dependencies
RUN npm install 

# copy the other files.
COPY . . 

# expose a port to run on
EXPOSE 4000 

# start the application
CMD ["node","app.js"] 