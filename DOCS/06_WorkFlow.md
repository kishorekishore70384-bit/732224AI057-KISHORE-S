- Start with “When clicking ‘Execute workflow’” – this trigger starts the workflow manually.
- The workflow reads all rows from your Google Sheet using Get row(s) in sheet.
- The IF node checks a condition (example: row number, age, name, etc.).
- If the condition is true, the data goes to the Append row in sheet node and gets added to Sheet-1.
- If the condition is false, the data goes to Append row in sheet1 and gets added to another sheet.
- Click Execute Workflow to test — the output shows how many rows went to the True branch and False branch.
# screenshot
<img width="1251" height="648" alt="Screenshot 2026-02-08 095950" src="https://github.com/user-attachments/assets/c9d94c5a-05b6-4bee-8d36-4fe96760eadb" />
