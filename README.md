# monitoringset

This is a solution that allows you to monitor and manage the status, latency and performance of a Replica Set or a sharded cluster, with a focus on high availability and data replication.

You will use: 

MongoDB
Docker
AWS CloudWatch (Custom metrics)


**MongoDB** Replica Set or Sharded Cluster in Docker: Simulates a environment for MongoDB by replicating primary and secondary nodes in Docker containers.

**AWS CloudWatch**: Used to log custom metrics (node ​​health, latency, active connections, resource usage) and set alarms to detect critical issues such as disconnections or high replication latency.

**Docker**: Docker containers allow you to create a controlled environment to test and validate MongoDB configurations without relying on physical hardware.


~You will need to create a AWS Account for this and create an IAM user.
~You will need to create an .env filled:
AWS_ACCESS_KEY = "________your__AK"
AWS_SECRET_KEY = "_________your_SK"
AWS_DEFAULT_REGION=ur-region
MONGO_URI=mongodb://___________


