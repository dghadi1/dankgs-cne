# dankgs-cne
dankgs cloud native enterprise is an extremely simple bootstrapping kit for green field enterprises to setup their IT infrastructure and tooling based on cloud native technologies.

# Components
A platform for enterprise use can have many components categorized by purpose, and origanizations should be able to choose from an available list of implementations. Here is a first pass at the possible list of components

## Compute Layer
The Compute layer comprises of a provisioned node with an operating system reached over an ip address or a hostname
### node
A node can be from any of the following choices
1. AWS
2. Azure
3. GCE
4. DigitalOcean
5. Rpi
### Operating System
Any linux operating system capable of running containers (or custom built using linuxkit)
1. Ubuntu
2. CoreOS
3. CentOS
4. linuxkit

## Resource Abstraction, Orchestration and Communication Layer
This layer primarily deals with a container orchestration system providing the following capabilities
### Resource Abstraction (example - mesos, kubernetes, swarm, etc)
### Task scheduling (example - marathon, kubernetes, swarm, etc)
### Container Runtime (mesos, docker, cri-containerd, rkt, etc)
### Service Discovery, Load balancing and networking
### package management (such as helm for kubernetes, stacks for swarm and frameworks for mesos)

## Management and DevOps Layer
This layer provides for enterprise wide tooling for engineers, project managers, and support staff.
### CI/CD tooling (such as drone, jenkins, etc)
### Developer workspaces (codenvy, etc)
### Version control system (github, bitbucket, gogs, gitlab, etc)
### Access Management (auth0)
### Product Management (jira, trello, etc)
### Code Governance (sonarcube, blackduck, etc)
### APM tools (dynatrace, newrelic, etc)
### Logging stacks (ELK, Sumologic, Splunk, etc)

## Microservices Layer
This layer provides an ecosystem for engineers to build their backends as APIs and microservices through the following components
### API Gateway/Service Mesh (based on static API models such as swagger, graphql, Odata, etc) - (examples include, linkerd, envoy, etc)
### RPC System (gRPC, Akka, Akka .NET etc)
### Integrations (REST, SOAP, JDBC, MQ, NoSQL, etc)
### Persistence (RDBMS such as pgsql, mysql, NOSQL such as mongodb, redis, cassandra, dynamo, etc, Streams such as kafka, flink, spark, nats, etc)
### intellingence (such as tensorflow, sparkML, pytorch, etc)



