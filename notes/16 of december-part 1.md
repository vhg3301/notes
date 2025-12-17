# Security tools
## DATA: 16/12/2025
## What i will learn
- Logs
- SIEM dashboards
- Common SIEM tools

## Log 
A record of events that occur within an organization's systems and networks

## Common log sources
- Firewall logs
A firewall log is a record of attempted or established connections for incoming traffic
from the internet. It also includes outbound requests to the internet from within the network

- Network logs
A network log is a record of all computers and devices that enter and leave the network.
It also records connections between devices and services on the network.

- Server logs
A server log is a record of events related to services, such as websites, emails, or file shares.
It includes actions such as login, password, and username requests.

Understanding logs is important, because SIEM tools rely on logs to monitor systems
and detect security threats

## Security Information and Event Management (SIEM)
- An application that collects and analyzes log data to monitor critical activities in an organization
It provides real time visibility, event monitoring and analyzing, and automatic alerts
It also stores all log data in a centralized location
The SIEM tool needs to be configured and personalized to help the organization with more efficiency

## SIEM dashboards
SIEM dashboards use visual elements like charts, graphs, and color-coded alerts to help security analysts work more efficiently. 
Instead of reading through thousands of logs manually, analysts can quickly identify threats, spot patterns, and prioritize incidents at a glance.
Visual data enables faster decision-making and immediate response to security incidents, making it essential for effective threat detection and monitoring.

## Metrics
Key technical attributes, such as response time, availability, and failure rate, which are used
to assess the performance of a software application

# Different types of SIEM tools
## Self-hosted
- This application is installed, configured and maintained by the organization and depends on the organization's infrastructure
They are managed and maintained by an IT department, instead of a third-party supplier
The self-hosted SIEM tools are useful when an organization wants to maintain confidential data

## Cloud-hosted 
- These applications are maintained and managed by a SIEM provider, making them accessible through the internet
Cloud SIEM tools are ideal for organizations that don't want to invest in the creation and maintenance of their own infrastructure 

## Hybrid
- Organizations may choose a hybrid SIEM solution to leverage benefits of the cloud while also maintaining physical control of confidential data

Splunk Enterprise, Splunk Cloud and Chronicle are common SIEM tools that many organizations use to help protect their data and customers

# Splunk
- Splunk is a data analysis platform, and Splunk Enterprise provides SIEM solutions 

## Splunk Enterprise
- A self-hosted tool used to retain, analyze, and search an organization's log data to provide
security information and alerts in real-time

## Splunk Cloud
- A cloud-hosted tool used to collect, search, and monitor log data

## Chronicle 
- A cloud-native tool designed to retain, analyze and search data
Chronicle provides log monitoring, data collection and data analysis
 
Like cloud-hosted tools, cloud-native tools are maintained and managed by the provider
But cloud-native tools are specifically designed to take full advantage of cloud computing capabilities
such as availability, flexibility and scalability, because threat actors are frequently improving their strategies to compromise the confidentiality, integrity and the availability of their targets

# What we covered 
- Logs (firewall logs, network logs and server logs)
- SIEM dashboards
- Common SIEM tools (Splunk, Chronicle)

# Why "part 1"?

These notes are the third module the Google cybersecurity course
But in the same day, i advanced and continued learning, this is why is part 1 

