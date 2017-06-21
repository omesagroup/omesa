# Service Implementation

The Service Implementation building block provides a set of distinct capabilities in support of the realization of goals associated with the Service Orientation paradigm. In OMESA, a service is defined as a bounded application that abstracts and encapsulates business functionality making it accessible through a standard endpoint.

Depending on specific design concerns and the combination of capabilities required to address them, OMESA acknowledges two general service implementation styles: 

![](/images/omesa_service_implementation_1.png)

1. **Semi-Decoupled:** Services in this category are commonly those implemented under traditional Service Oriented Architectures (SOA), therefore sharing a common runtime environent. They are usually aimed for a high degree of reusability & composability at the cost of low physical / logical autonomy. 
2. **Fully-Decoupled:** This kind of services are highly autonomous and mostly self-contained. They don't share a runtime environment and are usually associated with architectural styles such as Microservices Architecture and Self-Contained Systems (SCS).

## Core Capabilities

As shown by the following diagram, some of the Core Capabilities are common to both service implementation styles, while others can be much more suitable or even exclusive to one of them. 

![](/images/omesa_service_implementation_2.png)

So for example, "Shared Runtime" would clearly speak of a semi-decoupled solution while "Independent Runtime", "Choreography" or "Stateless Processing" inequivocally relate to fully-decoupled services. In the case of "Service Stability" or "Domain Driven Design", while they could be applied to some extent in a semi-decoupled scenario (for example a traditional SOA Architecture), they're much more suited and thus appear clearly tilted towards the fully-decoupled side.

Within the OMESA model, Core Capabilities can also be mapped to one or more Design Patterns, thus providing a link between abstract and concrete design views. 

![](/images/omesa_service_implementation_3.png)

Identifying the desired and / or necessary Core Capabilities for a particular solution as well as the Design Patterns best suited to realize them is key when it comes to delivering an assertive design and eventually justifying specific implementation choices. 

<i><small><sup>*</sup>Although design pattern documentation is not within OMESA's main concerns, for the purpose of this body of work we have researched and handpicked a set of references which we consider highly qualified. However, both individuals and organizations are encouraged to apply their own criteria when choosing, qualifying and mapping their trusted design patterns to architectural blueprints based on OMESA's Core Capability model.</small></i>

## Core Capability Definitions

* **Orchestration** - Supports the automated execution, coordination and management of workflows comprised by complex service composition logic. This capability can be realized by applying design patterns such as: [Capability Composition][link1], [Process Abstraction][link2], [Composed Message Processor][link3].
* **Service Virtualization** - Promotes loose coupling between application logic providers and its consumers by abstracting physical components through an intermediary service layer. Related design patterns include: [Decoupled Contract][link4], [Service Facade][link5], [Legacy Wrapper][link6].
* **Service State Management** - Enables a group of semi-decoupled services to transition across stateful / stateless conditions predictably and on-demand, by temporarily deferring service state data to a dedicated repository. Related design patterns include: [State Repository][link7], [Service Grid][link8], [Partial State Deferral][link9].
* **Shared Runtime** - Provides a centralized design and execution platform where multiple physical / logical resources are made available and shared by whole service inventories. Related design patterns include: [Process Centralization][link10], [Rules Centralization][link11], [Resource Pool][link12].
* **Common Data Model** - Standardizes data exchange by adopting a common vocabulary which can span one or more service inventories as well as their related applications and data sources. Related design patterns include: [Canonical Schema][link13], [Schema Centralization][link14], [Domain Inventory][link15].
* **Service Interaction Security** - Focuses on security issues and threats related to data exchange among service providers and consumers. Related design patterns include: [Direct Authentication][link16], [Exception Shielding][link17], [Brokered Authentication][link18].
* **Business Logic** - Fosters reusability and functional abstraction by isolating, regrouping and expressing solution logic through service capabilities consistent with an underlying business model. Related design patterns include: [Agnostic Context][link19], [Utility Abstraction][link20], [Entity Abstraction][link21].
* **Service Mediation** - Facilitates service interaction by positioning an intermediary layer, which is able to actively alter the nature of exchanges in order to produce a desired outcome. Related design patterns include: [Splitter / Aggregator][link22], [Message Router][link23], [Resequencer][link24].
* **Service Connectivity** - Supplies services with pluggable interfaces based on distinct connectivity providers. Related design patterns include: [Channel Adapter][link25], [Multichannel Endpoint][link26], [Messaging Bridge][link27].
* **Payload Transformation** - Enhances interoperability among heterogeneous service consumers and providers by applying intermediate transformation logic to the data being exchanged. Related design patterns include: [Data Model Transformation][link28], [Data Format Transformation][link29], [Content Enricher / Filter][link30].
* **Asynchronous Messaging** - Decouples message producers and consumers by leveraging asynchronous delivery channels provided byan underlying messaging framework. Related design patterns include: [Point to Point Channel][link31], [Pub-Sub Channel][link32], [Event-Driven Messaging][link33].
* **Service Stability** - Promotes overall system resiliency by positioning mechanisms designed tocontain and confine potentially catastrophic breakdowns. Related design patterns include: [Circuit Breaker][link34], [Bulkheads][link35], [Backpressure][link36].
* **Choreography** - Enables efficient and purposeful service interaction in a global scope without introducing a single-point of control. Related design patterns include: [Event Sourcing][link37], [Parallel Model][link38], [CQRS][link39].
* **Stateless Processing** - Enhances service scalability by using state offloading techniques to minimize resource consumption while still guaranteeing consistent output. Related design patterns include: [Stateless Component][link40], [Response Caching][link41], [IOStrategies][link42].
* **Independent Runtime** - Ensures development, deployment and execution independence for a particular set of fine-grained services. Related design patterns include: [Containerization][link43], [Microservice Deployment][link44], [Decentralized Data Management][link45].
* **Domain Driven Design** - Facilitates the design and development of complex software projects byestablishing flexible building blocks and a common language around a well-defined domain core. Related design patterns include: [Bounded Context][link46], [Ubiquitous Language][link47], [Consumer Driven Contracts][link48].

## References

The following references were used by OMESA exclusively for research and example purposes. Credit due to the respective authors & owners of the content.

* http://soapatterns.org/		
* http://www.enterpriseintegrationpatterns.com		
* https://martinfowler.com/		
* http://www.reactivemanifesto.org		
* https://github.com/Netflix/Hystrix/wiki/How-it-Works	
* http://www.cloudcomputingpatterns.org/	
* http://assets.en.oreilly.com/1/event/79/Stability%20Patterns%20Presentation.pdf	
* https://www.thoughtworks.com/insights/microservices	
* https://12factor.net/	
* https://javaee.github.io/grizzly/iostrategies.html
* http://coresecuritypatterns.com/patterns.htm		
* https://skife.org

[link1]: <http://soapatterns.org/design_patterns/capability_composition>
[link2]: <http://soapatterns.org/design_patterns/process_abstraction>
[link3]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/DistributionAggregate.html>
[link4]: <http://soapatterns.org/design_patterns/decoupled_contract>
[link5]: <http://soapatterns.org/design_patterns/service_facade>
[link6]: <http://soapatterns.org/design_patterns/legacy_wrapper>
[link7]: <http://soapatterns.org/design_patterns/state_repository>
[link8]: <http://soapatterns.org/design_patterns/service_grid>
[link9]: <http://soapatterns.org/design_patterns/partial_state_deferral>
[link10]: <http://soapatterns.org/design_patterns/process_centralization>
[link11]: <http://soapatterns.org/design_patterns/rules_centralization>
[link12]: <https://martinfowler.com/bliki/ResourcePool.html>
[link13]: <http://soapatterns.org/design_patterns/canonical_schema>
[link14]: <http://soapatterns.org/design_patterns/schema_centralization>
[link15]: <http://soapatterns.org/design_patterns/domain_inventory>
[link16]: <http://soapatterns.org/design_patterns/direct_authentication>
[link17]: <http://soapatterns.org/design_patterns/exception_shielding>
[link18]: <http://soapatterns.org/design_patterns/brokered_authentication>
[link19]: <http://soapatterns.org/design_patterns/agnostic_context>
[link20]: <http://soapatterns.org/design_patterns/utility_abstraction>
[link21]: <http://soapatterns.org/design_patterns/entity_abstraction>
[link22]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/Sequencer.html>
[link23]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/MessageRouter.html>
[link24]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/Resequencer.html>
[link25]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/ChannelAdapter.html>
[link26]: <http://soapatterns.org/design_patterns/multi_channel_endpoint>
[link27]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/MessagingBridge.html>
[link28]: <http://soapatterns.org/design_patterns/data_model_transformation>
[link29]: <http://soapatterns.org/design_patterns/data_format_transformation>
[link30]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/DataEnricher.html>
[link31]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/PointToPointChannel.html>
[link32]: <http://www.enterpriseintegrationpatterns.com/patterns/messaging/PublishSubscribeChannel.html>
[link33]: <http://soapatterns.org/design_patterns/event_driven_messaging>
[link34]: <https://martinfowler.com/bliki/CircuitBreaker.html>
[link35]: <https://skife.org/architecture/fault-tolerance/2009/12/31/bulkheads.html>
[link36]: <http://www.reactivemanifesto.org/glossary#Back-Pressure>
[link37]: <https://martinfowler.com/eaaDev/EventSourcing.html>
[link38]: <https://martinfowler.com/eaaDev/ParallelModel.html>
[link39]: <https://martinfowler.com/bliki/CQRS.html>
[link40]: <http://www.cloudcomputingpatterns.org/stateless_component/>
[link41]: <http://soapatterns.org/candidate_patterns/response_caching>
[link42]: <https://javaee.github.io/grizzly/iostrategies.html>
[link43]: <http://soapatterns.org/design_patterns/containerization>
[link44]: <http://soapatterns.org/design_patterns/microservice_deployment>
[link45]: <https://martinfowler.com/articles/microservices.html#DecentralizedDataManagement>
[link46]: <https://martinfowler.com/bliki/BoundedContext.html>
[link47]: <https://martinfowler.com/bliki/UbiquitousLanguage.html>
[link48]: <https://martinfowler.com/articles/consumerDrivenContracts.html>
