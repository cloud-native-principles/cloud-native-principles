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


## Contributing to and Using this content

**CONTRIBUTING**

We encourage civil discourse and debate about the principles. It's not only acceptable but desirable for the points to be discussed and adapted to where the community as a whole feels we are. In other words, it is ok to disagree with a principle and propose an alternative.

How to contribute:
- [Add ideas and comments to existing issues](https://github.com/cloud-native-principles/cloud-native-principles/issues)
- [create a new issue](https://github.com/cloud-native-principles/cloud-native-principles/issues/new)
- Make changes to documents by:
   - [fork the repo](https://github.com/cloud-native-principles/cloud-native-principles/fork)
   - make your change in your fork (+branch)
   - [create a PR](https://github.com/cloud-native-principles/cloud-native-principles/pulls)


**LICENSE**

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
