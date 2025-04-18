FROM node:18

WORKDIR /customer-service

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node","index.js"]