
# C99 Shell Script

> **Disclaimer**: This script is intended **strictly for educational and authorized security testing purposes**. Unauthorized usage may violate laws and result in serious consequences. Use only in environments where you have explicit permission.

## 📌 About

This is a **C99 PHP web shell**, commonly used in ethical hacking labs and security research to demonstrate vulnerabilities in misconfigured web servers. It provides a powerful interface for interacting with the file system, executing commands, and performing basic administrative tasks via the web.

---

## ⚠️ Legal Notice

**Never use this script on unauthorized systems.**  
By using this code, you agree that you are solely responsible for any consequences.

---

## 🚀 Features

- File manager: Upload, rename, delete, move, and edit files
- Command execution via web interface
- Server and PHP configuration display
- MySQL interface (if supported)
- Mass deface options (for testing only)
- Password protection (optional)

---

## 🛠️ Usage

1. Upload `c99.php` to a PHP-enabled web server.
2. Navigate to the script in your browser:
   ```
   http://yourdomain.com/c99.php
   ```
3. If password protected, enter the required credentials.

> 💡 **Tip**: For realistic lab environments, rename the file to a less conspicuous name (e.g., `media.php`, `load.php`, etc.).

---

## 🔐 Security Suggestions

If you're using this in a honeypot or lab:
- Rename the script frequently.
- Enable `.htaccess` rules or firewall restrictions.
- Use it in isolated environments like Docker or virtual machines.
- Monitor and log access for research purposes.

---

## 📁 Directory Structure

```
c99-shell/
├── c99.php         # Main shell script
├── README.md       # This file
```

---

## 📚 References

- https://owasp.org
- https://github.com/tennc/webshell
- https://www.exploit-db.com

---

## 🤝 Contribution

This script is maintained for **security research and education only**. If you wish to contribute improvements or educational examples, feel free to fork and submit a pull request.

---

## 📄 License

Distributed under the MIT License. See the [LICENSE](LICENSE) file for more information.
