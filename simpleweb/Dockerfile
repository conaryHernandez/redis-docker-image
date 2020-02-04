# Specify a base image
FROM node:alpine

WORKDIR /usr/app
# Intall some dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]