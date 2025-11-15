# Elavatelabstask2
# 🛡️ Phishing Indicators Report

This repository contains a detailed analysis of a sample phishing email.  
The goal is to highlight common phishing characteristics and provide a reference for training, awareness, and security documentation.

---

## 📑 Overview

Phishing emails are designed to trick recipients into revealing sensitive information or downloading malicious files.  
This report examines a suspicious email sample and identifies key indicators of phishing.

---

## 🔍 Indicators Identified

### 1. Sender’s Email Address
- Claimed: `support@paypal.com`
- Actual: `support@paypa1-security.com`
- **Indicator:** Domain spoofing using lookalike domains.

### 2. Email Header Analysis
- Originating IP traced to a free mail service, not PayPal servers.
- **Indicator:** Discrepancy between claimed sender and actual sending server.

### 3. Suspicious Links or Attachments
- Button labeled *“Verify Your Account”* links to `http://paypal.verify-login.com`.
- **Indicator:** Link does not match PayPal’s legitimate domain.

### 4. Urgent or Threatening Language
- Example: *“Your account will be suspended within 24 hours unless you verify your information.”*
- **Indicator:** Pressure tactics using urgency and fear.

### 5. Mismatched URLs
- Visible text: `https://paypal.com/login`
- Actual hyperlink: `http://malicious-site.ru/paypal`
- **Indicator:** Hidden redirect to malicious site.

### 6. Spelling and Grammar Errors
- Example: *“spe ling mistake”*, *“your informations are required.”*
- **Indicator:** Poor grammar and spelling errors.

### 7. Attachments
- File: `Invoice.pdf.exe`
- **Indicator:** Double extension disguises executable malware.

---

## ✅ Summary of Traits
- Spoofed sender domain  
- Header discrepancies  
- Malicious/mismatched URLs  
- Urgent and threatening language  
- Spelling and grammar errors  
- Suspicious attachment  

---

## ⚠️ Conclusion
The analyzed email exhibits multiple phishing characteristics and should be treated as **malicious**.  
Do not click links, download attachments, or provide any personal information.

---

## 📂 Repository Contents
- `phishing_indicators_report.pdf` → Full polished report in PDF format  
- `README.md` → This documentation file  

---

##
