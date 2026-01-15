# 🤖 AI-Powered “Ask-Anything” Telegram Bot

### Built with n8n + Google Gemini

This project is an **AI-driven Telegram chatbot** that allows users to **ask any question in natural language** and receive **instant, intelligent replies** using **Google Gemini**.

The entire system is built using **n8n workflow automation**, making it **low-code, scalable, and easy to extend**.

---

## 🧠 What Does “Ask-Anything” Mean?

Users do **not** need to follow fixed commands.

They can simply type questions like:

* “What is my attendance?”
* “Which doctor is available today?”
* “What is the company leave policy?”
* “Show student marks for semester 6”

The **AI Agent understands the question**, finds the relevant data, and responds in **human-like language**.

---

## 🔄 Complete Workflow Explanation (Step-by-Step)

1️⃣ **User sends a question on Telegram**

* Any normal language question (no commands)

2️⃣ **Telegram Trigger (n8n)**

* Instantly activates the automation workflow

3️⃣ **Data Source Access**

* Fetches relevant data from:

  * Google Sheets
  * Internal datasets
  * Predefined records

4️⃣ **JavaScript Code Node**

* Cleans, filters, and structures the data
* Prepares input for the AI model

5️⃣ **AI Agent (Google Gemini)**

* Understands user intent
* Generates a context-aware response
* Converts raw data into clear answers

6️⃣ **Response Delivery**

* AI reply is sent back to the user on Telegram
* Happens in real time

---

## 🛠️ Technology Stack

* **n8n** – Workflow automation
* **Telegram Bot API** – User interaction
* **Google Sheets** – Data storage
* **JavaScript** – Custom logic (Code nodes)
* **Google Gemini Chat Model** – AI responses
* **AI Agent** – Decision-making & orchestration

---

## 🎯 Real-World Applications (Detailed)

### 🎓 Education (Teachers & Students)

* Teachers can quickly find:

  * Attendance
  * Marks
  * Student records
* Students can ask:

  * Exam dates
  * Syllabus details
  * Notices
* Reduces paperwork and saves time

---

### 🏥 Healthcare (Hospitals & Clinics)

* Patients can ask:

  * Appointment status
  * Doctor availability
  * Report collection timings
* Staff can automate:

  * FAQs
  * Scheduling information
* Reduces front-desk workload

---

### 🏢 Companies & Corporate Offices

* Employees can ask:

  * Leave policies
  * Holiday lists
  * HR rules
* Acts as:

  * Internal company chatbot
  * HR support assistant
* Improves productivity and response time

---

### 🛍️ Business & Customer Support

* 24×7 automated customer query handling
* Product and service information
* Lead generation chatbot
* Reduces manual support costs

---

## 🌟 Why This Project Is Useful

* ✅ Users can **ask any question naturally**
* ✅ Saves time by automating repetitive queries
* ✅ Reduces manual effort in organizations
* ✅ Scalable across industries
* ✅ Built using low-code tools
* ✅ Easy to customize and extend

---

## 📚 What I Learned

* Designing AI Agents for real users
* Integrating LLMs into automation workflows
* Using no-code + low-code effectively
* Building production-ready AI systems

---

## 🚀 Future Improvements

* Add conversation memory
* Role-based access (Teacher / HR / Admin)
* Database integration
* Cloud deployment
* Analytics & logging

---

## 👨‍💻 Author

**Snehal Salve**
AI | ML | Data Science Enthusiast

---



