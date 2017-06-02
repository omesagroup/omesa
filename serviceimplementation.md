# Service Implementation Layer

This layer’s role within a Software Architecture, would be to provide a set of distinct capabilities in support of the realization of goals associated with the Service Orientation paradigm.  Depending on the level of decoupling enforced by specific service design, OMESA divides the Service Implementation layer into two sub-layers: 

![](/images/omesa_service_implementation_1.png)

1. **Semi-Decoupled:** Services in this category are commonly those implemented under a SOA architecture, with high potential for reusability & composability but low physical / logical autonomy. 
2. **Fully-Decoupled:** This kind of services are highly autonomous and mostly self-contained. A solution in this category would commonly be associated with implementation styles such as Microservices, SCS (Self-Contained Systems), etc.

## Core Capabilities

![](/images/omesa_service_implementation_2.png)

* **Orchestration** - Supports the automated execution, coordination and management of workflows comprised by complex service composition logic. 
* **Service Virtualization** - Promotes loose coupling between application logic providers and its consumers by abstracting physical components through an intermediary service layer. 
* **Service State Management** - Enables a group of semi-decoupled services to transition across stateful / stateless conditions predictably and on-demand, by temporarily deferring service state data to a dedicated repository. 
* **Shared Runtime** - Provides a centralized design and execution platform where multiple physical / logical resources are made available and shared by whole service inventories. 
* **Common Data Model** - Standardizes data exchange by adopting a common vocabulary which can span one or more service inventories as well as their related applications and data sources.
* **Service Interaction Security** - Focuses on security issues and threats related to data exchange among services and service compositions. 
* **Business Logic** - Fosters reusability and functional abstraction by isolating, regrouping and expressing solution logic through service capabilities consistent with an underlying business model.
* **Service Mediation** - Facilitates service interaction by positioning an intermediary layer, which isable to actively alter the nature of exchanges in order to produce a desired outcome. 
* **Service Connectivity** - Allows services to exchange Supplies services with pluggable interfacesbased on distinct connectivity providers  
* **Payload Transformation** - Enhances interoperability among heterogeneous service consumers and providers by applying intermediate transformation logic to the data being exchanged. 
* **Asynchronous Messaging** - Decouples message producers and consumers by leveraging asynchronous delivery channels provided byan underlying messaging framework.
* **Service Stability** - Promotes overall system resiliency by positioning mechanisms designed tocontain and confine potentially catastrophic breakdowns. 
* **Choreography** - Enables efficient and purposeful service interaction in a global scope without introducing a single-point of control.
* **Stateless Processing** - Enhances service scalability by using state offloading techniques to minimize resource consumption while still guaranteeing consistent output.
* **Independent Runtime** - Ensures development, deployment and execution independence for a particular set of fine-grained services.
* **Domain Driven Design** - Facilitates the design and development of complex software projects byestablishing flexible building blocks and a common language around a well-defined domain core. 
