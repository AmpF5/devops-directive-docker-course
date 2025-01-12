FROM node:19.6-alipine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install 

USER node

COPY --chown=node:node  ./srs .

CMD [ "node", "index.js" ]
