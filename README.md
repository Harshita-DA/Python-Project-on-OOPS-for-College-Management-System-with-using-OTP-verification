# Python-Project-on-OOPS-for-College-Management-System-with-using-OTP-verification
# College Management System

## Overview
This Python program is a simple College Management System that allows users to create colleges, add teachers and students, and display their details. The program also includes an OTP-based email verification system for authentication when adding teachers and students.

## Features
- Create a college with a unique ID and name.
- Add teachers and students to a college.
- OTP verification via email before adding a teacher or student.
- Display details of teachers and students in a college.
- Menu-driven user interface for easy interaction.

## Technologies Used
- **Python**: Core programming language.
- **SMTP (smtplib)**: For sending OTP verification emails.
- **MIME (email.mime)**: For formatting email messages.
- **Random**: To generate OTPs.

## Installation
1. Clone this repository or download the script.
2. Ensure you have Python installed (version 3.x recommended).
3. Install the required dependencies:
   ```sh
   pip install smtplib email
   ```
4. Update the email credentials in the script with valid details.

## Usage
1. Run the script using:
   ```sh
   python script.py
   ```
2. Follow the menu options to interact with the program.
3. When adding a teacher or student, an OTP will be sent to their email for verification.
4. Enter the OTP correctly to complete the addition process.

## Security Note
- **Email Credentials**: Avoid hardcoding your email credentials in the script. Instead, use environment variables or a secure method to store them.
- **SMTP Configuration**: Ensure your email provider allows SMTP access.

## Future Enhancements
- Add a GUI for better user interaction.
- Enhance security by encrypting sensitive data.

## Author
- Developed by [Your Name]
- Contact: [Your Email]



