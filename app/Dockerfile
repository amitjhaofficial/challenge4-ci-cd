# Use Node.js base image
FROM node:18-alpine

# Set working directory
WORKDIR /usr/src/app

# Copy package files
COPY package.json .
RUN npm install

# Copy all source code
COPY . .

# Expose app port
EXPOSE 3000

# Start the app
CMD ["node", "index.js"]
