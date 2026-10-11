## Local Application URLs

The following URLs can be used to access the Quick Commerce Delivery Monitoring application locally.

| Service | URL | Purpose |
|---|---|---|
| Delivery Metrics | http://localhost:8000/metrics | View delivery metrics exported by the Python application |
| Prometheus | http://localhost:9090 | Access the Prometheus monitoring interface |
| Prometheus Targets | http://localhost:9090/targets | Check whether monitoring targets are UP or DOWN |
| Prometheus Alerts | http://localhost:9090/alerts | View configured alert rules and their states |
| Grafana | http://localhost:3000 | Access the Grafana monitoring dashboard |

### Grafana Dashboard

Dashboard name: **Quick Commerce Delivery Monitoring**

The dashboard displays the following metrics:

- Total Deliveries
- Pending Deliveries
- On-the-Way Deliveries
- Average Delivery Time

### How to Run Locally

1. Start the Python delivery metrics application.
2. Start the Prometheus Docker container.
3. Start the Grafana Docker container.
4. Open the Grafana URL above and view the dashboard.

**Note:** These URLs use `localhost`, so they work on the computer running the services. The services and their Docker containers must be running to access them.