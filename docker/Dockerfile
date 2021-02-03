FROM node:14-alpine3.10
WORKDIR /home/node/app
RUN apk update && \
    apk add git yarn build-base autoconf automake libtool pkgconfig nasm bash && \
    yarn global add zenn-cli
EXPOSE 8000 9000
