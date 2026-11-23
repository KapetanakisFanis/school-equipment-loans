<div align="center">

[🇬🇷 Ελληνικά](README.md) · 🇬🇧 **English**

# 📦 School Equipment Loans

**A simple app for keeping track of the equipment a school lends to its teachers.**
No installation, no accounts, no server. Runs in any web browser.

[**▶ Open the app**](https://ΟΝΟΜΑ-ΧΡΗΣΤΗ.github.io/ΟΝΟΜΑ-REPOSITORY/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![No server](https://img.shields.io/badge/server-not%20needed-2f6b3f?style=flat-square)
![Data](https://img.shields.io/badge/data-local%20only-b45309?style=flat-square)
![No dependencies](https://img.shields.io/badge/dependencies-none-1d5a87?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-1d5a87?style=flat-square)

</div>

---

## ✨ Features

| | |
|---|---|
| **Log a loan** | First name, last name, equipment, quantity, date, pick-up time, return date and time (multi-day loans supported) |
| **Pending returns** | Records without a return time are marked “Pending”, with a “Return” button that fills in the current date and time |
| **Search and filters** | Find records by teacher, equipment or note, and show only pending or returned loans |
| **Edit and delete** | Correct or remove any record |
| **Export to Excel** | UTF-8 CSV file that opens directly in Excel |
| **Print** | Clean, printable list |
| **Backup** | Save all records to a file and restore them later |
| **Two languages** | Greek and English, with an ΕΛ / EN switch. Your choice is remembered |

## 🚀 How to use it

### Option 1: Online (GitHub Pages)
Open the app link from any computer or phone. Nothing else is needed.

### Option 2: Locally, without internet
1. Click **Code → Download ZIP** on this page.
2. Unzip the file.
3. Double-click `index.html` to open it in Chrome, Edge or Firefox.

## 🔒 Personal data (GDPR)

- Data is **stored only in the browser** of the computer you are using. It is never sent to a server and is never uploaded to GitHub.
- No external services, tracking cookies or analytics are used.
- Only the teacher's name is recorded, which is the minimum needed.
- To erase a teacher's data, simply delete their records.

> ⚠️ **Important:** Never commit backup files (`.json`) or exports (`.csv`) containing real names to the repository. The included `.gitignore` excludes them automatically.

## 💾 Good to know

- **Each computer and browser keeps its own list.** Records are not shared automatically between computers.
- To move data to another computer: **Backup** on the first one, then **Import** on the second.
- Clearing the browser's browsing data deletes the records. Make regular backups and keep them in a safe, encrypted place.

## 🛠️ Customizing it

The whole app is a single file, `index.html` (HTML, CSS and JavaScript, no libraries). You can change fields, colors or texts with any text editor. All texts for both languages are collected in the `T` object at the start of the JavaScript code, so adding another language means adding one more block there. Suggestions are welcome as an *Issue* or a *Pull Request*.

## 📜 License

Released as open-source software under the [MIT License](LICENSE). You are free to use, modify and share it, as long as you keep the copyright notice.

© 2026 Fanourios Kapetanakis

## 📄 Compliance note

The app is provided as an organizational tool. Before using it in a school, consult your Data Protection Officer (DPO) and record the processing in your school's Record of Processing Activities, as required by the GDPR.
