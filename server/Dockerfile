FROM node:alpine3.10
WORKDIR /app
COPY package*.json /app
RUN npm install
COPY . .
EXPOSE 4000
CMD [ "npm", "run", "start" ]
