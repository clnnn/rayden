### Server:

- **Websocket** server (fallback to **Long Polling**)
- **Binary**-first (E.g. Protobuf, Flatbuffers)
- **Hexagonal/Ports & Adapters** architecture
- Can be integrated with **Spring Websockets**
- Can be integrated with **Jakarta EE**
- **rxJava** API Adapter
- **Java 9+ Flow** API Adapter
- **Heartbeat**
- **Metrics** -  (E.g. using Dropwizard Metrics)
- **Cluster/Cloud** support (E.g. Hazelcast, Redis)
- **Sticky session** support
- **Messaging** Integration (E.g. Kafka, RabbitMQ)
- **Kotlin** Bindings (+coroutines)
- **Spring Boot** starter

### Client (chidori-client):

- Implemented in **TypeScript**
- **rxJS** Bindings
- **Callbacks** (alternatives to rxJS)
- Injectable **Angular** Service
- Support for **modern browsers** (E.g. Chrome)
- nrwl workspace? (core libs, bindings, angular service)

*Some features are not compatible with one with another but this will be clear after the implementation starts.*

Development features (*should be achieved using free and open-source solutions*):
* CI/CD
* ArchUnit/JDependency
* Unit Tests
* Integration Tests
* Published on github/maven repository
* Modular
* Minimized dependency on other libraries
* Easy to setup development environment
* Generated documentation
