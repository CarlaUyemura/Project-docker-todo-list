FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz .

COPY package*.json ./

RUN npm install

COPY . .


CMD ["npm", "start"]