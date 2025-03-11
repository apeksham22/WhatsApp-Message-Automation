# WhatsApp Message Automation

This Python script allows users to schedule and send WhatsApp messages using the Twilio API. The user inputs the recipient's name, phone number, message, and scheduled date/time, and the script sends the message at the specified time.

## Features
- Automates WhatsApp messaging using Twilio API
- Allows users to schedule messages for a future date and time
- Simple user input interface

## Prerequisites
- Python 3.x
- Twilio account with WhatsApp API access
- Required Python libraries:
  - `twilio`
  - `datetime`
  - `time`

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install the required dependencies:
   ```bash
   pip install twilio
   ```

## Usage
1. Set up your Twilio credentials by replacing `account_sid` and `auth_token` in the script.
2. Run the script:
   ```bash
   python WhatsApp_Message_Automation.py
   ```
3. Enter the required details:
   - Recipient's name
   - Recipient's WhatsApp number (including country code)
   - Message content
   - Scheduled date and time (YYYY-MM-DD HH:MM format)
4. The script will wait until the scheduled time and send the message automatically.

## Notes
- Ensure that your Twilio account is verified and has WhatsApp API enabled.
- The phone number must be in the correct format (e.g., `+1234567890`).
- The script should be run continuously to ensure message delivery at the scheduled time.

## Author
Your Name - [GitHub Profile](https://github.com/apeksham22)

## Acknowledgments
- [Twilio API Documentation](https://www.twilio.com/docs/whatsapp/api)

