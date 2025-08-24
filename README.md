# CS 320 Portfolio Submission

## Reflection

**How can I ensure that my code, program, or software is functional and secure?**  
I ensure functionality and security by writing thorough unit tests that validate both correct behavior and invalid inputs. Using techniques like `assertThrows`, I can test how my code responds to invalid data, and I make sure all input is validated. Avoiding shortcuts and always checking boundary cases helps me write secure and robust code.

**How do I interpret user needs and incorporate them into a program?**  
I interpret user needs by carefully reading through the software requirements and translating each one into testable behaviors. For example, if a requirement states that a phone number must be exactly 10 digits, I include both passing and failing test cases for that constraint. This way, I ensure the implementation reflects what the user needs.

**How do I approach designing software?**  
I start by breaking down the problem into logical components (like Contact, Task, and Appointment). I write the object classes first, making sure each field has proper validation, and then I build services to manage those objects. I rely heavily on test-driven thinking — I often write the test cases first or in parallel with the functionality to guide design decisions.
