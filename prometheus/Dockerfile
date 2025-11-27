FROM prom/prometheus:latest
COPY config/ /etc/prometheus/
EXPOSE 9090
CMD [ "--config.file=/etc/prometheus/prometheus.yml", "--storage.tsdb.path=/prometheus" ]
