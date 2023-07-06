FROM node:14-alpine
WORKDIR /Backend
ADD package*.json ./
RUN npm install
ADD . .
EXPOSE 5000
CMD [ "npm","start" ]
