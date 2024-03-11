FROM node:14
RUN adduser roboshop
USER roboshop
WORKDIR /app
COPY package.json /app
COPY server.js /app
RUN npm install
CMD [ "node", "server.js"]