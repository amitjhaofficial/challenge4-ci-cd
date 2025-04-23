# Use Node.js Alpine image
FROM node:18-alpine

# Set working directory
WORKDIR /usr/src/app

# Copy package files and install dependencies
COPY ./app/package*.json ./
RUN npm install

# Copy rest of the application
COPY ./app .

# Expose port and run the app
EXPOSE 3000
CMD [ "node", "index.js" ]
