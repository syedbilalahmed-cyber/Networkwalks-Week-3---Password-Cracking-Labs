<h1 align="center">🛡️ NETWORKWALKS — WEEK 03</h1>

<h2 align="center">🔐 PASSWORD CRACKING & PASSWORD SECURITY LABS</h2>

<p align="center">
  <strong>John the Ripper • Johnny • Hash Analysis • Networkwalks Tools • AI-Assisted Security Exploration</strong>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Cybersecurity-0F172A?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Cybersecurity" />

  <img src="https://img.shields.io/badge/Password%20Cracking-DC2626?style=for-the-badge&logo=keycdn&logoColor=white" alt="Password Cracking" />

  <img src="https://img.shields.io/badge/John%20the%20Ripper-2563EB?style=for-the-badge" alt="John the Ripper" />

<img src="https://img.shields.io/badge/NETWORKWALKS-2563EB?style=for-the-badge&logoColor=white" alt="Networkwalks"/>

<img src="https://img.shields.io/badge/WEEK-03-7C3AED?style=for-the-badge" alt="Week 03"/>

<img src="https://img.shields.io/badge/PASSWORD_SECURITY-0F766E?style=for-the-badge" alt="Password Security"/>

<img src="https://img.shields.io/badge/JOHN_THE_RIPPER-DC2626?style=for-the-badge" alt="John the Ripper"/>

<img src="https://img.shields.io/badge/JOHNNY-475569?style=for-the-badge" alt="Johnny"/>

<img src="https://img.shields.io/badge/HASH_ANALYSIS-0891B2?style=for-the-badge" alt="Hash Analysis"/>

<img src="https://img.shields.io/badge/STATUS-COMPLETED-16A34A?style=for-the-badge" alt="Completed"/>

</p>

<p align="center">
  <strong>W3-PS-FINAL | CYBERSECURITY | ETHICAL HACKING | NETWORKWALKS</strong>
</p>

---

# 👤 PROJECT INFORMATION

| Field | Details |
|---|---|
| 👨‍💻 **Developer / Student** | **Syed Bilal Ahmed** |
| 🎓 **Program** | Cybersecurity & Ethical Hacking |
| 🏢 **Organization** | Networkwalks |
| 🧑‍🏫 **Mentor** | Waqas Karim (CCIE) |
| 📚 **Batch** | B082 |
| 📅 **Week** | Week 03 |
| 🔐 **Primary Focus** | Password Cracking & Password Security |
| 🧪 **Environment** | Authorized Educational Laboratory |
| 📊 **Project Status** | Completed |

---

# 🛡️ Week 3 Cybersecurity Projects

## Password Cracking, Networkwalks Tools & AI Security Lab

This repository contains my **Week 3 Cybersecurity & Ethical Hacking
project work**, completed as part of my practical cybersecurity training.

The repository includes two required password-security projects and one
optional AI-based security lab using **Claude Desktop and HexStrike MCP**.

---

## 📌 Projects Completed

| Project | Title | Status |
|---|---|---|
| W3-PM1 | Password Cracking with John the Ripper | ✅ Completed |
| W3-PM2 | Password Cracking with Networkwalks Tools | ✅ Completed |
| W3-OPTIONAL1 | AI/JTR Password Cracking with Claude & HexStrike MCP | ✅ Completed |

---

# 🔐 Project 1 — Password Cracking with JTR

## 📖 Overview

This project demonstrates password recovery using **John the Ripper (JTR)**
and **Johnny GUI** in a controlled cybersecurity lab environment.

The objective was to recover the password of a protected PDF by extracting
its password hash and processing the hash with John the Ripper.

John the Ripper supports multiple password hash formats and can be used by
security professionals to test password strength. Johnny provides a graphical
interface for easier interaction with JTR.

---

## 🛠️ Tools Used

- John the Ripper (JTR)
- Johnny GUI
- Windows
- PDF Hash Extraction
- Notepad
- Protected PDF

---

## 🔎 Project Workflow

1. Install John the Ripper.
2. Install and configure Johnny GUI.
3. Locate and configure `john.exe`.
4. Obtain the protected PDF used for the lab.
5. Extract the PDF password hash.
6. Save the hash into `hash1.txt`.
7. Open the hash file using Johnny.
8. Start a password recovery attack.
9. Wait for the password recovery process to complete.
10. Use the recovered password to open the protected PDF.

The lab documentation describes the JTR and Johnny workflow, including
installation, configuration, hash extraction, password recovery, and PDF
verification. 

---

## 🧪 My Results

### JTR Installation

![JTR Installation](screenshots/project-1/jtr-installation.png)

### Johnny Configuration

![Johnny Configuration](screenshots/project-1/johnny-configuration.png)

### PDF Hash Extraction

![PDF Hash](screenshots/project-1/pdf-hash.png)

### Hash File

![Hash File](screenshots/project-1/hash-file.png)

### Password Recovery

![Password Recovery](screenshots/project-1/password-recovery.png)

### Final PDF Verification

![PDF Verification](screenshots/project-1/pdf-verification.png)

---

# 🔓 Project 2 — Password Cracking with Networkwalks Tools

## 📖 Overview

This project demonstrates password recovery using the **Networkwalks Hash
Calculator** and **Networkwalks Password Cracker**.

Unlike the first project, these tools run directly in a web browser and do not
require a local password-cracking application.

The lab workflow extracts the hash from a protected PDF and then uses the
Networkwalks Password Cracker to perform a dictionary-based password recovery
process.

---

## 🛠️ Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser
- Windows
- Protected PDF

---

## 🔎 Project Workflow

1. Obtain the encrypted PDF used for the lab.
2. Open the Networkwalks Hash Calculator.
3. Upload the protected PDF.
4. Extract the PDF hash beginning with `$pdf$`.
5. Copy the complete hash value.
6. Open the Networkwalks Password Cracker.
7. Paste the extracted hash.
8. Start the password-cracking process.
9. Wait for the tool to identify a matching password.
10. Use the recovered password to open the protected PDF.

The official lab describes the Hash Calculator and Password Cracker workflow,
including extracting the `$pdf$` hash and starting the password recovery
process. 

---

## 🧪 My Results

### Hash Calculator

![Hash Calculator](screenshots/project-2/hash-calculator.png)

### Extracted PDF Hash

![Extracted Hash](screenshots/project-2/extracted-hash.png)

### Password Cracker

![Password Cracker](screenshots/project-2/password-cracker.png)

### Cracking Process

![Cracking Process](screenshots/project-2/cracking-process.png)

### Recovered Password

![Recovered Password](screenshots/project-2/recovered-password.png)

### PDF Verification

![PDF Verification](screenshots/project-2/pdf-verification.png)

---

# 🤖 Optional Project — AI Security Lab

## Claude Desktop + HexStrike MCP

### 📖 Overview

This optional project demonstrates the setup of an AI-assisted cybersecurity
lab using **Claude Desktop and HexStrike MCP on Kali Linux**.

The lab environment uses a Kali Linux virtual machine with Claude Desktop
and the HexStrike-AI MCP server. :contentReference[oaicite:1]{index=1}

---

## 🛠️ Technologies Used

- Kali Linux
- Claude Desktop
- HexStrike MCP
- Python
- Git
- GitHub
- MCP

---

## 🔎 Project Workflow

1. Install Claude Desktop on Kali Linux.
2. Add the Claude Desktop GPG key.
3. Add the package repository.
4. Update the package list and install Claude Desktop.
5. Sign in to Claude Desktop.
6. Clone the HexStrike-AI repository.
7. Create and activate a Python virtual environment.
8. Install the required Python dependencies.
9. Start the HexStrike MCP server.
10. Configure the MCP server in Claude Desktop.
11. Verify that the server is running.

---

## 1️⃣ Install Claude Desktop on Kali Linux

The Claude Desktop Debian repository is used to install Claude Desktop on
Kali Linux.

GitHub repository and detailed instructions:

https://github.com/aaddrick/claude-desktop-debian

### Add the GPG Key

```bash
curl -fsSL https://pkg.claude-desktop-debian.dev/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/claude-desktop.gpg

```
### Add the Repository
```bash
echo "deb [signed-by=/usr/share/keyrings/claude-desktop.gpg arch=amd64,arm64] https://pkg.claude-desktop-debian.dev stable main" | sudo tee /etc/apt/sources.list.d/claude-desktop.list

```
### Update and Install
```bash
sudo apt update
sudo apt install claude-desktop
```
### 2️⃣ Sign in to Claude Desktop

After installation, open Claude Desktop and complete the sign-in process.
### 📸 Result


### 3️⃣ Clone HexStrike-AI

Clone the HexStrike-AI repository:
```bash
git clone https://github.com/0x4m4/hexstrike-ai.git
cd hexstrike-ai
```
📸 Result

### 4️⃣ Create Python Virtual Environment
```bash
python3 -m venv hexstrike-env
source hexstrike-env/bin/activate
```
📸 Result

### 5️⃣ Install Dependencies
```bash




