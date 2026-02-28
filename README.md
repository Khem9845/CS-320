# CS-320

**Software Testing, Automation, and Quality Assurance**

**Khem  Khatiwada**

Southern New Hampshire University

**Course Overview**

This repository showcases selected artifacts from CS-320, with a focus on software testing, automation, and quality assurance principles. The projects demonstrate my ability to design secure, reliable backend services and apply structured unit testing techniques using JUnit.
The work in this repository highlights my understanding of validation logic, defensive programming, requirement analysis, and automated testing strategies aligned with professional software engineering practices.


**Reflection**

**How can I ensure that my code, program, or software is functional and secure?**

I ensure functionality and security through structured unit testing, robust input validation, and defensive programming practices. In the Contact Service project, I enforced strict validation rules, including ID length limits, null checks, and proper phone number formatting. I applied JUnit testing with boundary-value analysis, equivalence partitioning, and negative testing to verify both valid and invalid scenarios. Automated testing helps detect regressions quickly and ensures updates do not break existing features, while validating inputs before processing strengthens overall system security.

**How do I interpret user needs and incorporate them into a program?**

I begin by carefully reviewing the functional requirements and identifying constraints such as field length limits, uniqueness rules, and logical restrictions. I translate these requirements into validation logic within the code and create corresponding test cases to verify compliance. For example, if an ID must be unique and no longer than 10 characters, I enforce that rule in the program and test it thoroughly. I also consider edge cases and misuse scenarios to ensure the system behaves correctly under unexpected conditions and aligns with user and business requirements.

**How do I approach designing software?**

I approach software design incrementally and systematically. First, I analyze the requirements and identify the core entities and services needed. Then, I design classes with clear responsibilities and maintain separation of concerns. I implement validation logic early to prevent defects from spreading. After building the core functionality, I write comprehensive unit tests to verify correctness. Testing is not an afterthought; it is integrated into the design process. This approach supports maintainability, scalability, and long-term reliability.

