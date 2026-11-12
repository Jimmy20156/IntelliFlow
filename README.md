# IntelliFlow — IEEE Smart Formatter

IntelliFlow turns your capstone manuscript (PDF) into a two-column **IEEE conference paper**:
- live preview
- validation checks
- an IEEE structure guide
- PDF export

## 🌐 Use it online

<!-- online-link -->

**[Open IntelliFlow online](https://jimmy20156.github.io/IntelliFlow/)**: nothing to install; sign in with your @csucc.edu.ph Google account.

<!-- /online-link -->

This link never changes: it always opens the current IntelliFlow server. Bookmark it.

## ⬇ Download

**Latest version: 1.1.0**

**[Download IntelliFlow-Setup.exe](https://github.com/Jimmy20156/IntelliFlow/releases/download/v1.0.5/IntelliFlow-Setup.exe)**. If the installer is from an earlier version, IntelliFlow updates itself to 1.1.0 the first time you open it while online.

Older versions and release notes are on the [Releases page](https://github.com/Jimmy20156/IntelliFlow/releases).

## Requirements
- Windows 10 or 11 (64-bit)
- About 6 GB of free disk space
- No Docker, Python or LaTeX needed: everything is included.
- Internet is optional. You need it only for AI assist, sending emails and updates.

## Install
1. Run **IntelliFlow-Setup.exe**.
   - If Windows SmartScreen says *"Windows protected your PC"*, click **More info → Run anyway**. The installer isn't code-signed.
2. Click through the installer. There is nothing to fill in: no account is created during installation.
3. On the last page, leave **Launch IntelliFlow now** checked and click **Finish**.
4. Your browser opens. The first start takes up to a minute. Click **Continue with Google** and use your **@csucc.edu.ph** school account. New here? It creates your account and emails you a code to confirm it.
5. Go to the **Dashboard** and upload your capstone PDF.

To open IntelliFlow later, use the **IntelliFlow** shortcut on the desktop or in the Start menu. It runs in the background: look for the IntelliFlow icon near the clock. Right-click it and choose **Quit** to stop it.

## Updates
IntelliFlow checks for updates each time you open it. When a new version is out, a blue **"IntelliFlow x.y.z is available"** bar also shows at the top of the app.

To update, use one of these. Your accounts and manuscripts are always kept.
- **Usual case:** close IntelliFlow (the IntelliFlow icon near the clock → **Quit IntelliFlow**) and open it again while online. It updates by itself in a few seconds.
- **If the bar or the start page says "Download the new installer":** download it and run it over the old version.
- **Any time:** download the latest **IntelliFlow-Setup.exe** above and install it over the old version.

## Your data
Your accounts, manuscripts and settings are stored in `%LOCALAPPDATA%\IntelliFlow`. Uninstalling asks whether to keep this folder.

- **Settings:** to send real emails, open the `.env` file in that folder and fill in the `EMAIL_*` lines. Then restart IntelliFlow.
- **Logs:** if something goes wrong, the log is at `logs\intelliflow.log` in the same folder.
