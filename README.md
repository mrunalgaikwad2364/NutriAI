# 🤖 NutriAI – Personalized Indian Dietician AI 🥗

An AI-powered personalized diet and fitness assistant designed for Indian users.  
NutriAI generates **culturally relevant Indian meal plans**, calculates nutritional needs, tracks daily intake, and suggests **customized Indian home workouts/yoga** — all powered by **Google’s Gemini 1.5 Flash**.

---

## 📌 Features

- **User Profile Collection**  
  Collects age, gender, height, weight, region preference, dietary preference, health conditions, and fitness goals.

- **Goal Classification**  
  Classifies health goal into **Weight Loss**, **Weight Gain**, or **Balanced Diet**.

- **Personalized Meal Plans**  
  Uses **Gemini 1.5 Flash via LangChain** to generate full-day culturally relevant meal plans.

- **Nutrition Tracking**  
  Calculates **BMR, calorie, and protein goals**; logs daily meals and computes remaining intake.

- **Fitness Recommendations**  
  Suggests **Indian home workouts & yoga** tailored to user profile and health conditions.

- **Automated Workflow**  
  Built with **LangGraph** for structured step-by-step processing.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **LLM:** Gemini 1.5 Flash (via LangChain)  
- **Workflow Orchestration:** LangGraph  
- **Libraries:** LangChain, Matplotlib, re  
- **API:** Google Generative AI  
- **Platform:** Google Colab  

---

## 📂 Project Workflow

1. **Collect user input** → Name, demographics, lifestyle, health conditions.
2. **Classify goal** → Weight loss / gain / balanced.
3. **Generate meal plan** → LLM generates Indian diet plan.
4. **Calculate nutrition targets** → BMR & protein goals.
5. **Track meals** → Log daily intake.
6. **Show remaining goals** → Calories & protein left.
7. **Recommend workouts** → Indian home exercise/yoga.

---

## 📊 Example Output

**Sample Goal:** Female, 20, South Indian vegetarian, PCOS, weight loss  
- **Calories Goal:** 1596 kcal  
- **Protein Goal:** 67g  
- **Meal Plan:** South Indian vegetarian plan (Idli Sambar, Brown Rice Sambar, Moong Dal Khichdi)  
- **Exercise Plan:** Yoga & bodyweight workout routine

---
## 📈 Future Improvements
1.Add web & mobile app interface
2.Multi-language support (Hindi, Marathi, etc.)
3.Save & load user profiles
4.Recipe recommendations with nutritional breakdown
5.Integration with fitness tracker

---
