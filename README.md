# PBEL-NOVELia-AI-chatbot
AI-powered emotion-aware book recommendation chatbot using IBM Watsonx
# 📚 NOVELia – Emotion-Aware AI Book Recommendation Chatbot

Welcome to **NOVELia**, an AI-powered book recommendation chatbot that understands your emotions and suggests books that fit your mood. 
Built as part of the **PBEL IBM Virtual Internship (AI Domain)**, NOVELia leverages **IBM Watsonx Assistant** to create a personalized, 
emotionally intelligent reading experience.

![NOVELia Banner](https://i.postimg.cc/hvFcm4hT/Default-Mystical-feminine-aura-or-glowing-abstract-spirit-surr-0.jpg)

---

## 🌟 Features

- 🤖 Emotion-aware responses (Sad, Angry, Happy, Anxious, etc.)
- 🎯 Mood-to-Genre mapping
- 📖 Personalized book recommendations
- 🔁 Follow-up recommendations
- 💬 Real-time chatbot powered by IBM Watsonx
- 🖼️ Stylish and responsive front-end design

---

## 🧠 Technologies Used

| Tool              | Purpose                                 |
|------------------|-----------------------------------------|
| IBM Watsonx       | AI Assistant, NLP & dialog flow         |
| HTML5 / CSS3      | Front-end development                   |
| JavaScript        | Basic chatbot interaction (optional)    |
| GitHub Pages      | Deployment & hosting                    |

---

## 💡 Project Structure


📁 PBEL-NOVELia-AI-chatbot/
├── index.html         # Main website interface with Watsonx integration
├── style.css          # All UI styling and responsive layout
├── script.js          # Optional (e.g., animations or chatbot logic)
├── README.md          # This documentation file
└── assets/            # (Optional) images, logos, screenshots, etc.

🚀 Getting Started

1. **Clone the Repository**
--bash
git clone https://github.com/HarshkumarG007/PBEL-NOVELia-AI-chatbot.git
cd PBEL-NOVELia-AI-chatbot

2. **Deploy on GitHub Pages**
    Go to your GitHub repo settings
    Scroll to "Pages"
    Select branch: main and folder: / (root)
    Save and visit:
    👉 https://harshkumarg007.github.io/PBEL-NOVELia-AI-chatbot/

🤖 **How NOVELia Works**
      User is greeted and asked for their current emotional state
      Watsonx maps mood to relevant book genres
      User selects a preferred genre
      NOVELia recommends a book based on mood + genre
      User can ask for more suggestions or give feedback

📦 **Integration with IBM Watsonx**
The chatbot is powered by Watsonx Assistant with a customized dialog flow structure:


📁 NOVELia Dialog Flow
 ├─ 👋 Welcome & Greeting (#greeting)
 │   └─ 🧠 Emotion Recognition (#EmotionRecognition)
 │       └─ 🎭 Emotional State Handlers
 │           ├─ 😢 Sad (#Sad)
 │           ├─ 😰 Anxious (#Anxious)
 │           ├─ 😠 Angry (#Angry)
 │           ├─ 😕 Confused (#Confused)
 │           ├─ 😐 Neutral (#Neutral)
 │           ├─ 😊 Happy (#Happy)
 │           └─ 😍 Nostalgic/Other
 │               ↓
 ├─ 🎯 Mood To Genre Mapper
 │   ↓
 ├─ 📌 Genre Preference Matcher (@Genre)
 │   ↓
 ├─ 📖 Book Recommender
 │   └─ 🔁 Another Recommendation Handler (#Another_recommendation)
 ├─ 🙋‍♂️ Clarification Handler (#Clarification)
 ├─ 🙏 Feedback Handler (#Thanks)
 └─ 🚫 Fallback Handler (Anything Else)


📸 **Screenshots **
    📷 chatbot interface
    📷 genre selection
    📷 recommendation response


🧑‍💻 **Developer Info**
    👤 Harsh Kumar Gupta
    AI Intern | PBEL IBM Virtual Internship 2025

GitHub: @HarshkumarG007

📄 **License**
This project is licensed under the Apache 2.0 License.

🙏 **Acknowledgements**
IBM SkillsBuild & Watsonx Team
PBEL Internship Program 2025
All mentors and contributors

**⭐ If you found this helpful or inspiring, don’t forget to star the repo!**
