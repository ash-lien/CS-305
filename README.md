# CS-305
Artemis Financial Vulnerability Assessment Report

Artemis Financial is a financial company that wanted to improve their software for web application and increase the security. Since they created personalized financial plans for their users, it was important that they maintained integrity within their web app. 

When I found their software security vulnerabilies, I came up with a mitigation plan to adress the vulnerabilities that were discovered. It is important to code securely because it can reduce the changes of vulnerabilities, threats, and attacks. Those are also reasons why software security is important for a company's overall well-being. Since Artemis Financial is a company that works with their user's money, it is important that they have strong security to make sure their information does not get compromised.

The part of the vulnerability assessment that was challenging to me was the initial going through each vulnerability in the report. It seemed very daunting at first, however when reading through, it was made easy to understand by taking the time to read all the descriptors of each of the vulnerabilities that showed. This led me to understand what they were in order to create a mitigation plan.

One layer of security that was added was the self-signed certificate. This ensured that there was secure communication between the users and the web interface. This is important for Artemis Financial as security is a top priority as they work with individualized financial plans. The second layer of security that was added was the SHA-256 hash algorithm. This ensured that any attackers would not be able to intercept the data being transmitted. It adds another layer of protection to the data being transferred when users are interacting with the web interface. The last layer of protection that was added was updating the version of the spring-boot software to the current version. It is important to keep software up to date to reduce the number of vulnerabilities. In the future, to assess vulnerabilities I will use the dependency check to view the vulnerabilities and come up with a mitigation plan.

I made sure the code and software application were functional and secure by implementing the SHA-256 algorithm and the self-signed certificate. After these features were added I tested the code to make sure that it was running correctly. After refactoring the code, I ran another dependency report and checked to see if new vulnerabilities were added.

One resource that I used that was helpful to me was stack overflow. Many of the problems I encountered during my assignments I was able to find information about how to come up with solutions to them. ANother tool that was helpful to me was the Maven dependency check. I was able to view and assess what my vulnerabilties were within the program. Both of these will be helpful to me in the future.

What I would show from this assignment would be the list of vulnerabilities that was found and the mitigation plan that I came up with. This would show future employers that I was able to understand what the vulnerabilities were and how to correct them. 
