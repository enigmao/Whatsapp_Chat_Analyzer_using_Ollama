
# Chat Authentic Analyzer

**Description:**  
An authentic analyzer for chats, which provides helpful insights.

This project is implemented in Python and deployed using **Streamlit**.  
It analyzes chat conversations (e.g., from WhatsApp, Messenger, etc.) and provides insights such as:  
- Word frequencies  
- User activity patterns  
- Sentiment analysis  
- Visualization of trends  

---

## 🚀 Installation

Clone the repo and install requirements:
```bash
git clone https://github.com/yourusername/chat-analyzer.git
cd chat-analyzer
pip install -r requirements.txt
```

## ▶️ Run the Streamlit App

```bash
streamlit run Analyzer.py
```

Then open the URL shown in the terminal (default: http://localhost:8501).

---

## 📊 Features
- Upload chat files
- Get insights on message statistics
- Visualize message trends with charts
- Perform sentiment analysis on conversations

---

## 📂 Repository Structure
```
.
├── Analyzer.ipynb      # Jupyter notebook version
├── Analyzer.py         # Streamlit app (converted from notebook)
├── requirements.txt    # Dependencies
├── README.md           # Documentation
└── .gitignore
```

---

## 📝 Deployment (Optional)
To deploy on Streamlit Cloud:
1. Push this repo to GitHub.
2. Go to https://streamlit.io/cloud and link your repo.
3. Set the main file to `Analyzer.py`.

---

## License
MIT License. Free to use for research and learning.
