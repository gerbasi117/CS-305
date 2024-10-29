# CS-305

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Answer: The client, Artemis Financial, is a company in the finance sector that requires secure software for handling sensitive financial data. The primary objective was to implement secure communication channels and encryption techniques to protect data transmissions, particularly by using SSL encryption and AES (Advanced Encryption Standard) to ensure data integrity and confidentiality. The project also involved generating certificates and assessing vulnerabilities to ensure robust software security.

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

Answer: I effectively identified and mitigated potential vulnerabilities by following industry-standard practices, such as implementing SSL encryption for secure communication. Coding securely is critical as it prevents unauthorized access, data breaches, and other security risks that can harm the company’s reputation and financial stability. By securing the software, I helped Artemis Financial protect its clients' sensitive information, enhancing trust and compliance with regulatory standards, which is essential for the company’s long-term success and resilience.

**Which part of the vulnerability assessment was challenging or helpful to you?**

Answer: One challenging aspect of the vulnerability assessment was ensuring that all dependencies were up to date and free from known vulnerabilities, as it required an in-depth understanding of the dependencies and their potential security risks. However, this process was also very helpful, as it improved my skills in dependency management and reinforced the importance of regular updates and thorough testing to maintain a secure environment.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

Answer: I increased layers of security by implementing SSL/TLS encryption, using strong encryption algorithms like AES, and generating secure certificates. For future projects, I would use automated vulnerability scanning tools, such as OWASP ZAP or dependency-check plugins, to quickly identify vulnerabilities. Additionally, I would consider threat modeling techniques to prioritize and address the most critical security risks systematically.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

Answer: To ensure functionality and security, I conducted thorough testing after each modification, including functional and unit tests, to validate that the application performed as expected. I also used Maven's dependency-check tool to verify that no new vulnerabilities were introduced with each code change. By consistently testing and analyzing dependencies, I could confidently ensure that the code remained secure.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

Answer: I utilized tools such as the Java Keytool for certificate generation, Maven for dependency management, and Spring Boot for implementing SSL within the application. The use of these tools and adherence to coding best practices, like encryption and secure communication protocols, will be invaluable for future projects requiring a secure development environment.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

Answer: I would showcase this project as a comprehensive example of my ability to implement secure software practices, including SSL encryption, vulnerability assessment, and dependency management. This assignment demonstrates my proficiency in secure coding, understanding of encryption protocols, and commitment to maintaining software security. It reflects my capability to protect sensitive data and comply with industry standards, which are essential skills for any role in software development or cybersecurity.
