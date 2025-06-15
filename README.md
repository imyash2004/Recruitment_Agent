# Yash Recruitment Agent 🚀

An AI-powered resume analysis tool built with Streamlit and OpenAI. Analyze resumes, generate interview questions, and improve resume quality with a modern dark-themed interface.

## 🎯 Features

- **Resume Analysis**: Score resumes (0-100) with detailed feedback
- **Q&A System**: Ask questions about uploaded resumes
- **Interview Questions**: Generate personalized questions by difficulty
- **Resume Improvement**: Get suggestions with before/after examples
- **Dark Theme**: Customizable interface with visual analytics
- **Export Reports**: Download analysis, questions, and improved resumes

## 🚀 Live Demo

[https://recruiment-agent.streamlit.app/](https://recruiment-agent.streamlit.app/)

## 🛠️ Quick Start

### Prerequisites
- Python 3.8+
- OpenAI API Key

### Installation & Run

```bash
# Clone repository
git clone <repository-url>
cd yash-recruitment-agent

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run main.py
```

The app will open at `http://localhost:8501`

## 🎯 Supported Roles

AI/ML Engineer | Frontend Engineer | Backend Engineer | Data Engineer | DevOps Engineer | Full Stack Developer | Product Manager | Data Scientist

## 📖 Usage

1. **Enter OpenAI API Key** in the sidebar
2. **Upload PDF Resume** 
3. **Select Role** or upload custom job description
4. **Analyze Resume** and get detailed feedback
5. **Use Additional Features**:
   - Ask questions about the resume
   - Generate interview questions
   - Get improvement suggestions
   - Create optimized resume versions

## 🔧 Configuration

### Environment Variables (Optional)
```bash
# Create .env file
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

### Project Structure
```
yash-recruitment-agent/
├── main.py          # Main application
├── ui.py            # UI components
├── agents.py        # AI logic
├── yash.jpg         # Logo (optional)
├── requirements.txt # Dependencies
└── .env            # API keys (optional)
```

## 🚨 Troubleshooting

| Issue | Solution |
|-------|----------|
| API Key Error | Verify OpenAI API key is valid with credits |
| PDF Upload Fails | Ensure PDF is not password-protected |
| App Won't Start | Check Python version (3.8+) and dependencies |
| Styling Issues | Clear browser cache, enable JavaScript |

## 📄 License

MIT License

---

**Built with Streamlit & OpenAI | v1.0.0**