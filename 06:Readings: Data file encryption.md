## Readings: Data file encryption
Below you will find reading materials and additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

### Reading
### Applying The CIA Triad To Your Enterprise File Transfer

#### What Are MD5, SHA-1, and SHA-256 Hashes, and How Do I Check Them?

#### You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?
Confidentiality - Encrypt everything
Integrity: I would use an appropriate hashing technique, probably SHA-256, as it is preferred
Availability: To ensure the highest levels of availability, I would utilize the 3-2-1 storage solution. 3 copies, 2 different local data stores, 1 off-site server.
#### Explain how hashing verifies data integrity using non-technical terms.

#### How is hashing and encryption different?
Hashing: The primary purpose of hashing is to create a fixed-size and unique representation (hash value) of input data.
Encryption: Converting data into a different format using an algorithm and a key. This key can be broken.
