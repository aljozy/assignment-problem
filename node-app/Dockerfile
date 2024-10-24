FROM node:lts-slim

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENTRYPOINT [ "node" ]
EXPOSE 3000

CMD ["server.js", "0.0.0.0"]
