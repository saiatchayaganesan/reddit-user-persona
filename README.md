# 🧠 Reddit User Persona Generator

This project generates a **persona summary** of a given Reddit user based on their recent posts and comments.  
It identifies topics of interest, tone of communication, and engagement style using Python and NLP.

---

## 🚀 Why I Chose This Project

The task was assigned as part of the **AI/LLM Engineer Intern assignment at BeyondChats**.  
I chose this concept because it involves:
- **NLP (Natural Language Processing)** for analysis
- **APIs and scraping** for real-world data usage
- **Practical AI application** without needing paid LLMs

This shows my ability to build smart tools using open-source technologies.

---

## 🧩 Problem Statement

Reddit users share a lot about themselves in comments and posts.  
But it's time-consuming to read through all of them to understand a user's personality.

**The problem**:  
How do we generate a concise, explainable user profile from unstructured Reddit data?

---

## ✅ The Solution

This tool:
- Takes a Reddit username as input  
- Scrapes their recent **posts and comments**  
- Filters noise using **stopword removal**  
- Analyzes:
  - **Topics** of interest  
  - **Language tone** (positive, negative, neutral)  
  - **Activity level**  
- Outputs a clean, human-readable **persona summary**  
- Cites examples from their own Reddit content

---

## 🔧 Technologies Used

- 🐍 Python 3
- 📦 [PRAW](https://praw.readthedocs.io/) – Reddit API Wrapper
- 🧠 [NLTK](https://www.nltk.org/) – for text cleaning and tone analysis

