# Gemini-Calorie-Counter-App

Welcome to the Gemini-calorie-Counter-App! This application leverages cutting-edge AI technology to analyze food images and provide detailed nutritional information. 

## Overview

The AI Nutrition App is designed to offer a seamless user experience for obtaining nutritional information from food images. Users can upload an image of their meal, optionally provide a specific prompt, and receive detailed nutritional data, including calorie content.

## Features

- **Image Upload**: Users can upload images of their meals.
- **Prompt Input**: Users can provide specific prompts for detailed nutritional queries (default prompt: "Calculate the amount of calories").
- **AI Analysis**: Utilizes the Gemini 1.5 Pro latest model for backend processing to analyze the food image and provide nutritional information.
- **Streamlit Frontend**: Simple and intuitive user interface built with Streamlit.

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Frontend framework for creating an interactive web application.
- **Gemini 1.5 Pro Model**: AI model for handling backend image processing and nutritional analysis.

## Installation

1. **Rename the `.env_sample` file to `.env` and replace `YOUR_API_KEY` with your Gemini API Key:**
    ```python
    GEMINI_API_KEY = AIzaSyDosA1HuIKOimiYpSrW3Xa5jZQqWFU_Qmw
    ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open the app in your web browser.
2. Upload an image of your meal.
3. (Optional) Enter a specific prompt for the analysis.
4. Click the "Analyze" button.
5. View the nutritional information provided by the app.

## Example Prompts

- "Calculate the amount of calories"
- "How much protein is in this meal?"
- "What is the carbohydrate content?"

