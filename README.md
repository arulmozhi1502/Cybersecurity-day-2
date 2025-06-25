# Cybersecurity-day-2
#  Task 2: Analyze a Phishing Email Sample

## Objective
Identify phishing characteristics in a suspicious email sample to better understand and defend against email-based threats.

---
## what is phishing??
  - Phishing is the act of pretending to be someone/something to get information, in most cases, this is usually a password.
  - Attackers may send links or attachments designed to infect the recipient's system with malicious software or lure them into providing financial information, system credentials or other sensitive data.

## Refered Tools 
- Email client or saved email file (text format)
- Free online email header analyzers
   1. Google Admin Toolbox
   2. MAX Toolbox Email Header Analyzer
   3. Mailheader.org
   4. DNSChecker
   5. Zoho -> Toolkit -> email-header-analyzer
- Free online links and URL analyzers
    1. VirusTotal
    2. OpenPhish
    3. URLScan
    4. PhishTool Lookup
    5. URLVoid
- Free Text/Content checkers
    1. MailReach
    2. F-Secure
    3. Email-Checker
---

## Deliverables
A written report listing all phishing indicators found in the analyzed email.

---


## 1️. Obtain a Sample Phishing Email
  - Downloaded a phishing email from a public phishing archive.
  - Reference links: 
    -- "https://caniphish.com/free-phishing-test/phishing-email-templates"
    -- "https://security.berkeley.edu/education-awareness/phishing/phishing-examples-archive"
    
  - Saved in `.eml` or `.txt` format.

## 2️. Examine Sender’s Email Address
- **Check for spoofed domains** (e.g., `support@paypa1.com` instead of `paypal.com`)
- Look for strange subdomains or unverified addresses.
- Suspicious links
- language grammer used: **look for urgency like "act now", "last chance", etc.**
- Dangerous Attachments that might be of types .zip, .html, .exe, etc

 ### Spoofed emails
  Email spoofing is a common form of phishing attack designed to make the recipient believe that the message originates from a trusted source.
  
## 3️. Analyze Email Headers
- Copied raw email headers into **online email header analyzer**.
- Checked for:
  - SPF/DKIM/DMARC failures
  - Unexpected mail relay servers
  - Discrepancies between "From", "Reply-To", and "Return-Path"

## 4️. Identify Suspicious Links or Attachments
- Noted file attachments (e.g., `.zip`, `.exe`, `.html`) or links to non-legit domains.
- Hovered over all links to reveal real destinations (e.g., `http://malicious-site.ru` instead of `www.paypal.com`)

## 5️. Look for Urgent or Threatening Language
Examples:
- “Your account will be locked in 24 hours.”
- “Immediate action required!”

## 6️. Detect Mismatched URLs
- Found cases where display text and actual link don’t match.
- Example:
  - Text: `www.amazon.com`
  - Real link: `http://login.verify-amazon.support.ru`

## 7️. Check for Grammar or Spelling Errors
- Identified poor sentence construction, misspellings like:
  - “Congratulation, You have win the prize.”
  - “Click hear to reset password.”

## 8️. Summarize Phishing Traits Found
The email displayed these common phishing traits:
- Spoofed sender address
- Unusual URL redirection
- Grammar and spelling issues
- Unverified attachments
- Sense of urgency

---

## Outcome
- Gained awareness of phishing red flags.
- Learned how to read and interpret raw email headers.
- Improved ability to assess email threats in a structured, technical way.

---

> 🔐 *Reminder: Always analyze phishing samples in a secure, offline, or sandboxed environment.*
>> blog that helped me "https://intezer.com/blog/automate-analysis-phishing-email-files/#h-how-to-inspect-phishing-email-files-like-an-experienced-analyst"
>> https://blog.usecure.io/the-most-common-examples-of-a-phishing-email
