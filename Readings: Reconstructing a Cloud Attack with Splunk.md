## Readings: Reconstructing a Cloud Attack with Splunk
Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
### What is a reverse proxy?
A reverse proxy is a server that sits in front of web servers and forwards client  requests to those web servers. Unlike a traditional proxy, which protects client identities, a reverse proxy acts on behalf of the servers non clients and serves as an intermediary for requests directed at these servers.
#### What are the benefits of a forward proxy?

#### Explain the differences between a forward and a reverse proxy?
A forward proxy, positioned between the client and the internet, serves several purposes:

Privacy and Security: Masks the user's IP address, enhancing anonymity.
Content Filtering: Restricts access to certain websites or content, useful in organizational or educational settings.
Caching: Stores local copies of frequently accessed resources, reducing bandwidth usage and improving access speeds.
Access Control: Manages internet access for internal network users, enforcing organizational policies.
Direction of Proxying: Forward proxies serve clients wanting to access various servers on the internet. Reverse proxies protect and manage access to a specific server or group of servers.
Primary Use Case: Forward proxies focus on client anonymity and network control, whereas reverse proxies are geared towards load balancing, security, and performance enhancement for web servers.
Operational Position: Forward proxies are situated close to the client side, while reverse proxies are positioned near the server side.

#### Explain to your manager why your organization might benefit from implementing a reverse proxy?

Enhanced Security: By obscuring the backend server's identity, a reverse proxy can protect against direct attacks.
Improved Load Balancing: Efficiently distributes traffic across servers, ensuring stability and reduced downtime.
Performance Optimization: Caching and compressing content can significantly improve website load times.
SSL Encryption: Centralizes SSL/TLS processing, streamlining certificate management and encryption tasks.
