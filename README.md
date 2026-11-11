# NLP Machine Translation

**Name:** Noah C Frami  
**Date:** 11/11/2026

## Project Description

This project uses Python to compare translations from Google Cloud Translation and DeepL. The program takes a sentence, translates it into another language using both services, and displays the results side by side.

The goal is to see how accurate and natural the translations are and identify any mistakes.

## Project Files

- `main.py` - Runs the translation program.
- `translator.py` - Connects to the translation APIs.
- `test_cases.json` - Contains 10 sentences used for testing.
- `README.md` - Explains the project and how to use it.
- `requirements.txt` - Lists the required Python libraries.
- `.env.example` - Shows which API credentials are needed.

## Setup Instructions

1. Download or clone the project from GitHub.
2. Open the project folder in PyCharm.
3. Install the required libraries by running:

   `pip install -r requirements.txt`

4. Find the `.env.example` file and make a copy named `.env`.
5. **IMPORTANT: Open the `.env` file and enter your own Google Cloud Translation and DeepL API credentials before running the program.**
6. Save the `.env` file.
7. Run the program using:

   `python main.py`

**Note:** The program will not be able to use the translation services without valid API credentials. Never upload your `.env` file or private API keys to GitHub.

## How the Program Works

The program sends the same sentence to Google Cloud Translation and DeepL. It then displays both translations so they can be compared.

The project also includes 10 test cases with different types of sentences, including simple sentences, longer sentences, idioms, pronouns, and technical vocabulary.

## Translation Evaluation

Each translation is evaluated using two categories:

**Adequacy:** How well the translation keeps the original meaning.

**Fluency:** How natural and grammatically correct the translation sounds.

Both categories use a rating scale from 1 to 5:

- 1 = Poor
- 2 = Weak
- 3 = Acceptable
- 4 = Good
- 5 = Excellent

The results help determine which translation service performs better.

## Error Analysis

Some translation errors can include incorrect meanings, awkward wording, missing information, and problems translating idioms.

Comparing the results helps show where each translation service performs well and where it struggles.

## Reflection

### What I Learned

I learned how to use Python to connect to translation APIs and compare results from different services. I also learned about adequacy and fluency and why both are important when evaluating translations. Just because a translation sounds correct does not always mean it keeps the original meaning.

### What Was Challenging

The most challenging part was setting up the API keys and getting the translation services connected to Python. It was also challenging to compare translations because sometimes both services give different answers that are still correct. This project helped me better understand how machine translation works and why it is not always perfect.
