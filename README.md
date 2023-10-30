# MailHook
<h4 align="center">Email Forensics</h4>

SPAM, spear phishing, and spear phishing emails are sent to every organisation. The first thing that must be done when such emails are received is to obtain the email headers, attachments, email addresses, and embedded URLs. These should then be shared with the internal security analysts or the MSSP who is currently handling your security. 

The reason is to find all the required information i.e. to perform end-to-end Email Forensics in order to find answers like. 

- Who sent the email?
- From where it originated?
- How many people have received the email?
- Does the email contained a phishing link or it contained only plain text?
- Does the email contains any attachments?

---

## Supported Email Extensions

Currently the script is able to scrape the data from the following extensions only. 

- **.msg**
- **.eml**

```

## Butchering Details From Emails

These headers include the following.
- FROM
- TO 
- SUBJECT
- DATE
- CC
- BCC
- Attachments


# Usage - EML/MSG Formats
It is required to save the first email recevied and have it supplied to NightOwl. The extension should be `.eml` or `.msg` for the NightOwl to work properly.

The attachments will be stored automatically in `Attachments` folder.

---
