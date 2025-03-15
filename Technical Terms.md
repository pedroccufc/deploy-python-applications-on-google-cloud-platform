# Technical Terms

**Important!** During the classes, some technical terms related to application storage and network configurations are mentioned. To ensure that the classes do not become too “tied down” to these terms, we have included a brief description of each one below. We suggest that you read them quickly before continuing.

### Infrastructure as a Service (IaaS)
A cloud computing model that provides IT infrastructure resources, such as servers, storage, and networking, on demand and on a pay-as-you-go basis. Instead of purchasing, configuring, and managing their own equipment, companies can rent these resources from a cloud provider. It’s like renting a furnished apartment: you have everything you need to get started, without having to worry about utility bills and building maintenance. With IaaS, you only pay for what you use, and you can increase or decrease the amount of resources as needed.

### Load balancing
A process that distributes internet traffic across multiple servers. This prevents a single server from becoming overloaded and improves the performance of a website or application. In the case of a website, if all visits were directed to a single server, it could become slow or even crash. With load balancing, traffic is divided across multiple servers, ensuring that all visitors have a faster and more stable experience.

### Autoscaling
A feature of cloud computing systems that allows them to automatically adjust the capacity of resources, such as servers or instances, according to real-time demand. Imagine a restaurant: during peak hours, more waiters are needed to serve all the customers. In autoscaling, it’s the same idea: when traffic on a website increases, more computing resources are automatically allocated to ensure that the service remains fast and efficient. This flexibility is essential for optimizing costs, since you only pay for the resources that meet demand at any given time.

### Serverless
A cloud computing model that allows you to run code without having to manage servers. It's like hiring a taxi service: you request a ride and the car comes to you, without having to worry about vehicle maintenance or the route. In the serverless scenario, you write your code and the platform takes care of executing and scaling it automatically, charging you only for the execution time. It's ideal for applications that have peak demand or that need to scale quickly, such as an e-commerce application during Black Friday.

### Backend
Part of an application that the user cannot see directly, but which is essential for its operation. It is like the backstage of a theater: while the audience watches the play, an entire team works behind the scenes to ensure that everything runs smoothly. In the case of a website or application, the backend is responsible for storing and processing data, performing calculations, managing communication with databases and other applications, and ensuring information security. In short, the backend is the “brain” of the application, taking care of all the operations that happen behind the scenes.

### API
An acronym for Application Programming Interface, it is a software intermediary that facilitates communication between different applications, promoting interoperability and code reuse. An API is like a menu in a restaurant. It provides a set of defined rules and functions that allow different applications to communicate and exchange information with each other. Imagine that each application is a chef, and the menu is the API. By following the instructions on the menu, the chefs can prepare different dishes, even if they do not know all the recipes in full. In the world of technology, APIs allow developers to create more complex and interconnected applications, reusing existing functionalities and facilitating the integration of different systems.

### Microservices
An architectural approach that divides an application into small, independent services, each responsible for a single, specific function. Imagine a factory: instead of having one large machine that does everything, the factory is divided into several smaller machines, each specialized in a specific stage of production. Similarly, in a microservices application, each service is like a small machine that works autonomously, communicating with other services through APIs. This modularization facilitates the development, maintenance, and scalability of the application, allowing each service to be updated or replaced in isolation, without affecting the functioning of the system as a whole.

### Container
Container is like a standardized box that encapsulates a complete application, including all its code, libraries, and dependencies needed to run in any environment. It is like a self-contained package, ready to be transported and run anywhere. This standardization facilitates the portability of applications, as it ensures that they work the same way regardless of the operating system or infrastructure where they are executed. Containers are lightweight and share the kernel of the host operating system, which makes them more efficient than traditional virtual machines.

### Kubernetes
Container orchestration platform that automates the deployment, scaling, and management of containerized applications. Like a conductor orchestrating an orchestra, Kubernetes does the same for your containers, ensuring that they all work in harmony. It simplifies the task of managing complex environments, allowing you to focus on developing your applications instead of worrying about infrastructure. Kubernetes offers features such as auto-scaling, load balancing, self-healing, and service discovery, making it an essential tool for anyone working with microservices and cloud applications.

### DevOps
An approach that combines software development (Dev) and IT operations (Ops) practices, aiming to automate and integrate processes between these two areas. Instead of working in silos, development and operations teams collaborate more closely, using tools and methodologies that accelerate software development, deployment, and maintenance. DevOps aims to deliver software faster, more reliably, and with higher quality, allowing companies to be more agile and respond to market demands more efficiently.

### CI/CD
Short for **Continuous Integration and Continuous Delivery** (or Continuous Deployment). It is a set of practices that automates the software development process, from writing code to delivering it to the end user. Imagine a car assembly line: each step is automated and integrated with the next, resulting in a complete car ready for delivery. In CI/CD, code is integrated into the master repository frequently, automatically tested and, if everything is correct, automatically deployed to a production environment. This automation allows development teams to deliver software faster, more reliably and more frequently, responding to market demands more quickly.

### Endpoint
This is the final point of a connection on a network. It is like the entry or exit port of a system, where data is sent or received. Imagine a telephone conversation: each telephone is an endpoint, being the starting and ending point of the conversation. In the context of APIs, an endpoint is the specific address (URL) that a client (another application) uses to communicate with a server. It is like a street address: when you type in the correct address, you arrive at the right house. Endpoints define the actions that can be performed on a system, such as fetching data, creating records or updating existing information.
