# 🛡️ TrustLens
### Detect • Explain • Verify • Act Safely

**Your digital safety companion for a smarter, safer internet.**

TrustLens is a digital safety platform designed to help users identify potentially suspicious messages, URLs, and screenshots. It analyzes content, highlights warning signs, explains potential risks, and provides practical safety guidance to help users make informed decisions online.

---

## ✨ Why TrustLens?

In today's digital world, suspicious messages, misleading links, and online scams can put personal information and digital security at risk. TrustLens aims to make digital safety easier to understand and accessible to everyone.

**Our mission:** Help people recognize potential online threats, understand why they may be risky, and take safer actions.

## 🚀 Key Features

🔍 **Message Analysis**  
Analyze text messages to identify potentially suspicious language, scam patterns, and warning signs.

🔗 **URL Safety Analysis**  
Examine URLs for suspicious characteristics that may indicate potential online risks.

🖼️ **Screenshot Analysis with OCR**  
Extract text from uploaded screenshots and analyze the extracted content for potential warning signs.

📊 **Risk Assessment**  
Present a risk score or risk level based on the implemented analysis rules.

💡 **Clear Risk Explanations**  
Help users understand which patterns triggered a warning and why they deserve attention.

🛡️ **Actionable Safety Guidance**  
Provide practical next steps to help users verify information and avoid risky actions.

---

## 🔄 How It Works

**01 — Submit**  
Enter a suspicious message, provide a URL, or upload a screenshot.

**02 — Analyze**  
TrustLens examines the submitted content using its implemented analysis methods.

**03 — Understand**  
Review the risk assessment and the warning signs identified.

**04 — Act Safely**  
Follow the suggested precautions and verify suspicious requests through trusted, official channels.

---

## 🧰 Technology Stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite |
| Backend | Python, FastAPI |
| Database | SQLite |
| Screenshot Text Extraction | OCR |

---

## 📁 Project Structure

```text
TRUSTLENS-main/
├── src/              # Frontend application
├── backend/          # FastAPI backend
├── package.json      # Frontend dependencies
├── .gitignore        # Files excluded from Git
└── README.md         # Project documentation
```

*Additional files and folders may be present in the project.*

---

## ⚙️ Getting Started

### Prerequisites

Install the following tools:

- Git
- Node.js and npm
- Python 3
- pip

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/TrustLens.git
cd TrustLens
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Set Up the Backend

```bash
cd backend
python -m venv .venv
```

Activate the environment in Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Start the backend using the correct FastAPI application entry point configured in the project.

### 3. Set Up the Frontend

Open a second terminal in the project root and run:

```bash
npm install
npm run dev
```

Open the local development URL displayed in the terminal.

> **Note:** Verify the project's actual backend entry point and required configuration before running it. Screenshot OCR may require additional dependencies.

---

## 🎯 Project Goals

- Make digital safety easier for everyday internet users.
- Help users recognize suspicious content and understand potential risks.
- Encourage safer online habits and independent verification.
- Provide clear, accessible safety guidance through a simple interface.

## 🔮 Future Enhancements

Potential improvements include enhanced OCR for blurry screenshots, expanded analysis rules, stronger validation, improved error handling, and broader automated testing.

## 🔐 Security & Privacy

- Never commit passwords, API keys, authentication tokens, or private user data.
- Keep local databases and backups out of the public repository unless they contain deliberately prepared, safe sample data.
- Verify sensitive requests independently through official sources.

## ⚠️ Disclaimer

TrustLens is an informational digital safety tool. Its assessments may be imperfect and should not be treated as definitive proof that content is safe or malicious. Always verify suspicious links, financial requests, and account-related messages through official channels.

---

## 🤝 Contributing

Ideas, suggestions, and constructive feedback are welcome. When reporting an issue, provide reproducible steps and relevant error messages without sharing sensitive information.

---

### 🛡️ TrustLens
**Detect • Explain • Verify • Act Safely**

*Building awareness. Encouraging verification. Promoting safer digital experiences.*
