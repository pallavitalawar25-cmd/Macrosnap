# 🥗 MacroSnap

MacroSnap is an AI-powered nutrition assistant that helps users estimate calories and macronutrients from meal descriptions and meal photos.

## Features

- 🥗 AI nutrition assistant
- 💬 Text-based meal analysis
- 📸 Meal image analysis using Gemini
- 📊 Calorie and macronutrient estimation
- 📱 WhatsApp integration using Twilio
- 🧑‍🍳 Simple Streamlit interface

## Tech Stack

- Python
- Streamlit
- Google Gemini
- Twilio WhatsApp API

## How It Works

1. User enters their name and WhatsApp number.
2. User describes a meal or uploads a meal photo.
3. Gemini analyzes the meal.
4. MacroSnap provides estimated calories and macronutrients.
5. The application includes WhatsApp summary functionality through Twilio.

## Setup

Create a virtual environment and install dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
