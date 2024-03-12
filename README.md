Rules For Notification Service

Rules
Check Notification Data Completeness
This rule checks if the notification request contains all the required fields: mode, subject, body, and recipient.

Check Notification Mode Validity
This rule verifies if the specified notification mode is valid by checking if it matches any of the predefined values.

Check Email Validity
If the notification mode is "EMAIL", this rule ensures that the recipient's email address is valid by using a regular expression pattern.

Save Notification Entity
Once all the validation checks pass, this rule triggers the saving of the notification entity and the sending of the email. Note that the actual logic for saving and sending email is implemented in Java code.
