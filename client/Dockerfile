FROM node:lts-alpine
RUN mkdir /app
WORKDIR /app
COPY package*.json ./
COPY public ./
RUN npm install
COPY public public
COPY src src
CMD npm start