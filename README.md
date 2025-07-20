🛡️ Burp Suite Professional – NYD-SEC Edition
<p align="center"> <a href="https://www.tiktok.com/@officialnayad"><img src="https://img.shields.io/badge/TikTok-@officialnayad-black?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok"></a> <a href="https://www.instagram.com/official__nayad"><img src="https://img.shields.io/badge/Instagram-@official__nayad-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a> <a href="https://github.com/NAYAD-12"><img src="https://img.shields.io/badge/GitHub-NAYAD--12-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/nayad-tadesse?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app"><img src="https://img.shields.io/badge/LinkedIn-Nayad%20Tadesse-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> </p>
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
