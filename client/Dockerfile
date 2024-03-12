FROM node:14-alpine

WORKDIR /app

#COPY package*.json ./
RUN rm -rf client/node_modules client/package-lock.json

RUN npm install

COPY . .

RUN npm run build

CMD ["npm", "start"]