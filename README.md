# Open-Zipkin implementation
Proof of concept for Zipkin using Elasticsearch as the storage, the stack is setup / orchestrated using docker swarm. 
Also used are tools such as cadvisor for monitoring & visualizer for getting a visual representation of the stack. 

Zipkin is a distributed tracing system. It helps gather timing data needed to troubleshoot latency problems in microservice architectures. It manages both the collection and lookup of this data. 

# Docker 1.13
This implementation uses the Docker Stack command for spinning up the entire stack in one go. And would need docker engine V-1.13 for running. 

#
