# AI Resume Assistant

**AI Resume Assistant** is a Streamlit-based application that helps job seekers create tailored resumes and cover letters using generative AI. It evaluates resume-job fit, detects skill gaps, and offers professional suggestions—all in minutes.

> Boost your application success with data-driven, personalized job materials powered by NLP and LLMs.

---

## Features

### Resume-Job Match Score
- Uses **TF-IDF** vectorization and **cosine similarity** to score how well your resume matches a job description.
- Instantly see if your resume alignment is strong enough (>70% is a good target).

### Missing Keyword Detection
- Automatically extracts important skills/keywords from the job description.
- Identifies what's **missing** in your resume using NLP & regex techniques.

### Resume Tailoring (Smart Phrase + GPT)
- Inserts missing keywords into professionally written **bullet templates**.
- Enhances them using **GPT-3.5**, making your resume impactful and ATS-friendly.

### Cover Letter Generator
- Creates a customized cover letter from your resume.
- Highlights your key achievements aligned to the target role.
- Uses GPT to adapt tone and format (e.g., formal, concise).

### Smart Summary Report
- Resume Match Score
- Matched vs. Missing Skills
- Resume Readiness Rating (Out of 5)
- Suggested Next Steps

---

## Demo (Streamlit UI)

Upload your resume and job description → Get tlored bullets, a cover letter, match score, and a summary report.

---

## Technologies Used

- `Python` (core logic)
- `Streamlit` (frontend)
- `Scikit-learn` (TF-IDF vectorization)
- `Open GPT-3.5 API` (generative enhancement)
- `PyPDF2` & `python-docx` (file reading)
- `Regex + NLTK` (keyword extraction)
- `Cosine Similarity` (resume-job fit)
- `Smart Phrase Bank` (resume coaching)

---

## Target Audience

- **Students / Entry-level professionals** (ages 21–30)
- **Career switchers / Mid-level professionals** (ages 30–45)
- **Universities & Career Centers** (B2B opportunity)

---

## How It Works

1. **Upload** your resume and job description.
2. System:
   - Extracts text
   - Vectorizes documents using TF-IDF
   - Calculates similarity
   - Detects missing keywords
   - Enhances resume bullets
   - Generates cover letter
3. **Output**:
   - Tlored content
   - Match score
   - Final summary report

---

## Future Enhancements

- iOS/Android/Desktop apps
- Multi-language support
- A/B testing on bullet styles
- Subscription-based premium features
- Social sharing & referral tools

---

## Folder Structure

AI-Resume-Assistant/
</br>
├── main terminal.py            # CLI version (testing/core logic)
</br>
├── Streamlit app.py            # Streamlit web UI
</br>
├── Report - AI Resume Assistant.pdf  # Full project documentation
</br>
├── AI Resume Assistant Presentation  # Pitch-style presentation

---

## License/Disclaimer

This project is for educational and demonstration purposes only.

---

## Acknowledgements

- OpenAI for the GPT API
- Scikit-learn for NLP tooling
- Streamlit for rapid prototyping
