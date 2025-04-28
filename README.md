# rss-feed-to-google-sheets
Automation to fetch RSS feed and save it into Google Sheets



# RSS Feed to Google Sheets Automation

This project fetches blog posts from an RSS Feed and saves them automatically into a Google Sheet using an automation workflow.


## Workflow Diagram

Below is the visual workflow created in n8n:

![RSS Workflow Diagram]  ![image](https://github.com/user-attachments/assets/5f85d5af-9554-4dd0-aad0-9a599d4b9dac)


## How It Works

1. **RSS Feed Trigger**:
   - Watches the [n8n Blog RSS feed](https://blog.n8n.io/rss/).
   - Detects new posts automatically.

2. **Edit Fields**:
   - Extracts important information from the RSS feed:
     - Post Title
     - URL Link
     - Published Date

3. **Google Sheets**:
   - Appends the extracted blog post data into a connected Google Sheet.
   - Each new post adds a new row in the sheet.

## Technologies Used

- [n8n](https://n8n.io/) for automation
- Google Sheets API
- RSS feed reading

## Benefits

- Real-time blog monitoring
- No manual copy-paste needed
- Data is neatly organized in Google Sheets

## Setup Instructions

1. Clone this repository.
2. Import the workflow into your n8n instance.
3. Connect your Google Sheets credentials.
4. Set up the RSS feed URL.
5. Activate the workflow!




## Author

- ADIL

---

