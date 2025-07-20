🛡️ Burp Suite Professional – NYD-SEC Edition
<p align="center"> <a href="#"><img src="https://madewithlove.org.in/badge.svg" alt="Made with Love"></a> <a href="https://buymeacoffee.com/cyb3rzest"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-donate-red" alt="Donate"></a> <a href="https://twitter.com/cyb3rzest"><img src="https://img.shields.io/badge/Twitter-%40CyberZeast-blue.svg" alt="Twitter"></a> <a href="https://github.com/cyb3rzest/Vasuki/issues"><img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg" alt="Contributions welcome"></a> <a href="#"><img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg" alt="Bash"></a> <a href="https://github.com/cyb3rzest?tab=followers"><img src="https://img.shields.io/badge/GitHub-%40cyb3rzest-red" alt="GitHub"></a> </p>
👊 NYD-SEC Presents: Burp Suite Pro Installer

This repo gives you a clean, ready-to-deploy method to install and activate Burp Suite Professional on Windows and Linux (Kali/Ubuntu/Parrot). No fluff, just the juice.
🪟 Windows Installation Steps

    Prep Folder

        Copy everything into: C:\Burp

        Create the folder manually if needed.

    Set PowerShell Policy

Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process

Run the Setup

./Windows_Setup.ps1

Change Shortcut Icon

    Right-click Burp-Suite-Pro.vbs → Make Shortcut.

    Go to Shortcut tab → Click Change Icon.

    Select burp-suite.ico from C:\Burp.

icon

Add to Start Menu

    Move Burp-Suite-Pro.vbs to:

        C:\ProgramData\Microsoft\Windows\Start Menu\Programs\

🐧 Kali Linux Installation Steps

Run the installer script as root:

sudo bash Kali_Linux_Setup.sh

🔐 Burp Suite Pro Activation

    Modify license string:
    Example: license to NYD-SEC

    Run loader.jar (Key Generator)

    In Burp:

        Paste the License Key.

        Click Next.

    Select Manual Activation

    Copy License Request → Paste into the Keygen

    Copy License Response from Keygen → Paste back into Burp

    Click Next, then you're done.

🎬 Video Guide

    Windows Setup
    Windows

    Linux Setup
    Linux

🚀 Launch Burp Suite Pro

    Windows
    Use the Start Menu or your new desktop shortcut.

    Kali Linux
    Just run:

    burpsuite

🔧 Contribute to NYD-SEC

💬 Got a better way to install? Found a bug? Wanna flex some script-fu?
Pull requests and issues are welcome — we’re building something solid together.

Let me know if you want a dark theme version, terminal-styled markdown, or even Amharic localization. I gotchu.
