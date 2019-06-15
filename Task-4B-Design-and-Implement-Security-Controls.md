# Task 4B - Design and Implement Security Controls for System

----------------------------

## T4B1: Devise TWO security controls to address risks identified in your risk assessment. You must provide written documentation regarding the controls which:

- describes the security control and the risk it addresses
- describes how the security control relates to human interaction with the system

Multi-Factor Authentication
Source: https://searchsecurity.techtarget.com/definition/multifactor-authentication-MFA

In order to address the issues and risks identified two security controls will be implemented.

The first is multifactor authentication. Multifactor authentication is a security system that requires a user to be able to supply more than one method of authentication from different categories of credentials. In order to verify their identity, multifactor authentication allows a combination of two or more independent credentials, such as a password and biometric verification to identify the employee, or the person in question.

The objective of creating a multifactor authentication is that it will allow the unauthorized person to have difficulty in attaining two different credentials that are necessary to breach a certain device server network or database.

In terms of how the security control will allow human interaction with the system: The employee must be able to type their password to be able to verify their identity into the system, but must also supply an additional independent credential, such as a biometric verification of the fingerprints, or the retina, or a response to a six digit pin that is sent to their mobile phone.

Having multiple layers of authentication will then prevent possible risks such as an infiltrator being able to login with an employee password, and then entering the Ubuntu machine as previously discussed, and escalating their privileges through the variety of security vulnerabilities.

Audit Trail
Source: https://en.wikipedia.org/wiki/Audit_trail

An audit trail can also be used as a security control to address risks as previously mentioned. An audit trail is a chronological record or a set of records that contain the source and destination of a particular activity or operation, procedure or event that is significant. In most cases, this is for security purposes. In information security, the term audit trail means a record of attempted or and completed accesses to services, and these are compiled using a path linking sequence of events, which can trace the origin of the activity. This can allow security personnel, to be able to examine and reconstruct the events to determine whether or not the attempted or completed access to a service was, in fact, a malicious attempt to breach security.

The risk it addresses is quite diverse since it is on the network and it will be able to prevent or impact the attempted breaches of many network style attacks.

Therefore, in terms of the Ubuntu machine, can catch a malicious orchestrator while they are attempting to access the machine. An audit trail does not directly prevent a person from accessing a certain machine. However, it can be used as a method of determining and learning about particular methods of how an attacker would think, and prevent future attempts.

In terms of the human interaction that's required with the system, the machine will be unaffected, however, all the log files that are compiled will be sent to be analyzed by a defensive security team.

----------------------------

## T4B2: Develop TWO procedures relating to the use of the security controls. The procedures should list of steps which describe each step required for the security control to be implemented and utilised by a user.

NOTE: this task links closely to Task 4C and will enable you to prepare to deliver that task.

**Setting up Multi-Factor Authentication**

Firstly setting up the Multifactor authentication as an additional layer of security can be used on the Ubuntu machine. Instead of simply entering a username and password, users can now connect to the server, and be required to enter a token, using the Google authentication app through SSH. The recommended method of using the 2FA authentication is through downloading the application 'Google Authenticator' through mobile phone.

The prerequisite is that there is a server, which is running the Ubuntu 18.04 operating system, a user that has sudo privileges, and a phone running an Android or Apple iOS, and has Google Authenticator downloaded.

Firstly, login to the Ubuntu server, and use the command line to install Google pluggable authentication module (PAM), which allows users on a Linux system to have a one time password on Google Authenticator.

This can be installed by first updating the repository information using sudo app-get update, and then installing Google PAM using sudo apt-get install lib-pam-google-authenticator.

Next in the command prompt, type google-authenticator and allow authentication tokens to be time based. A QR code can then be scanned, as it will appear on the command line prompt. Some additional settings can be entered that can prevent man in the middle attacks. Afterwards the SSH can be configured, which can allow the Google Authenticator to begin authorization next time.

When an attempt to login to the Ubuntu server it will request a verification code from the Google authenticator app.

**Setting up an Audit Trail**

The audit trail can be installed on Ubuntu using `sudo apt install -y auditd audispd-plugins`. It can ve used to monitor and audit the system, such as changes of particular files and unauthorized changes, as well as monitoring of system calls, functions and detect anomalies and crashing processes. This can be used for intrusion detection purposes.

The auditd.conf file allows the daemon to focus on where and how it should log events, while the rules for auditing is examined using the auditctl parameter.

A command to monitor changes to the /etc/passwd file can be written as such `auditctl -a exit,always -F path=/etc/passwd -F perm=wa`. Now everytime the /etc/passwd file is changed, a log file containing the details will be sent to a specified location.

-----------------------------

## T4B3: Implement TWO security controls on the system. You must supply evidence of the implementation and operation of the security control. You must include:

- a short written explanation of the evidence which itemises what you are providing and what it demonstrates

The evidence of implementing security controls are in the evidence folder.

1. After completing the google authentication installation on Ubuntu, it is possible to sign in using SSH and providing the information as prompted, will allow the user to authenticate.
2 and 3. Installation of google authenticator on the server.
4. The authentication QR for the phone to be able to authenticate into the server.

5 and 6. The installation of the audit trail using the command as specified.
7. Placing a watch on the /etc/passwd system

-----------------------------------

## T4B4: Review the risks to the system and security controls you have devised and utilise the NIST Risk Management Framework Information Systems and Organisations to plan monitoring tasks . Your plan must include:

- TWO tasks for monitoring the operation of a security control and the risk(s) it addresses

- an outline of the management process for monitoring the effectiveness and sufficiency of the security control 

For Multi-factor authentication:

One task that has been devised and utilized in a NIST Risk Management Framework information systems and organizations, is the monitoring of ongoing authorization. In this circumstance, the outcome is for the officials who are responsible for authorization to conduct ongoing authorization using the results derived from continuous monitoring activities, and then communicate such changes to determine risk and risk acceptance decisions.

This is determined by an ongoing and constant evaluation, to determine whether the risk is maintained and remains acceptable. The discovery and results from the continuous monitoring process can provide a useful insight to the officials to make decision making that is based off real time and risk based evaluation through inputting the results of system level risk assessment, as well as various security and privacy plans, ongoing authorization task can create an output that helps determine the level of risk. The ongoing authorization that should be used, and whether or not such security control mechanism should be adjusted and changed

Another task framework that is provided by NIST is the ongoing risk response, which is the output of continuous monitoring activities, is analyzed and then responded to appropriately. In such a circumstance, an organization would input their risk assessment results and receive risk acceptance decisions, as well as an update on their security assessment reports. The information that is received by an assessor during the continuous monitoring phase is provided to the system owner, and in the form of an updated security assessment report, which can be used to determine the level, and appropriate risk response. That should be proposed to the system owner who can then subsequently make an appropriate risk response.

This should be ongoing and deterministic based off changes and controls can be modified or enhanced depending on the risk response assessment, or reassessment. 

In such case, the management process for monitoring the effectiveness and sufficiency of multifactor authentication can be quite simple. The effectiveness can be maintained by determining the amount of incidents where a party or another user has attempted to authenticate into the server, but is unsuccessful due to the multifactor authentication. Such attempted logins will be realized, and logged, and can be analyzed by parties security parties that can then determine the effectiveness of this security control, and whether or not it should be reflected upon.

In order to determine the sufficiency, and whether or not it can protect against unauthorized users or unauthorized access, the monitoring of changes on the system as well as using an auditing process to log any access can be used to determine how many successful attempts multifactor authentication has succeeded in preventing the security breaches.

-------------------------------