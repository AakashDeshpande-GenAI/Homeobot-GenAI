# Homeobot: A Generative AI Homeopathic Doctor

> A conversational AI agent developed during the Google 5-Day Gen AI Course, designed to simulate a preliminary consultation with a homeopathic doctor.

**Winner of the Completion Certificate in the associated Kaggle competition.**

---

## Table of Contents
* [Problem Statement](#problem-statement)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Setup and Usage](#setup-and-usage)
* [Demo](#demo)
* [Lessons Learned](#lessons-learned)

---

## Problem Statement
Exploring the capabilities of modern Large Language Models (LLMs) to create specialized conversational agents. This project aimed to build a proof-of-concept AI, "Homeobot," that can understand a user's health symptoms in natural language and suggest potential homeopathic remedies based on a knowledge base, simulating an initial-level consultation.

## Features
*   Built using Google's Generative AI models (e.g., Gemini).
*   Prompted with a specific knowledge base of homeopathic principles.
*   Natural Language Understanding (NLU) to interpret user queries.
*   Provides reasoned suggestions for remedies based on the input symptoms.
*   Long context window - Chatting with patients - get symptoms
*   Few-shot prompting - quick remedy suggesion
*   Voice command parser - ask quick remedies
*   Image understanding - Diagnosis by image understanding.
*   Audio understanding - get symptoms/quick remedies in audio format
*   Grounding - latest updates and medicines.
*   Generative AI agent - a chatbot

## Technologies Used
*   Python 3
*   Google AI Generative Language (Gemini API)
*   Pandas for data handling
*   Kaggle Notebooks for development and experimentation
*   Google speechtotext
*   Google texttospeech
*   Langchain
*   Search Grounding
*   Few shot prompting

## Setup and Usage
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Homeobot-GenAI.git
    cd Homeobot-GenAI
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Open and run the notebook:**
    *   The main logic is contained within `notebooks/homeobot_project.ipynb`. Open this in Jupyter Notebook or VS Code.

## Demo
!Homeobot chatboot (images/Homeobot_chatboot.png)

## Lessons Learned
This project was a deep dive into prompt engineering and the practical application of LLMs. A key challenge was ensuring the model's responses were constrained to the provided homeopathic knowledge base to prevent hallucination. This project solidified my understanding of building real-world applications with Generative AI.
