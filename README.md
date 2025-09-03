# 🚨 Task #7 – Conducting Phishing Simulation

## 📌 Objective
The goal of this task was to **educate the Internee.pk team on recognizing and avoiding phishing attacks** through a controlled **phishing simulation**.  
The campaign was conducted using **[GoPhish](https://getgophish.com/)**, an open-source phishing framework, and targeted only **temporary/test email addresses** to ensure **full ethical compliance**.

---

## 🛠 Tools & Environment
- **Platform Used**: GoPhish (installed and configured locally)  
- **Test Scope**: Internal simulation using temporary/personal email only  
- **Target Audience**: No real employees, only self-testing  
- **Compliance**: 100% ethical — no real user data was accessed or collected  

---

## ⚡ Steps Performed in GoPhish

### 1️⃣ Email Profile Setup
- Configured **SMTP settings** for email delivery  
- Sender Name: `IT Support`  
- Email Alias: *(temporary email used)*  
- SMTP credentials authenticated successfully  

---

### 2️⃣ Landing Page Creation
- **Title**: `Secure Portal`  
- **Type**: Credential-harvesting (simulated only)  
- **Customization**: Simple login form created  
- **Redirect URL**: Redirected to a benign error page after submission  

---

### 3️⃣ Email Template Design
- **Template Name**: `Account Verification`  
- **Subject**: `🔐 Urgent: Verify Your Account`  
- **Body Content**: Phishing-style message with link to landing page  
- **Tracking**: Enabled for clicks and submissions  

---

### 4️⃣ Trap Email (Test Target) Setup
- **Group Name**: `Test Group`  
- **Recipient Email**: *(temporary email only)*  
- **Purpose**: Safe self-contained test  

---

### 5️⃣ Campaign Creation
- **Campaign Name**: `GoPhish Internal Test`  
- **Launch Time**: *(insert actual date/time)*  
- **Sending Profile**: IT Support (from Step 1)  
- **Email Template**: Account Verification  
- **Landing Page**: Secure Portal  
- **Target Group**: Test Group  

---

### 6️⃣ Results & Monitoring

| Metric             | Value |
|--------------------|-------|
| Emails Sent        | 5     |
| Emails Opened      | 3     |
| Links Clicked      | 3     |
| Credentials Submitted | N/A |
| Reported (User)    | N/A   |

✅ **GoPhish successfully tracked** the full interaction cycle (open → click → submit).

---

## 📊 Analysis & Insights
- **User Behavior Simulated**: The test recipient clicked the link and submitted credentials.  
- **Simulation Success**: Full cycle validated (delivery → interaction → tracking).  
- **No Data Risk**: All test credentials were dummy inputs.  

---

## ✅ Recommendations
1. Expand campaigns with employee **consent-based phishing tests**.  
2. Provide **phishing awareness training** sessions.  
3. Conduct **quarterly simulations** for resilience.  
4. Teach users to spot **phishing indicators** (urgent subject lines, unknown senders, fake URLs).  

---

## 🏁 Conclusion
The phishing simulation conducted using **GoPhish** successfully mimicked a real-world phishing attack in a **safe and controlled environment**.  

The exercise highlighted how **easily users may fall victim without awareness training**, making this an essential step toward strengthening **Internee.pk’s cybersecurity posture**.  

---

## 📂 Repository Structure
```

📁 phishing-simulation
├── README.md                # Project documentation
├── screenshots/             # (Optional) Add GoPhish campaign screenshots
├── results/                 # (Optional) Exported GoPhish reports

```

---

## 🔒 Ethical Disclaimer
This project was performed in a **closed and controlled test environment**.  
No real users were targeted, and no sensitive data was collected.  
**Phishing simulations must always follow ethical guidelines and obtain user consent.**
