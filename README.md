# SNHU-CS-305
CS-305 Software Security

1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Our client, Artemis Financial, is a consulting company that develops individualized financial plans for their customers. The financial plans include savings, retirement, investments, and insurance. Artemis Financial wants to modernize their operations. As a crucial part of the success of their custom software, they also want to use the most current and effective software security. Artemis Financial has a RESTful web API. They are seeking our company, Global Rain’s expertise about how to protect the organization from external threats.

2. What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Manually inspecting the code I came across multiple vulnerabilities within the different different Java files. The code as presented left Artemis at risk to multiple forms of attack. Artemis also did not use HTTPS to share sentive information, thus putting their company but more importantly the customers data at risk. Looking through the vulnerabilities assessment, showed that most of Artemis's system was outdated, in need of updating the software to ensure that every vulnerability was patched. Coding securely is crucial for several reasons, as it helps protect applications, systems, and the data they handle from various security threats. Software security adds significant value to a company's overall wellbeing in several ways. Investing in robust software security measures, as Artemis has done, not only protects the company's sensitive information and infrastructure but also provides numerous indirect benefits that contribute to its overall health and success.

3. What part of the vulnerability assessment was challenging or helpful to you?

I did not find the vulnerability assessment challenging due to the resources we had available. We were introduced to the NATIONAL VULNERABILITY DATABASE and CVE search where every vulnerability was addressed, with details of how the vulnerability affected consumers, but also how to fix or patch the vulnerability.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security the layers of security by first updating Maven Dependency to 8.2.1, so that the static dependency check is updated to the newest available software version. From there we utilized the algorithm cipher Advanced Encryption Standard (AES) algorithm. AES is a symmetric encryption algorithm that is widely used and considered secure. It operates on block sizes of 128 bits and supports key lengths of 128, 192, and 256 bits. I then added a RestController to serve as the secure controller for the hash RESTful endpoint. From there I utilized SHA-256 as the hashing cipher for this function.

To assess vulnerabilities and decide on mitigation techniques I would do the following, I would start by using automated tools to scan systems and applications for known vulnerabilities, and prioritize them based on their severity, impact, and likelihood of exploitation. From there I would do regular penetration tests to simulate attacks on our system and find vulnerabilities. I would also analyze the system architecture and data flows to identify potential threats and vulnerabilities, and develop strategies for mitigating them.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To ensure that the code and software applications were both functional and secure, it was essential to follow best practices learned from SDLC and adopt a proactive approach to security. I Implemented secure coding practices, such as input validation, output encoding, and proper error handling, to minimize vulnerabilities in the code. I used continuous integration (CI) and continuous testing to identify and address issues early while working on the code. After refactoring the code I used the Maven dependency static test report to ensure no new vulnerabilities were introduced into the code.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

For each assignment I used the resources provided by the program to develop an understanding of the topic. From there I utilized resources like the Shapiro Library to find more information on the topic, if I wanted to further explore the topic I would utilize Google, as well as the extremely valuable StackOverflow website. 

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment.

I would showcase both Project 1 and Project 2 from this course, where I successfully showed my understanding of how important security is, how to look for vulnerabilities using the Maven dependency and then utilizing the resources from the the NATIONAL VULNERABILITY DATABASE and CVE search website to find how each vulnerability affected users but also how to patch the exploit, refactored code to meet the security requirements for each assignment, and finally using a cipher algorithm to generate a checksum and certificate.
