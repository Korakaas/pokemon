FROM node:16.20.0

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]