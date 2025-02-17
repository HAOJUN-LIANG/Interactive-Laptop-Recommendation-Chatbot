## Interactive Laptop Recommendation Chatbot

---

### Project Introduction
The **Interactive Laptop Recommendation Chatbot** is an AI-driven assistant that helps users select the best laptop based on their budget, purpose, and preferences. It features natural language interaction, image-based laptop identification, and personalized recommendations to streamline the laptop-buying process.

#### Key Features:
- **AI-powered Laptop Recommendations** - Get suggestions based on budget, usage (gaming, work, study), portability, and brand.
- **Laptop Image Recognition** - Upload an image of a laptop for model identification and analysis.
- **Data-Driven Insights** - View comparison tables, pricing trends, and historical recommendations.
- **Advanced Filtering** - Refine search results by specific preferences like RAM, GPU, weight, and battery life.
- **Secure User Authentication** - Create an account to save search history and track past recommendations.

---

### Project Demo
For detailed instructions, please refer to the **User Guide** section in the **Final Report**.

---

### System Architecture

This chatbot is a **Flask-based AI system** that integrates:
- **Backend**: Flask, SQLite
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: OpenAI GPT-4 API
- **Visualization**: Chart.js for price, specification comparison

---

### Project Structure
```
Interactive_Laptop_Recommendation_Chatbot/
├── Image recognition datasets for laptops/
├── templates/
│   ├── index.html
│   ├── login.html
│   └── result.html
├── app.py
├── categorize.py
├── chat_history.db
├── Final Report.pdf
├── laptop_advisor.db
├── laptop_recommendations_2.db
├── laptop_recommendations_3.db
├── laptop_recommendations_4.db
├── README.md
├── requirements.txt
└── test.py
```

---

### Installation & Setup

Follow these steps to clone and set up the project:

#### Step 1: Clone the Repository
```
git clone https://github.com/HAOJUN-LIANG/Interactive-Laptop-Recommendation-Chatbot.git
cd Interactive_Laptop_Recommendation_Chatbot
```

#### Step 2: Create and Activate a Virtual Environment
```
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows
```

#### Step 3: Install Dependencies
```
pip install -r requirements.txt
```

#### Step 4: Run the Flask Server
```
python app.py
```
Access the chatbot at: ```http://127.0.0.1:5000/```

---

### Team Members
This project is part of the ***Foundations and Application of Generative AI*** at **Technical University of Munich**. The team is composed of the following members:

- **Lingwei Lu (MMDT)**
  - Team Lead
  - Full-Stack Developer
  - Project Management & Requirements
- **Kairui Zhang (MMDT)**
  - AI Specialist
  - Backend Developer
  - Presentation Strategist
- **Haojun Liang (BIE)**
  - Data Retriever
  - Backend Developer
- **XiaoYao Wang (BIE)**
  - Debugging & Testing
  - Frontend Development
