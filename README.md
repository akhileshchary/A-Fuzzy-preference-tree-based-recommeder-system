# A Fuzzy Preference Tree-Based Recommender System

A research-driven project that implements a **Fuzzy Preference Tree (FPT)** model for building intelligent and adaptive recommender systems.  
The system uses fuzzy logic and preference-based decision trees to provide accurate and personalized recommendations for users.

---

## 🧩 Overview

Traditional recommender systems rely on collaborative filtering or content-based filtering, which often struggle with uncertainty and user preference fuzziness.  
This project integrates **fuzzy logic** and **decision tree learning** to handle vague or imprecise user preferences effectively.

The core algorithm constructs a *fuzzy preference tree* that models user satisfaction levels and predicts suitable recommendations.

---

## 🛠️ Features

- ✅ Fuzzy preference modeling  
- 🌲 Preference tree learning algorithm  
- 🎯 Personalized recommendation generation  
- 💾 Database-backed data storage (MySQL or SQLite)  
- 🧮 Rule-based reasoning for better explainability  
- 🧪 Experimental evaluation on custom datasets

---

## 📁 Project Structure

A-Fuzzy-preference-tree-based-recommeder-system/
├── database/
│ └── database.sql # SQL file for database schema and data
├── src/ # Source code (if applicable)
├── LICENSE
├── README.md
└── .gitignore


---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/akhileshchary/A-Fuzzy-preference-tree-based-recommeder-system.git
cd A-Fuzzy-preference-tree-based-recommeder-system

### 2. Set up the database

Import database.sql into your MySQL or SQLite database.

Update database configuration in the project’s source code (if applicable).

### 3. Run the system

Depending on the implementation:

If it’s a Java project:

javac Main.java
java Main


If it’s a Python project:

python main.py

## 🧠 Algorithm Description

Input collection: User preferences and historical data.

Fuzzy modeling: Convert crisp input into fuzzy linguistic variables.

Tree construction: Generate a fuzzy preference tree using training data.

Recommendation: Compute user-item matching scores based on fuzzy inference.

Evaluation: Measure precision, recall, and F1-score of recommendations.

## 📊 Example Use Case

A movie recommendation scenario:

User provides fuzzy preferences such as "I like action movies somewhat but love sci-fi."

The system constructs a fuzzy preference tree to interpret these preferences.

Outputs top-ranked movie recommendations with fuzzy confidence scores.

## 🧪 Experimental Results (Optional)

(You can add graphs, screenshots, or metrics here.)

## 📜 License

This project is licensed under the Apache License 2.0 — see the LICENSE
 file for details.

## 👨‍💻 Author

Akhilesh Chary
📧 akhileshcharymogili@gmail.com
🌐 https://github.com/akhileshchary

## ⭐ Acknowledgements

Inspired by academic research on fuzzy decision trees and recommender systems.

Built as part of a university or personal research project.