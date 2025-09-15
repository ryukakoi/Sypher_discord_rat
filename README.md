# Educational Discord RAT

**⚠️ WARNING & DISCLAIMER**
> This software is provided for **EDUCATIONAL PURPOSES ONLY**. It is intended for use in controlled, ethical environments to study cybersecurity principles, penetration testing, and defensive techniques.
>
> **Unauthorized use** of this tool on systems you do not own or have explicit permission to test is **ILLEGAL** and **UNETHICAL**. The developer assumes **no liability** for any misuse or damage caused by this software. You are solely responsible for ensuring your actions comply with applicable laws.

---

## 📖 Overview

This is a proof-of-concept Remote Administration Tool (RAT) that uses Discord's API for communication. It is designed to demonstrate how seemingly benign applications can be leveraged for command and control (C2) operations. This project is intended for cybersecurity education, helping students and professionals understand attack vectors to better defend against them.

## 🚀 Features (For Educational Analysis)

```
'!help - This list\n'
'!screenshot - Grab desktop pic\n'
'!webcam - Snap webcam photo\n'
'!shell <cmd> - Run system command\n'
'!info - Victim details (incl. IP)\n'
'!openfile <path> - Open file on victim PC\n'
'!download <path> - Download file from victim\n'
'!listdir [dir] - List directory contents (default current)\n'
'!message <text> - Show message box on victim\n'
'!shutdown - Shut down victim PC\n'
'!restart - Restart victim PC\n'
'!execute <url> - Download and run exe from url\n'
'!lock - Lock victim screen\n'
'!clipboard - Get clipboard content\n'
'!setclipboard <text> - Set clipboard content\n'
'!kill <process> - Kill process by name\n'
'!sound <url> - Play audio from url\n'
'!wallpaper <url> - Set desktop wallpaper from url\n'
'!volume <0-100> - Set system volume\n'
'!processes - List running processes\n'
'!beep <freq> <duration> - Play system beep\n'
'!checkboot - Check persistence status\n'
'!ping - Check if RAT is online'
```

## 🛠️ Installation & Setup

1. Run setup.bat
2. Enter bot and guild id
3. compile or run 


## 🔬 How to Use for Learning

1.  **Study the Code:** Analyze how the client communicates with the C2 server.
2.  **Monitor Network Traffic:** Use tools like Wireshark to observe the traffic it generates. Can you detect it?
3.  **Practice Defense:** Use this tool in a virtual lab to test:
    *   Antivirus/EDR detection rates.
    *   Network monitoring and intrusion detection systems (IDS).
    *   Forensic analysis and incident response procedures.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details. By using this software, you agree to the terms stated in the disclaimer above.
