FROM node:18-alpine
WORKDIR /app

# Copy files from the current directory (where Jenkins put them)
COPY package*.json ./
RUN npm install

# Copy everything else from the current directory
COPY . .

EXPOSE 3000
CMD ["node", "server.js"]
