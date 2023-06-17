FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV DB_PORT 3000
EXPOSE $DB_PORT

CMD ["node", "app.js"]