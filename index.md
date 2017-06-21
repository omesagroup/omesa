# OPEN MODERN SOFTWARE ARCHITECTURE PROJECT

## Background
Digital disruption has changed the way businesses do business, naturally the way business software is developed, deployed and maintained, and inevitably the software that vendors sell and most importantly how they sell it.

This disruption is reflected in new software architectural styles adopted (i.e. [Reactive manifesto][link1], [12 factor app][link2]) and in most cases shared by the likes of Netflix, LinkedIn, Amazon, eBAY, Uber and others. Although at first glance they just seem as an evolution of Service Oriented Architectures (SOA), one can't close the eyes and pretend that nothing has changed. The truth is, a lot has changed.

Specially with the introduction of [Microservices Architecture][link3], and "the cloud" as "the" preferred way to deliver/adopt business software with speed, agility and low costs, it might seem as if the days of SOA are ending and that traditional enterprise integration patterns patterns no longer apply and have become legacy.... The addition of new technologies in support of Internet of Things, Artificial Intelligence, Mobility, Responsive Web Apps and API Management, is making it more difficult for architects (those who still care about architecture) to come up with elegant designs that truly deliver blended and balanced capabilities that bring together the old with the new whilst still delivering business benefits.

The truth is that most organisations in the world aren't Netflix or LinkedIn and were not born digital. They don't have the luxury of starting from a blank sheet of paper. Most businesses still run legacy systems and traditional (on-premise) software. For them moving to a Microservices Architecture and adopting cloud is not necessarily a trivial task and will require careful planning and thinking.

The Open Modern Enterprise Software Architecture (OMESA) project was born with the purpose to bring back architectural best practices into modern architectures whilst keeping in mind that the "new" most co-exists with the "old". It provides reference architectures and guiding principles to help architects from any organisation realise the benefits that modern technologies and architectures can bring to the business whilst avoiding the creation of "micro-silos" or ad-hoc solutions.

## Objectives
OMESA has 4 main objectives:
  - To deliver a modern and enterprise-wide software reference architecture suitable to combine ”existing" with the "new”.
  - Provide guiding principles and definition of terms to ensure the architecture can be interpreted and applied.
  - Deliver a vendor agnostic capability model that can add tangible business value to organisations.
  - Bring back architectural best practices (based on real live experiences) into modern solutions that are suitable for organisations of any size and industry.
  
## Fundamental Building Blocks

OMESA proposes the following fundamental building blocks: 

![](/images/omesa_reference_arch_1.png)

These four categories constitute a fairly simple entry point to the model, but should be comprehensive enough to encompass a high variety of concepts related to software architecture and design:

1. Delivery Experience
2. API
3. [Service Implementation][link8]
4. Persistence

## Reference Architecture

Once the fundamental building blocks have been established, the OMESA model aims to simplify software design by relying on a reference architecture which can be further decomposed into smaller, more specific blocks. All of these elements can be part of an enterprise architecture but none of them are necessarily enforced. 

![](/images/omesa_reference_arch_6.png)

Within this context, Core Capabilities are key when it comes to justifying the presence of any particular layer and ultimately producing a cohesive design by bridging the gap between high-level (conception: layers, sublayers) and low-level (execution: design patterns) perspectives. For example:

![](/images/omesa_service_implementation_2.png)

A huge part of our body of work is focused on identifying, describing and mapping these Core Capabilities to qualified design patterns throughout the model's different layers.

## Copyright and License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Copyright 2017 [omesagroup][link4]

[link1]: <http://www.reactivemanifesto.org>
[link2]: <https://12factor.net>
[link3]: <http://microservices.io>
[link4]: </contributors>
[link5]: </LICENSE>
[link6]: </deliveryexperience.md>
[link7]: </api.md>
[link8]: <http://omesa.io/serviceimplementation>
[link9]: </persistence.md>


