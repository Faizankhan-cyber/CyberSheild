# 🛡️ CyberShield

### AI-Powered Digital Fraud & Phishing Detection Platform

> **CyberShield helps users detect phishing, fraud, malicious links, and digital scams by combining explainable security rules with AI-assisted analysis.**

[![Live Demo](https://img.shields.io/badge/Live-Demo-00C853?style=for-the-badge)](https://cybersheild01.netlify.app/)
[![Built With](https://img.shields.io/badge/Built%20With-AI%20%2B%20Cybersecurity-6C63FF?style=for-the-badge)](#)
[![Hackathon](https://img.shields.io/badge/Hackathon-PH--03-FF6B35?style=for-the-badge)](#)

---

## 🚨 Problem

Digital services have made everyday life easier, but they have also created new opportunities for cybercriminals.

Users regularly encounter:

* Phishing emails
* Fake SMS messages
* Malicious URLs
* Bank impersonation
* KYC scams
* UPI and payment scams
* Fake job offers
* Prize and reward scams
* Social engineering attacks
* Suspicious QR codes
* Fraudulent messages and websites

The biggest problem is that many users cannot easily understand **why** something is suspicious.

A simple warning such as:

> "This link may be dangerous."

doesn't tell the user what they should look for or what they should do next.

---

# 💡 Our Solution

**CyberShield** is an AI-assisted digital safety platform designed to help users identify potential phishing and digital fraud.

Instead of only producing a binary:

> Safe / Unsafe

CyberShield provides an **explainable risk assessment**.

The platform analyzes available signals, calculates a risk score, identifies potential scam categories, explains the warning signs in simple language, and provides recommended safe actions.

### Core flow

```text
          User Input
              │
      ┌───────┼────────┐
      ↓       ↓        ↓
    Email   Message    URL
      │       │        │
      └───────┼────────┘
              ↓
      Security Analysis
              ↓
       Detection Engine
              ↓
       Risk Score 0–100
              ↓
       Threat Category
              ↓
       Explainable Result
              ↓
        Safe Action Guide
```

---

# ✨ Key Features

## 🔗 1. URL Threat Analysis

CyberShield analyzes suspicious URLs for potential risk indicators such as:

* Suspicious domain patterns
* Unusual URL structures
* Suspicious keywords
* Potential impersonation indicators
* URL obfuscation
* Suspicious redirects where applicable
* HTTP/HTTPS security signals
* Other URL-based indicators

The system combines multiple signals rather than treating a single indicator as proof of malicious activity.

---

## 📧 2. Email Analysis

Users can submit suspicious emails for analysis.

CyberShield looks for common phishing indicators including:

* Urgency
* Threatening language
* Requests for sensitive information
* Suspicious links
* Impersonation patterns
* Payment requests
* Credential requests
* Social-engineering techniques

The result explains **why the message may be suspicious**.

---

## 💬 3. Message & SMS Scam Detection

CyberShield can analyze suspicious messages and identify common fraud patterns.

Examples include:

* Account suspension scams
* OTP scams
* KYC scams
* Fake rewards
* Payment requests
* Delivery scams
* Job scams
* Bank impersonation

---

## 🤖 4. AI-Assisted Threat Explanation

AI is used as an **explanation and assistance layer**, not as the only security decision-maker.

The system can transform technical detection signals into simple explanations such as:

> "This message creates urgency by threatening account suspension and asks for sensitive information. These are common indicators of phishing."

This makes CyberShield useful for people who may not have cybersecurity knowledge.

---

## 🎯 5. Risk Scoring

Every analysis produces a risk score from:

```text
0 ─────────────────────────────── 100
LOW          MEDIUM       HIGH     CRITICAL
```

The score is based on detected indicators and their severity.

### Example

```text
Risk Score: 87/100

Risk Level: HIGH

Detected:
• Urgency
• Credential request
• Suspicious URL
• Possible impersonation
```

The score is intended as a decision-support signal and **not a guarantee that content is malicious or safe**.

---

# 🇮🇳 Indian Digital Scam Awareness

CyberShield is designed with common digital fraud patterns relevant to Indian users in mind.

Examples include:

### UPI Scams

* Fake payment requests
* UPI PIN requests
* QR payment scams
* Fake refunds

### KYC Scams

* Fake KYC expiration messages
* Account-blocking threats
* Fake verification links

### Banking Scams

* Fake bank security alerts
* Account suspension threats
* Credential harvesting

### Other Common Scams

* Fake job offers
* Fake delivery messages
* Lottery and prize scams
* Investment scams
* Customer-support impersonation

---

# 🛡️ Safe Action Recommendations

CyberShield doesn't stop at detection.

When a threat is identified, the platform provides practical recommendations.

For example:

### If a phishing message is detected:

1. Do not click the suspicious link.
2. Do not reply to the sender.
3. Do not share passwords or OTPs.
4. Verify the request through the organization's official website or application.
5. Report the suspicious message.
6. If financial information has been compromised, contact the relevant financial institution immediately.

This turns CyberShield from a simple detector into a **digital safety assistant**.

---

# 🧠 Explainable Security

One of the main design goals of CyberShield is **explainability**.

Instead of simply saying:

```text
❌ PHISHING DETECTED
```

the platform attempts to answer:

```text
WHY?

⚠️ Urgent language
⚠️ Sensitive information requested
⚠️ Suspicious link
⚠️ Possible impersonation

WHAT SHOULD I DO?

🛡️ Do not click the link
🛡️ Do not share credentials
🛡️ Verify through an official channel
```

This helps users learn how scams work while protecting themselves.

---

# 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       USER          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   CyberShield UI    │
                    │  Web Application    │
                    └──────────┬──────────┘
                               │
             ┌─────────────────┼─────────────────┐
             ▼                 ▼                 ▼
        Email Input       Message Input      URL Input
             │                 │                 │
             └─────────────────┼─────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Detection Engine    │
                    │                     │
                    │ • Pattern Analysis  │
                    │ • URL Analysis      │
                    │ • Scam Signals      │
                    │ • Risk Calculation  │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   AI Explanation    │
                    │       Layer         │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Risk Engine      │
                    │                     │
                    │ Score + Category    │
                    │ + Evidence          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  User Safety Guide  │
                    └─────────────────────┘
```

---

# 🔐 Security & Privacy

CyberShield follows a security-first design approach.

### Principles

* API keys should never be exposed in frontend code.
* Sensitive credentials should never be entered into the scanner.
* The system should avoid unnecessary storage of sensitive information.
* Suspicious URLs should not automatically be opened.
* AI should not be treated as an unquestionable security authority.
* External threat intelligence should be clearly separated from local analysis.
* Detection results should be presented as assessments rather than absolute truth.

### ⚠️ Important

CyberShield is a security assistance tool.

**Never enter real passwords, OTPs, PINs, card numbers, authentication tokens, or other highly sensitive information into the scanner.**

---

# 🧪 Example Detection

### Suspicious Email

```text
Subject: URGENT - Your Bank Account Will Be Suspended

Your account will be suspended within 24 hours.

Click the link below to verify your account.

You must provide your password and OTP.
```

### CyberShield

```text
🔴 HIGH RISK

Risk Score: 90/100

Threat Type:
Credential Phishing

Warning Signs:
• Urgency
• Account suspension threat
• Password request
• OTP request
• Suspicious verification link

Recommended Action:
Do not click the link or provide any credentials.
Verify the message through the bank's official application.
```

---

# 🧪 Demo Mode

CyberShield can be demonstrated using controlled examples such as:

* Safe email
* Bank phishing email
* Fake KYC message
* UPI scam
* Fake prize message
* Suspicious URL
* Job scam
* Delivery scam

All demonstration data should be fictional and must not contain real credentials or financial information.

---

# 🛠️ Technology

The project uses a modern web-based architecture with AI-assisted security analysis.

### Frontend

* React
* TypeScript
* HTML
* CSS
* Modern responsive UI

### Security Analysis

* Rule-based threat detection
* URL analysis
* Pattern recognition
* Risk scoring
* Explainable security signals

### AI

* AI-assisted threat explanation
* Natural-language security summaries
* Human-readable recommendations

### Deployment

* Netlify

---

# 📁 Project Structure

A simplified structure:

```text
CyberShield/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── ...
│   │
│   ├── lib/
│   │   ├── analyzeThreat.ts
│   │   ├── history.ts
│   │   └── ...
│   │
│   ├── pages/
│   │   ├── ...
│   │
│   ├── App.tsx
│   ├── index.css
│   └── ...
│
├── package.json
├── package-lock.json
├── tsconfig.json
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

## 2. Enter the project

```bash
cd CyberShield
```

## 3. Install dependencies

```bash
npm install
```

## 4. Start the development server

```bash
npm run dev
```

The application will then be available through the local development URL shown by Vite.

---

# ⚙️ Environment Variables

If AI or external services are configured, create a `.env` file using the project's `.env.example`.

Example:

```env
VITE_AI_API_KEY=your_api_key_here
```

### Never commit real API keys.

Add `.env` to `.gitignore`.

---

# 📊 Risk Classification

CyberShield uses a risk-based model rather than a simple binary classification.

| Risk        | Meaning                                           |
| ----------- | ------------------------------------------------- |
| 🟢 LOW      | Few suspicious indicators detected                |
| 🟡 MEDIUM   | Some potentially suspicious indicators            |
| 🟠 HIGH     | Multiple strong warning signs                     |
| 🔴 CRITICAL | Strong evidence of a potentially dangerous threat |

These classifications are **risk assessments**, not guarantees.

---

# 🎯 Why CyberShield?

Most users don't need another complicated cybersecurity dashboard.

They need to know:

> **"Is this dangerous?"**

and more importantly:

> **"Why is it dangerous, and what should I do?"**

CyberShield focuses on those two questions.

### Our approach

```text
Detect
  ↓
Explain
  ↓
Educate
  ↓
Protect
```

---

# 🏆 Hackathon Problem Statement

**PH-03 | CyberShield – Digital Fraud & Phishing Detection**

### Theme

* Cybersecurity
* Artificial Intelligence
* Digital Safety

### Challenge

Develop an intelligent solution that can identify potential digital fraud or phishing attempts and help users understand and respond to such threats safely.

### CyberShield's Approach

CyberShield addresses the challenge through:

* Explainable threat detection
* AI-assisted analysis
* Risk scoring
* Scam classification
* URL analysis
* Digital safety recommendations
* User education

---

# 🔮 Future Improvements

Possible future development includes:

* Browser extension with real-time website warnings
* Advanced QR-code analysis
* Screenshot/OCR analysis
* Phone-number reputation checking
* Real-time threat-intelligence integrations
* Email header analysis
* Domain-age and WHOIS intelligence
* Multi-language scam detection
* WhatsApp/SMS integrations
* Mobile application
* Enterprise security dashboard
* SOC integration
* Continuous threat intelligence updates
* Improved machine-learning models trained on verified datasets

---

# ⚠️ Limitations

CyberShield should not be treated as a replacement for:

* Antivirus software
* Endpoint protection
* Security operations teams
* Bank fraud systems
* Professional cybersecurity investigation

A legitimate message may sometimes contain suspicious characteristics, and sophisticated attacks may evade detection.

CyberShield therefore presents its output as a **risk assessment and safety recommendation**, not absolute proof.

---

# 👥 Team

### Team CyberShield

**Project:** CyberShield – AI Digital Fraud & Phishing Detection

**Problem Statement:** PH-03

**Domain:** Cybersecurity + Artificial Intelligence + Digital Safety

---

# 📌 Project Status

**Status:** Hackathon Prototype 🚀

CyberShield is being developed as a working prototype demonstrating how AI and explainable security analysis can help everyday users identify and respond safely to potential digital fraud.

---

# 🌐 Live Demo

**CyberShield:**
https://cybersheild01.netlify.app/

---

# 📄 License

This project is created for educational and hackathon purposes.

If this project is released publicly, add the appropriate open-source license here.

---

## 🛡️ CyberShield

### Detect. Explain. Protect.

> **Don't just tell users that something is dangerous. Teach them why.**
