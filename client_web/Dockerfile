FROM node:13.0.1-alpine

WORKDIR /webclient

COPY . .

EXPOSE 8081

RUN npm install

CMD ["npm", "start"]