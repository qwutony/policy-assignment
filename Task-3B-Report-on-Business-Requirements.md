# Task 3B: Report on Business Requirements and Produce Proposal for Implementation of Technology

------------------------------------

## T3B1: Analyse your research and the feedback you have received from Task 3A relating to business priorities:

- finalise a list of at least THREE business priorities or more that you have identified from your research and on the basis of feedback
- for each business priority, identify how the technology you propose may assist the business to achieve its priorities (2 - 3 sentences for each priority maximum).

Business Priorities of Facebook
1. To continue the globalisation of the provision of Social Networking services around the world. Rapid and efficient deployment of standardized systems can be implemented by Docker, minimising the cost of expansion. 
2. The envisionment of a private social network, both client-side and server-side. Using Docker to create separate containers allows for improved privacy and isolation of sensitive information.
3. Drive increased cost savings and return on investment for shareholders. Docker can dramatically reduce infrastructure resource use and intensity, since fewer resources are needed to run the same application.

------------------------------------

## T3B1: Define the client's business domain by describing in your own words what the business does and listing the THREE business priorities you have identified from your research.

The clients that we are acting for is Facebook. Facebook is a social networking website that allows users to comment, share and post links, as well as chat live through Messenger, and share photos and memories through Instagram. There are many other functionalities that Facebook possesses, such as being able to play games or order food or share content and make it publicly accessible. It is also possible to share within a certain selected group, or page of people.

Facebook initially began as a social networking website at Harvard University, and through Mark Zuckerberg guidance, it became popular and overtaking MySpace, which was the rival social network in the world at that time. Facebook's ability to appeal to people and businesses is the reason why it attracts many people to the website. Anyone who is not technically minded can also sign up and use Facebook, and its user-friendliness further contributes to its success. The business itself has since grown, and there are more 'experiences' that have been adopted by the company, including Facebook and Messenger, Instagram, and WhatsApp. 

The main mission of the client's business domain is to be able to allow more and more users to connect on the platform, and as such, allow more people to adopt using the internet, share their ideas, experiences, and to communicate with friends and families in an easy and efficient method. 

As such, there are many business priorities that Facebook emphasizes on. The first is to continue the globalization of the provision of social networking services around the world, and to allow more and more people to connect to the internet and to connect to social networks. The second is the vision of a private social network where users can be able to communicate through private interactions with encryption and safety and interoperability to communicate through different networks and different applications. And finally, Facebook wants to increase cost savings and return on investment for shareholders. Since it's a large public company, Facebook prioritises its shareholders and wants to continue, generating profits for them.

--------------------------------------

## T3B2: Outline the features of the technology and how they will benefit the organisation.

Historically, in cloud computing, virtual machines have been used extensively, because they have the advantages of isolation and resource control, allowing a single operating system with its own memory management to create more operating systems through a hypervisor, and run several individual applications that are separate to the host machine. Thus, separating each server into many operating systems can allow more applications to be run efficiently.

Docker containers have much more potential than virtual machines, because a Docker container is able to share the resources of a single kernel and operating system, as well as application libraries, instead of having a hypervisor and creating more operating systems on top. Therefore, each system will only run a single operating system. This means that Docker containers have a lower system overhead than virtual machines and can perform similar or better when running an application in comparison to virtual machines, but can comparatively run more applications on a single server than its respective counterpart. As such, the use of containerization of applications and Docker makes it easier to create deploy and run applications by using containers.

Another advantage is that Docker can package up an application, with everything that it needs, including libraries and other dependencies and ship it out as a single package. This means that developers, or people from other countries who require the same standardized system can be able to deploy Docker containers in a rapid method, and thereby reducing the overhead costs, and the costs needed to deploy the infrastructure in a timely fashion.

Moreover, the benefits to Facebook itself, is that Docker offers a higher return on investment and cost savings than its comparisons. When performing managerial decisions in an institution or corporation such as Facebook, selecting a product with a highest return on investment will oftentimes drive down costs and increase profits, and especially in the case of large established companies such as Facebook, they need to continue to generate steady profits on the long term, in order to attract shareholders. Docker can facilitate savings on this scale by reducing infrastructure resources. As mentioned previously, Docker is more efficient than virtual machines. When compared directly, there are fewer resources needed to run the same application. Because of these reduced infrastructure requirements, organizations can save server costs, as well as the employee overhead needed to maintain them since Docker images can be easily deployed. And this allows the teams to be smaller and more effective.

As mentioned, containers also allow for standardization. Since Facebook has an objective of globalization. It's the biggest issue is that service must be constantly deployed in each country. And these servers may not be exactly the same as the ones in America or the headquarters, Docker base architecture allows standardization, because it is possible to create a container, and then, commit changes to the Docker image.

Docker containers are more secure. Docker ensures that applications and resources can be isolated and segregated. If there is a breach in a Docker container, the malicious orchestrator will find it a difficult time in actually controlling the server itself rather than simply a Docker image, and therefore, from a security perspective, Docker ensures that applications are completely segregated and allows the server controller to be able to manage the traffic flow to him from the container. So from an architectural point of view, each container has its own resources, and therefore will be unable to be breached, and other resources, be used.

---------------------------------------

## T3B3: Research current industry accepted hardware and software required to implement the technology you have chosen.

Describe both the software and hardware requirements and general features of these required for the project.

Docker is a very versatile software platform, and thus it doesn't have a difficult requirement for software and hardware. In order to run Docker Daemon and some very light containers, it will need a minimum of 512 megabytes of CPU. Docker itself can also be run on many low performance devices, such as a Raspberry Pi, or the Beaglebone black, and therefore, the hardware requirements isn't very difficult as well.

The intention of Docker, is to allow a server to maximize its resources, so it will also try to keep its software and hardware requirements to a minimum, such that it will also increase the resource usage efficiency of the server.

-----------------------------------------

## T3B4: Outline the role of stakeholders within the business and the degree of involvement that would be required in the process of implementing your chosen technology. 

Your outline must include:
- details about who and what teams or parts of the business will need to be involved and consulted during the implementation of the technology
- details about stakeholders external to the company and how they will be involved in the project

There are many different stakeholders both within the business and outside of the business that would be involved in the process of implementing Docker. The first stakeholder would be the shareholders of the company. The shareholders of the company prioritize on generating a profit, and therefore increasing their own bottom line. The shareholders will want to know if implementing the technology of Docker would allow them to generate more revenue and in return, achieve the company's goals and ambitions. If the shareholders, do not agree with the investment of Docker, they can hold a shareholder's meeting to propose a new solution or rejected Docker entirely.

Another and more important stakeholder for implementing Docker technology is Management. Management includes the CEO, the CTO and other related Chief officers must get together and discuss whether implementing Docker would provide benefits in the short, medium and long term futures for the company. In the circumstance where there are disagreements within Management, the implementation of the technology may be put on hold, or rejected altogether.

When discussing what teams or parts of the business will actually be involved or consulted during the implementation of the technology, the most important teams are the development, security and operations team. The development team will perform work with the Docker company for enterprise integration and allow a seamless transition from the current infrastructure that Facebook is using to Docker. The security team, which is led by the CISO would primarily investigate whether Docker as a third party application would be safe to be implemented in Facebook, and to find vulnerabilities and other issues that may arise. The operations team formulates a connection between the development security and management teams, and is responsible for the day to day operations for managing Docker.

In terms of other stakeholders, there can be third party applications that Facebook is already partnered with that should be notified of a transition from Facebook's current infrastructure to Docker and allow the third party applications to understand the implications and consequences that may arise from using Docker as an application. Furthermore, creditors, and other people who Facebook are associated with should be notified as this can influence their business decisions.

-----------------------------------------

## T3B5: Specify how you will implement at least TWO quality assurance practices when determining the scope and requirements of the implementation plan. You must: 

- provide detail about how you will conduct the quality assurance
- explain what it will demonstrate and how it will provide an assurance of quality

Quality assurance practices can include conducting a risk analysis of a network or system to provide assurance that security controls exist to address security issues, testing the technology at scale, conducting case studies of other projects where the same or similar technology has been implemented.

There are several quality assurance practices that will be implemented to ensure that Docker falls within the scope and requirements of the implementation plan.

The first Quality Assurance practice is to test the technology at scale, to determine the effectiveness of Docker when implemented within a server or within a network of servers, before it is to be deployed by Facebook at large. The first implementation will be done through unit testing on a single server, where a Docker daemon will be installed, and several containers will be run at maximal performance to see just how many containers can be run for a given amount of resources.

Secondly, a network testing Quality Assurance practice will be implemented, and this will be to run several Docker Daemon's across a network of servers and have them to be interconnected to determine the efficiency that Docker provides on a network basis.

In order to analyze the risk that comes with implementing Docker and transitioning from a prior infrastructure, case studies of other projects where a similar technology has been implemented will be used to conduct a test. The tests can include consulting other firms to see if the technology that was implemented has actually created a benefit, or hire independent researchers to determine these statistics. Moreover, In order to determine risk, penetration testers will be hired to perform vulnerability assessments, as well as penetration testing on servers that have Docker installed and determine if there are any security issues that needs to be addressed.

------------------------------------------

## T3B6: Examine the system's current hardware, software and communication functions and describe them in general terms. Note: you may need to conduct some research and speculate on elements of this if information is not available.

A hardware function is any individual device or cluster of devices which support a business function, for example: a server and proxies which allow connectivity with different systems.
A software function is any piece of software or code which supports a business function, for example: an operating system, an application or service such as a web server, database, or other service that relies on a software application.
A communication function is any aspect of a system that involves communication between systems or the infrastructure that enables that communication to support a business function. For example: a business premises may have multiple floors and have their network connected by fibre optic cable, a business may have multiple geographical locations and have a system which supports geo-redundancy, or dedicated data-lines between locations and/or systems.

Facebook has many up to date, hardware, software and communication functions that are required for its day to day operation.

In 2017, it released its new server hardware fleets which features the Bryce Canyon, which is a major storage chassis that is used primarily for high density storage with increased efficiency and performance. It allows for the support of up to 72 HDDs, to be stored in a single chassis, which allows for more powerful processes and memory footprint of up to four times larger than its predecessor.

Moreover, it also has a GPU server known as the Big Basin, which allows high performance training of larger and deeper neural networks. This allows a memory size to be increased to 16 gigabytes. It also features a dual socket motherboard, known as the Tioga Pass, as well as a platform, known as Yosemite V2, which is a new form of computing platform.

In terms of software that Facebook uses in its systems, in some way, it is still a LAMP site, because it uses Linux, Apache, mySQL and PHP to extend its operations. However, even though Facebook still uses PHP, it has a built-in compiler, which allows native code to be used on its web servers and therefore boosting performance.

Facebook also uses Linux, but it is optimized for its own purposes and Facebook uses mySQL as a key-value storage, and this allows web servers to be easily optimized and performed.

There are also many other custom systems, such as Haystack, which is a highly scalable object storage system that is used to store the amount of photos that Facebook has. There is also Scribe which has a login system that can operate at Facebook scale, other pieces of software include memcached, Cassandra, which is Instagram, Hadoop, and Hive.

Finally, in terms of communication functions. The business premise itself has multiple floors, that are all connected by fiber optic cables, and the business has many different geographical locations including a West Coast and East Coast data center in America, and has a system which allows the movement of traffic among data centers to be more efficient in circumstances of disasters. This is coined 'Maelstrom' by Facebook, and allows for constant rigorous health monitoring and safety check processes which ensures that when disaster occurs in the ever changing environments of data that large amounts of data can be moved at a rapid pace to quickly replenish these data centers.