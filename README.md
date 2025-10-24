# fleetman-monitoring
Monitoring and logging stack for the Fleetman system.

### Overview 
Configuration and Deployment files for setting up **logging and monitoring** of the Fleetman microservices system.

### Current Status
The Fleetman microservices application has been successfully deployed — this repository now focuses on integrating the **ELK stack (Elasticsearch, Logstash, Kibana)** and **Prometheus + Grafana** for observability.
<img width="1018" height="151" alt="sys" src="https://github.com/user-attachments/assets/5cf456ac-fdb7-4540-a76b-15f7ff34c96d" />



### Deployment Status

The following components have been successfully deployed and are running:

- **Fluentd** (log collection)
- **Elasticsearch** (log storage & search)
- **Kibana** (log visualization)

**All pods are in `Running` state, indicating the stack is ready to use.**
<img width="880" height="259" alt="on" src="https://github.com/user-attachments/assets/ca03855c-b52f-4253-afd3-a00c568b0e3d" />


**All system components are running well beisde elk stack components**
<img width="880" height="259" alt="all" src="https://github.com/user-attachments/assets/d25e486f-50e8-4d4e-9eaf-0799f0068add" />

