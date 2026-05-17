1. What is Apex?
Apex is the programming language used in Salesforce.  
It is used when normal clicks, flows, and configuration are not enough.
Using Apex, developers can create custom business logic, validations, integrations, and automation.
For example, in a college management system, Apex can automatically block student registration when course seats are full.

2.Difference Between Flow and Apex
Flow: 
No-code automation
Easy to create
Best for simple automation
Faster development
Apex:
Coding language
Requires programming knowledge
Best for complex logic
More flexible
  Difference Between Configuration and Coding
Configuration:
Configuration means building features using clicks without writing code.
Examples:
- Creating objects
- Validation rules
- Flows
- Formula fields
Coding:
Coding means writing custom logic using Apex or Lightning components.
Examples:
- Payment integration
- Complex calculations
- External APIs
  
3. Real Examples Where Apex Is Needed
Example 1 – Complex Fee Calculation
If scholarship, attendance, and category all affect fees, Flow becomes difficult. Apex can handle this logic better.
Example 2 – Payment Gateway Integration
To connect Salesforce with external payment systems, Apex APIs are required.

4. Integrated College Management System
CRM:
Salesforce helps manage student admissions and course records.
Objects:
- Student
- Course
- Faculty
- Attendance
Relationships:
Students are connected with courses and faculty members.
Validation:
Email field should not be empty during registration.
Flow:
Automatic email notification is sent after admission approval.
Apex:
Apex checks course seat availability before registration.

5.Pseudocode Examples:
Example 1
IF seats are full  
THEN block registration
Example 2
IF attendance < 75%  
THEN notify student
Example 3
IF fee is not paid  
THEN prevent exam registration

 6.Reflection
I understood that enterprise systems cannot depend only on clicks and configuration because some business logic becomes very complex.
Flows are useful for simple automation, but Apex gives more flexibility and control.
Developers should avoid unnecessary coding because configuration is easier to maintain and faster to build.

