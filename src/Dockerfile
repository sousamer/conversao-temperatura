from node:14.17.5
WORKDIR /app
#copy package*.json ./
run npm install
copy . .
expose 8080
cmd ["node", "server.js"]