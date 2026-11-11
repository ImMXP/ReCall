<div align="center">

# 🧠 ReCall

**A Windows app for studying smarter with spaced repetition and the forgetting curve.**
<br>
مراجعات ذكية بالتباعد الزمني

![Version](https://img.shields.io/badge/version-1.0.0-6366f1?style=for-the-badge)
![Platform](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Offline](https://img.shields.io/badge/works-offline-22c55e?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/license-MIT-f59e0b?style=for-the-badge)](LICENSE)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="recall-logo-animated.gif">
  <img src="recall-logo-animated.gif" alt="ReCall Logo" width="512">
</picture>

</div>

---

## ✨ Features

- **Forgetting curve:** see how much you still remember of each subject, and which one to review first.
- **AI-made quizzes:** copy a ready prompt, send it with your lecture to any AI, then drag the JSON file it gives you into a subject.
- **Flashcards and multiple choice:** two quiz modes, plus a "review my mistakes" round.
- **Neural map of subjects:** unlimited nested sub-topics, connected with animated memory threads.
- **Your layout:** long-press to move subjects anywhere, and pick a background (code, aurora, dots, grid, or your own image).
- **Dark and light themes** with a full Arabic (RTL) interface.
- **Private by default:** everything stays on your device, with no account and no server.

## 📥 Download

Get the latest installer from the [**Releases**](../../releases/latest) page and run `ReCall-Setup-1.0.0.exe`.

> [!NOTE]
> The installer isn't code-signed yet. If Windows shows *"Windows protected your PC"*, click **More info → Run anyway**.

## 💾 Where is my data?

Everything is saved in a local SQLite database on your PC:

```
%APPDATA%\ReCall\recall.db
```

Use the **File** menu to back it up or restore it. Uninstalling ReCall keeps your data.

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">
<br>

Made with ❤️ for anyone who'd rather remember than re-read.

</div>
