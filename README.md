# SoftwareSecurity
CS-305 Software Security
Briefly summarize your client, Artemis Financial, and their software requirements. Who was this client? What issue did they want you to address?

Artemis Financial is a consulting company specializing in individualized financial plans, be it savings, retirement, investments, and/or insurance. They have approached Global Rain to 
modernize their operations and enhance the security of their web application. They are looking to modernize the application with secure communications and transferring of client data. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s 
overall wellbeing?

I was able to implement the Maven Dependancy Check into the POM file easily enough. Running the dependancy checks is crutial for correcting coding that may be suseptible to attacks and 
having already been identified. Coding securely is important to preserve the integrity and intended usage of your application. When a company's application is secure, customers should 
never have to hear that their data has been compromised. Average users most likely do not seek out why a site is secure, they tend to assume data is handled honestly. Because of this,
a company typically suffers once users are alerted to a security breach.

What part of the vulnerability assessment was challenging or helpful to you?

The helpful part of the vulnerability assessment was the Maven check. The challenging part to this was determining which CVE codes to worry about. Some were easy to identify, some took
a bit of digging.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Layers of security were increased by following best practices to coding using Maven. Encryption and HTTPS were also added to ensure sites were secure and cross-site scripting and other
forms of attacks are near impossible to execute. I would use the Maven Dependancy checks to find the vulnerable code and follow each hit to find mitigation methods.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

The code and software application were found to be functional by running the code without errors. They were found to be secure by checksum testing for encryption efforts and verifying
a secure connection by way of a lock symbol in the address bar, letting you know your are connected via HTTPS and the site presented a valid certificate. After refactoring the code, 
simply run a new dependancy check to find any new vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Seeing the Springboot application work is a great start at using programs like this in the future. Getting to use some of the plug-ins, such as Maven, is by far the most beneficial 
tools that I think will be carried forward. I also enjoyed seeing how to create certificates and keys, seeing how they interact to provide secure communications. The use of encryption 
was exciting to see take shape and will undoubtedly be used again.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this 
assignment?

Hard to say I will not have a better understanding of computer science as a whole in the future. From this point in time, I may say I have a fair understanding of software security
based on certificate authorities, encryption software, vulnerability assessments and more. I may show that I can implement Maven and scan for vulnerabilities, I believe this is a simple 
task that can generate a lot of valuable data.
