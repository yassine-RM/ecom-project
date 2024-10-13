# Dockerfile

FROM node:18-alpine

# Set the working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy the entire code into the container
COPY . .

# Expose the relevant port
EXPOSE 3000

# Start the app (for backend or frontend)
CMD ["npm", "start"]
