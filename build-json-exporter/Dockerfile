FROM quay.io/prometheuscommunity/json-exporter:v0.2.0

WORKDIR /usr/src/app

COPY config.yml /config/config.yml

ENTRYPOINT /bin/json_exporter --config.file=/config/config.yml
