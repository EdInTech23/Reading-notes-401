## Readings: Intrusion Detection and Prevention Systems (IDS/IPS)
Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

### Reading
#### The Pros and Cons of Network Intrusion Detection Systems

#### List 2 differences between firewalls and an IDS?
Functionality: Firewalls control access to a network by allowing or blocking traffic based on rules, while an IDS monitors and analyzes network or system activities for malicious activities or policy violations.
Prevention vs. Detection: Firewalls are preventive, actively blocking unauthorized access, whereas IDS are primarily for detection, identifying potential security breaches without necessarily blocking traffic.

#### Under what circumstances would you choose a network-based IDS over a host-based IDS?
Large Network Environments: For monitoring large, dispersed networks effectively.
External Threat Focus: If the main concern is external threats before they reach individual hosts.
Limited Host Resources: In situations where host performance is crucial and should not be impacted by security tools.

#### Name 3 major drawbacks of a NIDS?
Difficulty with Encrypted Traffic: NIDS struggle to inspect encrypted traffic effectively.
Resource Intensive: They require significant processing power and memory, leading to high costs.
False Positives/Negatives: High rates of false alarms and missed detections, necessitating additional resources for managing and fine-tuning the system.
