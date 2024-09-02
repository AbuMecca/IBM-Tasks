FROM node:22-alpine

COPY Dockerfile/package.json /app/

COPY Dockerfile/src /app/

WORKDIR /app

RUN npm install

CMD ["node", "server.js"]
