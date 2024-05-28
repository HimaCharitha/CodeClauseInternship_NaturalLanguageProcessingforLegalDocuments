# CodeClauseInternship_Natural-Language-Processing-for-Legal-Documents
## Legal Document Summarizer

![Description of the GIF](https://github.com/HimaCharitha/CodeClauseInternship_NaturalLanguageProcessingforLegalDocuments/blob/main/nlp.gif)

## Aim
Develop an AI system that can extract and summarize key legal information from complex legal documents.

## Description
This project implements advanced Natural Language Processing (NLP) techniques to process and understand legal language, identify key clauses, and generate concise summaries. The system leverages Python, SpaCy, NLTK, and Transformer models to achieve this.

## Technologies
- Python
- SpaCy
- NLTK
- Transformers (Hugging Face)
- Pandas

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/legal-document-summarizer.git
    cd legal-document-summarizer
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Place your legal documents in the `data` directory.

2. Run the script to extract and summarize legal information:
    ```sh
    python main.py --input data/legal_document.txt --output summaries/summary.txt
    ```

## Project Structure

legal-document-summarizer/
│
├── data/
│ └── legal_document.txt # Example legal document
│
├── models/
│ └── summarizer_model/ # Directory for the Transformer summarization model
│
├── notebooks/
│ └── exploration.ipynb # Jupyter notebook for initial data exploration and model development
│
├── src/
│ ├── main.py # Main script to run the extraction and summarization
│ ├── extract.py # Module for clause extraction
│ ├── summarize.py # Module for summarization
│ └── utils.py # Utility functions
│
├── summaries/
│ └── summary.txt # Output directory for summaries
│
├── README.md # This file
├── requirements.txt # List of dependencies
└── .gitignore # Git ignore file

## Example
To extract and summarize key information from a legal document, run:
```sh```
python src/main.py --input data/legal_document.txt --output summaries/summary.txt
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

### `requirements.txt`
Add a `requirements.txt` file for the necessary Python packages:
- spacy
- nltk
- transformers
- pandas
