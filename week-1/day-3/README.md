1. Difference Between App, Object, Record, Field
App:
An App is a complete workspace in Salesforce that contains objects, tabs, and features for a specific purpose like Sales or Service.
Object:
An Object is like a database table used to store data. Example: Account, Contact, Student.
Record:
A Record is a single entry inside an object. Example: One student’s data inside the Student object.
Field:
A Field is a column in an object that stores specific information like Name, Age, or Email.
2. Standard vs Custom Objects
Standard Objects:
These are already available in Salesforce. Example: Account, Contact, Opportunity.
Custom Objects:
These are created by users based on business needs. Example: Student__c, Course__c.
3. College Data Model
Objects Used:
Student
Course
Faculty
Relationships:
A Student can enroll in many Courses (Many-to-Many)
A Faculty can teach multiple Courses (One-to-Many)
Simple Structure:
Student → Course (Enrollment relationship)
Course → Faculty (Assigned teacher)
Diagram:
<img width="1470" height="956" alt="Screenshot 2026-05-12 at 22 06 06" src="https://github.com/user-attachments/assets/379d736b-37c3-4bdd-820d-2495b7aeee56" />
4. Formula Fields
Formula Fields are fields that automatically calculate values based on other fields.
Example:
If Marks are stored, we can calculate Result:
If Marks > 35 → Pass
If Marks < 35 → Fail
Formula fields help reduce manual work and errors.
5. Validation Rules
Validation Rules are used to enforce data accuracy before saving records.
Example 1:
Age must be greater than 18 for student registration.
Example 2:
Email field must contain “@” symbol.
These rules prevent incorrect data from being stored.
6. Reflection – Why Structured Data Matters
Structured data is important because it keeps information organized, consistent, and easy to access.
In enterprise systems like Salesforce:
It improves decision making
Reduces data duplication
Increases efficiency
Helps automation and reporting
