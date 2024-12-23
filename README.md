# AI Dietician Bot
The AI Dietician Bot provides personalized diet plans based on user inputs such as age, gender, weight, height, activity level, and weight goals. It uses the Random Forest algorithm to predict meal recommendations and calorie needs, helping users manage their daily calorie intake and achieve their health and fitness goals.

The bot operates in a Jupyter Notebook environment and interacts with users through text prompts. After collecting user information, the bot calculates the necessary calories, BMI, and weight goals and suggests suitable meals (breakfast, lunch, dinner).

## Features
* **Personalized Diet Plans:** Recommends daily calories and meal plans based on user inputs.
* **BMI Calculation:** Calculates BMI and weight status (underweight, normal, overweight).
* **Meal Suggestions:** Provides meal recommendations (breakfast, lunch, dinner) using a trained Random Forest model.
* **Weight Management:** Helps users achieve their weight goals (gain, lose, maintain) with adjusted calorie recommendations.

## Technologies Used
* **Python 3.x**
* **Jupyter Notebook**
* **pandas, numpy, scikit-learn** for data processing and machine learning

## Installation
1. **Clone the repository**
   
            git clone https://github.com/HarshaliGhumate/AI-Dietician-Bot.git
2. **Install dependencies:**

            pip install pandas numpy scikit-learn
3. **Launch Jupyter Notebook**
   
4. **Open the main.ipynb notebook** and follow the instructions to interact with the bot.

## How It Works
1. **User Inputs:** The bot collects personal details such as age, gender, height, weight, activity level, and weight goal.
2. **Calorie Calculation:** The bot calculates the user’s BMI and estimates their daily calorie needs to maintain, gain, or lose weight.
3. **Meal Suggestions:** Based on calorie requirements, the bot suggests meals using the Random Forest model, trained on the nutritional data in food.csv.

## Datasets
1. **food.csv:** Contains nutritional information for various food items and meal types (breakfast, lunch, dinner).
2. **nutrition_distribution.csv:** Contains categorized nutritional data for meals.

