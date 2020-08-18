# Cloud Native Principles

In order to talk about cloud native applications and systems we need to define cloud native.  CNCF provides a high-level overview of what it means to be cloud native and lists some implemtations as well as the benefits they provide in the [CNCF Cloud Native Definition v1.0 defintion](https://github.com/cncf/toc/blob/master/DEFINITION.md).

The [cloud native principles](https://github.com/cloud-native-principles/cloud-native-principles) seek to further clarify the underlying fundamental concepts of what it means to be cloud native.

NOTE: This is a work in progress.

## Principles

- Service discovery
- Loosely coupled services
- Microservices
- Low overhead/coarse grained packaging 
   - examples: containers, unikernel
- Declarative consumtion model
   - includes apis and configration
   - applies to all layers: infra, workloads, platform, and components
- Immutable infrastructure 
- Designed for automation

Each of these concepts are covered in more depth in the [cloud-native-principles.md paper](https://github.com/cloud-native-principles/cloud-native-principles/blob/master/cloud-native-principles.md).

When these principles are implemented they lead to benefits such as:
- Increased interoperability
- Increased resilence
- Increased scalability
- Lowered risk


Defining these concepts help in applying cloud native metholodgies to different technology domains.  For instance in the networking and communication service provider spaces, the [Cloud Native Networking papers](cloud-native-networking-preamble.md) illustrate this. 


