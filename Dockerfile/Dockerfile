FROM node:22-alpine

COPY IBM-Tasks/Dockerfile/package.json /app/

COPY src /app/

WORKDIR /app

RUN npm install

CMD ["node", "server.js"]
