20.03.2024 - Rafe Fitzpatrik
Isights from Devops, Technical Architecture and cloud Engineering

Security
LO3.7.2.4
User experience design
Investigate the key steps in managing security incidents and how to apply them.
This is a cybersecurity learning outcome, so you need to find relevant resources.  You want to merge case studies which you can find online on when this happens for real, ask guest speakers, and also what you would do in your own project.  For example, what happens if an API key is made public? What are the actions you would do to fix the situation? 

Q: As a DevOps engineer, what actions do you suggest to properly manage security?

* Avoid adding passwords into code
* Implement logging, monitoring & alerting
    * Observability is a key tenet of DevOps
    * Understanding what is happening in my system
    * Knowing what good looks like and what bad looks like
    * Tracking processes
    * User experience
    * Relevant alerting
* Data Governance
    * Understanding what data profiles you are dealing with, as it can affect logging
* Operational Tasks
    * Coding to enable these tasks
    * Renewing certificates every month
* Role-based Access Control (RBAC)
    * Getting permission levels into the system on day one
    * Using these permission levels throughout the Route to Live
* Every feature will have different flavors of the above. If you have strategies and patterns set up for design elements, then you have:
    * A common vocabulary
    * An understood way of thinking
    * Leads to common ways of coding Instead of having a super user, different roles should be set, and role-based access control should be implemented.



Technical
LO3.8.1.5
Software release management
Determine configuration management processes for use throughout the product development life cycle in storing software deliverables and controlling and tracking changes to software both at component and release level, using configuration management tools effectively, and apply change management processes properly.
This is all about maintaining common configurations across a wide infrastructure - infrastructure as code.  It includes technologies such as Docker, Kubernetes, Puppet, Chef, OpenShift, Ansible, package.json and similar files.  Your dependencies both software, hardware and cloud move at different rates, how are you going to effectively manage that?  You should think about this from the point of view of 3 stages, a dev infrastructure, a test infrastructure and a production infrastructure.  Each of these is a release cycle and needs to be controlled and repeatable on a regular basis up to 100's of times a day.  Case studies include companies such as Facebook and Netflix.

Q: How should I effectively manage software, hardware, and cloud infrastructure?

* Writing code and deploying it with added configuration while  keeping code and configuration separate.
* Rafde says that in the past, he had basic configuration for separate stages. When he never versioned the code, the old configurations were thrown out with the old artifacts.
Q: What does he mean by not keeping configuration with the code? They keep configuration files separate to freely recreate different configurations and scenarios.

* Really good unit tests allow for a good understanding of requirements for a new person coming in.
* Creating and using patterns.


Security
LO3.9.1.4
Insight from data
Maintain and manage software and hardware patching, particularly implementing vulnerability patching where vulnerabilities are identified. 
Why do you need to do this?  How can you do this in a structured way?  How is it done in industry?  Does it always work?  What happens when it doesn't? Is the risk of failure worse than not doing it?  What is patching anyway?  What is hardware patching?  How do you recover form a bad patching?  What vulnerabilities in the news required patching - think zero day vulnerabilities?  What types of vulnerability are most easily fixed with patching?  How does a company like Microsoft rank how important patches are?

Q: Did you ever have to patch something at your work? Did you find that challenging? 
* Their infrastructure is on virtual machines, AWS Linux, Red Hat, and Windows. From the Amazon marketplace, I can get Windows versions. When creating "golden images," they add basic functionalities, test logs, and performance tests.
* Their patching strategy is on a monthly basis, and they determine when to apply patches. Once they see a vulnerability, they think about applying patches.

How do coding decisions affect DevOps?

* Hard coding
* Configuration living with code
* No test frameworks


MVP is never 'done'

* Many of the examples given are of MVPs that are still 'in life', past the point when MVP 2.0 or 3.0 should have started
* Knowing when to start the next version of MVP and culturally being allowed to do so is hard (do not overcomplicate)
* Good MVPs should uncover the direction of the next iteration
* MVPs should never dictate the decision when to make the next version

