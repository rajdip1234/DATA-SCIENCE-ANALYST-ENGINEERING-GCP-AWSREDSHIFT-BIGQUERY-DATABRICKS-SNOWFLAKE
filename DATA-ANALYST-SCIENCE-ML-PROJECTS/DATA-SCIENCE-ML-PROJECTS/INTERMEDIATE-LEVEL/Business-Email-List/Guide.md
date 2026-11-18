<!--For Google Account Set Up-->

Step 1: Turn on 2-Step Verification

Google requires 2-Step Verification before it lets you create an App Password.
• Open your Google Account: Go to your Google Account Security Settings.
• Select 2-Step Verification: Scroll down to the "How you sign in to Google" section and click on 2-Step Verification.
• Follow the prompts: Click Get Started and follow the on-screen steps to link your phone number or an authenticator app.

Step 2: Create an App Password

Once 2-Step Verification is active, you can generate a special password just for your app.
• Go to App Passwords(https://myaccount.google.com/apppasswords): Visit the direct Google App Passwords page and sign in if prompted.
• Name your app: Type a clear name for the app or device you are connecting (such as "Outlook" or "Website Mailer") and click Create.
• Copy the 16-digit code: A pop-up will display a 16-character password in a yellow bar. Copy this code immediately because you cannot view it again.

Step 3: Connect Your App

• Open your app settings: Go to the login or SMTP settings of your third-party app or device.
• Enter your credentials: Type your full Gmail address as the username.
• Paste the App Password: Paste the 16-digit App Password into the password field instead of your regular Gmail password.

•For GMAIL-search on google or similar browser with "host name for gmail"
Incoming Mail Servers (Receive)

• IMAP Hostname: imap.gmail.com
	• Port: 993 (Security: SSL/TLS)
• POP3 Hostname: pop.gmail.com
	• Port: 995 (Security: SSL/TLS)

Outgoing Mail Server (Send)

• SMTP Hostname: smtp.gmail.com
	• Port (TLS): 587 (Security: STARTTLS)
	• Port (SSL): 465 (Security: SSL/TLS)

<!--For Yahoo Account Set Up-->
• Sign in your Yahoo account first.
• Then go security setting->App password->Give App name->Generate Password-Note It Down

•For Yahoo-search on google or similar browser with "host name for gmail"
The hostnames for Yahoo Mail depend on whether you are receiving or sending email:
• Incoming Mail (IMAP): imap.mail.yahoo.com (Port 993, SSL/TLS required)
• Incoming Mail (POP3): pop.mail.yahoo.com (Port 995, SSL/TLS required)
• Outgoing Mail (SMTP): smtp.mail.yahoo.com (Port 465 for SSL/TLS, or Port 587 for STARTTLS)
For more setup details, you can visit the official Yahoo Mail IMAP Help Page(https://help.yahoo.com/kb/SLN4075.html) or the Yahoo POP Access Instructions(https://help.yahoo.com/kb/SLN4724.html).


•Also visist for StartTls working process-https://www.twilio.com/en-us/sendgrid->https://www.twilio.com/en-us/products/email-api