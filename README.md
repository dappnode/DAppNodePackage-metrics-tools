# DAppNode package metrics-tools 

Blackbox exporter + json exporter

![avatar](blackbox-exporter-avatar.png)

Blackbox exporter + json exporter. The blackbox exporter allows blackbox probing of endpoints over HTTP, HTTPS, DNS, TCP and ICMP. This allows to add latency metrics to prometheus: 8.8.8.8 (Google), 1.1.1.1 (Cloudflare), web3.dappnode.net (remote) and ns.dappnode.io (dyndns)

Json exporter it's a prometheus exporter which scrapes remote JSON by JSONPath. This adds ETH price to prometheus by using the coingecko API
