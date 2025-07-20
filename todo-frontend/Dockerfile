FROM node:alpine
LABEL version="1.0"
WORKDIR /task
COPY package*.json /
RUN npm install
COPY . .
CMD ["npm","start"]
EXPOSE 3000



