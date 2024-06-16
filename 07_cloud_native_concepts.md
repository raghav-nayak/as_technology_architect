**cloud native** means entire infrastructure is on cloud.


- Disposable infrastructure
	- All infra is easy to dispose off
	- scale down or removal is as simple as adding new components
	- easy to scale up and scale down
- Bounded components
	- each component is focused on its own function
- Isolated components
	- great amounts of isolate to reduce *blast radius* to enhance resilience
- Decision on component by component basis for the specific value based service from a particular cloud provider
- **Multi-cloud vs polyglot cloud**
	- polyglot cloud
		- when you have portability between cloud providers and move between them
		- e.g. using kafka as opposed to kinesis
	- multi-cloud
		- when you actively have services from multiple cloud providers in your architecture
- Vendor lockin
- Reactive properties
	- Responsive
		- cache and cache elimination
	- Resilient
		- bulkheads
	- Elastic
	- Message-driven
		- event streams
- Virtualization, resource pooling and dedicated
	- Virtualization
		- Running virtual computers on abstract layers
	- Resource pooling
		- Serve multiple customers with same resources
	- Dedicated


<hr>

## **Polyglot cloud** vs. **Multicloud**
The terms **polyglot cloud** and **multicloud** refer to different strategies for managing and deploying applications across cloud environments. Here's a detailed explanation of each term and their differences:

### Multicloud
**Definition:**
- **Multicloud** refers to the use of multiple cloud services from different cloud providers (such as AWS, Google Cloud Platform, Microsoft Azure, etc.) to host various workloads, applications, or services.

**Key Characteristics:**
- **Provider Diversity:** Utilizes services from multiple cloud providers.
- **Risk Mitigation:** Reduces the risk of vendor lock-in and provides redundancy.
- **Best-of-Breed Solutions:** Allows organizations to choose the best services from each provider based on their strengths and cost-effectiveness.
- **Geographic Distribution:** Enhances global reach and compliance by leveraging different data centers worldwide.

**Use Cases:**
- A company uses AWS for its machine learning capabilities and Google Cloud for its data analytics services.
- Deploying disaster recovery solutions on a secondary cloud provider to ensure business continuity.

### Polyglot Cloud
**Definition:**
- **Polyglot Cloud** refers to the practice of using multiple programming languages, frameworks, and platforms to develop and deploy applications within a single or multiple cloud environments.

**Key Characteristics:**
- **Language Diversity:** Utilizes various programming languages and frameworks tailored to specific tasks or components within applications.
- **Microservices Architecture:** Often associated with microservices, where different services are built using the most suitable language or technology.
- **Developer Flexibility:** Enables development teams to use the best tools and languages for their specific needs, enhancing productivity and innovation.
- **Integration Complexity:** May require robust integration strategies to ensure seamless communication between services written in different languages.

**Use Cases:**
- A web application with a frontend written in JavaScript (Node.js), backend services written in Java (Spring Boot), and data processing tasks handled by Python scripts.
- Developing a suite of microservices where each service is implemented using the most appropriate language or framework for its specific function.

### Key Differences
1. **Scope and Focus:**
    - **Multicloud:** Focuses on utilizing multiple cloud providers to host services and applications, emphasizing provider diversity and risk mitigation.
    - **Polyglot Cloud:** Focuses on using multiple programming languages and technologies within cloud environments, emphasizing developer flexibility and tailored solutions.
2. **Purpose:**
    - **Multicloud:** Aims to leverage the strengths of different cloud providers, avoid vendor lock-in, and ensure high availability and redundancy.
    - **Polyglot Cloud:** Aims to optimize development by using the best tools and languages for different parts of an application, often within a microservices architecture.
3. **Implementation:**
    - **Multicloud:** Involves managing resources, configurations, and services across various cloud platforms.
    - **Polyglot Cloud:** Involves developing and maintaining codebases in multiple languages and ensuring they work together seamlessly.
4. **Challenges:**
    - **Multicloud:** Managing multiple cloud environments, integrating services from different providers, and maintaining consistent security and compliance.
    - **Polyglot Cloud:** Handling integration, communication, and deployment complexities across different languages and frameworks.

In summary, while both **multicloud** and **polyglot cloud** strategies aim to enhance flexibility and optimize resource usage, they operate at different levels: **multicloud** focuses on the infrastructure and provider diversity, whereas **polyglot cloud** focuses on the application development process and language diversity.
