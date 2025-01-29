# whatsapp


Booking Management Automation

Problem Overview

Our client is facing a major challenge: receiving booking reservations every 5 minutes via email, each with unique time and location details. The current process requires:

Searching the email and a contact list (in a spreadsheet) for location, time, and relevant contacts.

Sending messages to the appropriate people and also notifying a communication channel (e.g., Slack or MS Teams) in case someone is missing from the contact list.

Providing customer support in parallel with all these tasks.


Solution: Python Automation

To solve this, we've created a Python-based automation system with the following capabilities:

📧 Email Parsing: Automatically reads and processes incoming booking reservation emails.

🔍 Data Comparison: Compares booking details in the email with contact information in a spreadsheet.

🎯 Targeted Messaging: Sends personalized messages to the right contacts based on the booking details.

⚡ Handles High Traffic: Can efficiently manage up to 2,000 requests per day.

⏱ 24/7 Service: Runs continuously without downtime, ensuring that bookings are processed round the clock.

📊 Data Analytics: Automatically generates detailed reports for tracking and analyzing performance.

🤖 Bonus Feature: Potential integration of a customer support chatbot to assist with queries.


Project Structure

/src: The core code for email reading, data comparison, and messaging.

/data: Sample data files (e.g., booking info, contact lists).

/docs: Documentation on how the system works and potential setup.

/tests: Unit tests to ensure the system works as expected.


How It Works

1. Email Parsing: The system reads incoming emails to extract booking details.


2. Data Comparison: The system compares email data with the contact list from the spreadsheet to identify who needs the information.


3. Message Dispatch: The system sends messages to the identified contacts.


4. Channel Notification: If a contact is missing from the list, a notification is sent to the communication channel.


5. Reports: Each transaction is logged and reported for tracking.



Collaborators

This project is being developed by Nqobile Muyambiri and Craig M. We will be posting updates as we progress.


