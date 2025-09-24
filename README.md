# FUTURE-INTERNS-TASK_3
A lightweight, secure, and user-friendly web application for encrypted file sharing, built with Flask and Fernet cryptography. Designed with ethical UX principles and modular architecture to ensure confidentiality, integrity, and ease of use.

📦 Features
- 🔑 End-to-End Encryption using Fernet (symmetric cryptography)
- 🧩 Modular Flask backend for clean architecture
- 📁 Secure file upload, encryption, and download
- 🖥️ Simple, intuitive web interface
- 🧠 Ethical design: no key storage, full user control
  
🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript (or React if used)
Backend: Python (Flask/Django) / Node.js / Java (choose based on your implementation)
Database: MySQL / PostgreSQL / MongoDB
Security: AES/RSA encryption, HTTPS, JWT Authentication

🚀 Getting Started

Prerequisites

pip install flask cryptography

Run Locally

python app.py

🔐 Encryption Workflow
- Upload: User selects a file.
- Encrypt: File is encrypted using a generated Fernet key.
- Download: Encrypted file is downloadable; user must retain the key to decrypt
- Upload interface: “Select file for encryption”
- Key display: “Fernet key shown once—save securely”
- Download interface: “Enter key to decrypt and download”
  
📄 Documentation
- Encryption Logic: See utils/encryptor.py
- Key Management: Keys are generated per session and never stored
- Security Notes: Users are responsible for retaining their keys
  
✅ Best Practices
- Use HTTPS in production
- Do not store encryption keys server-side
- Consider adding user authentication for access control
  
🔮 Future Enhancements
- User login and key vault
- Cloud storage integration (e.g., AWS S3)
- Admin dashboard for usage analytics
- Mobile-friendly UI
  
🧠Ethical Considerations
- No hidden data collection
- Full transparency in encryption workflow
- User retains control over their files and key













