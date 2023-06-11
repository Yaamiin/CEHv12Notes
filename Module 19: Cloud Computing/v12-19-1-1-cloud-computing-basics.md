- Filename: eccouncil-ceh31250-v12-19-1-1-cloud-computing-basics.md
- Show Name: CEHv12 (312-50)
- Topic Name: Cloud Computing - Cloud Computing
- Episode Name: Cloud Computing Basics
================================================================================


Cloud Computing Basics
--------------------------------------------------------------------------------

Objectives:
--------------------------------------------------------------------------------

--------------------------------------------------------------------------------


+ Types of Cloud Services
  - IaaS
  - PaaS
  - SaaS
  - IDaaS
    + ID as a Service
    + Identity and Account Management Services
      - SSO
      - MFA
  - SECaaS
    + Security as a Service
      - Pentests
      - AV/EDR
      - Incident Response
  - CaaS
    + Container as a Service
      - Container/app/cluster management
  - FaaS
    + Function as a Service
      - Microservices
      - App Functions
        + AWS Lambda

+ Responisibility Areas
  - On Prem
    + ALL Subscriber
  - IaaS
    + Subscriber
      - Applications
      - Data
      - Runtime
      - Middleware
      - OS
    + Service Provider
      - Virtualization environment
      - Metal servers
      - Storage
      - Network
  - PaaS
    + Subscriber
      - Applications
      - Data
    + Service Provider
      - Runtime
      - Middleware
      - OS
      - Virtualization environment
      - Metal servers
      - Storage
      - Network
  - SaaS
    + ALL Serice Provider

+ Deployment Models
  - Public
  - Private
    + Single org use
  - Community
    + Multiple org use
      - Common industry and security concerns
        + Healthcare
        + Transportation
        + Hotel
  - Hybrid
    + Some mixing of the cloud Deployment Models
  - Multi-Cloud
    + Environment that spans across Multiple cloud providers
      - Single management interface

+ NIST Cloud Deployment Reference Architecture
  - https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication500-292.pdf
  - Cloud Consumer
  - Cloud Provider
  - Cloud Carrier
    + The org that provides network connectivity between consumers and providers
  - Cloud Auditor
    + 3rd-party examiners
      - Regulation and compliance
      - Security and services
  - Cloud Broker
    + Intermediary that specializes in cloud management
      - Categories
        + Service aggregation
          - The cloud broker combines and integrates multiple existing services
            into new service, carrying responsibility of data integration between
            cloud consumer and cloud providers.
        + Service intermediation
          - A cloud broker provides value-added service, enhancing an existing
            service by improving some of its capabilities.
        + Service arbitrage
          - This is similar to service aggregation but with flexible dynamic
            choice of service providers based on the broker’s internal evaluations.

+ Cloud Storage Architecture
  - Front-End
    + Where the end user interacts with the data through an API
  - Middleware
    + Data De-duplication and Replication
  - Back-End
    + Metal hardware 
