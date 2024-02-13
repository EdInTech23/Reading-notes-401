
## Readings: Persistence

Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.
Reading

### PowerShell Empire No Longer Maintained

    While no longer maintained by its original creator as of writing, PowerShell Empire has been forked many times and was used by nation state actors from 2015-2019. The PowerShell Empire project is now actively maintained by BC Security. As you read this article, take note of its original purpose as well as the tactical advantages offered to its users.

#### What is one of the major advantages of PowerShell Empire?
Advantage: PowerShell Integration and Stealth

One of the primary advantages of PowerShell Empire is its deep integration with PowerShell, a native scripting language and management framework present in nearly all modern Windows systems. This allows PowerShell Empire to:
Blend in with legitimate system activity: PowerShell is heavily used by admins; it makes attacks harder to distinguish from normal operations.
Operate "filelessly" in many cases: Attackers can execute malicious code directly in memory, rather than needing to drop files to disk. This reduces the footprint on the target system and makes detection more difficult.
  
   #### What are some of the APT groups that have been known to use PS Empire and into which step of the Cyber Kill Chain does the use of PS Empire fall?
APT Groups:

FIN7: A financially-motivated cybercrime group with a history of targeting point-of-sale systems.
APT32 (OceanLotus): A Vietnamese threat group attributed to government-backed espionage campaigns.
Others: Various additional groups have utilized PowerShell Empire as its open-source nature makes it an accessible and adaptable tool.
Cyber Kill Chain Step:

PowerShell Empire primarily falls within the Actions on Objectives phase of the Cyber Kill Chain.  An attacker who has already gained an initial foothold in a network would use PowerShell Empire to:

Maintain persistence
Perform lateral movement
Extract valuable data
Cause disruption
 ####    What are the four main components needed to pull off an attack using PS Empire?
Empire Server: This acts as the command and control (C2) server. It's where the attacker sets up their control infrastructure, generates payloads, and issues commands to infected systems.
Agents (or Stager): These are malicious payloads, usually in PowerShell script format, designed to establish the initial connection back to the Empire server.
Listeners: Listeners are configurations running on the Empire server that define how the server will accept communications from the infected agents. Options include HTTP, HTTPS, and others.
Modules: Modules are the individual tools and exploits within PowerShell Empire. These provide the attacker with a variety of post-compromise actions such as credential harvesting, privilege escalation, and data exfiltration.
Bookmark and Review

    Hacking with Empire – PowerShell Post-Exploitation Agent

