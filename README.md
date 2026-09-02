# EssayQuiz Anekdot 📝📚

A web-based essay assessment platform designed for Indonesian language learning, focusing on **Teks Anekdot** exercises and analysis.

The application allows students to enter their personal information, analyze an illustrated anecdote, and submit answers to a series of essay questions digitally.

## ✨ Features

* 📝 Essay-based assessment
* 📚 Teks Anekdot learning exercise
* 👨‍🎓 Student information form
* 🔢 Attendance number validation
* 🏫 Class information
* 🖼️ Anecdote illustration
* ✍️ Multiple essay questions
* ☁️ Online answer submission
* ⚠️ Input validation
* 📱 Responsive web interface
* 🔔 Submission status notification

## 🎯 Project Overview

**EssayQuiz Anekdot** is a web-based educational assessment application designed to digitize the process of collecting students' answers for Indonesian language exercises.

Students can enter their identity, observe the provided illustration, answer the questions, and submit their responses through the website.

## 📖 Learning Topic

The application focuses on **Teks Anekdot**, a form of Indonesian text that commonly contains humorous or entertaining elements while conveying criticism, commentary, or a particular message.

Students are asked to analyze an illustrated anecdote and identify several important elements of the text.

## 📝 Assessment Questions

The assessment contains questions related to:

1. **Topic** — Identifying the topic presented in the illustration.
2. **Criticism** — Identifying the subject or material of criticism.
3. **Humor** — Identifying the humorous or comedic element.
4. **Structure** — Identifying the structure of the anecdotal text.

The structure question covers:

* Abstrak
* Orientasi
* Krisis
* Reaksi
* Koda

## 🔄 Assessment Workflow

```text
Student
   │
   ▼
Open EssayQuiz Anekdot
   │
   ▼
Enter Student Information
   │
   ├── Full Name
   ├── Attendance Number
   └── Class
   │
   ▼
View Anecdote Illustration
   │
   ▼
Analyze the Illustration
   │
   ▼
Answer Essay Questions
   │
   ├── Topic
   ├── Criticism
   ├── Humor
   └── Text Structure
   │
   ▼
Submit Answers
   │
   ▼
Google Apps Script
   │
   ▼
Answer Data Collection
```

## 🔐 Input Validation

The application provides client-side validation for the student's attendance number.

Validation includes:

* Attendance number cannot be empty
* Attendance number must be numeric
* Attendance number must be a positive number

An error message is displayed when an invalid attendance number is entered.

## ☁️ Answer Submission

Student answers are submitted through a **Google Apps Script Web App** endpoint configured in the HTML form.

JavaScript uses `FormData` and `fetch()` to send the student's information and essay answers.

```text
HTML Form
    │
    ▼
JavaScript Validation
    │
    ▼
FormData
    │
    ▼
Google Apps Script
    │
    ▼
Answer Data
```

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* Google Apps Script
* Google Sheets / Google Workspace integration

## 📂 Project Structure

```text
EssayQuiz-Anekdot/
│
├── index.html
├── Anekdot.png
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AnantaR07/EssayQuiz-Anekdot.git
cd EssayQuiz-Anekdot
```

### 2. Run the Project

This is a static HTML project and can be opened directly in a web browser.

For development, you can also use **Live Server** in Visual Studio Code.

### 3. Configure Google Apps Script

The application uses a Google Apps Script Web App to receive submitted answers.

To configure your own endpoint:

1. Create a Google Apps Script project.
2. Configure the script to receive form data.
3. Deploy the project as a Web App.
4. Copy the deployment URL.
5. Replace the existing `action` URL in the HTML form.

Example:

```html
<form
  action="YOUR_GOOGLE_APPS_SCRIPT_URL"
  method="post"
>
```

## 🎓 Educational Purpose

This project demonstrates how web technologies can be used to create simple digital learning and assessment tools.

The application can be adapted for:

* Indonesian language exercises
* Essay assessments
* Classroom assignments
* Text analysis exercises
* Image-based questions
* Digital worksheets
* Student answer collection

## 🔮 Future Improvements

Possible improvements include:

* 👨‍🏫 Teacher/admin dashboard
* 📊 Assessment statistics
* 📋 Student answer history
* 📝 Multiple question sets
* 🔐 Teacher authentication
* 💯 Teacher scoring system
* 📈 Student performance reports
* 📄 PDF report generation
* ⏱️ Quiz timer
* 🗂️ Multiple classes
* 📚 Additional Indonesian language topics
* 🔔 Submission notifications

## 📌 Project Status

**Completed — Educational Web Development Project**

## 👨‍💻 Author

**Ananta Romadhan**

Junior Full Stack Developer | IoT Engineer

GitHub: https://github.com/AnantaR07

````

## Topics GitHub

```text
html
css
javascript
education
educational-technology
edtech
online-quiz
essay-quiz
essay-assessment
online-assessment
indonesian-language
anekdot
teks-anekdot
language-learning
student-assessment
google-apps-script
````

## Hasil rename

| Bagian     | Lama           | Baru                                             |
| ---------- | -------------- | ------------------------------------------------ |
| Repository | `quiz-essay-1` | **`EssayQuiz-Anekdot`**                          |
| Materi     | Teks Anekdot   | **Teks Anekdot**                                 |
| Jenis      | Essay          | **Essay Assessment**                             |
| Platform   | HTML           | **HTML + CSS + JavaScript + Google Apps Script** |

Kalau kamu punya **`quiz-essay-3`**, sebaiknya nanti kita buat penamaan yang sama juga, misalnya `EssayQuiz-[Materi]`, supaya semua project pendidikanmu terlihat **rapi dan konsisten di GitHub portfolio**.
