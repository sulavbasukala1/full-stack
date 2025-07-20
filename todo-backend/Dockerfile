FROM node:alpine
LABEL todo version="1.0"
WORKDIR /task
COPY ./package*.json /
RUN npm install
COPY . .
EXPOSE 5000
CMD ["npm", "start"]

