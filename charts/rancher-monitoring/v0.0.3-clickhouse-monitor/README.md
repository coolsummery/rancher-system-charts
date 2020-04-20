# rancher-monitoring

Installs [prometheus-operator](https://github.com/coreos/prometheus-operator) to create/configure/manage Prometheus clusters atop Kubernetes.

Installs [clickhouse-exporter](https://github.com/f1yegor/clickhouse_exporter) to monitor clickhouse-cluster,default monitor address http://access-clickhouse-cluster.clickhouse:8123/
please define service or hostname for "access-clickhouse-cluster.clickhouse"

> **Tip**: Only use for Rancher Monitoring!!!

## Prerequisites
  - Rancher 2.2+
