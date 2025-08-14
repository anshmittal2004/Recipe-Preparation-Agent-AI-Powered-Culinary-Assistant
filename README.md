🍳 Recipe Preparation Agent
The Recipe Preparation Agent is an innovative AI-powered culinary assistant developed as part of an IBM internship project. Built using IBM Watsonx AI Studio and the Granite-3-3-8b-instruct model with Retrieval-Augmented Generation (RAG), this solution transforms available ingredients into personalized, step-by-step recipes. It minimizes food waste, accommodates dietary preferences, and provides practical cooking tips, making it a valuable tool for home cooks and professionals alike.

🌟 Project Overview
This repository contains the codebase and documentation for a smart recipe prediction model trained on the Cleaned_Indian_Food_Dataset.csv. Leveraging advanced NLP and machine learning techniques, the agent delivers real-time, accurate recipe suggestions, validated with 90% training accuracy and 3-fold cross-validation. The project demonstrates end-to-end AI development, from data preprocessing to model deployment, and is hosted on IBM Cloud Lite.

🔑 Key Features

Dynamic Recipe Generation: Creates recipes based on user-provided ingredients.
Custom Instructions: Offers clear, step-by-step cooking guides with substitutions for missing ingredients.
Dietary Flexibility: Adapts to vegetarian, vegan, gluten-free, or other preferences.
Accuracy Optimization: Utilizes cross-validation and tuned model parameters for reliable predictions.
User-Friendly Tips: Includes cooking hacks and time-saving methods.
Scalable Design: Built for integration with Watsonx Runtime and future enhancements.


🛠 Technical Stack

Platform: IBM Watsonx AI Studio, IBM Cloud Lite
Model: Granite-3-3-8b-instruct (Foundation Model)
Technologies: Retrieval-Augmented Generation (RAG), Natural Language Processing (NLP), Prompt Engineering
Programming: Python 3.11 (Jupyter Notebook)
Data: Cleaned_Indian_Food_Dataset.csv (11.19 MB, 9 columns)
Dependencies: LangChain, IBM Watsonx API, Object Storage


🚀 Getting Started
Prerequisites

Git installed on your system
IBM Watsonx AI Studio account
Python 3.11 environment
Access to IBM Cloud Lite

Installation

Clone the repository:git clone https://github.com/your-username/Recipe-Preparation-Agent.git
cd Recipe-Preparation-Agent


Install dependencies:pip install -r requirements.txt

(Note: Create a requirements.txt file with dependencies like langchain, ibm-watsonx-ai, etc., if not already present.)
Set up IBM Watsonx credentials in Recipe Agent.ipynb (follow the notebook instructions).

Usage

Launch Jupyter Notebook:jupyter notebook


Open Recipe Agent.ipynb and execute the cells.
Input ingredients and preferences to generate recipes.


📊 Performance Metrics

Accuracy: 90% on training data with 10% holdout validation.
Cross-Validation: 3-fold validation for robust generalization.
Build Time: Preprocessing and model selection optimized (e.g., 68 seconds).


📋 Sample Interaction
Input:  

Ingredients: rice, tomato, onion, green chili  
Preference: vegetarian

Output:Recipe: Spicy Tomato Fried RiceInstructions:  

Heat 2 tbsp oil in a pan over medium heat.  
Add chopped onions and sauté until golden brown.  
Add diced tomatoes and green chilies, cooking until soft.  
Stir in cooked rice, salt, and spices; mix well for 5 minutes.  
Serve hot with a side of yogurt.Tip: Use pre-cooked rice to save time.


🌱 Future Enhancements

Multilingual Support: Extend to multiple languages.
Voice Interface: Integrate voice-enabled interactions.
Nutrition Analysis: Add calorie and nutrient tracking.
Meal Planning: Generate weekly plans with grocery lists.


🎓 Achievements

Certifications: IBM SkillsBuild (Getting Started with AI), LangChain RAG
Internship Milestone: Successfully deployed an AI solution at IBM, completed as of August 14, 2025.


🤝 Contributing
Contributions are welcome! Please fork the repository and submit pull requests with enhancements or bug fixes. For major changes, open an issue first to discuss.

📧 Contact
Developed by Ansh Mittal.

📜 License
This project is licensed under the ILAN License by IBM.
