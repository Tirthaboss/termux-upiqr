## 🚀 Termux UPI QR Generator – `termux-upiqr`

![License](https://img.shields.io/github/license/Tirthaboss/termux-upiqr)
![Made for Termux](https://img.shields.io/badge/platform-Termux-blue?logo=termux)
![Python](https://img.shields.io/badge/language-Python-yellow?logo=python)
[![Install from GitHub](https://img.shields.io/badge/Install%20via-Termux%20pkg-brightgreen)](https://tirthaboss.github.io/termux-upiqr)
[![Demo Video](https://img.shields.io/badge/Watch-Demo%20Video-orange?logo=youtube)](https://github.com/Tirthaboss/termux-upiqr/assets/demo.mp4)

> A lightweight, blazing-fast Python-based UPI QR Generator and Email Sender — installable via `pkg install upiqr` on Termux.

---

### 🧠 Why I Built This

While experimenting with mobile-first automation and CLI-first utility tools, I realized the power of bringing financial tools like **UPI** directly into Termux — no app install needed.

This project reflects my passion for **Python**, **Linux CLI**, and **real-world problem solving** through **micro-automation**.

---

## ✨ Features

✅ **Generate UPI QR codes** instantly
✅ **Send via email** (automated Gmail SMTP integration)
✅ Fully **offline QR rendering in terminal**
✅ Built as a **Termux .deb package** (`pkg install upiqr`)
✅ Minimal dependencies, fast startup
✅ Built with clean code, proper UX, and real-world usage in mind

---

## 📆 Installation (via `.deb` package)

```bash
# Add custom source
echo "deb [trusted=yes] https://Tirthaboss.github.io/termux-upiqr ./"> $PREFIX/etc/apt/sources.list.d/upiqr.list

# Update and install
pkg update
pkg install upiqr

# Run
upiqr
```

---

## 🖼️ Screenshot

```
📱 Scan this QR Code with any UPI app
██████████████  ██    ████████████
██        ██  ██████  ██        ██
██  ████  ████    ██  ██  ████  ██
...
```

---

## 📀 Demo Video

[https://github.com/Tirthaboss/termux-upiqr/assets/demo.mp4](https://github.com/Tirthaboss/termux-upiqr/assets/demo.mp4) *(Demo QR Generation and Email Send)*

---

## ⚙️ Built With

* Python 3
* Termux/Linux Shell
* `qrcode`, `termcolor`, `pyfiglet`, `smtplib`
* Gmail SMTP App Password system
* .deb packaging via `dpkg-deb`

---

## 🔐 Security Notice

* This tool uses **Gmail App Password** (not your main password) for secure authentication.
* Passwords are never logged, stored, or transmitted anywhere outside your Gmail SMTP session.

---

## 👨‍💻 About Me

I'm **Souporno Chakraborty**, a passionate developer who loves creating powerful tools using **Python**, **Termux**, and **automation** to solve real-life needs.

💼 I specialize in:

* Python scripting & microservices
* Linux CLI tools and deb packaging
* Cross-platform automation (Termux, Android, desktop)
* RESTful APIs, AI integration, DevOps basics

---

## 💼 Hire Me

If you're an HR, CTO, or engineering manager looking for someone who:

* **Turns code into impact**
* Understands user experience even in CLI tools
* Builds for **efficiency**, **portability**, and **scale**

Feel free to explore my work and [connect with me on LinkedIn](https://linkedin.com/in/soupornochakraborty) or email me at **[soupornochakraborty40@gmail.com](mailto:soupornochakraborty40@gmail.com)**.

> I'm currently open to full-time or contract developer roles. Let's build something meaningful together!

---

## 📜 License

MIT License — Free to use, modify, and enhance.
