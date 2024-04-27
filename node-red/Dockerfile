FROM nodered/node-red:3.1.9

WORKDIR /data

COPY package.json .

RUN npm i --unsafe-perm --no-update-notifier --no-fund --only=production

WORKDIR /usr/src/node-red
