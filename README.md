# 📊 Decision Tree for Internship Candidate Evaluation

**Name:** Kamakshi Pal  

---

## 📌 Use Case
This project presents a deterministic decision tree designed to evaluate candidates applying for a Data Science internship based on their technical skills, project experience, and problem-solving ability.

---

## 🎯 Objective
To create a structured and transparent evaluation system that ensures fair and consistent candidate screening.

---

## 🌳 Decision Tree
START
│
├── Does the candidate have basic Python knowledge?
│       ├── No → REJECT
│       └── Yes → Next Step
│
├── Does the candidate know SQL or data handling?
│       ├── No → REJECT
│       └── Yes → Next Step
│
├── Has the candidate worked on at least 1 project?
│       ├── No → WAITLIST
│       └── Yes → Next Step
│
├── Can the candidate explain their project clearly?
│       ├── No → WAITLIST
│       └── Yes → Next Step
│
├── Does the candidate show problem-solving ability?
│       ├── No → WAITLIST
│       └── Yes → SELECT
│
END

---

## 🧠 Explanation of Logic

This decision tree follows a step-by-step filtering approach:

- **Technical Skills Check:** Ensures candidate has foundational Python and SQL knowledge  
- **Project Experience:** Evaluates hands-on exposure  
- **Communication Skills:** Assesses clarity in explaining work  
- **Problem-Solving Ability:** Final determinant for selection  

Candidates who satisfy all criteria are selected, while others are either rejected or placed on a waitlist.

---

## ⚠️ Guardrails Against AI Hallucination

To ensure reliability and accuracy:

- The system is **fully deterministic** (rule-based, no randomness)  
- Each decision is based on **explicit yes/no conditions**  
- No assumptions are made beyond input data  
- The process is **transparent and interpretable**  

---

## ✅ Advantages

- Simple and easy to understand  
- Scalable for large applicant pools  
- Eliminates ambiguity in decision-making  
- Ensures fairness and consistency  

---

## 🚀 Future Improvements (Optional)

- Convert into an automated evaluation tool  
- Integrate scoring instead of binary decisions  
- Extend to AI-based candidate assessment  

---

## 🏁 Conclusion

This decision tree provides a structured, fair, and efficient method to evaluate candidates for a Data Science internship, ensuring consistency and transparency in the selection process.
