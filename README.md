# FUTURE_CS_02
# Phishing Email Detection & Awareness System

## 📌 Overview
This project focuses on phishing email detection and cybersecurity awareness as part of the Cyber Security Internship at Future Interns.

The objective was to analyze suspicious email samples, identify phishing indicators, classify threats, and provide practical security awareness guidelines to help users recognize and avoid phishing attacks.

---

## 🎯 Objectives
- Analyze phishing email samples
- Identify common phishing indicators
- Classify emails based on risk level
- Explain phishing techniques in simple terms
- Provide awareness and prevention guidelines

---

## 🛠️ Tools Used
- Manual Email Analysis
- Browser DevTools
- Encryptomatic Email Viewer

---

## 📂 Project Scope
The project involved:
- Inspecting sender domains
- Reviewing email authentication headers
- Identifying malicious links
- Detecting social engineering techniques
- Classifying emails as:
  - SAFE
  - SUSPICIOUS
  - PHISHING

---

## 📧 Email Samples Analyzed

### Sample 1 — Credential Phishing
| Parameter | Details |
|---|---|
| Subject | Unusual sign.in activity |
| Sender | no-reply@access-accsecurity.com |
| Classification | PHISHING |

#### Indicators Detected
- Fake sender domain
- Fear-based language
- Missing SPF
- Missing DKIM
- DMARC misconfiguration

---

### Sample 2 — Legitimate Email
| Parameter | Details |
|---|---|
| Subject | Your Amazon Order #2847562 has shipped |
| Sender | shipment@amazon.com |
| Classification | SAFE |

#### Analysis
- SPF passed
- DKIM passed
- DMARC passed
- Legitimate sender behavior observed

---

### Sample 3 — Suspicious Promotional Email
| Parameter | Details |
|---|---|
| Subject | You have won a $1000 Gift Card! |
| Sender | rewards@promo-offers-win.net |
| Classification | SUSPICIOUS |

#### Indicators Detected
- Suspicious domain
- “Too good to be true” offer
- Urgency tactics
- Malicious-looking link
- No personalized recipient name

---

## 🚩 Common Phishing Indicators
The following warning signs were identified during analysis:
- Fake or misspelled domains
- Urgent or threatening language
- Suspicious hyperlinks
- Missing SPF/DKIM/DMARC
- Requests for credentials
- Financial reward scams
- Lack of personalization

---

## 🛡️ Phishing Awareness Guidelines

### Golden Rules
- STOP before clicking links
- CHECK sender domains carefully
- THINK before responding
- VERIFY requests independently
- REPORT suspicious emails immediately

### Best Practices
- Enable Two-Factor Authentication (2FA)
- Never share passwords via email
- Hover over links before clicking
- Access websites directly through browsers
- Report suspicious messages to IT/security teams

---

## 📊 Classification Summary
| Classification | Count |
|---|---|
| PHISHING | 1 |
| SAFE | 1 |
| SUSPICIOUS | 1 |

---

## 📁 Repository Structure
```bash
├── report/
│   └── PHISHING_EMAIL_DETECTION.pdf
├── screenshots/
├── README.md
