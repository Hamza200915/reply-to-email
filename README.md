# Make.com - AI Email Assistant

This repository contains the Make.com scenario blueprint for an automated AI email assistant.

## Workflow
The scenario does the following:
1.  **Gmail:** Watches for new incoming emails.
2.  **OpenAI:** Analyzes the email content.
3.  **Google Sheets:** Searches for relevant information in a spreadsheet.
4.  **OpenAI:** Generates a draft reply based on the email and spreadsheet data.
5.  **Tools (Sleep):** Waits for a short period.
6.  **Gmail:** Sends the generated email as a reply.

## How to Use
1.  Download the `.json` file from this repository.
2.  In your Make.com account, go to the "Scenarios" page.
3.  Click "Create a new scenario".
4.  In the editor, click the **`...`** menu and select **"Import Blueprint"**.
5.  Select the `.json` file to import the scenario.
6.  You will need to re-configure the connections (Gmail, OpenAI, Google Sheets) to use your own accounts.
