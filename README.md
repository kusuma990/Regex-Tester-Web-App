# Regex-Tester-Web-App
# 🚀 Regex Tester Web App (Flask)

A simple and beginner-friendly web application built using Flask that allows users to test **Regular Expressions (Regex)** on a given input string and view all matching results — similar to a basic version of regex tools.

---

## 📌 Project Overview

This application allows users to:

* ✍️ Enter a test string
* 🔍 Enter a regular expression (regex pattern)
* ▶️ Click a button to find matches
* 📋 View all matched results instantly

---

## 🧠 How It Works (Simple Explanation)

1. User enters:

   * A text (example: `hello 123 world 456`)
   * A regex pattern (example: `\d+`)

2. The app processes the input using Python’s `re` module.

3. It finds all matches using:

   re.findall(pattern, text)

4. The results are displayed on the web page.

---

## ⚙️ Technologies Used

* Python 🐍
* Flask 🌐
* HTML (for frontend)

---

## 📁 Project Structure

RegexApp/
│
├── app.py
└── templates/
└── index.html

---

## 🛠️ Setup Instructions (Step-by-Step)

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/regex-tester.git

cd regex-tester

---

### 2️⃣ Install Dependencies

Make sure Python is installed, then run:

pip install flask

---

### 3️⃣ Run the Application

python app.py

You will see:

Running on http://127.0.0.1:5000/

---

### 4️⃣ Open in Browser

Go to:

http://127.0.0.1:5000/

---

## 🌐 How to Use

1. Enter any text in the **Text Area**
2. Enter a **Regex Pattern**
3. Click **Submit**
4. View the list of matches

---

## 🧪 Example Inputs

### Example 1

Text:
hello 123 world 456

Regex:
\d+

Output:

* 123
* 456

---

### Example 2

Regex:
[a-z]+

Output:

* hello
* world

---

## 📚 Key Concepts Used

* `Flask` → Web framework
* `HTML Forms` → Taking user input
* `POST Method` → Sending data to backend
* `re.findall()` → Finding all matches
* `Jinja2` → Displaying results dynamically

---

## ⚠️ Error Handling

* If the regex pattern is invalid, the app shows:

  Invalid Regular Expression

---

## 💡 Future Improvements

* Highlight matches in the text
* Show match positions (start, end index)
* Add regex flags (IGNORECASE, MULTILINE)
* Improve UI with CSS or Bootstrap
* Add live preview (without reload)

---

## 🙌 Author

Created by Kusuma Kumari Bodduluri
- 🔗 LinkedIn: www.linkedin.com/in/kusuma-kumari-bodduluri
- 💻 GitHub: https://github.com/kusuma990
- 🎓 Data Science Student

---

## ⭐ Support

If you found this project helpful:

* ⭐ Star this repository
* 🔁 Share with others
* 💡 Try adding new features

---

## 🎯 Conclusion

This project is a great starting point to learn:

* Flask basics
* Handling user input
* Regular expressions
* Building real-world tools

Happy Coding 🚀
