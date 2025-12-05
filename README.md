# Quiz App (JavaScript)

Interactive JavaScript quiz app with timer, scoring and instant feedback.

**Live demo:** https://quizappjsc.netlify.app/

---

## Overview
This is a lightweight, responsive quiz application built with plain HTML, CSS and JavaScript. It features a per-question timer, progress bar, immediate correct/wrong feedback, and a results screen.

---

## Features
- 10-question quiz powered by a `questions` array
- 15-second timer per question with visual countdown
- Progress bar that fills while time runs
- Immediate feedback with tick/cross icons
- Score summary at the end and option to replay or quit
- Clean, mobile-friendly UI

---

## Tech stack
- HTML5
- CSS3
- Vanilla JavaScript

---

## Installation / Run locally
1. Clone the repo  
   ```bash
   git clone https://github.com/kirtisharma1111/Quiz-App.git
   cd "Quiz-App"
Open index.html in your browser or serve the folder with a simple dev server:

bash
Copy code
# using Python 3
python -m http.server 5500
# then open http://localhost:5500 in your browser
Project structure
pgsql
Copy code
.
├─ index.html
├─ style.css
├─ script.js
├─ question.js
└─ README.md
Customize questions
Edit question.js where the questions array is defined. Each question object uses this format:

js
Copy code
{
  numb: 1,
  question: "Question text",
  options: ["A", "B", "C", "D"],
  answer: "Correct option text"
}
Make sure answer exactly matches one of the strings in options.

Contributing
Contributions are welcome — open an issue or submit a pull request.

License
This project is open source — feel free to reuse the code. Add a license file if you want to set a specific license (MIT, GPL, etc.).

Live demo: https://quizappjsc.netlify.app/

yaml
Copy code

---

# Quick Git commands to add this README and push
Run these inside your repo folder:

```bash
# create README.md (if you haven't already pasted it)
# then:
git add README.md
git commit -m "Add README with project overview and live demo link"
git push
