# Smart ATS Resume Checker using Google-Gemini Pro Vision

An AI-powered Resume Analyzer built using Google Gemini Pro Vision (LIM Model).  
This application allows users to upload a resume (PDF) and extract structured candidate information and score instantly using AI.

---

## 🚀 Features

- Upload Resume (PDF)
- AI-powered resume parsing
- Extract:
  - Candidate Name
  - Contact Information
  - Skills
  - Work Experience
  - Education
- Instant structured output
- Clean and interactive UI
- No database required (stateless application)

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **AI Model:** Google Gemini Pro Vision
- **API Integration:** Google Generative AI SDK

---

## 📋 Requirements

Make sure the following are installed:

- Python 3.9+
- Git
- Google Gemini API Key

---

## 📦 Installation & Setup

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
https://github.com/PKdivyesh1/Smart-ATS-Resume-Checker.git
```
###2️⃣ Create Virtual Environment (Recommended)
```
python -m venv venv
```
Activate it:

Windows: ``` venv\Scripts\activate ```

Mac/Linux: ```   source venv/bin/activate ```

### 3️⃣ Install Dependencies
``` pip install -r requirements.txt ```

### 4️⃣ Set Up Environment Variables

Create a file named .env in the root directory and add:

GOOGLE_API_KEY=your_api_key_here

### 5️⃣ Run the Application
streamlit run app.py

![Smart-ATS-Resume-Checker](webview.png)
