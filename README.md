Project Reflection 

Throughout this course, I focused on developing software that is both functional and reliable by applying principles of software testing, automation, and quality assurance. The artifacts in this repository demonstrate my ability to implement core functionality, validate requirements through unit testing, and evaluate different testing strategies to ensure software quality. 


Ensuring Functional and Secure Software 

I ensure that my code is functional by validating requirements early and using unit tests to confirm that each component behaves as expected. For example, in the Contact Service project, I created unit tests to verify that objects cannot be created or updated with invalid data, such as null values, empty strings, or values that exceed defined length constraints. These automated tests allow me to detect defects early and prevent regressions when changes are made. 


Security is supported through consistent input validation and defensive programming practices. By enforcing validation rules at the object and service levels, the software prevents invalid or unsafe states from occurring. While unit testing alone does not provide complete security, it plays a key role in identifying logical flaws and ensuring that validation rules remain enforced throughout the development of lifecycle. 


Interpreting User Needs and Incorporating Them into a Program 

I interpret user needs by translating requirements into clear, testable conditions that guide both implementation and testing. Rather than treating requirements as abstract statements, I convert them into specific rules, such as required fields, acceptable input lengths, and expected behaviors. These rules are then enforced directly in the code and verified through unit tests. 
  

This approach ensures that the software does not merely run without errors but also behaves in a way that aligns with user expectations. Writing tests that directly map to requirements helps confirm that the program fulfills its intended purpose and reduces the risk of missing critical functionality. 

  
Software Design Approach 

My software design process begins with understanding requirements and organizing the program into well-defined components with clear responsibilities. Data classes are responsible for maintaining valid state, while service classes manage operations such as creating, updating, and deleting records. This separation of concerns improves readability, maintainability, and testability. 


I also design with testing in mind by keeping methods small, predictable, and easy to verify through automated tests. By iterating between implementation and testing, I can refine the design, address edge cases, and ensure the final product is robust and aligned with quality assurance best practices. 
