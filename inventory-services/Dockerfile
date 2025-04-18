FROM node:18

WORKDIR /inventory-service

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node","index.js"]