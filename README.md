# 📧 Phishing Email Analysis – Fake Bank Alert

## 🔍 Email Summary
- **Sender**: support@yourbank-secure.com
- **Subject**: Urgent: Verify Your Account Immediately
- **Date**: 22 May 2025
- **Link**: http://yourbank-secure-login.com/verify
- **Attachment**: secure_verification_form.zip
- **Tool**:MXToolbox

---

## 🚩 Phishing Indicators

| Indicator                 | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Spoofed Email             | Domain mimics legitimate bank but is not verified                           |
| Failed SPF/DKIM/DMARC     | Email failed all three authentication checks                                |
| Suspicious Link           | Uses a fake login URL, could lead to credential theft                       |
| Urgent Language           | Creates panic by threatening account suspension                             |
| Generic Greeting          | "Dear Customer" instead of real name                                        |
| Malicious Attachment      | Zip file possibly containing malware                                        |
| IP Origin Discrepancy     | Sender IP not linked to real banking infrastructure                         |

---

## 🔎 Header Analysis (via MXToolbox)
- **SPF**: Failed
- **DKIM**: Failed
- **DMARC**: Failed
- **IP Address**: 203.0.113.45 → Residential ISP (not a bank)

---

## 🛡️ Conclusion

This is a **high-risk phishing attempt** combining:
- **Spoofed identity**
- **Urgent psychological manipulation**
- **Malicious payload (attachment)**

---
