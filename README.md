# Analyze-a-Phishing-Email-Sample
Task 2

## Objective
Identify phishing characteristics in a suspicious email sample using header analysis, content inspection, and security intelligence tools.

---

## Email Sample Details
- **Subject:** Urgent: Microsoft account security alert  
- **Sender Email:** support@office-365-notifications[.]com  

---

## Tools Used

### MX Lookup
- MX Lookup tools

### Online URL / Attachment Analysis
- AnyRun
- Browserling
- Hybrid Analysis
- urlscan

### Reputation Check
- VirusTotal
- Dehashed
- Cisco Talos Intelligence
- AbuseIPDB

### Phishing Analysis
- ISIT Phishing

---

## 1. Sender Address Analysis
The sender's email domain does not match the official domain of the organization.

- Official domain: `@microsoft.com, @microsoftsupport.com, or @mail.support.microsoft.com`
- Received domain: `support@office-365-notifications[.]com`

This indicates possible **email spoofing**.

---

## 2. Email Header Analysis
Header analysis indicates:
- SPF/DKIM authentication failed or misaligned
- Sending IP address does not match official mail servers
- Possible header manipulation detected

These discrepancies suggest a **forged or suspicious email origin**.

---

## 3. Suspicious Links or Attachments
- Displayed link: `https://office-365-notifications[.]com`or Recover account click Box
- Actual destination: `http://192.168.xx.xx/login`

This mismatch indicates **phishing redirection**.

Suspicious attachment:
- `Account_Update_Form.zip`

---

## 4. Urgent or Threatening Language
The email contains urgency tactics such as:
- “Your account will be suspended within 24 hours.”
- “Immediate action required.”

Such language is commonly used in phishing attempts.

---

## 5. URL Reputation Check
Reputation checks show the domain/IP is newly registered or flagged as suspicious by security intelligence platforms.

---

## 6. Spelling and Grammar Errors
Example error:
- “Please verify your informations immediately.”

Legitimate organizations typically maintain professional communication standards.

---

## 7. Additional Indicators
- Generic greeting (“Dear Customer”)
- Requests for sensitive information (passwords, OTP, banking credentials)
- Suspicious compressed attachment

---

## Conclusion
The analyzed email shows multiple phishing indicators:

- Spoofed sender address  
- Header inconsistencies  
- Suspicious links and attachments  
- Urgent threatening language  
- Grammar errors  
- Requests for sensitive information  
- Suspicious domain/IP reputation  

**Therefore, the email is highly likely to be a phishing attempt and should be reported and deleted immediately.**

