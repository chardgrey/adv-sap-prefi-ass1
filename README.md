## Assignment in Advanced Systems Integration & Architecture

1.	Define Service Oriented Architecture (SOA).

Service Oriented Architecture is known for its enterprise-wide approach for software development. What he does is collect reusable software components, or services. This service has codes and data that can be used for specific business functions and these services can communicate with each other over a network, they used standard protocol to provide the functionality of the entire application. Architectural frameworks create a reusable service that can be operated using standard protocol. Also supports the new generation of agile applications that are made for business, application, and technical services.  Architectural frameworks allow us to create external or business partnerships interfaces to project inter-enterprise integration.

2.	List and discuss the characteristics of SOA.

-	Standardized service Contracts: It stated its service description or rules or protocol. Services use this to state their purpose or rules, services capabilities, and use standard protocol or standardized service contracts.
-	Loose Coupling: Services optimized their relationship with each other by creating a specific type of relationship that do specific task with this it eliminates the dependency with each other.

-	Abstraction: 
o	This encapsulates or hides its logic/code from the users. 
o	Avoid irrelevant information. 
o	Hides irrelevant information about service.
o	Makes the weakly associated components work.
o	Has a significant role in designing a service composition.

-	Service reusability: Logic or method that can be reused for other services get divided to get its maximum use.

-	Autonomy:

o	Services need to have access to logic/code they encapsulate through abstraction.
o	It needs to have an ability to independently stand for their own logic without getting affected by outside influence.
o	Services must have been isolated.
o	With these you gain benefits of 
	Reliability
	Behavioral predictability

-	Statelessness:
o	The services should be independent.
o	Incorporate state management deferral extensions within the goal.
o	Increase service scalability.
o	Support the service logic and improve its reuse.
-	Discoverability:
o	Services need to be discoverable in a service registry.
o	Services need to have appropriate information for discovery which can also connect with humans.
o	Store metadata in service registry.
-	Composability:
o	Service breaks big problem to small problem. To help with Reusability principle.
o	Service execution should be efficient, and each process needs to be in good condition.
-	Interoperability:
o	Services should use standard methods that anyone can be able to use the service.
o	With all of this, this is also called as principle.

3.	Define Microservices.

-	Microservices architectures are made up with loosely relationship, reusable, and specialized with components. Microservices are typically built as individual applications. This way it made them agile, scalable, and resilient as possible. Microservices more likely found in cloud-native architectural approach by using them, teams can update code efficiently use different stacks for different components and scale the component independently with this method it reduces the waste and the cost associated with having to scale applications with much more efficient to load each individual features. Microservices architecture is a cloud-based approach where a single application is built as a collection of loosely coupled and independently deployable services. Every service has its own data model and database in addition to its own stack. Message brokers, event streaming, and REST APIs are how services communicate with one another. Services are categorized by constrained contexts and business capabilities.

Microservices provide many advantages, such as simpler code changes, the freedom for teams to use various technology stacks, and the capacity to scale individual components separately, which lowers waste and expenses related to scaling complete systems.

4.	List and discuss the benefits of using Microservices.

-	Independently deployable: 

o	The most important characteristics of microservices is that because of how smaller and independently microservices are compared to SOA.
o	Microservices fit today’s trend with their feature of being small, cross functional around one service or a collection of services and have them to work as agile fashion.
o	The small size of the services with each boundary and communication patterns makes it easier to understand, making its user understand the code much better. With this the contribution to the services might get faster and will benefit the efficiency and morale of the employees.

-	Right tool for the job:

o	In n-tier architectural pattern, an application is commonly shared with stack, and a large relational database but this architectural pattern has its drawbacks. Significant drawbacks are every component of an application shared the same stack, database, and data model even if there is a better tool or much more efficient to use for the job of certain elements.
o	While Microservices model components are deployed independently and just communicate with some sort of combination of event streaming. So, it’s possible for the stack of every component of the service to be optimized for specific services that the application might need. Technology changes all the time so smaller services might be the most efficient thing to use because it is much easier to scale and less expensive to upgrade with much more advanced technology as it becomes available.

-	Precise scaling

o	Microservices individual services can be individually deployed but they can also be individually scaled. The result benefits its user with the proper use it can lessen required infrastructure rather than monolithic applications because they are able to scale only a component that need to be upgraded rather than the entire application needs to be scaled in the case of monolithic application.

-	Microservices and cloud services

o	Microservice are not exclusive for cloud computing but there are important reasons why they applied microservices to it. The reason for it being applied is because of how microservices are getting popular amongst other architectural styles and cloud being popular hosting for this new generation of technology.
o	The benefits of microservices architecture are utilization and cost benefits associated with deploying and scaling components individually. These benefits would still be seen around on premises infrastructure while the real optimization is found when combined with small, independent scalable components coupled with on demand, pay per use infrastructure.
o	Secondly, the most important benefit of microservices is that each component can be easily adapted to the stack efficiently for a specific job. Stack proliferation can lead to serious complexity and overhead when you manage it on your own but when you consume the supporting stack as cloud services can reduce the number of challenges while managing. It is not recommended to do your own microservices, especially when just starting out but it is not impossible.


5.	List and discuss the similarities and differences of SOA and Microservices.

-	The similarities of SOA and Microservices are they both made the loosely coupled, reusable, and have their components specialized.

-	Size and scope: When it comes to size and scope Microservices are much more focused on smaller tasks while SOA services are designed to operate with large and enterprise-wide reuse.
-	SOA is intended for enterprise-wide concept which enables the loosely coupled interface to be reused and make the other application to be reuse functionality in other applications. While microservices architecture is an application scoped concept which do enables the internal of a single application to be broken up into single pieces. With this concept it can be easily changed, scaled, and administered an application.
-	Reusability: When it comes to reusability in SOA, the reuse of integrations at the level of enterprise level is the primary goal of the architecture. While the microservices architecture creates microservices components that are reused at runtime throughout an application which led to the application being dependent that reduce agility and resilience. Microservices components way is getting copied and reused the code and accept the data duplication to help improving decoupling.
-	Synchronous calls: The reusable advantage of the SOA stands in this because of the availability of it across the enterprise with the use of API. While microservices applications, synchronous calls call a real time dependency which results to loss of resilience. It may also have a latency which impacts performance. In the entire microservice application communication patterns are based on asynchronous communication, such as event sourcing in which a publish model are used to enable microservices component to remain up to date on the changes happens in the data in another component.
-	Data duplication: The SOA services aims to synchronous get hold and changes directly to its primary source, which improves efficiency when it comes to maintaining complex data synchronization pattern. While microservices applications have local access to all the data that it needs for it to be independent from other microservices and other applications even if it means the need of data duplication which can cause complexity. So, it needs to be handled and maintained well for it to gain the advantages which were microservices features.
-	Communication: The microservices architecture and each service deployed independently with built in communication protocol. While SOA, each service must have shared a common communication protocol for it to work to each other. It is called an ESP, but it has its own weakness, because it can also became the single point of failure for the entire enterprise and when it also slows down the whole enterprise can be affected.
-	Interoperability: Microservices use lightweight messaging protocols while SOA open to much more diverse messaging protocols.
-	Service granularity: Microservices are made up for their specialized services that are designed to do one thing very well. While SOA can handle small, specialized services to enterprises-wide services.
-	Speed: SOA simplify development and troubleshooting. However it also became its weakness and it tends to slow down the operation more than Microservices. Microservices tends to duplicate to minimalize sharing of application.

