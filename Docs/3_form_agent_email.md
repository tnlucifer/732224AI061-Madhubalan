## Steps

- Click “Create Workflow.”

- Click “Add First Step.”

- Search for “Form Trigger” or “On Form Submission.”

- Select it and add it to the workflow.

- Click the “+” button after the trigger node.

- Search for “AI Agent.”

- Select AI Agent and add it.

- In the AI Agent node, under Source for Prompt, click “Define below.”

- Under Prompt › User, drag and drop the field “topic” from the On Form Submission node on the left into the User prompt box.

- Under the AI Agent node, click the “+” under Chat Model*.

- Search “Google Gemini Chat Model.”

- Select it to add the Gemini Model node.

- Click the “+” button to the right of the AI Agent node.

- Search for “Gmail” or “Send Email.”

- Select Send a Message (Gmail).

- Configure the Gmail node:

     - Recipient email

     - Subject

     - Body (insert the AI Agent’s response using expressions)

- Click “Execute Workflow.”

- Submit your form to test the workflow.

## Screenshot

<img width="917" height="436" alt="Screenshot 2025-11-22 101700" src="https://github.com/user-attachments/assets/a57c6e67-cbcf-4551-afb6-ead1124e68d7" />
