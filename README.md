# 🧠 Dumroo AI Query System (Natural Language Query + Role-Based Access)

This project demonstrates an AI-powered system that lets **school admins** query student data using **plain English**, while respecting **role-based access control** (RBAC).

Admins can ask:
- “Which students haven’t submitted their homework yet?”
- “Show me performance data for Grade 8 from last week.”
- “List all upcoming quizzes scheduled for next week.”

---

## ⚙️ Tech Stack

- **Python 3.9+**
- **LangChain**
- **OpenAI GPT-4-Turbo**
- **Pandas**

---

1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/dumroo-ai-query.git
cd dumroo-ai-query
2️⃣ Install dependencies

bash
Copy code
pip install -r requirements.txt
3️⃣ Set your OpenAI API key

bash
Copy code
export OPENAI_API_KEY="your_api_key_here"
4️⃣ Run the notebook or script

bash
Copy code
jupyter notebook dumroo_query_system.ipynb
