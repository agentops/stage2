FROM node:17.9.1 as build
WORKDIR /frontend
COPY package.json .
RUN yarn install
COPY . .
RUN yarn run build
