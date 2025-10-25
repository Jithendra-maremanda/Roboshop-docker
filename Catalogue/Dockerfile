FROM node:20
WORKDIR /opt/server

COPY *.js .
COPY package.json .

RUN npm install
ENV mongo="true" \
    mongoURL="mongodb://mongodb:27017/catalogue" 

CMD ["node","server.js"]

