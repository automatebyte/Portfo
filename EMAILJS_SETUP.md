# EmailJS Setup Instructions

To make your contact form functional, follow these steps:

## 1. Create EmailJS Account
- Go to https://www.emailjs.com/
- Sign up for a free account

## 2. Add Email Service
- In your EmailJS dashboard, go to "Email Services"
- Click "Add New Service"
- Choose Gmail (recommended)
- Connect your Gmail account (kipkogeidennis05@gmail.com)

## 3. Create Email Template
- Go to "Email Templates"
- Click "Create New Template"
- Use this template:

```
Subject: New Portfolio Contact Message

From: {{from_name}} ({{from_email}})

Message:
{{message}}

---
Sent from your portfolio contact form
```

## 4. Get Your Credentials
- Public Key: Found in "Account" > "General"
- Service ID: Found in "Email Services" 
- Template ID: Found in "Email Templates"

## 5. Update Your Code
Replace in `script.js`:
- `YOUR_PUBLIC_KEY` with your public key
- `YOUR_SERVICE_ID` with your service ID  
- `YOUR_TEMPLATE_ID` with your template ID

## 6. Test
- Deploy your site
- Fill out the contact form
- Check your email for messages

Your contact form will now send emails directly to kipkogeidennis05@gmail.com!