# 🌟 Daily Motivation Generator – AI-Powered Quote App

**Daily Motivation Generator** is a simple and uplifting web application that uses Hugging Face’s GPT-2 model to generate motivational quotes based on the user’s current mood. Whether you’re feeling anxious, unfocused, or just need a boost — this app delivers personalized encouragement instantly.

---

## 🚀 Features

✅ **AI-Generated Motivation**  
Uses GPT-2 from Hugging Face Transformers to generate original, mood-based quotes.

✅ **Customizable Mood Input**  
Choose from a list of moods:
- Feeling anxious  
- Need focus  
- Low energy  
- Feeling overwhelmed  
- Looking for inspiration  
- And more

✅ **Fast, Free, and Offline**  
Runs entirely on your machine — no API keys or internet required after install.

✅ **Simple and Clean UI**  
Built with Streamlit for instant interaction and visual feedback.

---

## 🖼️ Screenshots

![image](https://github.com/user-attachments/assets/656b2fc8-74e8-4b62-b312-57e744a59206)
![image](https://github.com/user-attachments/assets/77fc332d-bf45-4b14-9156-9ec8d5c155c9)
![image](https://github.com/user-attachments/assets/1d250061-6812-49ed-9347-cc49dec40afc)


- App landing page  
- Mood dropdown and button  
- Generated motivational message

---

## 💻 Setup and Installation

### 🧰 Prerequisites
- Python 3.10+
- pip (Python package manager)

### 📦 Local Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/daily-motivation-generator.git
cd daily-motivation-generator

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run app.py
```

---

## 📁 Project Structure

```
daily-motivation-generator/
├── app.py                    # Main Streamlit app
├── requirements.txt          # Python dependencies
└── .streamlit/
    └── config.toml (optional)
```

---

## ⚙️ Configuration

No external API keys or .env setup required!  
You can tweak model output randomness directly in the `app.py`:

```python
temperature=0.95
top_k=50
top_p=0.95
```

---

## 🧠 How It Works

1. User selects a mood from the dropdown
2. The app forms a prompt like:  
   _“A motivational message for someone who is feeling anxious:”_
3. GPT-2 generates a unique, encouraging sentence
4. Output is cleaned and displayed in the UI

---

## ☁️ Optional: Deploy on Streamlit Cloud

- Push your code to GitHub
- Go to [https://streamlit.io/cloud](https://streamlit.io/cloud)
- Create a new app linked to your repo
- Set the main file to `app.py`
- Done! You’ll get a public URL to share

---

## 📚 Usage Guide

1. Run the app locally or on Streamlit Cloud  
2. Select your mood  
3. Click **“Generate Motivation”**  
4. Read your personalized message  
5. Repeat or refresh for a new quote!

---

## 🔮 Future Improvements

- Save/download favorite quotes  
- Multi-language support (Hindi, Tamil, etc.)  
- Voice output (text-to-speech)  
- Mobile app integration  
- Daily quote scheduling/reminders

---

## 📌 License

This project is open-source and free to use under the [MIT License](LICENSE).
