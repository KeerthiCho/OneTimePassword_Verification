# OneTimePassword_Verification

# Python OTP Email Verification

A Python script that generates a 6-digit One Time Password (OTP) and sends it to a user via email for verification.

## Features
- Generates a random 6-digit OTP
- Sends the OTP to the provided email address using Gmail's SMTP server
- Verifies user input against the sent OTP
- Uses TLS encryption for secure email sending

## Requirements
- Python 3.x
- Gmail account
- Gmail App Password (normal Gmail password will not work)

## Setup
1. **Enable Gmail App Passwords**
   - Go to your Google Account security settings
   - Enable Two-Step Verification
   - Generate an App Password for "Mail" and your device
   - Copy the generated 16-character password

2. **Edit the script**
   - Replace `"Your Gmail Account"` with your Gmail address
   - Replace `"You app password"` with your Gmail App Password
   - Replace `'&&&&&&&&&&&'` with your Gmail address

Example:
```python
s.login("myemail@gmail.com", "abcd efgh ijkl mnop")
s.sendmail('myemail@gmail.com', emailid, msg)
