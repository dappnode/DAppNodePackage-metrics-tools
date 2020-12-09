FROM quay.io/prometheuscommunity/json-exporter

WORKDIR /usr/src/app

COPY config.yml /config/config.yml

ENTRYPOINT /bin/json_exporter --config.file=/config/config.yml
