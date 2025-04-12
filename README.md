🌟 Sparkle: AI Health Insight Engine & Chatbot Prototype

Take-Home Assignment – AI Intern
Company: Zoom My Life
Role: AI Intern – Health Insight & Chatbot Prototype
Duration: 1–2 Weeks
Name: Kushal

---

🧠 Project Overview

Sparkle is a lightweight AI-powered prototype designed to provide personalized health guidance through a combination of an insight engine and a chatbot interface. This hands-on project simulates a real product feature actively developed by Zoom My Life, where AI meets empathy to help families manage their well-being.

---

🚀 Features

✅ Insight Engine (Hybrid AI Logic)
- Rule-based & logic-driven health analysis
- Generates contextual recommendations based on CSV health logs
- Supports hydration, sleep, mood, and steps data

💬 Health Chatbot (Streamlit UI)
- Natural Q&A style interaction
- Responds to user queries like:
  - “How am I doing this week?”
  - “What’s my sleep trend?”
- Context-aware, stateless chatbot using session-based insights

📊 Visual Dashboard
- Trend visualizations using Matplotlib
- Tracks fluctuations and patterns in health indicators

---

🗂️ Project Structure

zml/
├──zmlb
|    ├── backend/                          # Backend logic for insights and data processing
│    |   ├── __pycache__/                  # Python cache files
│    |   ├── data/                         # CSV files
│    |   ├── api.py                        #flask
│    |   ├── hybrid_insight_engine.py     # corelogic
│    |   ├── trends.py                    # trendsmatplot
│    |   ├── requirements.txt             # Python dependencies
│    |   └── render.yaml                  # Render deployment config
│    |
|    ├── sparkle-health-chatbot/
│       ├── __pycache__/
│       ├── data/                         # Input data or session files
│       ├── streamlit_chatbot.py         # streamlit chatbot ui
│       ├── hybrid_insight_engine.py
│       └── requirements.txt             # streamlitdependencies
│
├── zmlf/                             # React Frontend ts
│   ├── app/
│   │   ├── components/              # reusablecomponents
│   │   ├── config/
│   │   ├── insights/                # Insight display page
│   │   ├── layout.tsx              # layout wrapper
│   │   └── page.tsx                # main frontend page
│   ├── .vercel/
│   ├── tailwind.config.js          # tailwind css config
│   ├── tsconfig.json               # ts configuration
│   └── package.json
|
└── README.md                        #project overview




🛠️ Tech Stack

| Layer       | Tools / Frameworks                          |
|-------------|---------------------------------------------|
| Language    | Python,  TypeScript             |
| AI Logic    | Rule-based and Ml,Pandas, Matplotlib        |
| Chatbot UI  | Streamlit                                   |
| Frontend    | React (TypeScript + Tailwind)               |
| Deployment  | Render.com                                  |


🩺 Health Insights Generator + Chatbot

This project includes:
--> Flask backend for health trend analysis
--> Streamlit-based health chatbot
--> React frontend ('zmlf/app/')


🧪 Local Setup Instructions

1. Clone the repo

git clone https://github.com/HealthInsightGenerator.git
cd HealthInsightsGenerator

📥 Getting Started

-Backend

cd HealthInsightsGenerator/zmlb/backend
pip install -r requirements.txt
python api.py (or) python3 api.py


-Streamlit Chatbot run

cd HealthInsightsGenerator/zmlb/sparkle-health-chatbot
pip install -r requirements.txt
streamlit run streamlit_chatbot.py


---

🧪 Sample Queries

- “How am I doing this week?”
- “What’s my sleep trend?”
- “Am I drinking enough water?”
- “Any signs of stress?”

---

🌈 Sample Output

> “Hydration: Definitely pay attention to that low water intake! Even a small increase can make a big difference in your energy levels and overall well-being. Let's try to find some strategies to help you drink more water consistently. Maybe setting reminders, carrying a water bottle, or finding infused water recipes you enjoy?

Step Count: Excellent work on your step count! 9153 is fantastic progress. Let's keep that momentum going and see if we can nudge it closer to your ideal target. Remember, even small increases each day will add up.

Mood: It's important to acknowledge the recent dip in mood. I'm glad you're seeing that. Prioritizing self-care is absolutely key right now. Remember those activities that usually bring you joy, and try to schedule some time for them. Even small moments dedicated to yourself can help lift your spirits.”  
> “😔 Mood levels are down, and sleep hours are irregular. Signs point to mild fatigue or stress.”



📹 Demo Video
Link: https://drive.google.com/file/d/1v7JlWJQTSNdDmsHe9U-pVqIX1dZO-le4/view?usp=sharing

