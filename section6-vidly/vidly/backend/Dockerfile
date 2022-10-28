FROM node:alpine

RUN addgroup app && adduser -S -G app app
USER app

WORKDIR /app
COPY package*.json ./
COPY . . 

EXPOSE 3001 

CMD ["npm", "start"]