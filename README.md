# 📧 Spam Email Classifier

## 📌 Project Overview

The **Spam Email Classifier** is a web-based application developed using **HTML, CSS, and JavaScript**. It helps users identify whether an email is likely to be **Spam**, **Suspicious**, or **Safe** by analyzing the email content for commonly used spam keywords.

This project demonstrates the use of front-end web technologies and basic text analysis techniques to classify email messages without requiring a server or database.

---

## 🎯 Objectives

* Detect potential spam emails using keyword matching.
* Provide a simple and user-friendly interface.
* Display the spam probability percentage.
* Classify emails as **Safe**, **Suspicious**, or **Spam**.

---

## 🛠 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)

---

## ✨ Features

* Modern and responsive user interface.
* Paste any email content into the text area.
* Detects common spam-related keywords.
* Calculates an estimated spam probability.
* Displays one of the following results:

  * ✅ Safe Email
  * ⚠️ Suspicious Email
  * 🚫 Spam Email
* Runs entirely in the browser.
* No internet connection or installation required.

---

## 📂 Project Structure

```
Spam-Email-Classifier/
│
├── index.html
├── README.md
└── assets (optional)
```

---

## 🚀 How to Run

1. Download or clone the project.
2. Open the project folder.
3. Double-click **index.html** or open it in any modern web browser.
4. Paste an email message into the text box.
5. Click the **Check Email** button.
6. View the spam classification and spam probability.

---

## 🧠 Working Principle

1. The user enters an email message.
2. JavaScript converts the text to lowercase.
3. The application compares the email with a predefined list of spam keywords.
4. Based on the number of matched keywords, a spam probability is calculated.
5. The email is classified as:

   * **Safe Email** – Low spam probability.
   * **Suspicious Email** – Medium spam probability.
   * **Spam Email** – High spam probability.

---

## 📌 Advantages

* Easy to understand and use.
* Fast processing.
* No backend required.
* Lightweight and portable.
* Suitable for educational purposes.

---

## ⚠️ Limitations

* Uses keyword matching instead of Machine Learning.
* May produce false positives or false negatives.
* Cannot detect advanced phishing or sophisticated spam emails.

---

## 🔮 Future Enhancements

* Integrate Machine Learning for higher accuracy.
* Upload and scan email files.
* Real-time spam detection.
* Maintain a scan history.
* Add dark mode.
* Improve the spam detection algorithm using Natural Language Processing (NLP).

---

## 📸 Sample Output

**Input:**

```
Congratulations!

You have won ₹50,000 cash.
Click here to claim your free prize now.
```

**Output:**

```
Spam Probability: 85%

🚫 Spam Email
```

---

## 👨‍💻 Author

**Hari Krishnan N**

---

## 📄 License

This project is developed for educational and learning purposes.
