# Cybersecurity-day-2
# 🛡️ Task 2: Analyze a Phishing Email Sample

## 🎯 Objective
Identify phishing characteristics in a suspicious email sample to better understand and defend against email-based threats.

---

## 🧰 Tools Used
- Email client or saved email file (text format)
- Free online email header analyzers (e.g., Google Admin Toolbox, MXToolbox)

---

## 📦 Deliverables
A written report listing all phishing indicators found in the analyzed email.

---

## 🧭 Steps Followed

### 1️⃣ Obtain a Sample Phishing Email
- Downloaded a phishing email from a public phishing archive (e.g., phishtank.com or email sample databases).
- Saved in `.eml` or `.txt` format.

### 2️⃣ Examine Sender’s Email Address
- **Check for spoofed domains** (e.g., `support@paypa1.com` instead of `paypal.com`)
- Look for strange subdomains or unverified addresses.

### 3️⃣ Analyze Email Headers
- Copied raw email headers into an **online email header analyzer**.
- Checked for:
  - SPF/DKIM/DMARC failures
  - Unexpected mail relay servers
  - Discrepancies between "From", "Reply-To", and "Return-Path"

### 4️⃣ Identify Suspicious Links or Attachments
- Noted file attachments (e.g., `.zip`, `.exe`, `.html`) or links to non-legit domains.
- Hovered over all links to reveal real destinations (e.g., `http://malicious-site.ru` instead of `www.paypal.com`)

### 5️⃣ Look for Urgent or Threatening Language
Examples:
- “Your account will be locked in 24 hours.”
- “Immediate action required!”

### 6️⃣ Detect Mismatched URLs
- Found cases where display text and actual link don’t match.
- Example:
  - Text: `www.amazon.com`
  - Real link: `http://login.verify-amazon.support.ru`

### 7️⃣ Check for Grammar or Spelling Errors
- Identified poor sentence construction, misspellings like:
  - “Congratulation, You have win the prize.”
  - “Click hear to reset password.”

### 8️⃣ Summarize Phishing Traits Found
The email displayed these common phishing traits:
- Spoofed sender address
- Unusual URL redirection
- Grammar and spelling issues
- Unverified attachments
- Sense of urgency

---

## ✅ Outcome
- Gained awareness of phishing red flags.
- Learned how to read and interpret raw email headers.
- Improved ability to assess email threats in a structured, technical way.

---

> 🔐 *Reminder: Always analyze phishing samples in a secure, offline, or sandboxed environment.*

