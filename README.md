 🛡️ Phishing Email Analysis Report

 ✅ Task Title:
Analyze a Phishing Email Sample

 👤 Intern Name:
Mahin Kuddus Shaikh

 📬 Sample Phishing Email Used:
See `sample-email.txt` for full content.

 🕵️ Phishing Indicators Identified:

| No. | Indicator             | Description |
|-----|------------------------|-------------|
| 1   | **Email Spoofing**     | Sender email is `security-update@paypall.com` — note the misspelled domain “paypall.com”. |
| 2   | **Urgent Language**    | "URGENT", "Failure to do so will result in permanent suspension" creates pressure. |
| 3   | **Suspicious Link**    | The hyperlink points to `http://paypal.com.verify-update-securityalert-login.com`, which is **not** an official PayPal domain. |
| 4   | **Grammatical Errors** | Phrases like "verify your account information immediately" are poorly structured. |
| 5   | **Mismatched Branding**| Generic sign-off “PayPal Security Team” without actual contact information or formatting. |
| 6   | **Unusual Attachment** | The email includes an attachment `verify_form.doc` — phishing emails often include harmful files like `.doc`, `.exe`, `.zip`. |

 🧰 Tools Used for Analysis:
- Manual inspection
- Online header analyzers (optional)
- URL inspection (hover & check domain)

 🧠 What I Learned:
- Identifying spoofed senders
- Recognizing social engineering
- Detecting suspicious links and attachments

 📁 GitHub Repo Structure:
```
phishing-analysis-task/
├── README.md
├── sample-email.txt
└── screenshots/
    └── header-analysis.png (optional)
```
