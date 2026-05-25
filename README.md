TERRITORY MANAGER - GOOGLE SHEETS INTEGRATION GUIDE

STEP 1: PUBLISH THIS FILE TO GOOGLE SHEETS

Upload this file to Google Drive
Open it as Google Sheets (File > Open with > Google Sheets)
The 4 sheets will be preserved: Territories, Assignments, Comments, README
STEP 2: DEPLOY GOOGLE APPS SCRIPT (for write access)

In Google Sheets, go to Extensions > Apps Script
Paste the Apps Script code provided in the HTML app's Settings page
Deploy as Web App: Execute as 'Me', Access 'Anyone'
Copy the Web App URL
STEP 3: CONFIGURE THE HTML APP

Open the Territory Manager HTML file
Go to Settings tab
Paste the Apps Script Web App URL in 'Script URL' field
Enter your Google Sheet ID (from the URL between /d/ and /edit)
Enter your Google API Key (for read access from console.cloud.google.com)
Tap 'Save & Connect', then tap the sync button (⟳) in the header
SHEET STRUCTURE: Territories: territory_id last_completed_date Assignments: assignment_id | territory_id | assigned_to | date_assigned | date_completed | service_year Comments: comment_id | territory_id | assignment_id | comment_text | comment_date

DATE FORMAT: YYYY-MM-DD (e.g., 2025-09-01) SERVICE YEAR FORMAT: YYYY-YYYY (e.g., 2024-2025, Sept to Aug)
