# User-profile-check-and-E-mail-sender
This Python script collects user information such as name, date of birth, phone number, Instagram ID, and email,validates the input using regular expressions (regex), and sends an email containing the provided details.

## Features
- Validates user input for:
  - Name (only alphabets and spaces)
  - Date of Birth (format: `DD-MM-YYYY`)
  - Mobile Number (formats like `789-456-1234`)
  - Email (only Gmail addresses)
- Sends an email with the collected information to the user.

## Prerequisites
- Python 3.x
- `smtplib` (built-in)
- `email.mime` (built-in)
- Internet connection to send emails

## Installation
No additional installation is required as all dependencies are built into Python.

## Usage
1. Run the script:  
   ```bash
   python E-mail\ via\ python\ using\ regex.py
Enter your details when prompted.
If the input format is incorrect, the script will ask you to enter the value again.
After entering all details, the script sends an email to the provided Gmail account.
SMTP Configuration
The script uses Gmail's SMTP server to send emails:

SMTP Server: smtp.gmail.com
Port: 587
Login credentials are required.

#Important
Replace vijaykumarvuriti2@gmail.com and the password in server.login() with your own credentials.
If using a Google account, enable "Less secure apps" or use an App Password.
