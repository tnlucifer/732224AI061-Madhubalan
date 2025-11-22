## Steps for workflow1
- Click “Create Workflow.”

- Click “Add First Step.”

- Search for “Form Trigger” or “On Form Submission.”

- Select it and add it to the workflow.

- Click the “+” button next to the Form Submission node.

- Search “Google Sheets.”

- Select “Append Row in Sheet.”

- Connect your Google Sheets credential.

- Choose your:

     - Spreadsheet

     - Sheet (tab)

- Map the form fields (from the left panel) to the sheet columns.

- Save the workflow.

## Steps for workflow2

- Add a new workflow or continue in the same workspace.

- Click “Add Node.”

- Search “Google Sheets Trigger.”

- Select it and add it.

- Connect your Google Sheets account.

- Choose the same Spreadsheet and Sheet used earlier.

- Set event type to “Row Added.”

- Click the “+” button on the right side of the Google Sheets Trigger node.

- Search “Gmail” or “Send Email.”

- Select “Send a Message (Gmail).”

- Connect your Gmail credential.

- Configure the email:

     - Recipient Email

     - Subject

     - Body (Insert row values using expressions)

- Save the workflow.

- Click “Execute Workflow.”

- Submit your form to test:

     - Form submission → adds a new row in Google Sheets

     - New row added → triggers Gmail to send an email

## Screenshots

<img width="590" height="443" alt="Screenshot 2025-11-22 110020" src="https://github.com/user-attachments/assets/c9efabd3-2511-4705-ab46-909951c6500f" />
