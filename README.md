The cloud can, and most often does, include virtualization products to deliver the compute service, said Rick Philips, vice president of compute solutions at IT firm Weidenhammer. "The difference is that a true cloud provides self-service capability, elasticity, automated management, scalability and pay-as you go service that is not inherent in virtualization."

5 benefits:
ON DEMAND SELF SERVICE
Cloud computing enables end users to provision computing power, storage, networks and software in a simple and flexible way. Most users begin by using limited resources and increase them over time. On-demand self service methodology authorizes users to request resources on run time. This transition mostly takes place immediately, although it can depend on the architecture and resource availability of the cloud provider. 

BROAD NETWORK ACCESS
broad network access." Access to resources in the cloud is available over multiple device types. This not only includes the most common devices (laptops, workstations, etc.) but also this includes mobile phones, thin clients and so on. characteristic and enabler

RESOURCE POOLING
"Resource pooling" is a fundamental premise of scalability in the cloud. Without pooled computing, networks, and storage a service provider must provision across multiple "silos" or discrete, independent resources with few or no interconnections. Multi-tenant environments, where multiple customers share adjacent resources in the cloud with their peers, are the basis of public cloud infrastructures. With multi-tenancy, there is an inherent increase in operational expenditures, which can be mitigated by certain hardware configurations and software solutions, such as application and server profiles.

MEASURED SERVICE
"Measured service" indicates that usage of these "pooled resources" is monitored and reported to the consumer, providing visibility and transparency to consumption rates and costs. Usage monitoring, for the purposes of chargeback (or merely for cross-departmental reporting and budgeting) has been a long-time requirement of IT stakeholders -- another holy grail it seems -- but building such a system is usually not a core competency of most IT departments.

RAPID ELASTICITY
The final trait highlighted in the NIST definition of cloud computing is "rapid elasticity." Elastic computing is critical to cost reductions and time to market (TTM). Indeed the notion of elastic resources in the IT supply chain is so desirable that Amazon named their cloud platform "Elastic Compute Cloud" ("EC2"). In terms of FTE costs, as I will demonstrate in later chapters, the OPEX associated with provisioning (moves, adds, and changes or MAC) in the IT supply chain are typically the most significant portion of the charges related to application deployment.

--------------------------------------------------------------------------------

CONTROLLING COST
Reasons of waste:
	Complexity of Cloud Pricing and Bills
	Constant Change from Cloud Providers
	Decentralized Adoption of Cloud
	
Biggest waste:
	Over-provisioned instances
	Idle instances
	Selecting higher cost instance types or regions
	

MANAGEMENT COMPLEXITY
	Dynamic infrastructure
	The pace of innovation
	Lack of integrated management
	New distribution of ownership
	Specialised knowledge
	
RAPID DEMAND FOR CHANGE
	The various cloud systems management tools promise a broad suite of capabilities. First, technicians spend a lot of time bouncing from screen to screen to manage computing infrastructure. With some products, IT techs work from a single interface of consolidated cost and performance data. Today, corporations release software at a faster pace than ever before; new deployments are ready with the push of a few buttons. "One gaming company that we work with made 100 to 125 changes per month a few years ago," said Peter Scott, COO at DivvyCloud. "Now, the company makes thousands of changes per hour."

----------------------------------------------------------------------------------

SPEED AND SIMPLICITY	
IaC allows you to spin up an entire infrastructure architecture by running a script.

Not only can you deploy virtual servers, but you can also launch pre-configured databases, network infrastructure, storage systems, load balancers, and any other cloud service that you may need.

You can do this quickly and easily for development, staging, and production environments, which can make your software development process much more efficient


CONFIGURATION CONSISTENCY
Standard operating procedures can help maintain some consistency in the infrastructure deployment process. But human error will always rear its ugly head, which may leave you with subtle differences in configurations that may be difficult to debug.

IaC completely standardizes the setup of infrastructure so there is reduced possibility of any errors or deviations. This will decrease the chances of any incompatibility issues with your infrastructure and help your applications run more smoothly.

MINIMIZATION OF RISK
Imagine having a lead engineer be the only one who knows the ins and outs of your infrastructure setup. Now imagine that engineer leaving your company.

What would you do then? There’d be a bunch of questions, some fear and panic, and many attempts at reverse engineering.

INCREASED EFFICIENCY IN SOFTWARE DEVELOPMENT
Developer productivity drastically increases with the use of IaC. Cloud architectures can be easily deployed in multiple stages to make the software development life cycle much more efficient.

Developers can launch their own sandbox environments to develop in. QA can have a copy of production that they can thoroughly test. Security and user acceptance testing can occur in separate staging environments. And then the application code and infrastructure can be deployed to production in one move.
You can also include in your IaC script the spinning down of environments when they’re not in use. This will shut down all the resources that your script created, so you won’t end up with a bunch of orphan cloud components that everyone is too afraid to delete. This will further increase the productivity of your engineering staff by having a clean and organized cloud account.

Cost savings
Automating the infrastructure deployment process allows engineers to spend less time performing manual work, and more time executing higher-value tasks. Because of this increased productivity, your company can save money on hiring costs and engineers’ salaries.

As mentioned earlier, your IaC script can automatically spin down environments when they’re not in use, which will further save on cloud computing costs.

------------------------------------------------------------------------------------

Enforcement. Configuration enforcement may be the single most important feature of a configuration management tool. By running regularly and ensuring the machine is configured to the desired state, configuration management tools prevent configuration drift. Configuration drift can happen in a variety of ways: Package updates, live debugging, "helpful" coworkers, etc. Whatever the cause, being able to say with confidence, "This is how this machine is configured," is a great way to shorten incident resolution time and reduce surprises.

Enables cooperation. Configuration management tools make it easier for team members to cooperate. With one change, configuration can be updated across the entire infrastructure. Hand-editing configuration on machines can only lead to unexpected differences. By putting all of the configuration in one place, you can keep from stepping on someone else's (including future you) toes.

Version control friendly. Of course, the best way to enable cooperation is to have everything in a version control system. All of the tools listed below use some form of text for configuration. This means you can take advantage of the benefits of your favorite version control system. The benefits of version control are beyond the scope of this article, but let me assure you from experience that you really, really want your configuration in a version control system.

Enables change control processes. Because configuration management tools are textual and VCS-friendly, you can treat infrastructure changes like code. Changes can be submitted as diffs or merge requests and be subject to code review before approval. Having explicitly enumerated changes with timestamps can make reconstructing incidents much easier. With atomic changes, you can release them at a rate you're comfortable with instead of throwing a bucket of changes at your infrastructure all at once.

Abstraction. Few sysadmins maintain completely homogeneous environments. Even if you're an all-Linux shop, you probably have multiple distros that you support, or at least multiple versions of a distro. With configuration management tools, many of the operating-system-specific implementations of a configuration are abstracted away for you. The same configuration file can be used to manage, for example, the installation of Apache HTTPD on both Red Hat and Ubuntu systems.

------------------------------------------------------------------------------------
