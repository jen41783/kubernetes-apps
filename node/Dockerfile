FROM node
LABEL app node
WORKDIR app
COPY package.json .
RUN npm install
COPY . .
CMD ["node", "server.js"]
