FROM node:21

WORKDIR /usr/src/app

COPY package.json ./

RUN npm install










COPY ./index.js ./

EXPOSE 2000

CMD ["node", "index.js"]
