## Steps

- Click “Create Workflow.”

- Click “Add First Step.”

- Search for “Manual Trigger.”

- Select “When clicking ‘Execute workflow’” and add it.

- Click the “+” button next to the Manual Trigger node.

- Search for “Google Sheets.”

- Select “Get row(s) in sheet.”

- Connect your Google Sheets credential.

- Select your Spreadsheet and the Sheet you want to read.

- Configure how many rows to fetch or leave default settings.

- Click the “+” button to the right of the Get Rows node.

- Search for “If.”

- Add the If node to the workflow.

- Set up the condition based on the column you want to evaluate (e.g., Column value equals “Yes”).

- On the true output of the If node, click the “+” button.

- Search “Google Sheets.”

- Select “Append row in sheet.”

- Connect Google Sheets credentials (or reuse existing).

- Choose the Spreadsheet and Sheet where TRUE-condition rows should be added.

- Map the fields from the previous node to the new sheet columns.

- On the false output of the If node, click the “+” button.

- Search “Google Sheets.”

- Select “Append row in sheet1.”

- Connect your credentials (or reuse the same).

- Select the Spreadsheet and Sheet1 where FALSE-condition rows should go.

- Map all required fields for this sheet as well.

- Click “Execute Workflow.”

- The workflow will run:

     - Manual trigger starts the workflow

     - Rows are read from Google Sheets

     - IF node checks your condition

     - If TRUE → row is appended to Sheet A

     - If FALSE → row is appended to Sheet B
## Screenshot

<img width="954" height="461" alt="Screenshot 2025-11-22 120131" src="https://github.com/user-attachments/assets/b79cc8b5-5bff-4bdd-9c39-ae6ffe7b7844" />
