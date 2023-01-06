# Assignment for Salesforce Admin 

The assignment consists in:
1. A flow that assign leads based on the lead Country to the appropriate users (based on the country set on the User). Additionally, the lead status is updated to “Assigned” and an email is sent to the new owner informing him about the assignment of the record.
2. A validation rule that prevents users from closing leads if the Email and Lead Source fields are not filled in.
3. A formula field displayed on the lead record which calculates the priority of the lead based on the
Number of employees:‘Low’ for less then 50 employees, 
‘Medium’ between 50 and 100 employees and ‘High’ for over 100 employees.
