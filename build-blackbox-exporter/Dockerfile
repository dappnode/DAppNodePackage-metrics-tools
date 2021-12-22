FROM prom/blackbox-exporter:v0.18.0

WORKDIR /usr/src/app

COPY blackbox.yml /config/blackbox.yml

ENTRYPOINT /bin/blackbox_exporter --config.file=/config/blackbox.yml
