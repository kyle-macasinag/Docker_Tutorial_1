FROM node:alpine
WORKDIR /usr/app
COPY ./ ./
RUN apk add --update redis
CMD ["npm", "start"]