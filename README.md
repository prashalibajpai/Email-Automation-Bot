# Email Automation Bot
This bot reads your email messages with IMAP and saves email attachments into separate folder for each sender. 
It also sends an email containing either error and it's screenshot or the final success report based on the outcome.
It performs following activities:
- Fetches all unread emails from your email id which is configured using IMAP activity.
- Loops through each fetched email and extract relevant information.
- It now saves the email message and it's attachments in separate folders for each user.
- If there is any exception raised during the processing, it captures the error with screenshot and send out an email.
- If the process runs successfully without any errors, it creates a report and send it out as email.