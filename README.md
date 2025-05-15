# 📊 WhatsApp Chat Analyzer

This is an interactive data science project built with **Python** and **Streamlit** that allows you to analyze WhatsApp group chat data for insights into user activity, message patterns, emoji usage, timelines, and more.

---

## 🔍 Features

- 📂 Upload `.txt` WhatsApp export files
- 👥 Analyze chat statistics by individual or overall group
- 📈 Visualizations:
  - Total messages, words, media, links
  - Most active users
  - Most common words (stop-words filtered)
  - Emoji usage breakdown
  - Monthly & daily message trends
  - Most busy day & month
  - Hourly activity heatmap

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Streamlit
- Regex
- URLExtract
- Emoji

---

## 🧠 How It Works

1. Upload your `.txt` chat file exported from WhatsApp.
2. The data is preprocessed using regex to extract:
   - Date, time, sender, message content
   - Derived fields: year, month, day, hour, weekday, period
3. Visual and statistical summaries are generated for:
   - User activity
   - Word frequency
   - Emojis
   - Time-series analysis

---
Install dependencies
pip install -r requirements.txt


Run the app
streamlit run app.py

Upload your WhatsApp .txt file (from the sidebar) and start exploring!
📁 File Structure
├── app.py                 # Streamlit app UI
├── preprocessor.py        # Preprocess raw chat data
├── helper.py              # All analysis and visual functions
├── stop_hinglish.txt      # Custom stopword list for filtering
├── README.md              # This file
└── requirements.txt       # List of required Python packages

🧪 Sample Use Cases
Identify the most active members in a group

See which day of the week you chat most

Discover your most-used emojis

Spot your daily or monthly texting trends

📌 Note
Ensure your WhatsApp chat is exported without media

Only .txt format supported


