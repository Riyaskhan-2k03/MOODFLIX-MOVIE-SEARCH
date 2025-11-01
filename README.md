🎬 MoodFlix – AI Emotion-Based Movie Recommendation System

MoodFlix is an intelligent movie recommendation app that detects your mood using AI and instantly suggests movies that match your emotions.

Built using Python (Streamlit) + Machine Learning + Computer Vision, MoodFlix creates a personalized and emotional movie-watching experience — simply click a photo, let AI detect your emotion, and get relevant movie recommendations.

✨ Features

✅ Real-time emotion detection using webcam
✅ AI-powered movie recommendations based on mood
✅ Modern Streamlit UI
✅ User login & authentication
✅ Emotion history & analytics
✅ Backend API integration
✅ Works on laptop webcam & mobile camera

🧠 Tech Stack
Technology	Usage
Python	Backend logic & API
Streamlit	Frontend interface
Machine Learning	Emotion detection
Computer Vision (OpenCV / Deepface)	Emotion recognition from images
Movie API (TMDB / Custom)	Fetch movie recommendations
JWT Auth / REST API	Authentication & server communication
📸 How It Works

1️⃣ User logs in
2️⃣ Captures a selfie using webcam
3️⃣ AI model detects emotion (happy, sad, angry, surprised, etc.)
4️⃣ App fetches movies based on detected emotion
5️⃣ Shows recommendations & saves emotion history

🚀 Setup Instructions
# Clone the repo
git clone https://github.com/yourusername/moodflix.git
cd moodflix

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

📂 Project Structure
moodflix/
│── app.py              # Streamlit frontend
│── backend/            # API + ML model
│── requirements.txt
│── assets/             # Images / icons
└── README.md

📈 Emotion Categories

😊 Happy

😢 Sad

😡 Angry

😲 Surprised

😐 Neutral

😴 Bored

🎥 Demo

Add screenshots or GIF here

🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you want to improve.

⭐ Support & Feedback

If you like this project, please ⭐ star the repo
Ideas, issues & feedback are always welcome!
