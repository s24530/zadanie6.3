FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

RUN npm install -g jasmine

COPY . .

CMD ["npm", "test"]
