# AiPlanetech

🧠 Mental Health Chatbot
A machine learning-powered chatbot designed to provide emotional support by analyzing user messages and responding with empathetic and helpful replies.

🚀 Features
✅ AI-powered intent recognition using NLP and deep learning
✅ Customizable responses based on user emotions
✅ Colorful UI with Light/Dark mode toggle 🌙
✅ User-friendly interface with rounded buttons & smooth chat display
✅ Pre-trained model with emotional intent classification

🛠️ Technologies Used
Python 🐍
TensorFlow/Keras (Deep Learning Model)
NLTK (Natural Language Processing)
Tkinter (GUI)
Pickle (Model Data Storage)
Scikit-learn (Data Processing)
📂 Project Structure
bash
Copy
Edit
📦 MentalHealthChatbot
├── 📂 models/                 # Trained ML Model & Data
│   ├── emotion_model.h5       # Trained LSTM Model
│   ├── words.pkl              # Tokenized Words
│   ├── classes.pkl            # Intent Classes
├── 📂 Data/
│   ├── responses.json         # Chatbot Responses & Patterns
├── chatbot.py                 # Main Chatbot Script
├── model.py                   # Model Training Script
├── requirements.txt           # Dependencies
├── README.md                  # Project Documentation
🎨 UI Preview
Light Mode: Soft purple background 🌸
Dark Mode: Sleek Discord-like theme 🌑
Smooth chat display with user/bot message styling
💾 Installation & Setup
1️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
2️⃣ Run the Chatbot
bash
Copy
Edit
python chatbot.py
3️⃣ Train the Model (Optional)
bash
Copy
Edit
python model.py
🛠️ Customization
🔹 Modify responses.json to add new responses & patterns
🔹 Adjust error_threshold in chatbot.py for better predictions
🔹 Change UI colors & fonts in ChatBotUI class

📌 Future Enhancements
🗣️ Voice Input & Speech-to-Text
🌍 Multilingual Support
📖 Context-Aware Conversations
