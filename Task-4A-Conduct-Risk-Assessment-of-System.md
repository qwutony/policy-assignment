# Task 4A - Conduct Risk Assessment of System

--------------------------------

## T4A1: Research and identify potential threats and threat agents to the system.

Record the following information:

- define the attack surface

The attack surface in a software circumstance is where an unauthorized user can enter a system and extract data from an environment. The attack surface represents the different areas or points where the unauthorized user can enter, and commit to unauthorized actions. An example of an attack vector might be a user input field within a website, or certain protocols or services that are vulnerable to a particular attack, such as a buffer overflow attack.

In this circumstance, the particular system that we are investigating is the Ubuntu. 18.04.01 machine, and there are many entry points in which we can attack the Ubuntu machine using the Lynis auditing system. Firstly, it's important to note that the current Lynis version that we are using is outdated and the problems that may arise include: allowing a malicious user to exploit the system, since it is not patched, but also that the program may result in a incorrect analysis of the system.

Secondly, since this is a fresh instance of the Ubuntu machine, there is no password set for the single-user shell, which means that if a malicious orchestrator can physically access the machine. They can run another software or different operating system, which will allow for the tampering and execution of commands that is unintended by the user, such as resetting the root password, which can cause them to have catastrophic changes to the system.

- list the potential threats and define their likelihood, consequences, characteristics of potential threat agents and the level of risk

There are many different potential threats when it comes to managing a system. These threats can include information security threats such as viruses, worms and other types of malware. In a circumstance where a system is infected with these types of threats, then the consequence may be that certain data may be exploited, or the computer may be rendered incapable of performing its day to day operations.

Another potential threat could be that activists want to extract data from your organization, and performs a attack externally on one of the servers. Since the server is exposed externally, the likelihood of such an attack, could be significant, and the consequence of this attack could be quite high.

The threat that may arise from an outdated version of Linus is that there may be an improper method of auditing the system, which can undermine the integrity of the system, because simple issues may be highlighted differently, and critical issues may not be discovered.

The likelihood of a threat in that it can be abused by the malicious orchestrator is quite insignificant, because there are many difficulties in changing and updating the auditing system for a malicious orchestrated to act on. However, the consequence of not updating may be quite significant, because when performing an analysis the person may not realize that there are some problems to the system, and this can cause warnings or allow the user to be inaccurately guided.

In the second circumstance where password is not set, and physical access can allow an unauthorized user to operate, or create another operating system on the machine can cause potential problems, because a system can be compromised and then data exfiltrated through changing of password or the manipulation of the root level security.

- outline in tabular format FIVE threats and describe the risks they pose

Here are some example of threats and the risks they pose.

A common threat can be that a fire starts in your data center, and the risk that will result, is that the data may end up being corrupt,damaged or lost. And therefore, it is a risk to the business, and the risk to the information that is stored there.

Another example could be an insider decides to sell corporate secrets to a competitor. In that case, it is a business risk. Since information that may have business value is sent to a competitor who can then capitalize on that, causing damage to your own reputation, or to your own company.

Another example can be a physical risk, where an assassin wants to infiltrate and murder the CEO in a drastic example.

And in terms of information security, a potential threat is that there are vulnerabilities in external systems, which can be capitalized by hackers, which can then lead to certain servers being corrupt or damaged.

Finally, there are the information security threats such as viruses and worms that can infect a server and either exfiltrate data or cause irreparable damage.

----------------------------------

## T4A2: List the possible human interactions with the system and categorise and outline a plan to address each risk:

- information security

- financial - security

- legal

- reputational

You must identify at least ONE risk for each type of risk, AND have 10 risks relating to human interactions in total.

The list should be in tabular format and have the following columns: Description of human interaction (D), Risk Category (R), Plan to Address Risk (P).

D: Employee gives sensitive business information to competitor
R: Financial Risk
P: Take legal action against competitor seeking injunction and sue former employee for damages

D: Virus infects large portion of a server, caused by employee clicking on malicious email
R: Information Security Risk
P: Disable the server and remove the virus, using a backup in the process

D: Employee leaves the door open, causing attacker to infiltrate and graffitti the walls
R: Reputational Risk
P: Properly educate the employee, or fire him/her.

D: Employee sues for breach of contract 
R: Legal Risk
P: Undertake proper contract education

---------------------------------

## T4A3: Create an audit checklist to evaluate whether the system:

- prevents execution of malicious code and non-approved applications (application whitelisting strategy)

- has the latest versions of all applications to address security vulnerabilities

- has the latest version and security patches for the operating system - has appropriate constraints on features of applications

- restricts administrative privileges

- has multi-factor authentication for accessing the system

- utilises a data recovery strategy

- has a secured network interface

Checklist (15 items):
 - Has the system properly whitelisted certain execution of malicious code.
 - Does the system have a method of preventing non-approved applications to be unable to execute code
 - Has the system being patched such that the latest versions of all applications on the system are patched
 - Have the updates been done recently, and includes all the major applications that are used.
 - Does the system and force a strict authentication mode, which prevents normal users from having administrative privileges.
 - Has the system enforced a multi-factor authentication for accessing the system. This may include using a authentication system using the mobile phone.
 - Does the system, utilize a data recovery strategy, which uses other servers.
 - Is there a secure network interface that is being used on the system, or is the network interface insecure.
 - Does the system have any configuration network or infrastructure configuration issues.
 - Are the roles in the system properly identified, such that there are no weak username policies.
 - How is the authentication and authorization of the system being properly tested.
 - If the system has a web application service is there adequate content security policy that will prevent the execution of malicious code.
 - Is it possible for a malicious orchestrator to enumerate infrastructure and application admin interfaces.
 - Has a strong password policy been implemented?
 - Have the permissions and verifications been sufficiently validated?

------------------------------------

## T4A4: Evaluate the threats to the system, you must evaluate all the potential threats from your audit checklist according to their impact.

You must:

- identify the impact using an industry standard risk assessment tool/matrix
- describe the risk
- allocate priorities to each risk in terms of impact and state your reasons for the allocation

In order to evaluate the threats to the system, we will be using the modern risk matrix, which measures the consequence and the likelihood of a particular threat occurring. This is the industry standard risk assessment tool that will be using. We will be also using the audit checklist and finding out the impact of the problems. 

Where the system has not properly whitelisted the execution of certain code, it is possible that a malicious orchestrator can be able to activate malicious code while inside the server, and in the worst case scenario achieve remote code execution, thus controlling the entire system. The consequence of such is very high with a rating of five, and the likelihood varies depending on how well the system is fortified with security features.

If the system is not patched, or if the latest versions of all applications on the system are not patched, then there may be additional vulnerabilities, which may allow the malicious orchestrator to escalate privileges or to pivot into other systems, causing more damage than is necessary. This will further increase the consequence and likelihood on the risk matrix, making the problem a very severe one.

If the system doesn't enforce a strict authentication mode and normal users ordinary users are allowed to have administrative privileges, then the risk is that they will be able to abuse these administrative privileges, and as such, take control of various applications on the system, which may result in further privilege escalation. The likelihood of this occurring is dependent on how strict of an authentication the system has. But the consequence is severe. To prevent this, it is necessary to have a multi-factor authentication while accessing the system. This can include using a mobile phone to verify the authenticator.

Furthermore, in the event of a breach, and the orchestrator decides to destroy all the data on the server, a data recovery strategy should be implemented. If there is none, then the risk is that information may be lost in perpetuity, and this may result in both a business, and an information security risk, as well as cause reputational damage. The consequences is really severe. However, the likelihood is dependent on the certain configurations, and whether or not a data recovery strategy has been implemented.

Furthermore, in the circumstance where a system has a web application service and insufficient protection, such as implementing a content security policy is not used and malicious code is activated, then, it is very likely for a system to capitulate, and therefore, the consequence would also be severe. The likelihood of that is also dependent on other factors such as whether or not the system has been patched and the application has been patched.

When deciding the risk, if the consequence and likelihood are all high, then the result is that the risk is very severe and resources should be allocated to prioritize that problem. In all the above cases, the most dangerous and problematic case is if the system has not disabled the execution of malicious code. And if the system hasn't been patched because certain vulnerabilities, when combined together, may result in greater vulnerabilities, and thus creating more issues for the service. Therefore, there should be a greater prioritization, if those two problems are found.

----------------------------------