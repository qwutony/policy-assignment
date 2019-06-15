# Task 4D - Develop Recovery Plan and Re-evaluation Plan for System

----------------------------------

## T4D1: Outline the objectives of the security recovery plan and define the incident(s) it addresses.

The objective of a security recovery plan is to ensure that an organization can respond to an event of a security breach, or other security related incidents that affects the information system, and does minimize the effect of the incident on the organization.

An incident in this circumstance, can be a security breach in the most dramatic situation, but it can also entail other circumstances, such as a loss of data on accidental, or other security problems such as password policy breach.

-----------------------------------

## T4D2: Define the following regarding the recovery plan:

- maximum allowable downtime

- recovery time objective: how long will the recovery take?

- which software, hardware and infrastructure will be required to implement the recovery plan

Maximum Allowable Downtime, or otherwise known as Maximum Tolerable Downtime, is the maximum time a business can tolerate the unavailability of a particular business function. This is dependent on the business, and the problematic function. The tolerable downtime varies drastically, and is directly correlated to the expenses incurred by the business to fix the issue.

The recovery time objective is the time that is available to recover the resources from the disrupted system, and this is typically a part of the maximum tolerable downtime. It is the time that the business process can be retrieved from others backup systems, and then re-implemented into the original system.

The work time or work recovery time is the second segment of the maximum tolerable downtime, and this is the time that is required in which the software, hardware and infrastructure is required to get the critical business functions, back up and running in the system. There are many types of software, hardware and infrastructure that are required and this is dependent on what sort of security problem it is.

-----------------------------------

## T4D3: Describe the following:

- who is responsible for activating the plan?

- who are the people/roles required to implement the recovery plan?

- approved workarounds while the recovery plan is in effect or if the recovery plan fails or takes longer than the recovery time objective

The security recovery plan should be clearly defined with key roles, responsibilities and parties involved that are found in the policy. In the circumstance where a security recovery plan is needed, the activation of the plan lies with the highest ranking personnel that is responsible in that department. In the case where there's a security breach, that will be the chief information security officer. They would activate the plan, and then all personnel who are responsible would be required to implement the recovery plan. 

These include security teams that are hired as employees or other members of the development team and operations team, who have a security background or focus in the institution, and these people should have responsibilities in order to ensure that the that the recovery plan is as efficient as possible.

While the recovery plan is in effect, there should be approved workarounds in circumstances when the recovery plan fails or takes longer than the recovery time objective. These approved workarounds could be creating new servers that are automatically backed up by another server or to recreate the database using the limited information that is still stored on the server or to create other methods of providing services in the circumstance where a service is breached.

-----------------------------------

## T4D4: List the steps required to implement the recovery plan.

You must:

- write at least 5 steps

- have enough detail in each step to allow a technical person with some familiarity of the system to follow

Note: to minimise the detail your steps require you can refer to security policies or procedures that go into more detail, but you should give context and an explanation for how other documentation fits into the recovery plan.

In the event of a security issue with the Ubuntu server, there are several steps to follow to ensure the highest rate of recovery.

If the recovery is expected on new hardware, then ideally there should be a new OS installation from scratch. This includes consideration of obtaining new hardware, as well as an installation CD.If the installation is a virtual machine, it is easier to set up, than hardware.

Next, it is important to know the packages that should be installed to reproduce that server. Since the Ubuntu server is a completely new one with no additional installations, then this should be a fairly simple process. In the event where it is not, there are also custom configurations that should be remembered.

Some servers have methods of restoration of data, and the recovery plan should have insight into how to configure these in such a manner that would allow the restored data to be obtained, rather than to start off blank again. However, in some circumstances, the data that is restored may be older than in comparison to the one on the server. That may or may not be a problem, depending on the circumstance.

Also consider if there's a secondary server, and allow for the secondary server to copy the backup data using replication. However, there is an acceptable loss of data for each company, and that should be considered when performing a backup. Each server should have documentation, which lists any changes that have been made from a default server installation.

These problems can all be solved, but depend greatly on the specific environment.

---------------------------------

## T4D5: Review risk analysis program and develop a plan to re-evaluate system and identify new threats and risks. Your plan must:

- include a list of FOUR triggers for re-evaluation of the system, the threat model, and the risk assessment

Several triggers can cause the reevaluation of the system, the threat model and the risk assessment.

In the circumstance where the system completely fails, then it means that there is still a significant problem that should be addressed immediately. This could be related to the previous problem, or it can be unrelated, and should be regarded as another threat, that should be addressed with a new security recovery plan. It is very important to begin the re-evaluation of the system earlier.

Another trigger that can result in a re-evaluation is if there is the release of a vulnerability that affects the system in question, and this vulnerability can possibly cause harm, such as allowing a malicious orchestrator to run arbitrary code or to do something that's the organization does not intend to do. The plan should be developed in a way that will allow for re-evaluation of the system to identify these new vulnerabilities and rate them using the risk matrix.

In the event where there are multiple circumstances have failed multi-factor authentication by external users and these are all stored in a log file, the trigger should be activated. A re-evaluation of the system is necessary to determine if the system has been breached, and that if it poses a risk because other users and employees who have access to the system may be used as a attempt to privilege escalate onto other important systems in the organization.

Finally, another trigger should be a time-based trigger for re-evaluation on the system, because most old systems probably have vulnerabilities that remains undiscovered by both hackers and security professionals alike. And therefore, the reevaluation of a system that is perhaps several years old, should be done so with prudence.

--------------------------------

## T4D6: Develop a plan to check authoritative sources of information to identify threats and risks. Your plan must:

- provide THREE sources of information to be checked which provide security benchmarks (the sources of information must be authoritative which means it is from a hardware/software vendor or security specialist with recognised qualifications and reputation in industry)

- state the frequency of the checks

- define the purpose of checking each source of information and what part of the system it relates to

- how the checks are to be recorded and who is responsible for reporting new threats and risks

The three sources of information to be checked, which provides security benchmarks for the service in question are the CIS benchmarks, which stands for the Center of Internet Security, the Ubuntu Linux company, as well as the Lynis auditing system.

The CIS benchmarks give detailed checklists which allow for the determination of system hardening and security of the server. Moreover, the CIS benchmark, is the best practice standard for Linux based systems, and therefore is the go-to when determining threats and risks for these servers.

In order to determine the frequency of checks, it is dependent on the frequency of rebooting, and every time there is a new installation and boot up the Linux benchmark should be checked against the system.

Similarly, by using the Lynis auditing system, as well as the guidelines set out by the Ubuntu Linux company, they will be able to assist as secondary information to determine the threats and risks associated with the Ubuntu machine. As such the frequency of checks should be the same as the CIS benchmark.

The purpose of checking each source of information is for a well rounded scope in determining what is required for a system hardening to take place. The checks should be recorded into a file and documented for new threats and risks. The chief information security office and the security team are responsible, and it should be reported directly to higher-ups if there are any business impacts from the breach.

--------------------------------