 1. What is SOQL?
SOQL stands for Salesforce Object Query Language.
It is used to retrieve data from Salesforce objects.
Using SOQL, we can search and fetch records like students, courses, faculty details, and attendance data.
For example, we can find all students enrolled in a specific course.

2. What is an Apex Trigger?
An Apex Trigger is a piece of code that runs automatically when data changes in Salesforce.
Triggers work during events like:
- Insert
- Update
- Delete

3. Difference Between Flow and Trigger
Flow:
No-code automation 
Easy to create
Good for simple processes
Faster development
Trigger:
Code-based automation
Requires Apex programming
Good for complex business logic
More control and flexibility
Difference Between Before Trigger and After Trigger
Before Trigger:
Runs before data is saved 
Used for validation or updating values
Faster because record is not committed yet 
 After Trigger:
Runs after data is saved
Used for notifications and related actions
Used when record ID is needed

4.Trigger Use Cases
Example 1 – Welcome Email
Event:
After student registration
Action:
Automatically send welcome email to student.
Example 2 – Course Full Notification
Event:
After course seats become full
Action:
Notify faculty members that registration is closed.
Example 3 – Attendance Warning
Event:
After attendance update
Action:
Send warning if attendance drops below 75%.
Example 4 – Fee Payment Confirmation
Event:
After fee payment record update
Action:
Send payment confirmation message.
Example 5 – Exam Eligibility Check
Event:
Before exam registration
Action:
Block registration if attendance is below required percentage.

5.Query Examples
Query 1
Find all students in Course A.
Query 2
Find all courses handled by Faculty X.
Query 3
Find students with attendance below 75%.
Query 4
Find students who have not paid fees.
Query 5
Find courses with no remaining seats.

6.Reflection
I understood that enterprise systems need event-driven behavior because actions should happen automatically when data changes.
Manual work becomes difficult when thousands of records are involved.
Triggers and automation help systems react quickly, reduce human effort, and improve accuracy.
However, developers should avoid unnecessary automation because very complex logic can become difficult to manage and debug.



