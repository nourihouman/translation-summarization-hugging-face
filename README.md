# Translation and Summarization with hugging face

This project demonstrates text translation and summarization using Hugging Face's `transformers` library. It provides a simple interface to translate text between different languages and summarize large texts into shorter, concise versions.

## Project Structure

- `translation with hugging face.py`: The main script containing functions for translation and summarization.
- `requirements.txt`: A file listing the required Python libraries.

## Setup Instructions

### Prerequisites

- Python 3.6 or higher
- Git
- pip (Python package installer)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/nourihouman/translation-summarization-hugging-face.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd translation-summarization-hugging-face
    ```

3. **Create a virtual environment (optional but recommended)**:

    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use `env\Scripts\activate`
    ```

4. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```


## Models Used
Translation Model: facebook/nllb-200-distilled-600M
Summarization Model: facebook/bart-large-cnn

## Usage

### Translation

The `translate_text` function translates text from one language to another using the specified source and target language codes.

**Example:**

```python
from main import translate_text

source_lang = "eng_Latn"  # English
target_lang = "pes_Arab"  # Persian

