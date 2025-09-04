# AAGNI - AI Powered Personal Assistant

AAGNI is an AI-powered personal assistant built using Python.  
It combines speech recognition, natural language processing (NLP), and real-time data retrieval to deliver a smart, interactive, and customizable desktop assistant.  
The system supports both voice and text commands, providing features like news updates, weather reports, file management, and task automation.

---

## 🚀 Features
- 🎤 **Speech Recognition & Text-to-Speech** – Hands-free interaction using voice commands.  
- 🤖 **AI Query Handling** – Intelligent responses powered by GPT models.  
- 🌦️ **Real-Time Data Retrieval** – News and weather updates via APIs.  
- 💻 **Desktop Automation** – Open files, manage tasks, and control applications.  
- 🖥️ **GUI Support** – User-friendly interface built with Tkinter/PyQt.  
- 🔒 **Privacy & Offline Support** – Local processing for selected tasks.  

---

## 🛠️ Tech Stack
- **Programming Language:** Python 3.x  
- **Libraries & Frameworks:**  
  - `speechrecognition` (Speech-to-Text)  
  - `pyttsx3` (Text-to-Speech)  
  - `requests`, `BeautifulSoup` (API & Web Scraping)  
  - `tkinter` / `PyQt` (GUI Development)  
- **APIs Used:**  
  - OpenAI API (AI-driven responses)  
  - NewsAPI (News Updates)  
  - OpenWeather API (Weather Forecasts)  

---

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AAGNI-AI-Assistant.git
   cd AAGNI-AI-Assistant
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

pip install -r requirements.txt

OPENAI_API_KEY=your_key_here
NEWS_API_KEY=your_key_here
WEATHER_API_KEY=your_key_here

python main.py

📌 Future Scope

- IoT integration for smart devices
- Multilingual support
- Emotion recognition for personalized responses
- Mobile app version (Android/iOS)

📜 License
This project is licensed under the MIT License
