# prometheus
The Prometheus monitoring system and time series database.

Searches rancher-metadata for prometheus exporters and adds them to the
scrapers list.

Based off usmanismail/prometheus/. Thanks for the inspiration !

Simply add a "prometheus_port=NNNN" label to your prometheus exporters
containers in rancher, and the prometheus server will find them automatically.
