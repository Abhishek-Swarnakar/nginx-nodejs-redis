FROM node:14.17.3-alpine3.14

WORKDIR /usr/src/app

COPY package.json package-lock.json /usr/src/app/

RUN mpm ci

COPY server.js /usr/src/app/

CMD ["npm","start"]