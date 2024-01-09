## Readings: Cloud Security Principles and Frameworks
Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading
### AWS Architecture Blog - Compute Abstractions on AWS: A Visual Story

Bookmark and Review
13 Compliance Frameworks for Cloud-based Orgs
Cloud Security Alliance (CSA)
Cloud Controls Matrix (CCM)
CSA Security Guidance for Cloud Computing

#### Explain the levels of abstraction in AWS to someone without a technical background.
AWS provides a building with different floors who allow users to choose the level at which they want to interact. Some might stay on the 1st floor using basic services while others might go to higher floors for more specialized and advanced functionalities without having to worry about the underlying infrastructure in the basemen

#### What are the control plane and data plane responsible for in container abstraction?
A containers control plane that is responsible for exposing the API and interfaces to define, deploy, and lifecycle containers. This is also sometimes referred to as the container orchestration layer.
A containers data plane that is responsible for providing capacity (as in CPU/Memory/Network/Storage) so that those containers can actually run and connect to a network. From a practical perspective this is typically a Linux host or less often a Windows host where the containers get started and wired to the network.

#### Where does AWS Lambda fall in the layers of abstraction and what makes it so special?
 Lambda is that you don’t have to manage the infrastructure underneath the function you are running. No need to track the status of the physical hosts, no need to track the capacity of the fleet, no need to patch the OS where the function will be running. In a nutshell, no need to spend time and money on the undifferentiated heavy lifting.
