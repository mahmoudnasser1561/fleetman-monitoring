# fleetman-monitoring
Monitoring and logging stack for the Fleetman system.

### Overview 
Configuration and Deployment files for setting up **logging and monitoring** of the Fleetman microservices system.

### Current Status
The Fleetman microservices application has been successfully deployed — this repository now focuses on integrating the **ELK stack (Elasticsearch, Logstash, Kibana)** and **Prometheus + Grafana** for observability.

<img width="1018" height="151" alt="504150421-1ccb73bc-971b-4a4b-8794-132d5ed1eca7" src="https://github.com/user-attachments/assets/4931115c-a3af-4d8f-9e2c-6f4f625393c1" />


### Deployment Status

The following components have been successfully deployed and are running:

- **Fluentd** (log collection)
- **Elasticsearch** (log storage & search)
- **Kibana** (log visualization)

**All pods are in `Running` state, indicating the stack is ready to use.**
<img width="880" height="259" alt="Screenshot from 2025-10-24 07-35-22" src="https://github.com/user-attachments/assets/d926cbd7-a835-4d4b-97d7-47b3066ca17a" />

**All system components are running well beisde elk stack components**
<img width="880" height="259" alt="Screenshot from 2025-10-24 07-37-10" src="https://github.com/user-attachments/assets/0ad16e4b-b936-48f2-87a9-e462d1527192" />

