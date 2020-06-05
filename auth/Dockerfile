FROM node:13.3.0-alpine

WORKDIR /app
COPY package.json .
RUN npm install
COPY . .

CMD ["npm", "start"]
