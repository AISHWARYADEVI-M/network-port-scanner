Here is the complete, simplified Markdown code block using `#` symbols for easy alignment and copy-pasting directly into your GitHub `README.md`.

```markdown
# Network Port Scanner GUI

A lightweight and efficient TCP Port Scanner with a Graphical User Interface (GUI) built using Python and Tkinter. This tool helps identify open ports and associated services on a target system, supporting basic network security analysis.

> This project was developed as part of the VOIS Edunet AICTE Cybersecurity Virtual Internship.

# Project Overview

The Network Port Scanner is designed to perform port scanning on a given target (IP/hostname) within a specified range. It uses socket programming and multithreading to efficiently detect open ports and display results in real time.

# Features

* ✅ Simple and user-friendly GUI
* ⚡ Multi-threaded scanning (up to 500 threads)
* 🔍 Detects open TCP ports
* 🏷️ Service identification for common ports
* 📊 Real-time progress bar and live results
* ⏱️ Elapsed time tracking
* ⛔ Stop scan anytime
* 💾 Save results to a .txt file
* 💻 Cross-platform (Windows, macOS, Linux)

# Technologies Used

* **Python** – Core programming language
* **Tkinter** – GUI development
* **Socket Programming** – TCP port scanning
* **Multithreading** – Fast scanning
* **Queue Module** – Thread-safe communication
* **ChatGPT** – Used for development guidance, debugging, and documentation

# Installation

```bash
git clone [https://github.com/techtrainer20/nmap_portscan_gui.git](https://github.com/techtrainer20/nmap_portscan_gui.git)
cd nmap_portscan_gui
```

# Usage

```bash
python portscanergui.py
```

### Steps:
1. Enter Target IP address or Hostname
2. Specify Start Port and End Port
3. Click **Start Scan**
4. View results in real time
5. Optionally click **Save Results**

# Example Output

```text
Target: 10.246.27.179
Range: 1-5000

[+] Port 53 (DNS) is open

Scan complete.
Open ports found: 1
```

# Common Port Services

| Port | Service | Port | Service |
| :--- | :--- | :--- | :--- |
| 21 | FTP | 110 | POP3 |
| 22 | SSH | 143 | IMAP |
| 23 | Telnet | 443 | HTTPS |
| 25 | SMTP | 3306 | MySQL |
| 53 | DNS | 3389 | RDP |
| 80 | HTTP | 8080 | HTTP-Alt |

# How It Works

* **Connection:** The scanner attempts to establish a TCP connection using `socket.connect_ex()`
* **Logic:** If the connection is successful (returns 0), the port is marked open
* **Mapping:** Open ports are mapped to known services using a predefined dictionary
* **Speed:** Multithreading handles multiple ports concurrently to save time
* **Display:** Results are pushed from the queue to the GUI in real time

# End Users

* 🔐 **SOC Analysts** – Monitor open ports and detect vulnerabilities
* 🛡️ **Network Administrators** – Ensure secure configurations
* 🧪 **Ethical Hackers** – Perform reconnaissance
* 🎓 **Students/Learners** – Understand networking and security basics

# Limitations

* Detects only TCP ports (no UDP scanning)
* Service detection is based on port mapping, not real service probing
* May not detect ports blocked by firewalls

# Future Enhancements

* 🔄 UDP port scanning
* 🧾 Banner grabbing (service version detection)
* 🎨 Improved UI/UX (CustomTkinter)
* 🧠 Advanced scanning techniques (like SYN scan)

# Disclaimer

This tool is intended for educational purposes only. Use it only on systems you own or have explicit permission to scan. Unauthorized scanning may be illegal.

# License

This project is released under the MIT License.

# Acknowledgment

Developed as part of the VOIS Edunet AICTE Cybersecurity Virtual Internship Program, with guidance from mentors and learning resources.
```

Would you like me to help you generate a `requirements.txt` file or a `.gitignore` file for this repository?
