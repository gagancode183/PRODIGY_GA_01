🤖 Task 01 – Text Generation with GPT-2
Internship Track: Generative AI
Repo Name: PRODIGY_GA_01

This project demonstrates how to use OpenAI's GPT-2 language model to generate coherent text from a prompt using Gradio for the frontend and Hugging Face Transformers for model handling. The model is pre-trained and fine-tuned in a lightweight manner to create an interactive text generation app.

📁 Files Included
GPT2_Text_Generation.ipynb – Google Colab Notebook

README.md – Project documentation

🧠 What I Learned
✅ Tokenizing input text using GPT-2's tokenizer

✅ Generating high-quality output using beam search decoding

✅ Creating an interactive web interface using Gradio

✅ Understanding how to use and fine-tune GPT-2 with the Hugging Face Transformers library

✅ Deploying a small-scale language model generation demo

🔧 Tools & Libraries
Python

TensorFlow & TFGPT2LMHeadModel (Hugging Face)

Gradio – for building the frontend UI

Google Colab – for easy GPU-based execution

▶️ How to Run
Open the notebook in Google Colab

Install dependencies using the first two code cells:

bash
Copy
Edit
!pip install gradio --quiet  
!pip install transformers --quiet
Modify the prompt text inside the input box when the Gradio app launches.

The model will generate coherent text from your input using beam search.

🌐 Interface Preview
Input: Natural language prompt

Output: GPT-2 generated text (up to 100 tokens)

Frontend: Powered by Gradio in browser

🧪 Model Details
Model: gpt2 from Hugging Face 🤗

Generation Strategy: Beam Search

num_beams = 5

no_repeat_ngram_size = 2

max_length = 100

📌 Completed As Part Of
Prodigy InfoTech – Generative AI Internship
📅 July–August 2025
📍 #ProdigyInfoTech #GenerativeAI #GPT2 #AIInternship #TextGeneration


