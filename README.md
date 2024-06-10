Software engineering is the application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software; that is, the application of engineering to software.

Software engineering is a relatively new field, with its origins in the 1960s. As software became more complex and critical, it became clear that traditional engineering methods were not adequate for developing and maintaining it. Software engineering provides a set of best practices and methodologies that can be used to improve the quality, reliability, and maintainability of software.

Software engineering is a multidisciplinary field that draws on a variety of disciplines, including computer science, mathematics, engineering, and management. Software engineers must have a strong understanding of the fundamentals of computer science, as well as the ability to apply engineering principles to the development of software.

The software engineering process typically involves the following steps:

1. **Requirements gathering and analysis:** This step involves gathering and understanding the requirements of the software system.
2. **Design:** This step involves designing the software system, including its architecture, data structures, and algorithms.
3. **Implementation:** This step involves coding the software system.
4. **Testing:** This step involves testing the software system to verify that it meets the requirements.
5. **Deployment:** This step involves deploying the software system to the production environment.
6. **Maintenance:** This step involves maintaining the software system over its lifetime, including fixing bugs and adding new features.

Software engineering is a challenging but rewarding field. Software engineers have the opportunity to work on a variety of projects, from small personal projects to large enterprise systems. They can also work in a variety of industries, including healthcare, finance, and manufacturing.
definition of software Engineering 
Question 1: Describe and differentiate between the following software testing strategies: Unit Testing, Integration Testing, System Testing, and Acceptance Testing. Provide examples of test cases for each strategy for a hypothetical e-commerce platform. Discuss the importance of each testing strategy in the software development process and how they contribute to software quality assurance.

Answers:
1.	Unit Testing: 
This involves testing individual components or modules of a software system to ensure that each part functions correctly. Typically conducted by developers, unit tests isolate a single unit of code, such as a function or a class, to verify its correctness.
	Example of unit testing in E-commerce platform: this follows the following process
•	Add item to cart
•	Calculate price
•	Validate user payment

	Importance of Unit testing:
•	It helps catch bugs early in the development process, reduces the cost of fixing defects, and ensures that individual components work as intended, contributing to the overall reliability of the software.

	Contribution of Unit Testing to Software Quality Assurance:
•	Ensures that individual components work correctly, contributing to the reliability and maintainability of the code.

2.	. Integration Testing:  
This tests how different software units interact with each other. Modules or components are integrated and testing them as a group to identify any issues in their interactions.
Example of Integration testing in E-commerce platform: this follows the following process
•	User interface Testing
•	Payment gateway testing
•	Database integration



	Importance of Integration testing:
•	Integration testing identifies issues arising from interactions between different parts of the system. It ensures data flows smoothly between modules and functionalities work cohesively
	Contribution of Integration Testing to Software Quality Assurance:
•	Verifies that integrated components function together, ensuring system coherence and reducing integration issues

3.	System Testing:  
This testing the complete software system as a whole, simulating real-world use cases. It evaluates whether the system meets its overall functional and non-functional requirements.
	Example of System testing in E-commerce platform:
•	Full purchase process
•	User stress loading
•	System Stability and performance testing 

	Importance of System testing:
•	System testing reveals issues that might not be apparent in unit or integration testing. It provides a comprehensive evaluation of the system's functionality, usability, and performance before deployment
	Contribution of System Testing to Software Quality Assurance:
•	Validates the complete system against requirements, ensuring functional completeness and performance.

4.	Acceptance Testing:  
This is conducted to determine whether a system satisfies the acceptance criteria and is ready for delivery to the end-user. This type of testing can be done by the end-users themselves or by testers on behalf of the users.
	Example of Acceptance testing in E-commerce platform:
•	Usability testing
•	Feedback testing
•	Security testing




	Importance of Acceptance testing:
•	Acceptance testing ensures the software meets the needs of the intended users and stakeholders. It helps identify usability issues and ensure the system delivers the expected value before final release.

	Contribution of Acceptance Testing to Software Quality Assurance:
•	Confirms that the system meets user and business needs, ensuring the product's readiness for market release.


Question 2: Compare and contrast the Waterfall, Agile, and DevOps software development life cycle models. Discuss the advantages and disadvantages of each model.

Answers:
	Comparison between Waterfall, Agile, and DevOps software development life cycle models:
•	Waterfall: Best for projects with well-defined requirements and low likelihood of changes. Offers clear structure but lacks flexibility.
•	Agile: Ideal for projects with dynamic requirements and a need for rapid delivery. Promotes flexibility but can be less predictable.
•	DevOps: Suitable for environments that require continuous delivery and integration, fostering collaboration but demanding cultural shifts.

1.	Waterfall Model:
	Advantages:
•	Clear structure and documentation. 
•	Easier to manage for smaller projects

	Disadvantages:
•	Not suitable for complex project
•	Delays in one phase can impact the entire project timeline. 
•	Limited user involvement until later stages.

2.	Agile Model:
	Advantages: 
•	Flexibility and adaptation to requirements changes. 
•	Faster and continuous delivery
•	Encourages close collaboration between developers and users

	Disadvantages: 
•	Requires a high level of customer involvement.
•	Requires strong communication and team coordination. 

3.	DevOps Model:
	Advantages: 
•	Faster delivery and improved software quality. 
•	Increased collaboration between development and operations teams. 
•	More efficient deployment and infrastructure management.

	Disadvantages: 
•	Requires a cultural shift and collaboration between traditionally siloed teams. 
•	Can be challenging

Question 3: What are functional and non-functional requirements in software engineering? Provide an example of a software system and list five functional and five non-functional requirements for that system.

Answers:
	Functional Requirements
Functional requirements describe what the system should do, including tasks, functions, and behaviors the system must perform.

	U
Non-functional requirements define how the system performs a task, focusing on quality attributes such as performance, usability, reliability, etc.

Example: Library Management System
Functional Requirements
•	Search for Library Items: The system should enable users to search for books and other library items by title, author, or ISBN.
•	Check Out Items: Users should be able to check out library items for borrowing.
•	Return Items: The system should facilitate the return of borrowed items.
•	Track Overdue Items: The system should keep track of overdue items and send notifications to borrowers.
•	Generate Reports: The system should generate reports containing information on borrowing statistics, such as the number of items borrowed and returned within a particular period.

Non-Functional Requirements
•	Availability: The system should be available for users to access and use most of the time, ideally with an uptime of 99%.
•	Performance: The system should respond to user queries promptly, with a response time within 2 seconds or less.
•	Security: The system should be secure and protect user data, such as borrowing history and personal information.
•	Usability: The system interface should be user-friendly and easy for users with varying levels of technical expertise to navigate and perform tasks.
•	Scalability: The system should be scalable to accommodate a growing number of users and library items as the library's collection and user base expand.


References
1.	IEEE Standard Glossary of Software Engineering Terminology. Retrieved from: https://standards.ieee.org/standard/610_12-1990.html

2.	ISTQB. (2021). Testing Techniques. Retrieved from: https://www.istqb.org/downloads/category/16-advanced-level-documents.html
3.	Pressman, R. S. (2019). Software Engineering: A Practitioner's Approach. Publisher: McGraw-Hill Education
4.	Beck, K., & Andres, C. (2004). Extreme Programming Explained: Embrace Change. Publisher: Addison-Wesley Professional
5.	Humble, J., & Farley, D. (2010). Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation. Publisher: Addison-Wesley Professional
6.	Cohn, M. (2004). User Stories Applied: For Agile Software Development. Publisher: Addison-Wesley Professional
7.	Bass, L., Weber, I., & Zhu, L. (2015). DevOps: A Software Architect's Perspective. Publisher: Addison-Wesley Professional

