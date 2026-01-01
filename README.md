
# College Chatbot — St Joseph’s College of Engineering

# Project Overview
This project implements an intelligent College Chatbot designed to answer common queries related to St Joseph’s College of Engineering.  
The chatbot helps students and parents quickly get information such as courses, admission, timings, fees, contact details, hostels, and more.

The chatbot works using:
- Frequently Asked Questions (FAQ) dataset
- Natural language text processing
- TF-IDF + Cosine Similarity to match user questions with the most relevant answer

---

#College Details
**College:** St Joseph’s College of Engineering  
**Location:** Chennai, Tamil Nadu, India

---

# FAQs Used in the Chatbot
The chatbot currently supports the following questions and answers:

what is the college name → Our college name is St Joseph's College of Engineering.
what are the college timings → College timings are 7:50 AM to 3:00 PM.
where is the college located → The college is located in Chennai, Tamil Nadu.
how to get admission → Admissions are based on merit, counseling and management quota.
what is the fees → Average fee is around ₹4,00,000 for the full course (varies by department).
is hostel available → Yes, hostels are available for boys and girls.
is food available → We provide both vegetarian and non-vegetarian food.
what courses are offered → We offer CSE, IT, ECE, EEE, Mechanical, Civil, Chemical, AIML & ADS.
how are placements → We have around 80% placement rate every year.
how are exams conducted → We are conducting exams twice a year.
how to contact the college → Contact us at 9876543210 or email: info@stjosephscollege.edu.

We can easily add more questions to improve coverage.

#Tools & Technologies
- Python
- Jupyter Notebook
- Scikit-Learn
- TF-IDF Vectorizer
- Cosine Similarity
- Basic NLP concepts


# How the Chatbot Works
1️. Store questions and answers in a dictionary (FAQ dataset)  
2️. Convert text into numeric vectors using **TF-IDF**  
3️. Compare the user’s question with FAQ questions using **Cosine Similarity**  
4️. Return the closest matching answer

This makes the chatbot accurate and flexible, even when questions are typed differently.

# How to Run the Project
1. Download or clone this repository
2. Open the notebook in **Jupyter Notebook**
3. Install dependencies (if needed):

```bash
pip install scikit-learn
Run all cells

Type your question when prompted and view the chatbot response

# Future Enhancements
✔ Add GUI using Tkinter / Streamlit
✔ Add speech input and voice reply
✔ Connect chatbot to live website or database
✔ Add more FAQs and departments
✔ Include multilingual support

Author
Harini K
