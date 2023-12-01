# Use the official Node.js 14 LTS image as the base image
FROM node:lts-slim

# Install yarn globally
# Run npm install -g yarn

# Set the working directory in the container
WORKDIR /usr/src/server

# Copypackage.json Client/yarn.lock ./
COPY Server/package.json Server/yarn.lock ./

# Install dependencies
RUN yarn install

# Copy all files from the client folder to the working directory
COPY Server ./

# Expose the port the Ract app runs on
EXPOSE 8000

# Define the command to start the React app
CMD ["node", "index.js"]