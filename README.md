# U.S. Citizenship Civics Practice Quiz (2025 Revised Test)

## PROOF OF CONCEPT
This quiz is just a simple proof of concept and should not be used for studying or taking the 2005 U.S. Citizenship test. 

I created it in response to Washington Post article: Can you pass the new U.S. citizenship test? 
By Daniel Wu
October 23, 2025 at 6:30 a.m. EDT

## 🌟 Live Demo
This quiz is hosted for free on GitHub Pages:
**[View the Live Quiz Here](https://ramtackett.github.io/USciitizenShipQuiz/)**


---

## 📝 Project Overview

This is a simple, client-side, interactive multiple-choice quiz based on the **10 questions** featured in a Washington Post article previewing the 2025 revised U.S. Citizenship and Immigration Services (USCIS) civics test.

The project is built entirely using **HTML, CSS, and vanilla JavaScript** and requires **no backend server** or external dependencies, making it easy to host anywhere.

### Key Features
* **Self-Contained:** Everything is in a single `index.html` file.
* **Instant Feedback:** Shows correct/incorrect answers immediately upon submission.
* **Simple Scoring:** Calculates and displays the final score.
* **Mobile-Friendly:** Designed to work well on any screen size.

---

## 🛠️ Technology Stack

* **HTML5:** Structure and content.
* **CSS3:** Styling and layout.
* **Vanilla JavaScript (ES6):** Quiz logic, question management, and DOM manipulation.

---

## 🚀 Hosting and Setup

Since this is a fully contained front-end application, the easiest way to host it is using **GitHub Pages**.

### 1. Repository Setup (Bash/Terminal)

Assuming you have `git` installed and your project folder (`citizenship-quiz`) is ready:

```bash
# Initialize Git in your local folder
git init

# Add the main quiz file
git add index.html

# Commit the changes (using your private GitHub noreply email)
git commit -m "Initial commit of the complete civics quiz"

# Add the remote link (use your SSH URL for better security/convenience)
git remote set-url origin git@github.com:YOUR_USERNAME/citizenship-quiz.git

# Push the code to the 'main' branch on GitHub
git push --set-upstream origin main
