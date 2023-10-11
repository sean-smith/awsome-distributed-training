# Monitoring GPU Clusters

This section covers best practices for monitoring your clusters. We give instructions on how to use Grafana, a popular frontend for visualizing metrics, and CloudWatch, a AWS service with metrics, logs and dashboard capabilities.

## 1. Grafana

In this section we show how to monitor cluster resources with [AWS Managed Grafana]() and [AWS Managed Prometheus](). After setting up the base infrastructure, you'll have the option of setting up specific exporters, we have instructions on how to setup the following exporters:

| Prometheus Exporter       | Description              |
|---------------------------|--------------------------|
| Slurm Prometheus Exporter | Slurm scheduler metrics such as number of jobs, instances in DOWN state ect. |
| DCGM Metrics              | GPU Metrics              |
| EFA Exporter              | EFA traffic metrics such as packets sent and received.     |

## 2. CloudWatch

In this section we'll show you how to monitor your cluster with CloudWatch