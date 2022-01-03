FROM node:lts-alpine
RUN apk update && \
    apk --no-cache add git && \
    apk --no-cache add openssh

WORKDIR /workspaces/node_app

COPY ./package.json ./package-lock.json ./

RUN npm install --no-optional && npm cache clean --force

ENV PATH /workspaces/node_app/node_modules/.bin:$PATH

USER node

WORKDIR /workspaces/zenn-docs
