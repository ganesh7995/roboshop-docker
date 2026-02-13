FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npn istall
ENV MONGO="true"\
    MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node","server.js"]
