FROM prom/blackbox-exporter:master

WORKDIR /usr/src/app

COPY blackbox.yml /config/blackbox.yml

ENTRYPOINT /bin/blackbox_exporter --config.file=/config/blackbox.yml
