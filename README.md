# CS-305-8-1-Portfolio-Journal-Item
## CS-305 Portfolio for the Artemis Financial Practices for Secure Software Report


- ## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
     > Artemis Financial was seeking a developer to increase the level of security for their web application and also add secure communication mechanisms to meet their software security requirements.

- ## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

     > I think the use and implemenation of the SHA-256 algorithm cipher went well to address the security vulnerabilities of the application. It is incredibly important to write secure code that is maintainable and less vulnerable to security attacks that any company will potentially face.In the modern world of the internet every company has a website which must follow these security guidelines and improves the overall quality and security for the company. 

- ## What about the process of working through the vulnerability assessment did you find challenging or helpful?

     > The process of creating and generating the maven dependency check report was something I found to be both quite helpful and challenging when I first started. Learning how to integrate the check report and then running it through the NVD database of vulnerabilities was incredibly interesting and beneficial for myself as a software developer. 

- ## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

     > I was able to ensure the increased layer of security by addressing needs such as cryptography and the use of encryption in the project. I decided to implement the SHA-256 hashing algorithm for the refactor to properly encrypt the data and add a high level of security to the web application. Another area of security I needed to address was the client-server security, specifically generating a self-signed certificate with the Java key tool and then adding the key store for encrypted HTTPS security. In the future I would continue to use the maven check report to find and assess any other potential vulnerabilities within the codebase.

- ## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

     > I was able to ensure the code and software application was functional and secure by refactoring the codebase to include the Java security and Message Digest libraires to implement the SHA-256 hash function for data encryption. I also used the Spring Rest Controller for the check sum and make it visible in the web application and display the provided data along with the SHA hash value. After refactoring the code, I was able to run the maven check report once again to verify no additional vulnerabilites were introudced from the added libraries. 

- ## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

     > Some of the tools and resources I found useful for this project were the Maven dependency check and all of the Spring Boot libraries needed for the web appliction to function properly. I also incorporated various coding practices such as object oriented principles and proper API integration with all of the needed dependancies. 

- ## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

     > For this particular assignment, I would definitely showcase the full web application running with all of the security features added such as HTTPS and the SHA-256 cipher being used. An employer would feel confident knowing I am capable of designing a full application that is secure and functional.

