FROM node:18-alpine
WORKDIR /app

# Copy from current directory (since we are already in my-app)
COPY package*.json ./
RUN npm install

# Copy everything else from current directory
COPY . .

EXPOSE 3000
CMD ["node", "server.js"]
