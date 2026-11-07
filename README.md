# IntelliFlow — IEEE Smart Formatter

IntelliFlow turns your capstone manuscript (PDF) into a two-column **IEEE conference paper**:
- live preview
- validation checks
- an IEEE structure guide
- PDF export

## ⬇ Download

**[Download IntelliFlow-Setup.exe](https://github.com/Jimmy20156/IntelliFlow/releases/latest)** (coming soon)

Older versions and release notes are on the [Releases page](https://github.com/Jimmy20156/IntelliFlow/releases).

## Requirements
- Windows 10 or 11 (64-bit)
- About 6 GB of free disk space
- No Docker, Python or LaTeX needed: everything is included.
- Internet is optional. You need it only for AI assist, sending emails and updates.

## Install
1. Run **IntelliFlow-Setup.exe**.
   - If Windows SmartScreen says *"Windows protected your PC"*, click **More info → Run anyway**. The installer isn't code-signed.
2. Create the **administrator account** (username, email, password) when the installer asks.
3. On the last page, leave **Launch IntelliFlow now** checked and click **Finish**.
4. Your browser opens. The first start takes up to a minute. Then sign in with the account from step 2. The first time, IntelliFlow asks you to finish setting up the account.
5. Go to the **Dashboard** and upload your capstone PDF.

To open IntelliFlow later, use the **IntelliFlow** shortcut on the desktop or in the Start menu. It runs in the background: look for the IntelliFlow icon near the clock. Right-click it and choose **Quit** to stop it.

## Updates
IntelliFlow checks for updates each time you open it. Small updates install by themselves. When a big update needs a new installer, the start page shows a **Download the new installer** button. Installing over the old version keeps your accounts and manuscripts.

## Your data
Your accounts, manuscripts and settings are stored in `%LOCALAPPDATA%\IntelliFlow`. Uninstalling asks whether to keep this folder.

- **Settings:** to send real emails, open the `.env` file in that folder and fill in the `EMAIL_*` lines. Then restart IntelliFlow.
- **Logs:** if something goes wrong, the log is at `logs\intelliflow.log` in the same folder.
