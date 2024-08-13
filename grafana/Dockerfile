FROM grafana/grafana:9.5.9

RUN grafana cli plugins install gapit-htmlgraphics-panel

WORKDIR /etc/grafana/provisioning/datasources

COPY ./provisioning/datasources/influxdb-connection.yaml ./

WORKDIR /usr/share/grafana
