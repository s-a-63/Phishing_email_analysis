# Phishing Email Analysis - Internship Task 🛡️

This repository contains the analysis of a simulated phishing email as part of a cybersecurity internship project. The objective was to apply email threat detection skills and identify common phishing indicators using real-world techniques.

## 🧠 Objective

To analyze a suspicious phishing email using technical tools and manual inspection in order to raise awareness of phishing tactics and improve email security skills.

---

## 📝 What I Did in This Task

### 🔹 Step 1: Collected a Sample Phishing Email
- Instead of using a public sample, I used a phishing email I previously created during another internship using **Gophish**.
- The email pretended to report “suspicious activity” and urged the recipient to click a link to “verify login”.

### 🔹 Step 2: Analyzed the Email for Phishing Signs
- **Inspected sender address**: `cybercrime.analysts1930@gmail.com` – clearly not a legitimate government or organization domain.
- **Noted generic and urgent language**: No personalized greeting; used scare tactics like “Urgent: Account Suspicious Activity Detected”.
- **Identified link manipulation**: Clicking the link redirected to a fake login page designed to capture credentials.

### 🔹 Step 3: Examined the Email Header
- Used **Google Admin Toolbox - Messageheader Analyzer** to inspect technical metadata.
- Although the email **passed SPF, DKIM, and DMARC**, it was sent using Gophish and originated from Gmail – confirming it was simulated but structured like real-world phishing attempts.

### 🔹 Step 4: Created a Detailed Report
- Summarized all phishing indicators and observations in a professional Word report.
- Highlighted social engineering tactics, suspicious sender details, and header analysis.

---

## 📂 Contents
### ▶️  [`Documents/`](./Documents/)

- `Task 2- Phishing Email Analysis Report.docx` – Detailed written report with findings and screenshots.
- `task2 header_analysis.png` – Screenshot of the header analysis result from Google Toolbox.

---

## 🔧 Tools Used

- 📧 Gmail (to inspect and open the email)
- 🔍 [Google Admin Toolbox – Message Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)
- 🧪 Gophish (used during previous internship to simulate the phishing email)

---

## 🛡️ Key Learnings

- Even emails with valid SPF/DKIM/DMARC can be dangerous if crafted with malicious intent.
- Phishing often relies more on **social engineering** than on technical bypassing.
- Always verify sender authenticity, avoid clicking unknown links, and inspect headers when in doubt.

---

## 📫 Contact

Feel free to reach out or raise an issue if you'd like to collaborate or need help analyzing suspicious emails.

