## Cybersecurity Course - Daily notes

## Date: December 13, 2025
## Topics: Risks, Threats and Vulnerabilities

CIA Triad -- Confidentiality, Integrity and Availability 

Confidentiality - Only specific people have access to specific data
Integrity - The data has to be correct, authentic and reliable
Availability - Data has to be accessible to those who are authorized to access it

CSF - A voluntary framework that consists of standards, guidelines, and best practices
to manage cybersecurity risk

The CSF focuses on 6 core functions: Govern, Identify, Protect, Detect, Respond and Recover
that I've seen previously in the course.

For now we're going to see how CSF helps organizations in defending data
Example:

Imagine that one morning at work, you receive a high risk alert: an unknown device is connected 
to the organization. You DETECT and IDENTIFY who, why and where the attack is coming from, PROTECT the organization
by isolating the device, RESPOND by investigating the attack and RECOVER the data that was infected 
in the attack.

In this example, we can see how the CSF can be important, guiding the cybersecurity analysts.

## 6 Core Functions of the NIST CSF Structure

## Govern

- Establishing and maintaining policies, procedures, and risk management strategies that guide the organization's
cybersecurity approach.
Example:
As a security analyst, you may participate in developing security policies that define who has access to sensitive data,
or help create incident response procedures that the team must follow when a breach occurs. You might also work with management to assess
which assets are most critical to protect based on business priorities.

## Identify

- The management of cybersecurity risk and its effect on an organization's people and assets 
Example:
As a security analyst, you may need to monitor the devices on an internal network to identify
potential security issues.

## Protect

- The strategy used to protect an organization through the implementation of policies,
procedures, training, and tools that help mitigate cybersecurity threats
Example:
As a security analyst, you and your team may encounter new and different threats and attacks. For this reason,
studying historical data and making improvements to procedures is essential.

## Detect

- Identifying potential security incidents and improving monitoring capabilities to increase
the speed and efficiency of detections
Example:
As an analyst, you will need to configure a new security tool to verify if it's flagging low, medium or high risk
and alerting the security team about any potential threats or incidents.

## Respond

- Making sure that the proper procedures are used to contain, neutralize, and analyze security incidents, and implement improvements to 
the security process
Example:
As an analyst, you could be working with the team to collect and organize data, to document an incident and suggest
improvements to the process to prevent the incident from happening again.

## Recover

- The process of returning affected systems back to normal operation
Example:
As an entry level security analyst, you may work with your security team to restore systems, data and assets
such as financial or legal files, that have been affected by an incident like a breach.

# OWASP - Open Web Application Security Project

## OWASP Security Principles

- Minimize attack surface area
Minimizing the attack surface area involves protecting and preventing vulnerabilities in the surface area,
such as weak passwords and phishing, which can be prevented.

- Principle of least privilege
Having a limit on the privileges of every employee can be useful to prevent attacks.
For example:
If one of the employees has been hacked, the threat cannot have access to the data and assets that they may have wanted,
making the hack useless for the threat.

- Defense in depth
This principle focuses on having different and multiple ways to protect the organization,
such as MFA authentication or smart firewalls.

- Separation of duties
This means that it is not a good idea to give many privileges to one person.
For example: the person in a company who signs the paychecks should not also be the person who prepares them.

- Keep security simple
As the name suggests, when implementing a security solution, unnecessary complexity should be avoided.
The more complex a security solution is, the harder it is for the people in the company to collaborate.

- Fix security issues correctly
This principle means that when a vulnerability or security flaw is discovered, it has to be fixed
completely and properly. This includes understanding the root cause, testing the fix, and documenting the solution
to prevent similar issues from happening again.

## How to Stay Updated About Cybersecurity?

Staying updated in cybersecurity is very important. By knowing the different threats and vulnerabilities in cybersecurity,
you can become a more efficient professional. This task is simple: just by following
sites, blogs and using AI such as Perplexity, Claude or ChatGPT to get the most recent news about cybersecurity can help you in your daily
work. You can follow sites like Medium, Hacker News and more to see the most recent news.
For example:
I follow these types of "cybersecurity journals" and I learned about a new type of malware: how it works, how to defend against it, how it can be used and how to prevent it.
I also learned about the Cloudflare attack with 11 TB of DDoS, and how to protect against DDoS attacks.

## Now that we covered the most important principles, the question is... How it all work together?

## Security Audit

- A review of an organization's security controls, policies, and procedures against a set of expectations
There are 2 types of security audit: internal and external

## Internal Audit

An internal security audit is used to help improve an organization's security posture, and can help a security team in:

- Identify organization risk

- Assess controls 

- Correct compliance issues

## Common elements of internal audits

- Establishing the scope and goals

- Conducting a risk assessment 

- Completing a control assessment 

- Assessing compliance 

- Communicating results

## Scope

Scope refers to the specific criteria of an internal security audit 
- Scope requires that organizations identify people, assets, policies, procedures, and technologies that may impact the organization's security posture
 
## Goals

Goals are an outline of the organization's security objectives. 
- Although more senior level security team members usually establish the scope and goals of the audit,
entry level security analysts may be asked to review and understand the scope and goals to complete other elements of the audit

## Risk assessment

Risk assessment is the systematic process of identifying, analyzing, and evaluating potential security threats and vulnerabilities that could harm
an organization's assets, operations, or data. It involves determining the likelihood of threats occurring and the potential impact they would have,
enabling organizations to prioritize security measures and allocate resources effectively

## Key components

- Asset identification
What needs protection (data, systems, infrastructure)

- Threat identification 
What could go wrong (hackers, malware, natural disasters)

- Vulnerability analysis
Weakness that threats could exploit

- Impact assessment
Potential damage if threat occurs

- Likelihood evaluation
Probability of the threat happening 

- Risk prioritization
Ranking risks to address the most critical first
