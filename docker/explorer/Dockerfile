FROM node:6.11-alpine

WORKDIR "/opt"

RUN apk add --update git make g++ && \
    git clone https://github.com/xGioe/blockchain-explorer

WORKDIR "/opt/blockchain-explorer"

RUN npm install

CMD npm run start

EXPOSE 8080
