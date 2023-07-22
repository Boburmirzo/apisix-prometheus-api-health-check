# Monitor API Health Check with APISIX and Prometheus

[APISIX](https://apisix.apache.org/) has a [health check](https://apisix.apache.org/docs/apisix/tutorials/health-check/) mechanism, which proactively checks the health status of the upstream nodes in your system. Also, APISIX integrates with [Prometheus](https://prometheus.io/) through its [plugin](https://apisix.apache.org/docs/apisix/plugins/prometheus/) that exposes upstream nodes (multiple instances of a backend API service that APISIX manages) health check metrics on the Prometheus metrics endpoint typically, on URL path **`/apisix/prometheus/metrics`**.

This repo demonstrates how to **enable and monitor API health checks** using APISIX and Prometheus.
