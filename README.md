# Legal Document Key Importance Classifier (LDKIC)

The Legal Document Key Importance Classifier (LDKIC) is a tool designed to analyze legal documents, identifying and classifying sentences based on their importance into categories such as risks, advantages, and ambiguities. Built with Streamlit, PyPDF2, and OpenAI's GPT models, this app provides a user-friendly interface for uploading legal documents and receiving an insightful analysis.

## Features

- **Document Upload:** Allows users to upload legal documents in PDF format.
- **Text Extraction:** Extracts text from uploaded documents using PyPDF2.
- **Document Analysis:** Utilizes OpenAI's powerful GPT models to analyze the text, identifying key sentences and classifying them into categories.
- **Interactive UI:** Streamlit-based interface for easy interaction with the tool.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Python (3.8 or newer)
- pip

### Installation

1. Clone the repository: git clone https://github.com/yourusername/LDKIC.git
2. Navigate to the project directory
3. Install required Python packages: pip install -r requirements.txt




### Usage

To run the app locally, execute the following command in your terminal: streamlit run app.py


Open your web browser and go to `http://localhost:8501` to view the app.

### Configuration

To use the OpenAI API, you need to set your API key. Replace `OPEN_API_KEY` in the `streamlit_app.py` file with your actual OpenAI API key:

```python
OPEN_API_KEY = 'your_api_key'



