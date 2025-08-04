# Cybersecurity Lab - Exploitation Training Environment
## OS-command-injuction

Welcome to **Cybersecurity Lab 01**, a self-contained virtual environment built for learning and practicing exploitation techniques in a real-world simulated setting.

---

## 📦 Lab Details

- **Lab Name:** Cybersecurity Lab 01
- **File Type:** VirtualBox OVA (Open Virtual Appliance)
- **Download Link:** [Download Lab_01.ova](https://www.mediafire.com/file/c9snqlfjc2ccwbd/Lab_01.ova/file)
- **OS:** CentOS 8
- **Services Running:** 
  - Web server on **port 80**
- **Frontend:** React (Vite)
- **Backend:** Node.js
- **Difficulty:** Beginner to Intermediate
- **Purpose:** Train learners in system/web exploitation and privilege escalation techniques.
- **Goal:** Gain **root privileges** and **capture the flag** on a protected endpoint.
- **Note:** This is **not a traditional CTF**. It is an open lab for exploration and learning.

---

## 🧪 Lab Features

- Realistic exploitation environment
- Web application vulnerabilities
- System misconfigurations
- Privilege escalation challenges
- Root-level flag accessible via a protected route

---

## 🚀 Getting Started

1. **Download and Import OVA:**
   - Use [VirtualBox](https://www.virtualbox.org/) to import the `.ova` file.
   - Go to **File > Import Appliance** and select `Lab_01.ova`.

2. **Start the VM:**
   - Once imported, boot the VM.
   - The lab will auto-start all required services.

3. **Access the Web Interface:**
   - Open your browser and navigate to `http://<VM-IP>:80`
   - You can find the IP using: `netdiscover`.

---

## 🏴 Objective

The main objective is to **gain root access** by:
1. Finding and exploiting a vulnerability on the web interface.
2. Pivoting through the system using misconfigurations or weaknesses.
3. Locating and accessing the root-only flag file (typically in `/root/` or hidden behind a privileged route).

---

## ⚠️ Legal & Ethical Notice

This lab is intended for **educational purposes only**. Do **not** use the skills learned here on unauthorized systems. Always follow **responsible disclosure** and ethical hacking guidelines.

---

## 🛠️ Troubleshooting

- Make sure your network adapter is set to **Bridged** or **NAT Network** to access the web server.
- Ensure port 80 is open and not blocked by host firewall.
- Use developer tools or tools like **Burp Suite**, **Nmap**, **Netcat**, etc. for deeper exploration.

---

## 🧠 Recommendations

- Use tools such as:
  - Burp Suite
  - Nmap
  - Nikto
  - Gobuster
  - John the Ripper
  - LinPEAS / LinEnum / polkit (for privilege escalation)

---

## ✍️ Feedback

If you find any bugs, suggestions, or want to contribute, feel free to reach out.

Happy Hacking!
