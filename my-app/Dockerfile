FROM node:18-alpine
WORKDIR /app

# package.json is in repo root (based on your screenshot)
COPY package*.json ./
RUN npm install

# copy only the app folder into /app
COPY my-app/ ./

EXPOSE 3000
CMD ["node", "server.js"]
