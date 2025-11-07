# 🥗 NutriWell — AI Nutrition Assistant Chatbot

## 📘 Project Overview
**NutriWell** is an AI-powered chatbot designed to provide users with personalized nutritional guidance, healthy meal suggestions, and general wellness advice. Built using **Google Dialogflow**, the chatbot offers an interactive and intelligent platform that promotes healthy eating habits through quick and accessible conversations.

NutriWell helps users:
- Get balanced diet recommendations  
- Understand calorie and nutrient information  
- Receive healthy lifestyle tips  
- Access food-related FAQs  

---

## 💡 Problem Statement
Many individuals struggle to maintain a balanced diet due to limited access to reliable nutritional information or professional guidance. Online resources can be overwhelming or inaccurate.  
**NutriWell** solves this by offering a **conversational AI assistant** that delivers instant, reliable, and easy-to-understand nutrition advice directly through chat.

---

## 🧑‍🤝‍🧑 Target Users
NutriWell is designed for:
- **Students** seeking quick and healthy meal ideas  
- **Fitness enthusiasts** monitoring nutrition and calorie intake  
- **Working professionals** who want time-efficient diet guidance  
- **Anyone** aiming to improve their eating habits and overall wellness  

---

## 🧩 Design and Development
**Platform:** Google Dialogflow  
**Languages Used:** JSON (for intents, entities, and agent configuration)  
**Integration Options:** Web, Telegram, and Google Assistant  

### 🧠 Intents
Below are all the chatbot intents that define NutriWell’s conversational logic:
CardioWorkoutIntent
Default Fallback Intent
Default Welcome Intent
DietPreferenceIntent
ExerciseType Intent
GoalGainMuscleIntent
GoalLoseWeightIntent
GoalMaintainWeightIntent
HIITWorkoutIntent
HydrationTips Intent
keto_diet
MainMenu Intent
nonveg_diet
paleo_diet
RunningWorkoutIntent
ShowMealPlan Intent
SupplementSuggestionIntent
UserAge Intent
UserGender Intent
UserWeight Intent
veg_diet
vegan_diet
YogaWorkoutIntent


### 🧾 Entities
Entities are data categories that help Dialogflow extract key information from user input.  
Below are the main entities used in **NutriWell**:

@diet_type
@exercise_type
@goal
@user_age
@user_weight
@ allergy_type
@ cooking_skill
@ cuisine
@ diet_goal
@ exercise_type
@ food_preference
@ gender
@ ingredient
@ meal_type
@ metric_unit
@Supplements


### ⚙️ System Structure
- **agent.json** — Defines the Dialogflow agent configuration.  
- **intents/** — Contains all chatbot intents and training phrases.  
- **entities/** — Defines recognized data types like diets, goals, and user details.  

---

## 🔄 Fallbacks
NutriWell implements multiple fallback layers:
1. **Default Fallback Intent** — Responds when a query doesn’t match any known intent.  
2. **Clarification Prompts** — Asks users to rephrase unclear inputs.  
3. **Guided Suggestions** — Provides examples of valid nutrition-related questions.  

Example fallback message:
> “I’m sorry, I didn’t quite understand that. Could you please rephrase or ask about a food item or meal plan?”

---

## 🧪 Testing Scenarios
Testing ensured NutriWell responded accurately and naturally:

| Test Case | Expected Behavior | Result |
|------------|------------------|---------|
| Ask for meal plan | Suggests balanced meals | ✅ Successful |
| Unknown food query | Activates fallback | ✅ Successful |
| Multiple consecutive questions | Maintains context | ✅ Successful |
| Switch topic mid-chat | Redirects smoothly | ✅ Successful |

---

## 🚀 Deployment and Integration
NutriWell can be deployed on:
- **Web chat interface**  
- **Telegram Bot**  
- **Google Assistant voice integration**

### Deployment Steps
1. Import `agent.json` into **Dialogflow Console**.  
2. Link all **intents** and **entities** folders.  
3. Test responses in the **Dialogflow simulator**.  
4. Deploy via **Dialogflow integrations** or connect with webhooks.

---

## 🧭 Reflection and Learnings
Through developing NutriWell, the following were key takeaways:
- Deep understanding of **Dialogflow NLP** and entity-intent mapping.  
- Importance of clear **conversation design and user experience (UX)**.  
- Handling **fallbacks and contextual replies** effectively.  
- Combining **AI and nutrition knowledge** to solve real-life health challenges.

---

## 🔮 Future Improvements
Planned enhancements for NutriWell:
- 🧠 **Personalized recommendations** based on user profile.  
- 📊 **Calorie tracker** for daily intake monitoring.  
- 🗣️ **Voice-based conversation** support.  
- 🌍 **Multilingual functionality** for broader access.  
- 📅 **Progress dashboard** to track nutrition goals.

---

## 🧾 Project Details
- **Project Name:** NutriWell  
- **Type:** AI Chatbot (Nutrition & Wellness)  
- **Technology:** Google Dialogflow  
- **Language:** JSON, NLP  
- **Created By:** Shivam Bhuva  
- **Date:** 2025  

## Chatbot Link

[https://bot.dialogflow.com/64abfa3c-15a1-41f2-8552-100203133cb1](https://shivammbhuva.wixsite.com/nutriwell)
