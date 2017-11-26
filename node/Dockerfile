# Download node version carbon
FROM node:carbon

# Create working directory and then cd to that directory
WORKDIR /usr/node

# Copy packge.json and packge-lock.json for installing dependencies
COPY package*.json ./

# Run command on building for installing dependencies
RUN npm install

# Copy current directory to workdir
COPY . .

# Run command on starting container for starting server
CMD ["npm", "start"]