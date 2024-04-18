# Pulsar Connectors and Security
# subbu harshil
## Pulsar Connectors (Chapter 6)

### Working with Connectors
- Overview of Pulsar Connectors and their role in data integration.
- Explanation of processing guarantees.

### Using Connectors
- Guide on using Pulsar Connectors.
  - Running Sources
  - Running Sinks
  - Monitoring Connectors

### Sample Source Connectors
- Examples of sample source connectors.
  - File Source Connector
  - MySQL Source Connector

### Sink Connectors
- Overview of sink connectors and their use cases.
  - Sample Sink Connector

### Developing Custom Connectors
- Guide on developing custom Pulsar connectors.
  - Developing a Source Connector
  - Developing a Sink Connector

## Pulsar Security (Chapter 7)

### Quick Overview of TLS
- Explanation of Transport Layer Security (TLS) and its importance in securing Pulsar.
  - TLS Termination
    - Prerequisites
    - Configuring the Broker
    - Configuring the Client
  - Mutual TLS
    - Configuring Mutual TLS in the Client
    - Configuring Mutual TLS in the Broker

### JSON Web Token (JWT)
- Introduction to JSON Web Tokens (JWT) and their use in Pulsar security.
  - Creating a Token
  - Configuring JWT in the Client
  - Configuring JWT In the Broker

### Authorization
- Overview of authorization in Pulsar.
  - Role Grants
  - Configuring Broker for Authorization
  - Configuring the Client for Authorization
