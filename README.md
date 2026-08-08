# 🏥 Arogya Sathi (આરોગ્ય સાથી) VoiceForBharat Day 3

Welcome to my Day 3 submission for the **10 Days of Voice Agents - #VoiceForBharat Edition** challenge!

Building upon the strict persona and safety guardrails established in Day 2, Day 3 focuses on giving Arogya Sathi the ability to [Insert Day 3 main objective, e.g., interact with external tools and take tangible actions].

## 🚀 Day 3 Upgrades: [e.g., Tool Calling & Dynamic Actions]

Arogya Sathi has been upgraded from a static persona to an active participant. Today's updates include:

*   **[New Feature 1]:** [Describe the feature, e.g., The agent can now securely log patient queries into a local JSON database.]
*   **[New Feature 2]:** [Describe the feature, e.g., Implemented function calling so the agent can pull real-time clinic hours.]
*   **Maintained Guardrails:** All emergency escalations (108 triggers) and medical disclaimer protocols from Day 2 remain actively enforced.
*   **Seamless Gujarati TTS:** Audio synthesis continues to run smoothly using Murf AI's Falcon-2 model.

## 🛠️ Tech Stack

*   **Frontend:** HTML5, JavaScript, Tailwind CSS
*   **Backend:** Python, FastAPI
*   **Voice & LLM:** Murf AI (GEN2, Diya, gu-IN), Google Gemini 1.5 Flash
*   **New Integrations:** [e.g., Pydantic for data validation / custom Python tool functions]

## ⚙️ Local Setup Instructions

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/voice-for-bharat-MurfAI-Day-3.git
cd voice-for-bharat-MurfAI-Day-3
```

**2. Configure Environment Variables**
Ensure your `.env` file in the `backend` directory contains:
```env
MURF_AI_API_KEY=your_murf_api_key
ASSEMBLYAI_API_KEY=your_assemblyai_api_key
GOOGLE_API_KEY=your_google_api_key
```

**3. Run the Backend & Frontend**
```bash
cd backend
# Activate virtual environment
.\venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux

python main.py
```
Open `frontend/index.html` using Live Server to start interacting.

---
*Built for the 10 Days of Voice Agents Challenge by Murf AI.*
