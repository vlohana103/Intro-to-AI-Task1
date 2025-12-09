# CS Career Recommendation Chatbot (AIML)

This project is a rule-based AIML chatbot created for **WGU – Intro to AI (Task 1)**.  
The chatbot helps users explore potential Computer Science career paths using a simple branching decision flow with button-based interactions.

The chatbot is designed to run on **Pandorabots**.

---

## 📌 Overview

The CS Career Bot begins when the user types **"Hello"**.  
It then guides the user through one of two paths:

### ✔ Path 1: User Already Knows What Job They Want
- User clicks **Yes!**
- Bot shows five job options:
  - Data Engineer
  - IT Consultant
  - Robotics Software Engineer
  - Back-End Developer
  - Front-End Web Developer  
- Each option displays a short job description and encouragement.

### ✔ Path 2: User Does *Not* Know What Job They Want
- User clicks **No!**
- Bot asks what type of work they prefer:
  - Data
  - Consultations
  - Robots
  - Code
  - Visuals  
- Bot recommends the matching career with a short description.

### ✔ Fallback Handling
If the user types anything other than **“Hello”**, the bot responds with:
> “Please enter ‘Hello’ or use the button prompts.”

This ensures predictable and user-friendly interaction.
