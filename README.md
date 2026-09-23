# androidsecurity-researchLab

# darkandroidhack_backdoor

**DarkAndroidhack_bacdoor** is a hacking Python and Bash toolset that automates two things:

1. **APK Backdooring** — Injecting a Metasploit payload into any legitimate
   Android APK while preserving the original app's functionality and signature
   handling, using Apktool for decompilation/recompilation and smali patching.
2. **ADB Exploitation** — Leveraging exposed Android Debug Bridge (port 5555)
   to gain remote shell access to Android devices that have ADB over TCP/IP
   enabled without authentication.
# For questions, full hacking tool, issues, complete access or contributions:

Telegram: https://t.me/cyberhackgeek
Email: darkhackgeek@gmail.com

## Prerequisites / Knowledge Required

Users of this tool should have working knowledge of:

- Any Linux distribution (Kali Linux recommended)
- Bash scripting
- Metasploit Framework (msfvenom / msfconsole)
- Apktool
- Android SDK / build tools
- smali / baksmali
- Java (keytool for signing, jarsigner / apksigner)

## Requirements

Install dependencies:

```bash
sudo apt-get update
sudo apt-get install apktool openjdk-11-jdk aapt android-sdk-build-tools
gem install apksigner   # or use apksigner from build-tools
