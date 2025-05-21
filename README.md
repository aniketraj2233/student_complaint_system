# 🛠️ Complaint Management System

![GitHub repo size](https://img.shields.io/github/repo-size/sahutushar/Complaint-management)
![GitHub stars](https://img.shields.io/github/stars/sahutushar/Complaint-management?style=social)
![GitHub forks](https://img.shields.io/github/forks/sahutushar/Complaint-management?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/sahutushar/Complaint-management)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

🚀 A cloud-based complaint management system for educational institutions, designed to streamline issue reporting and resolution between students and the administration.

---

## 🌟 Features

- 🎓 **Student Dashboard** to file and track complaints
- 🛡️ **Admin Panel** to manage and resolve issues
- 📧 Email alerts for status updates
- ☁️ Azure Blob storage for file uploads
- 🔒 Secure login with session management

---

## 🖼️ Demo Preview

> *(Add demo screenshots or GIFs here)*

| Student Panel | Admin Panel |
|---------------|-------------|
| ![student](https://via.placeholder.com/300x200?text=Student+Panel) | ![admin](https://via.placeholder.com/300x200?text=Admin+Panel) |

---

## ⚙️ Tech Stack

| Category   | Technologies Used |
|------------|--------------------|
| 👨‍💻 Backend | Python, Flask |
| 🖼️ Frontend | HTML5, CSS3, Bootstrap |
| 🗃️ Database | Azure SQL |
| ☁️ Cloud | Azure Blob Storage |
| 📬 Email | SMTP, Flask-Mail |
| 🔐 Auth | Flask-Login, Sessions |

---

## 🚀 Getting Started

### 📦 Requirements
- Python 3.7+
- Azure Account for Storage & DB
- SMTP Email Credentials

### 🛠️ Installation Steps

```bash
git clone https://github.com/sahutushar/Complaint-management.git
cd Complaint-management
python -m venv venv
source venv/bin/activate     # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python app.py

