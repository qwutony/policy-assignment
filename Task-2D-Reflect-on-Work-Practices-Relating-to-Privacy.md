# Task 2D: Reflect on Work Practices Relating to Privacy

**Review a privacy policy of your choice and review your practices relating to any of the applications, systems or networks you have implemented and answer on the following:**

The system I have implemented that will be reflected upon will be the *Secure Password Vault Application* that is written in Javascript and Node. The Privacy Policy that will be used is the Commonwealth Bank document.

T2D1 - What aspects of the privacy policy are relevant to the application?

 - How personal information is handled.
 - What information is collected.
 - How is that information used.
 - Who does the information that is stored shared with?
 - How is the information kept safe.
 - How to access, update and correct the information that is stored on the database.

T2D2 - What steps did you take at the time you developed the application to ensure the integrity, confidentiality and availability of information in the application?

 - Confidentiality: Implement a strong encryption on the authentication system, to ensure those without a valid credential cannot log in via other means. Ensure that passwords are converted to bullet points, and a toggle feature between bullet point and plain-text.
 - Integrity: Perform minor testing to ensure that the application's database cannot be edited in a malicious way, or overstepping the boundaries of their authorisation levels.
 - Availability: Ensure that the server runs with the connected database behind it.  Performed testing to ensure that the server can handle multiple requests.

T2D3 - What steps would you take now that you have studied privacy law and policy?

In addition to the aforementioned steps:
 - Confidentiality: Use password hashing so that passwords cannot be viewed by system administrators and such. Ensure viable user roles and permissions. Ensure no other users can access other individual accounts.
 - Integrity: Frequently back up the database to ensure no tampering. Implement firewalls, WAF and other defensive mechanism to prevent exploit of vulnerabilities that can lead to editing of the database. Prevention of SQL injection.
 - Availability: Host the server on Cloudflare to prevent DDOS attacks. Ensure server is backed up. 

T2D4 - How would you ensure that the system in which your application operates is secure according to the chosen privacy policy?

 - Ensure that the system is backed up frequently.
 - Have frequent Penetration Testing exercises.
 - Have frequent vulnerability scanning.
 - Always ensure that the system is patched whenever a security update is out.
 - Ensure that all passwords are hashed.
 - Leave only essential applications installed on the system.