| Service        | Pros           | Cons  |
| --------------- |:------------------:| -----:|
| VM               | Familiarity                                      | Managemnet Overhead(Patching)              |
|                  | Cost Effective                                   | Homegrown Deployment pipelines (Custom)    |
|                  |                                                  | Heavy to configure (Ingress/Egress)        |
| App Service      | Easy To start Control                            | Slow to scale in isolated deployments      |
|                  | Well Integrated management and monitoring tools  | Easy only for standard runtimes            |
| AKS              | Managed Service                                  |                                            |
|                  | Well Integrated management and monitoring tools  |                                            |



| MYSQL DB Service        | Pros           | Cons  |
| --------------- |:------------------:| -----:|
| VM          | Preferred db for OLTP workload                            | Managemnet Overhead(Patching)                          |
|             | Better control and flexibility in tuning configuration    |  Manage Housekeeping like storage,backups,georeplica   |
| Azure MySQL | Managed Service(backups,storage,read,replicas)            |                                                        |
|             | Management Tools (security,performance)                   |                                                        |
|             | Query performance Insights                                |                                                        |


| Analytical Platform        | Pros           | Cons  |
| --------------- |:------------------:| -----:|
| HD Insights      |  | Unavailability of ML libraries           |
| DSVM             |  | Lack of tight CI/CD process              |
|                  |  | User managed instances                   |
| Functions        |  | Harder Job orchestration                 |
|                  |  | Harder to manage heavy batch computes    |
| Databricks       |  |                                          |
|                  |  |                                          |
