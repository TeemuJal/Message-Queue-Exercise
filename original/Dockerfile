FROM node:10.22.1-alpine3.9
WORKDIR /original
COPY . .
RUN apk update && apk add bash coreutils
RUN npm install --silent