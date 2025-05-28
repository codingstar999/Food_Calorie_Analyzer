# 🍔 Food Calorie Analyzer using Google Gemini API and Huggingface opensource model

This project uses the power of **Google's Gemini Vision API** to analyze food images and estimate the total calorie count. Upload any image containing food, and the script will identify the items and return an approximate calorie value based on a local lookup.

---


https://github.com/user-attachments/assets/c35425bc-4b83-4fe1-8990-cff06c4ca6eb


## 🚀 Features

- 🔍 Detect food items from images using Google Gemini (multimodal vision model)
- 🔢 Estimate calories based on a built-in food-to-calorie mapping
- 🖼️ Works with real-world food photos (single or multiple items)
- 💡 Lightweight CLI tool for personal or research use
- 🛠️ Easy to expand with your own calorie dataset or use case

---

## 🧠 How It Works

1. You provide an image (`.jpg`, `.png`, etc.)
2. The script sends the image and a prompt to the Gemini API
3. Gemini returns a list of recognized food items
4. The script looks up each item in a predefined JSON calorie map
5. It prints the breakdown and total estimated calories

---

## 🧰 Requirements

- Python 3.8+
- Google API Key for Gemini
- `google-generativeai`, `Pillow`, `dotenv`

---

## 🔧 Setup

```bash
git clone https://github.com/codingstar999/Food_Calorie_Analyzer.git
cd Food_Calorie_Analyzer
pip install -r requirements.txt
