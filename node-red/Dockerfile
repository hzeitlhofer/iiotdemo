FROM nodered/node-red
RUN npm install --unsafe-perm node-red-contrib-influxdb
RUN npm install --unsafe-perm node-red-contrib-opcua
COPY flows.json /data/flows.json
