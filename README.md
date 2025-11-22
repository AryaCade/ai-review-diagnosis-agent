# ⭐ AI Review Diagnosis Agent

An AI-powered workflow built using **LangGraph** and **Google Gemini** that analyzes user reviews, detects sentiment, diagnoses issues, and generates personalized support responses.

This project demonstrates:
- LLM-powered **sentiment analysis**
- Automatic **issue classification** (UX, Bug, Performance, etc.)
- Emotional **tone detection**
- Urgency estimation  
- Conditional LangGraph workflow routing  
- Automated positive & negative response generation

---

## 🚀 Features

### ✓ **Sentiment Analysis**
Uses Gemini to classify reviews as:
- `positive`
- `negative`

### ✓ **Issue Diagnosis (for negative reviews)**
Extracts:
- Issue type  
- Tone  
- Urgency  

### ✓ **Automated Responses**
- Positive reviews → Thank-you message  
- Negative reviews → Empathetic support response  

### ✓ **LangGraph Workflow**
The app is powered by a state-based agent:
1. `find_sentiment`
2. Conditional routing  
3. `run_diagnosis` (only for negative reviews)  
4. Response generation

---

## 🛠️ Tech Stack

- **Python**
- **LangGraph**
- **LangChain**
- **Google Gemini (2.5 Flash)**
- **Pydantic** for structured output
- **dotenv** for environment config

---

## 📝 Example Output

```
Sentiment: negative
Issue: Performance
Tone: disappointed
Urgency: medium
AI Response: "I'm truly sorry for this experience..."
```

---

## 📚 Learning Purpose

This project was built to practice:
- LangGraph routing logic  
- Gemini structured outputs  
- State management in AI agent workflows  
- Building production-style review automation systems  

---

---

If you like this project, consider ⭐ starring the repository!
