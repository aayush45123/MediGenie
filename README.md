# 🩺 MediGenie – AI Powered Medical Chatbot

**MediGenie** is an intelligent medical assistant that combines AI chatbot functionality with a complete doctor appointment system. It helps users get instant answers to health-related questions and book appointments with Somaiya doctors – all in one platform.

---

## 💡 Features

- 🤖 Chatbot powered by Google's Gemini API
- 📚 Predefined disease detection using Python dictionary
- 🩺 Book appointments with Somaiya doctors
- 👨‍⚕️ View doctors, their profiles, schedules
- 🎤 Audio input for health questions (Speech to Text)
- 🎙 Text-to-Speech replies from the bot
- 🖥 Fully responsive frontend UI in pure HTML, CSS, and JS
- 🧠 Fast, intelligent, and context-aware responses

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Python, Flask
- **AI Integration**: Gemini API (`google-generativeai`)
- **Database**: MySQL (for local appointment storage)
- **Other Tools**: Flask-CORS, pyttsx3, SpeechRecognition

---

## 🚀 How to Run Locally

### 🧬 Clone the Repository

```bash
git clone https://github.com/yourusername/MediGenie-AI-POWERED-MEDICAL-CHATBOT.git
cd MediGenie-AI-POWERED-MEDICAL-CHATBOT
```

### 📦 Install Dependencies

```bash
pip install flask flask_cors google-generativeai pyttsx3 SpeechRecognition mysql-connector-python
```

### 🔑 Add Gemini API Key

Edit `backend/responses.py` and replace:

```python
GEMINI_API_KEY = "your_api_key_here"
```

### ▶ Start the Flask App

```bash
cd backend
python app.py
```

Then open `http://localhost:5000` in your browser.

---

## 🗂 Folder Structure

```bash
MediGenie/
├── backend/
│   ├── app.py
│   ├── responses.py
│   └── temp_audio.wav
│
├── frontend/
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   ├── login/
│   ├── chatbot/
│   ├── doctor/
│   ├── doctors_lists/
│   ├── doctors_profile/
│   ├── doctorsImg/
│   ├── aboutus/
│   └── homepage/
│
└── README.md
```

---

## 📌 Important Notes

- This project is for **educational purposes only** and does not provide real medical advice.
- Gemini API is used for demo intelligence — not for diagnosis.
- Appointments are for simulated Somaiya doctor data.

---

## 📷 Screenshots

### 🩺 Chatbot Interface  
![Chatbot](images/Screenshot%202025-05-06%20120723.png)

### 👨‍⚕️ Doctor Booking Page  
![Doctor Booking](images/Screenshot%202025-05-06%20120756.png)

### 📅 Appointment Schedule  
![Schedule](images/Screenshot%202025-05-06%20120818.png)

### 🔒 Login Page  
![Login](images/Screenshot%202025-05-06%20120855.png)

### 🏠 Homepage Design  
![Homepage](images/Screenshot%202025-05-06%20120932.png)


---

## 🧑‍💻 Developer

**Aayush Bharda**  
Mini Project @ K.J. Somaiya Institute  
🔗 GitHub: [aayush45123](https://github.com/aayush45123)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
