# day-5


# What is Apex?
Apex is a programming language in Salesforce used to add custom business logic and automation in Salesforce. It is similar to Java and is mainly used when Flow or configuration is not enough.

# Difference
Flow vs Apex
    Flow                                            	Apex
No coding required	                          Requires programming
Easy to create	                              More complex
Used for simple automation	                  Used for advanced automation
Drag-and-drop tool                           	Written using code
Faster development                          	More flexibility

Configuration vs Coding
Configuration                                           	Coding
Uses clicks, settings, and tools	                Uses programming languages
Easy to maintain	                                Requires developer knowledge
Best for simple tasks                           	Best for complex tasks
Less time required                              	More development time
Example: Flow Builder                            	Example: Apex


# Real Examples Where Apex Is Needed
Automatically assigning students to classes based on marks and seat availability.
Sending bulk email notifications to thousands of students at once.
Integrating Salesforce with external systems like payment gateways or college websites.

# Integrated College Management System Design
. CRM
The college management system uses Salesforce CRM to manage students, faculty, courses, attendance, and fees in one platform.

. Objects
Student Object
Faculty Object

. Relationships
One Department has many Students.
One Faculty teaches many Courses.

. Validation
Phone number must contain 10 digits.
Marks cannot exceed 100.
Email should be in valid format.

. Flow
Send admission confirmation email automatically.
Generate fee reminders automatically.

. Apex
Integrate online payment system with fee records.
Generate automatic semester reports for students.

# Pseudocode Examples
Student Admission Logic
IF student form is submitted
THEN create student record
AND send confirmation email

Fee Reminder Logic
IF fee due date is near
THEN send reminder message to student

Scholarship Logic
IF marks > 85 AND attendance > 90%
THEN scholarship = Approved
ELSE scholarship = Not Approved

# Reflection: Why Enterprise Systems Eventually Need Programming
Enterprise systems start with simple configuration tools, but as business requirements grow, programming becomes necessary. Coding helps organizations handle complex logic, integrations, security, and large-scale automation. In systems like college management, programming improves flexibility, efficiency, and customization according to organizational needs.
