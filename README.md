# 💔 Breakup Recovery Agent Community

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit)
![Google Gemini](https://img.shields.io/badge/Google-Gemini%202.0%20Flash-4285F4?style=for-the-badge&logo=google)
![Agno](https://img.shields.io/badge/Agno-Multi--Agent-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

### 🧠 AI-powered emotional recovery assistant built with Streamlit, Agno & Gemini 2.0 Flash

*Helping users process breakups through empathetic AI agents, emotional guidance, and personalized recovery plans.*

</div>

---

# 📖 Overview

Breakups are emotionally challenging, and many people struggle to process their feelings alone.

**Breakup Recovery Agent Community** is an AI-powered multi-agent application that provides emotional support through specialized AI agents working together.

Instead of relying on a single chatbot, this application uses multiple intelligent agents, each with a unique responsibility, to deliver comprehensive emotional recovery support.

Users can:

- ❤️ Share their feelings
- 📷 Upload breakup chat screenshots
- 📝 Receive emotional closure messages
- 🧠 Get therapist-style guidance
- 📅 Receive personalized daily recovery routines
- 💥 Get brutally honest feedback
- 📊 View a final AI-generated recovery summary

---

# ✨ Features

## 🧠 Multi-Agent AI System

The application consists of specialized AI agents working collaboratively.

| Agent | Purpose |
|--------|----------|
| ❤️ Therapist Agent | Emotional support and coping strategies |
| ✉️ Closure Agent | Writes messages you should never send |
| 📅 Routine Planner Agent | Builds a personalized recovery routine |
| 💥 Brutal Honesty Agent | Gives direct, unbiased reality checks |
| 👑 Team Leader | Combines every response into one final recovery summary |

---

## 📷 Chat Screenshot Analysis

Upload screenshots of conversations.

The AI can:

- Understand emotional context
- Detect communication patterns
- Identify unhealthy relationships
- Suggest healthier perspectives

Supported formats:

- PNG
- JPG
- JPEG

---

## ⚡ Parallel Multi-Agent Execution

Unlike traditional chatbots, every agent processes the user's input simultaneously.

Benefits include:

- Faster responses
- Different emotional perspectives
- Better overall guidance

---

## 🔐 Secure API Key Management

Gemini API keys are stored safely using:

```python
st.session_state
```

No API keys are permanently stored.

---

# 🛠 Tech Stack

| Category | Technology |
|------------|-------------|
| Frontend | Streamlit |
| AI Framework | Agno |
| LLM | Gemini 2.0 Flash |
| Vision Model | Gemini Vision |
| Language | Python |
| Image Processing | Pillow (PIL) |
| Search Tools | DuckDuckGo |
| State Management | Streamlit Session State |

---

# 🏗 Project Architecture

```
                User

                  │

                  ▼

          Streamlit Interface

          ┌───────────────┐
          │ User Feelings │
          │ Screenshot    │
          └───────────────┘

                  │

                  ▼

          Multi-Agent Team

 ┌───────────────────────────────────────┐
 │ Therapist Agent                       │
 │ Closure Agent                         │
 │ Routine Planner Agent                 │
 │ Brutal Honesty Agent                  │
 └───────────────────────────────────────┘

                  │

                  ▼

          Team Leader Agent

                  │

                  ▼

        Final Recovery Summary
```

---

# 📂 Project Structure

```
Breakup-Recovery-Agent/

│
├── app.py
├── agents.py
├── utils.py
├── requirements.txt
├── README.md
├── assets/
│   ├── logo.png
│   ├── screenshots/
│   └── demo.gif
│
└── images/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/krish24coder/Breakup-Recovery-Agent.git
```

Move into the project

```bash
cd Breakup-Recovery-Agent
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# 🔑 Environment Variables

Provide your Gemini API key inside the Streamlit sidebar.

```
GEMINI_API_KEY=YOUR_API_KEY
```

Or create a `.env` file.

```
GEMINI_API_KEY=YOUR_API_KEY
```

---

# 💻 Usage

### Step 1

Enter your feelings into the text box.

Example:

> "I can't stop thinking about my ex."

---

### Step 2

(Optional)

Upload a breakup chat screenshot.

Supported formats:

- PNG
- JPG
- JPEG

---

### Step 3

Click

```
Get Recovery Support
```

---

### Step 4

The AI team generates:

- ❤️ Therapist advice
- ✉️ Closure message
- 📅 Daily routine
- 💥 Brutal honesty
- 👑 Final recovery summary

---

# 📸 Screenshots

## Home Page

```
(Add Screenshot Here)
```

---

## Chat Screenshot Analysis

```
(Add Screenshot Here)
```

---

## Final Recovery Dashboard

```
(Add Screenshot Here)
```

---

# 🎯 Example Workflow

```
User Input
      │
      ▼
Upload Screenshot
      │
      ▼
AI Screenshot Analysis
      │
      ▼
Multi-Agent Collaboration
      │
      ▼
Individual Responses
      │
      ▼
Final Recovery Summary
```

---

# 🤖 AI Agents

## ❤️ Therapist Agent

Provides:

- Emotional validation
- Mental health coping strategies
- Positive encouragement

---

## ✉️ Closure Agent

Creates messages that help users express feelings without actually sending them.

Purpose:

- Emotional release
- Self-reflection
- Closure

---

## 📅 Routine Planner Agent

Generates:

- Morning routine
- Self-care activities
- Productivity suggestions
- Exercise recommendations
- Sleep schedule

---

## 💥 Brutal Honesty Agent

Provides:

- Reality-based advice
- Honest observations
- Relationship pattern analysis
- Tough but constructive feedback

---

# 🌟 Future Improvements

- Voice conversations
- Emotion detection
- Journal tracking
- Mood analytics dashboard
- Daily recovery reminders
- Spotify healing playlist integration
- WhatsApp chat import
- Mobile application
- Recovery progress tracker

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Kushagra Sharma**

BCA (AI & Data Science)

SAGE University, Bhopal

GitHub: https://github.com/krish24coder

LinkedIn: [https://www.linkedin.com/in/kushagra-sharma-5286433a8](https://www.linkedin.com/in/kushagra-sharma-5286433a8/)

---

<div align="center">

## ⭐ If you found this project helpful, please give it a Star!

Made with ❤️ using Streamlit, Agno & Google Gemini

</div>
