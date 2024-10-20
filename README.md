# MailMavin

MailMavin revolutionizes email management by automating filtering, summarization, and responses with Python, NLP, CV, and WhatsApp integration. The application quickly summarizes emails for efficient decision-making and provides a seamless way to manage communications.

## Features

- Fetch unread emails from Gmail.
- Summarize email subjects.
- Send summaries to WhatsApp using Twilio.

## Requirements

- Python 3.x
- `google-auth`
- `google-auth-oauthlib`
- `google-auth-httplib2`
- `google-api-python-client`
- `twilio`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/mail_mavin.git
   cd mail_mavin
2. Set up a virtual environment:
   python -m venv venv
3. Activate the virtual environment:
   .\venv\Scripts\activate
4. Install the required libraries:
   pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client twilio

5. Run the application:
   python mail_mavin.py
