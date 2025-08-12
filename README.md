# Phishing Email Analysis – Cyber Security Internship Task 2

## Overview
This repository contains the analysis of a phishing email sample. The email pretends to be a Microsoft Office 365 security alert to lure the victim into clicking a malicious link.

## Email Sample
![Phishing Email Screenshot](phishing mail sample.png)

## Phishing Indicators Found
1. **Spoofed sender address** – `microsoft@email-records.com` instead of official `@microsoft.com`.
2. **Urgent language** – High-severity alert to create panic.
3. **Suspicious link** – "View alert details" button likely leads to phishing site.
4. **Generic greeting** – No personalization.
5. **Branding abuse** – Microsoft & Office 365 logos misused.
6. **Timing errors** – Time mismatch in message.
7. **Unnecessary technical details** – Random ID to look authentic.

## Conclusion
This is a clear phishing attempt designed to steal user credentials by exploiting fear and urgency. Always verify:
- Sender's email domain
- URLs before clicking
- Email headers
- Whether the message contains personalization

## Tools Suggested
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Whois Lookup](https://whois.domaintools.com/)
- [PhishTank](https://phishtank.com/)

---
**Author:** *Your Name*
