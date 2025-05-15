# 📄 Smart ATS Resume Analyzer

A powerful tool that helps job seekers optimize their resumes for Applicant Tracking Systems (ATS) by matching resumes with job descriptions and offering keyword-based suggestions.

---

## 🚩 Problem Statement

In today's competitive job market, resumes must align closely with job descriptions to pass through ATS filters. Many candidates are rejected before a human ever sees their resume due to:

* Missing job-specific keywords
* Lack of alignment with job descriptions
* Unoptimized formatting or structure

**Smart ATS Resume Analyzer** addresses these issues by analyzing resumes against job descriptions using Google Gemini AI and providing actionable feedback.

---

## 💼 Business Use Cases

* ✅ **Resume Optimization**: Tailor resumes for specific job descriptions.
* 📋 **ATS Compliance**: Identify missing keywords to pass ATS filters.
* 🔍 **Efficient Screening**: Help recruiters and counselors assess candidate fit quickly.
* 🚀 **Improve Hiring Success**: Boost chances of interview selection.
* 🌍 **Scalable Career Support**: Integrate with HR platforms, job portals, or educational institutions.

---

## ✨ Key Features

| Feature               | Description                                                                |
| --------------------- | -------------------------------------------------------------------------- |
| 📊 JD Match Analysis  | Calculates how closely a resume matches a job description.                 |
| 🧹 Missing Keywords   | Detects important keywords missing from the resume.                        |
| 🧠 Profile Summary    | Generates a detailed analysis and improvement tips.                        |
| 📁 PDF Resume Support | Extracts resume content from uploaded PDF files.                           |
| 💻 Streamlit UI       | Intuitive, interactive, and user-friendly interface for seamless analysis. |

---

## ⚙️ How It Works

1. **📄 Upload Resume**
   Upload your resume in PDF format via the Streamlit interface.

2. **📄 Provide Job Description**
   Paste the job description you want to match your resume with.

3. **⚙️ Analyze Resume**
   The tool uses Google Gemini AI to compare and generate analysis.

4. **📈 View Results**

   * JD Match Score (0–100%)
   * List of missing keywords
   * Tailored profile summary with actionable suggestions

---

## 🧪 Project Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd smart-ats-resume-analyzer
```

### 2. Create Virtual Environment (with Conda or venv)

**Using Conda:**

```bash
conda create -p env python=3.10 -y
conda activate ./env
```

**OR using venv:**

```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY="your_api_key_here"
```

### 5. Run the Application

```bash
streamlit run app.py
```

---

## 📌 Future Enhancements

* 📄 Support for .docx and other formats
* 🧠 Role-specific feedback (Tech, Marketing, Design, etc.)
* 🌐 Multilingual resume analysis
* 🔗 Job board integration for auto-fetching JDs
* 📊 Analytics dashboard for recruiters/career coaches

---

## 🧠 Tech Stack

* **Frontend**: Streamlit
* **Backend**: Python, Google Generative AI (Gemini)
* **PDF Parsing**: PyPDF2
* **Environment Management**: Conda / venv

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this project and submit a pull request.

---

## 🙋‍♂️ Author

**Tushar Kurundkar**

📧 \[[Mail](mailto:alfaqtk@gmail.com)]
🌐 LinkedIn
