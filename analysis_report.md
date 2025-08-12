Phishing Email Analysis Report

Subject:
High-severity alert: Phish delivered due to tenant or user override

Sender:
Microsoft <microsoft@email-records.com>

  ⚠ Suspicious domain — Official Microsoft emails come from @microsoft.com or subdomains, not @email-records.com.


  Indicators of Phishing:

  | No. | Indicator                  | Evidence in Email                          | Why Suspicious                              |
| --- | -------------------------- | ------------------------------------------ | ------------------------------------------- |
| 1   | **Spoofed Sender Address** | `microsoft@email-records.com`              | Not an official Microsoft domain            |
| 2   | **Urgent Language**        | "A high-severity alert has been triggered" | Creates panic to make user click            |
| 3   | **Suspicious Link**        | "View alert details" button (URL hidden)   | Likely redirects to phishing site           |
| 4   | **Generic Salutation**     | No recipient name mentioned                | Microsoft usually addresses user personally |
| 5   | **Technical Jargon**       | Random message ID numbers                  | Used to appear legitimate but confuse user  |
| 6   | **Timing Discrepancy**     | 4:22 PM email mentions 9:22 PM time        | Indicates poor formatting or fake data      |
| 7   | **Branding Abuse**         | Microsoft & Office 365 logos               | Common tactic to make email look real       |


Likely Goal:

  To trick the user into clicking the link → steal login credentials for Microsoft account.

Header Analysis (Expected Findings if checked):

    SPF/DKIM/DMARC fail or mismatch

    IP address from suspicious foreign server

    Reply-to different from sender
