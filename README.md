Question Answering Inference using BERT
A Python-based Question Answering system using HuggingFace's Transformers and Gradio. This project utilizes the pre-trained BERT (deepset/bert-base-cased-squad2) model to extract answers from a given context. It also contains examples of text summarization and OpenAI GPT-based inference.

🔍 Features
Question answering from a custom input context.

Simple and clean user interface built with Gradio.

Uses HuggingFace Transformers (pipeline abstraction).

Examples of:

Web-based text summarization

GPT-3/OpenAI API inference for experimentation

📁 File Structure
bash
Copy
Edit
.
├── Question_Answering_inference_using_BERT.ipynb    # Main QA model notebook
├── OPENAI APIs inference.ipynb                      # GPT-3/OpenAI API experiment
└── Text_summarization_from_web.ipynb                # Web scraping + summarization
🚀 How to Run
🔧 Requirements
Install required dependencies:

bash
Copy
Edit
pip install transformers==4.6.0 gradio beautifulsoup4 requests
You may also need:

bash
Copy
Edit
pip install openai googletrans==3.1.0a0
