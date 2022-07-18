Concepts of Domain Driven Design

**Domain:** The subject area to which the user applies a program is the domain of the software.
It is also termed as sphere of knowledge.

**Subdomain:** The domain concept is very broad and abstract. To make it more concrete and tangible, it makes sense to split it up into smaller parts called subdomains. Finding these subdomains is not always an easy thing to do, and if you get them wrong, you can run into trouble down the road when the pieces in your puzzle all of a sudden do not fit well together.

Before you go looking for subdomains, you should think about the subdomain categories. All subdomains can be divided into three categories:

    - Core domains
    - Supporting subdomains
    - Generic subdomains
Not only will these categories help you to find your subdomains, they will also help you to prioritize your development efforts.
[Details](docs/Subdomain.md)

**[Domain Model](docs/DomainModel.md)** 

**Domain Expert:** Domain expert is a person who is an owner in a particular area or topic.

**Ubiquitous Language:** Ubiquitous language is a language communicated around the domain model and used by all team members to connect all the activities of the team with the software.

**[Bounded context](docs/BoundedContext.md)**

**[Context map](docs/ContextMap.md)** 

**Entity:** An object that can be identified uniquely or by its identifier. Entity can be identified either by its ids or combination of some attributes. Entity is an identity.

**Value Object:** An object that contains attributes but has no conceptual identity.

**Aggregate:** A collection of objects that are bound together by a root entity, otherwise known as an aggregate root.
The aggregate root guarantees the consistency of changes being made within the aggregate by forbidding external objects from holding references to its members.
The idea of an aggregate is to guarantee consistency, being the root responsible for data integrity and forcing invariants.

**Domain Event:** A domain object that defines an event (something that happens) and is an event that domain experts care about.

**Service:** Services can be categorized into three types in domain driven design.

Services can be of three types:  

    - Domain Services
    - Application Services
    - Infrastructure Services

[Details](docs/Service.md)

