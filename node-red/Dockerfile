FROM nodered/node-red:4.0.2

WORKDIR /data

COPY package.json .
COPY settings.js .

RUN npm i --unsafe-perm --no-update-notifier --no-fund --only=production

WORKDIR /usr/src/node-red
