Code Generator using LLM

An intelligent AI-powered Code Generator that converts natural language instructions into executable code using Large Language Models (LLMs).

This project demonstrates how LLMs can assist developers by automatically generating clean, structured, and context-aware code snippets from plain English prompts.

 Project Overview

The AI Code Generator takes a user’s natural language request like:

“Write a Python function to check if a number is prime”

and generates:

Well-structured code

Proper indentation

Comments (if needed)

Clean logic implementation

This project showcases:

Prompt engineering

LLM API integration

Model inference pipeline

Practical AI for developer productivity

 How It Works

User enters a natural language instruction.

The system sends the prompt to an LLM.

The LLM generates code.

The output is displayed in a formatted block.

 Tech Stack

Python

Jupyter Notebook

OpenAI / LLM API

Prompt Engineering

API Integration

(Optional) Streamlit / Gradio for UI

 Project Structure
code_generator.ipynb     # Main notebook
README.md                # Project documentation
requirements.txt         # Dependencies


 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/code-generator.git
cd code-generator
2️⃣ Install Dependencies
pip install -r requirements.txt

If using manually:

pip install openai python-dotenv
3️⃣ Set Up API Key

Create a .env file:

OPENAI_API_KEY=your_api_key_here

Or set directly:

import os
os.environ["OPENAI_API_KEY"] = "your_api_key_here"
 Usage

Run the notebook:

jupyter notebook

Open code_generator.ipynb and execute cells.

Example prompt:

"Generate a Python function to sort a list using merge sort"

Output:

def merge_sort(arr):
    ...
 Features

 Natural language → Code generation
 Clean formatting
 Supports multiple programming languages
 Customizable prompts
 Extendable for UI deployment

 Real-World Applications

Developer productivity tools

Coding assistants

Educational platforms

Automated boilerplate generation

API scaffolding tools

Interview preparation helpers

 Future Improvements

Add Streamlit web interface

Add syntax highlighting

Add multi-language support (Python, Java, C++)

Add code explanation mode

Add debugging mode

Add test case generation

 Skills Demonstrated

Large Language Model integration

Prompt Engineering

API handling

Practical AI system building

Notebook-to-production workflow

 Author

Amisha Singh
Aspiring AI/ML Engineer & SDE
GitHub: https://github.com/AmishaSingh0408
