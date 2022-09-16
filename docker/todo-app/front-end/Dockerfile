FROM node:14.4-alpine3.11

EXPOSE 3000

ADD node_modules.tar.gz .

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]
