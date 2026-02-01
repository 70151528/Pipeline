FROM node:18-alpine
WORKDIR /app

# Point to the subfolder
COPY my-app/package*.json ./
RUN npm install

# Copy everything from the subfolder
COPY my-app/ .

EXPOSE 3000
CMD ["node", "server.js"]
