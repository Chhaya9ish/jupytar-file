# jupytar-file
🧮 AI Calculator App using Gemini API
This is a simple AI-powered calculator built in Python using Google's Generative AI (Gemini 1.5 Pro). The app takes user input in natural language, sends it to the Gemini model, and returns a step-by-step explanation of the solution.

🔧 Features
Solve math problems using natural language

Get step-by-step explanations

Easy to use via Jupyter Notebook

Uses google.generativeai with Gemini 1.5 Pro model

▶️ How to Use
Install the Google Generative AI Python package:

bash
Copy
Edit
pip install google-generativeai
Set up your API key:

python
Copy
Edit
my_calcu.configure(api_key = "YOUR_API_KEY")
Run the notebook cells and enter your math problem when prompted.

📌 Example
text
Copy
Edit
Input: 5x + 10 = 30
Output: Solved equation with step-by-step explanation
