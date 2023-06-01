# Aperto-Animo

**Automated_Email_System_Solicit_Paper_Submissions**

This Jupyter Notebook contains a Python script that automates the process of sending personalized emails to a list of contacts for the purpose of soliciting paper submissions.  It uses the "pandas" library to read contact information from an Excel spreadsheet and the "smtplib" library to send emails through a Gmail account. Here's an explanation of the personalized fields in the email content:

{0}: Your name. It should be provided as a string in the "your_name" variable.

{1}: Your email address. It should be provided as a string in the "your_email" variable.

{2}: Contact's university. It is extracted from the "University" column in the Excel spreadsheet.

{3}: Contact's department. It is extracted from the "Department" column in the Excel spreadsheet.

{4}: Contact's title. It is extracted from the "Title" column in the Excel spreadsheet.

{5}: Contact's email address. It is extracted from the "Email" column in the Excel spreadsheet.

{6}: Publication year. It should be provided as a string in the "publication_year" variable.

{7}: Submission deadline. It should be provided as a string in the "deadline" variable.


{8}: Submission form link. It should be provided as a string in the "link" variable.

These  fields are used to compose the email content dynamically for each contact. The script iterates over each row (contact) in the Excel spreadsheet, retrieves the relevant information, and substitutes the  fields in the email template to create and send a customized email. Successful email sends are printed as confirmation messages; errors encountered during the sending process are displayed as error messages.
