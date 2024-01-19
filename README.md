# About-SRE
Objective: About SRE and SLI, SLO and SLA:
 
SITUATION: In a system cloud services, servers, database, networks are the services we rely on, sometimes there are outage issues that will decrease your business and customers and decrease the release process so to make sure the downtime is very low SRE-Site reliability engineer comes into picture.

TASK: As an SRE task is to create automation process for CI/CD and monitoring the loggings of system and to have the visibility. Create alert messages in detail with CloudWatch, Datadog SNS alerts and Prometheus depends upon the infrastructure. To make the outage short and to identify as soon as possible that can be done my SLI's and SLO's.

ACTION: SRE must be focusing on fixing the issues and detecting them early. SRE needs to have a thorough analysis of the issue and need to document for future purpose. Must collaborate with different teams by having a daily stand-up calls. The difference between DEVOPS Engineer and SRE is that Devops is more of what to implement and SRE is more of what to.

SLI and SLO’S: They have clear numerical indicators for defining that availability and the way that we go about doing that is by defining not just service level objectives that service level indicators to make the service more available.
so, services are most often metrics over time such as 
  >For latency be throughput of request per second. 
  >In a case of a batch system or failures for total number of requests that usually aggregated over time
   they are set by the threshold value. 

SLA: SLA is a service-level agreement and what it does is it says here is what I am going to do is I do not meet the level of reliability that is expected it is more of a kind of commercial agreement that describes what remediation you are going to take if your service is out of spec according to the contract, that is made between customer and the service provider.
-In collaborating with the product owners try to take SLA it is sort of an agreement to meet the services more productive, by agreeing on these metrics in advance we make sure that there is less of a chance of confusion and conflict in the future.
-Service provider must pay a lot of money or free credits to customer if failed to deliver the exact services agreed according to the customer.

RESULT: so, to summarize SLI's or service level indicators or metrics over time which inform about the health of a service which reduces the latency, Time load, Browsing time etc.
Ex: 95% of latency in the homepage request over past 5 min in < 300min.

-SLO's (service level objectives) which are agreed upon bounds for how often those SLI's must be met and finally they pop out automatically the objects to reach the target which were agreed like LB, ASG containers in Kubernetes make architecture more efficient.

-With that SLA's that are business level agreements which define the service of availability for our customer and the penalties for failing to deliver that availability helps to meet the targets like
  >Payment is done when 95 % less in latency issues i.e. if the SLI does not go down 99% less i.e. only few days in a year which increases customers.
