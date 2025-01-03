# Text-to-speech
We can change text into speech
# text-to-speech

# README

## Overview
This project uses Python to extract text from a PDF, summarize it with OpenAI's GPT, and convert it to audio. Designed for use in Google Colab.

---


## Steps to Run

### 1. Install Libraries
Install the following libraries:
- `openai`
- `pdfx`
- `langchain`
- `langchain-openai`
- `tiktoken`
- `gTTS`
- `IPython`

### 2. Upload PDF File
Upload your PDF in Colab:
```python
from google.colab import files
uploaded = files.upload()
```


## Output
- **Summary:** Printed in Colab.
- **Audio:** Saved as `output.mp3`.

---

## Notes
- Replace `OPENAI_API_KEY` with your API key.
- Ensure the PDF file is named `Article.pdf`.

---


## Contribution
Fork and submit pull requests for improvements or fixes.
