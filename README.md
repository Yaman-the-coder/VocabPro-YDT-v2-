<div align="center">
  <img src="icon.ico" width="80" alt="VocabPro YDT Icon" onerror="this.src='https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unsorted_dictionary.svg/1200px-Unsorted_dictionary.svg.png'; this.width=80;" />
  <h1>VocabPro YDT <small>v2</small></h1>
  <p><strong>Interactive gamified platform for vocabulary language learning exams.</strong></p>
  
  <br>
  
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Web_Audio_API-8A2BE2.svg?style=for-the-badge&logo=w3c&logoColor=white" alt="Web Audio" />
</div>

---


<img width="1827" height="917" alt="image" src="https://github.com/user-attachments/assets/5d01ff89-6884-4c34-8cab-609dfea2de2b" />



---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/book-open.svg" width="24" height="24" align="center" /> Overview
This web application called VocabPro YDT is built with plain Vanilla JavaScript and intended to enable users to build strong English vocabulary for YDT. Withflashcards, various gameified quiz options, sound feedbackand even local persistent learning tracking, it offers a lively user interface.

---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/sparkles.svg" width="24" height="24" align="center" /> Key Features

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/library.svg" width="20" height="20" align="center" /> Interactive Flashcards</h3>
      Flashcard-like cards for definition, meaning in Turkish, example usage, and part of speech. You can click to "Know / Don't Know" for learning statistics and see in which order should learn them.
    </td>
    <td width="50%" valign="top">
      <h3><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/gamepad-2.svg" width="20" height="20" align="center" /> Advanced Quiz Engine</h3>
      Test your knowledge through multiple dynamic modes: <strong>True/False</strong>, <strong>Multiple Choice</strong>, <strong>Fill-in-the-blanks</strong>, and a custom <strong>Matching Game</strong>.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/volume-2.svg" width="20" height="20" align="center" /> Procedural Audio Feedback</h3>
      Utilizes the native <code>AudioContext</code> API to generate pure oscillator waveforms (sine for correct, sawtooth for incorrect) for instant, gamified auditory feedback without external audio files.
    </td>
    <td width="50%" valign="top">
      <h3><img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/trending-up.svg" width="20" height="20" align="center" /> Progress Tracking</h3>
      Uses <code>localStorage</code> to persistently save learned words, calculate completion percentages, and track average quiz scores across sessions.
    </td>
  </tr>
</table>

---

### <img src="https://cdn.jsdelivr.net/npm/lucide-static/icons/folder-tree.svg" width="24" height="24" align="center" /> Project Structure

Based on the repository layout, the project is organized as follows:

```text
YDT/
├── assets/             # Images, fonts, and static assets
├── css/
│   └── main.css        # Main stylesheet (Tailwind utilities & custom animations)
├── data/
│   └── vocabulary.json # Core dataset containing word definitions and levels
├── docs/               # Project documentation
├── js/
│   └── app.js          # Core application logic, quiz engine, and audio generation
├── scripts/            # Helper scripts for deployment or building
├── icon.ico            # Application favicon
├── index.html          # Main application entry point
├── setup.sh            # Environment setup script
├── start.bat           # Windows startup script
└── start.sh            # Unix/Linux startup script
```
<br>
<hr>
<p align="center">
  <small>Made with 🤍 by <a href="https://github.com/yamanist0">yamanist</a></small>
</p>
