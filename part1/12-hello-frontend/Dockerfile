#!/usr/bin/env sh

FROM node:16
EXPOSE 5000
COPY example-frontend/package* ./
RUN npm install
COPY example-frontend .
RUN npm run build
RUN npm install -g serve
CMD [ "serve", "-s", "-l", "5000", "build" ]
