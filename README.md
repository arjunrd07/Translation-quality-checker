# Translation Quality Checker
# Overview
The Translation Quality Checker is an advanced machine translation quality assessment tool. It evaluates translations using a variety of metrics, including BLEU, ROUGE, METEOR, Levenshtein Distance, Cosine Similarity, and Sentence Embedding Similarity. This project uses state-of-the-art models like Helsinki-NLP for machine translation and SentenceTransformer for semantic analysis.

The tool is designed for researchers, linguists, and AI developers to evaluate and improve machine-generated translations effectively.

# Features
Translation of text using Helsinki-NLP models.
Back-translation for quality assessment.
Evaluation metrics:
BLEU: Measures n-gram overlap between reference and candidate translations.
ROUGE: Assesses recall-based overlap.
METEOR: Evaluates precision, recall, and alignment.
Levenshtein Distance: Quantifies edit distance.
Cosine Similarity: Compares TF-IDF vectors of sentences.
Sentence Embedding Similarity: Uses SBERT for semantic similarity.
# Project Structure
bash
Copy code
translation-quality-checker/
├── code/
│   ├── main.py                    # Main Gradio interface
│   ├── requirements.txt           # Python dependencies
│   ├── InstallationGuide.txt      # Setup instructions
├── docs/
│   ├── Presentation.pptx          # Project presentation
├── README.md                      # Project overview (this file)
# Getting Started
# Prerequisites
Python 3.8 or later
Git installed
Visual Studio Code (optional)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/YourUsername/translation-quality-checker.git
cd translation-quality-checker
Create a virtual environment and activate it:

bash
Copy code
python -m venv env
source env/bin/activate  # For Linux/macOS
env\Scripts\activate     # For Windows
Install dependencies:

bash
Copy code
pip install -r requirements.txt
# Usage
Running the Application
Navigate to the code/ directory.
Launch the Gradio interface:
bash
Copy code
python main.py
Open the link provided in the terminal to interact with the application.
Metrics Explained
BLEU (Bilingual Evaluation Understudy)
Measures n-gram overlap between generated and reference translations. A higher score indicates better translation quality.

ROUGE (Recall-Oriented Understudy for Gisting Evaluation)
Evaluates overlap between reference and candidate translations based on recall.

METEOR (Metric for Evaluation of Translation with Explicit ORdering)
Calculates precision, recall, and alignment for translation quality.

Levenshtein Distance
Measures the number of edits (insertions, deletions, substitutions) needed to transform one text into another.

Cosine Similarity
Quantifies similarity between text TF-IDF vectors.

Sentence Embedding Similarity
Uses SBERT (Sentence BERT) to compute semantic similarity.

Why Helsinki-NLP?
Helsinki-NLP offers specialized models for a wide range of languages, optimized for translation tasks, and is highly customizable. It outperforms generic translation APIs like Google Translate or Amazon Translate for research purposes.

# Future Enhancements
Develop a more advanced weight adjustment system using data analytics.
Extend support for additional metrics like TER (Translation Edit Rate).
Improve the interface for a smoother user experience.
Integrate a feedback loop for continuous model improvement.
Motivation
This project aims to address the growing need for reliable translation quality assessment in AI. With the rise of multilingual applications, ensuring translation accuracy is critical for user engagement and cultural sensitivity.

Acknowledgments
We would like to thank the following:

The Panel: For their valuable feedback and suggestions during the project evaluation.
Our Mentors: For their continuous guidance and support.
The Open-Source Community: For providing powerful libraries and tools.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have any questions or suggestions, feel free to contact:

Name: R.Mallikarjun Reddy
Email: pbox37@yahoo.com
GitHub: arjunrd07
