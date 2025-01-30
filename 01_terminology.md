## Terminology

Some of the TODOs to complete this terminology list are:

- [ ] Add the terms from [agile alliance](https://www.agilealliance.org/agile101/agile-glossary/), [wovenware terminology](https://www.wovenware.com/software-development-glossary/), [parasoft terms](https://www.parasoft.com/glossary/).
- [x] [IEEE Standard glossary for SE terminology (84 pages)](https://www.informatik.htw-dresden.de/~hauptman/SEI/IEEE_Standard_Glossary_of_Software_Engineering_Terminology%20.pdf), published in 2010 - just FYI, it might still contain a few useful terms for the current times.
- [ ] - Add "for more info" links to each term.
- [ ] - Add anchors & links for getting to the terms quickly using an index.

**Agile Development**: A framework for developing software in short, iterative cycles called sprints. Focuses on customer feedback and continuous improvement. It has the following benefits compared to the _Waterfall software development_ approach:

- Increased productivity and efficiency
- Improved communication and collaboration
- Enhanced customer satisfaction
- Reduced risk of failure
- Increased flexibility and adaptability

**Architecture Observability**: Architectural Observability is like having a very detailed map of a software application. It gives architects detailed visibility and context into an existing application’s architecture to profile and baseline how an application is architected, identifying domains and cross-domain contamination, collecting observable dynamic operational and static data to proactively fix issues, set baselines, detect drift, identify significant architectural events, and resolve architectural inconsistencies. For more info, refer to [this link](https://dzone.com/articles/the-agile-architect-mastering-architectural-observ) and [vFunction Platform](https://vfunction.com/use-cases/architectural-drift/) and [RedMonk Conversation - Shifting Architecture Left](https://vfunction.com/resources/video-redmonk-shifting-architecture-left/).

**Backlog**: A collection of features, requirements, and user stories that need to be implemented in a project. A prioritized list of features and tasks to be completed in an Agile project.

**Code Review**: The process of examining source code to ensure it meets certain standards and best practices. It helps improve the quality and maintainability of the codebase.

**Code Snippet**: A small piece of code used to illustrate a particular concept or technique.

**Command Query Response Seggregation (CQRS) Principle/Pattern**: The idea behind the CQRS pattern is very simple. Instead of having one unified model, you need to introduce two: one for reads and the other one for writes, and that’s it. CQRS was introduced by Greg Young back in 2010. Greg, himself, based this idea on the command-query separation principle coined by Bertrand Meyer. Command-query separation principle, CQS for short, states that every method should either be a command that performs an action, or a query that returns data to the caller, but not both. To follow this principle, you need to make sure that if a method changes some piece of state, this method should always be of type void, otherwise, it should return something. For more info, refer to [this link](https://codewithshadman.com/cqrs-design-pattern-csharp/) and [CQRS Pattern - Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/patterns/cqrs).

**DAST**: Dynamic Analysis for Security Testing, a type of security testing that uses automated tools to identify vulnerabilities in an application's code. Some of the open-source DAST tools are OWASP ZAP, Veracode SCA, and Burp Suite. This is a technique for testing web applications, mobile apps and APIs to identify vulnerabilities that can be exploited by attackers.

- Gartner predicts that by 2026, 50% of large global enterprises will use DAST as part of their security testing processes.

**DesignOps**: The intersection of design and operations, which aims to improve the efficiency and effectiveness of product development by integrating design thinking into the operational workflow.

**Development Value Stream**:
**DevOps**: It is practice in which development & operations are not treated as separate.

**DevSecOps**: A set of practices that combines development and security into a single process. This approach aims to ensure that security is integrated into every stage of the software development lifecycle, from development to deployment.

**Event-Driven Architecture (EDA)**: A software development paradigm that structures an application around the concept of events. Events are used to communicate between different components of the system.

- _Advantages_:

  - Improved scalability and flexibility
  - Increased fault tolerance and reliability
  - Easier maintenance and updates
  - Faster time-to-market

- _Disadvantages_:
  - Higher complexity and overhead
  - Potential for increased costs
  - Requires careful event handling and processing

**Fusion Team Strategy**: A fusion team strategy is a way to collaborate across departments to solve problems and achieve business goals. Fusion teams are often used in software development and digital transformation. When assembling a fusion team, don’t forget to:

1. Keep the team small — less than 9 people
1. Recruit people with expertise relevant to the goal
1. Appoint a team leader with sound digital judgment
1. Involve fusion team leaders to help create governance and compliance practices
1. Share insights and lessons learned across the organization 

For more info, refer to [this link](https://www.mendix.com/blog/fusion-teams-explained-benefits-roles-examples).

**GitOps**: A set of practices that aim to automate as much as possible, so that there's less room for human error and more time can be spent on high-value tasks. This enables teams to collaborate better and work faster.

**Interactive Application Security Testing (IAST)**: IAST is an application security testing method that tests the application while the app is run by an automated test, human tester, or any activity “interacting” with the application functionality. The core of an IAST tool is sensor modules, software libraries included in the application code. These sensor modules keep track of application behavior while the interactive tests are running. If a vulnerability is detected, an alert will be sent. For more info, refer to [this link](https://owasp.org/www-project-devsecops-guideline/latest/02c-Interactive-Application-Security-Testing).

**Kubernetes**: An open-source container orchestration system for automating the deployment, scaling, and management of containerized applications.

**Language Server**: Language Servers can provide language-specific features such as code completion, documentation, and formatting, which is far easier than implementing language support from scratch. It also reduces the need for constant maintenance and tracking of changes in relevant languages and tools, making it easier to bring consistent language support to various development environments. For more info, refer to [this link](https://tamerlan.dev/an-introduction-to-the-language-server-protocol/) and [implementation list of language servers](https://langserver.org/).

**Language Server Protocol (LSP)**: The Language Server Protocol (LSP) is an open-standard protocol developed by Microsoft. It enables communication between development tools and Language Servers. For more info, refer to [this link](https://tamerlan.dev/an-introduction-to-the-language-server-protocol/) and the [protocol specification](https://microsoft.github.io/language-server-protocol/).

**Microservices Architecture**: Software development paradigm that structures an application as a collection of small, independent services. Each service is responsible for a specific business capability and can be developed, tested, and deployed independently. For more info, refer to [this link](TODO) and [Monolithic vs Microservices Architecture: Pros, Cons and Which to Choose](https://www.openlegacy.com/blog/monolithic-application).

- _Advantages_:

  - Increased scalability and flexibility
  - Improved fault isolation and reliability
  - Easier maintenance and updates
  - Faster time-to-market

- _Disadvantages_:
  - Higher complexity and overhead
  - Increased communication and coordination challenges
  - Potential for increased costs

**Modular Monolith**: Modular monolithic architecture is a way of organizing a software application into a set of modules. These modules have specific functionality, which can be independently developed and tested, while the entire application is deployed as a single unit. There might arise a situation where a few modules need to be extracted for reasons such as scale. A modular monolithic application will enable this with minimal effort. For more info, refer to [When Modular Monolith is the better way to build software](https://www.thoughtworks.com/en-us/insights/blog/microservices/modular-monolith-better-way-build-software).

**Operational Value Stream**: Operational value streams correspond directly to a specific value driver. They:

- Represent the flow of business and the nature of the business
- Deliver end-customer value indefinitely as long as an organization continues to offer a given product or service
- Are supported by development value streams

For more info, refer to [this link](https://blog.planview.com/operational-vs-development-value-streams-whats-the-difference).

**OWASP**: The Open Web Application Security Project, an organization dedicated to improving the security of web applications.

**OWASP Top 10**: The Open Web Application Security Project (OWASP) publishes an annual list of the top ten most critical web application security risks. DAST tools are used to identify vulnerabilities that can be exploited by attackers and prevent attacks on web applications, mobile apps and APIs.

- Gartner predicts that by 2027, 30% of large global enterprises will use OWASP Top 10 as part of their security testing processes.

**Pair Programming**: A programming technique in which two developers work together on a single task, sharing their screens and keyboards.

**Penetration Testing**: A simulated cyber attack on a computer system or network to test its defenses and identify vulnerabilities. Some of the open-source penetration testing tools are Nmap, Metasploit, and Burp Suite.

**Pull Request**: A request submitted by a developer to add new features or changes to an existing codebase. It is reviewed by other developers before being merged into the main codebase.

**Refactoring**: The process of improving the internal structure and organization of existing code without changing its external behavior.

**SAST**: Static Analysis for Security Testing - A type of security testing that uses automated tools to identify vulnerabilities in an application's source code. Some of the open-source SAST tools are OWASP ZAP, Veracode SCA, and SonarQube.

**Security Auditing**: The process of evaluating an organization's or system's security controls to ensure they meet certain standards and regulations.

**Security Testing**: The process of identifying vulnerabilities in a system or application to improve its overall security posture.

**Service-Oriented Architecture (SOA)**: A software development paradigm that structures an application as a collection of services that can be accessed and used by other applications.

- _Advantages_:

  - Improved scalability and flexibility
  - Increased fault isolation and reliability
  - Easier maintenance and updates
  - Faster time-to-market

- _Disadvantages_:
  - Higher complexity and overhead
  - Potential for increased costs
  - Requires careful service design and implementation

**Shadow IT**: Shadow IT is the introduction of new tools and technology without the knowledge or approval from the IT department. And it’s becoming a big concern since IT is no longer the only source for developing apps. For more info, refer to [this link](https://www.techtarget.com/searchcloudcomputing/definition/shadow-IT-shadow-information-technology).

**Singleton Pattern**: A creational pattern that restricts a class from instantiating multiple objects.

**Site Reliability Engineer (SRE)**: SRE is a job function, a mindset, and a set of engineering practices to run reliable production systems. Google Cloud helps you implement SRE principles through tooling, professional services, and other resources. For more info, refer to [this link](https://cloud.google.com/sre).

**Software Engineering Intelligence**: For more info, refer to [this link](https://www.getport.io/glossary/software-engineering-intelligence-platform).

**Sprint**: A time-boxed period (typically 2-4 weeks) during which a team works on a subset of the backlog. The goal is to deliver a potentially shippable product at the end of each sprint.

**Sprint Planning**: A meeting at the beginning of each sprint to determine the tasks to be completed.

**Sprint Review**: A meeting at the end of each sprint to showcase the work completed and get feedback from stakeholders.

**Sprint Retrospective**: A meeting at the end of each sprint to reflect on what went well and what could be improved for the next sprint.

**Team**: A group of individuals with different skills and expertise who work together to achieve a common goal.

**Technical Debt**: The cost of implementing quick fixes or workarounds that need to be addressed later. It can lead to increased maintenance costs, decreased productivity, and reduced quality over time. For more info, refer to [this link](https://www.gartner.com/en/infrastructure-and-it-operations-leaders/topics/technical-debt).

**Value Stream**: Value Streams represent the series of steps that an organization uses to implement Solutions that provide a _continuous flow of value to a customer_. A SAFe portfolio contains one or more value streams, each of which is dedicated to build and support a set of solutions, which are the products, services, or systems delivered to the Customer, whether internal or external to the Enterprise. It is the sequence of activities an organization undertakes to deliver on a customer need. It comprises the end-to-end delivery process, from idea to outcome. For more info, refer to [this link](), [Planview: How to identify your value streams](https://info.planview.com/rs/456-QCH-520/images/Identifyng-Value-Streams.pdf) and [How to Identify Your Value Streams: 6 Strategies for Getting Started](https://blog.planview.com/how-to-identify-your-value-streams-6-strategies-for-getting-started/).

**Value Stream Management**: It is the practice of measuring and improving end-to-end flow, eliminating dependencies and bottlenecks to unlock capacity and deliver value more efficiently. The [Flow Framework](https://flowframework.org/) is a blueprint for practicing value stream management. It provides guidance on how to map and measure product value streams to gain full visibility into the work and its impact on business outcomes.

**Value Stream Mapping**: A technique used to visualize and analyze a process to identify areas for improvement, by identifying value-adding and non-value add steps in the process.
For more info, refer to [this link](https://www.lean.org/the-lean-post/articles/understanding-the-fundamentals-of-value-stream-mapping).

**Version Control System (VCS)**: Software that helps manage changes to source code over time. Some popular VCS tools are Git, SVN, and Mercurial.

**Vertical Slice Architecture (VSA)**: In this style, my architecture is built around distinct requests, encapsulating and grouping all concerns from front-end to back. You take a normal "n-tier" or hexagonal/whatever architecture and remove the gates and barriers across those layers, and couple along the axis of change. For more info, refer to [this link](https://www.jimmybogard.com/vertical-slice-architecture/) and [VSA by Milan Jovanovic](https://www.milanjovanovic.tech/blog/vertical-slice-architecture).
