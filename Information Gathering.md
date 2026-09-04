# Information Gathering
## What is information gathering?
-  Information gathering is the process of collecting the necessary information about the target systems, network and infrastructure before attempting to
  test or exploit vulnerabilities in the system/network
- The main purpose of this is to understand the attack surface which are the loopholes an attacker could use to exploit the system.


## Four Categories during the Information Gathering Process:
### (OSINT)-Open Source Intelligence
- Collecting information about the system or the target from the publically available sources
  Here, The system/Network are not being exploited directly
### Infrastructure Enumeration 
- Gathering information about the technical infrastructure of the target system/network
  The system and Network setup an organization consists of, which could include IP addresses, Cloud assets, Servers, Firewalls, Etc.
### Service Enumeration
- This is to identify what services are being provided/exposed by the hosts (The system connected to the network) which could be open ports, APIs,
  SSH, HTTPS, DNS
### Host Enumeration
- Gathering information and understanding individual system in depth such as Installed Software, Operating System, Services which are running, etc.

 ## How do we know if the collected information is necessary?
 - Helps in understanding the attack surface
 - Supports the Objective and the Scope of the pentest
   
   ** Out-of-Scope Assets **
   If an asset is discovered during the passive information which is outside the defined scope, Its prohibited to test it
   without Authorization.

Information gathering is not about finding all the possible details about a system/network rather prioritizing data which helps us in understanding
the attack surface and to determine where the further security testing is to be performed.
  
  
