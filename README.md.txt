# Complaint Classifier

1.Overview

Project allows users to upload police complaint audio files (`.mp3` / `.wav`) automatically transcribes and translates them to English then uses AI to classify the complaint into categories such as Robbery, Assault, Cybercrime etc.

2.Feature

- Upload .mp3audio files.
- Transcribe and translate audio using Whisper.
- Detect complaint category using Zero-Shot Classification.
- Train and export a simple ML algorithm for text data.
- Outputs printed results for further use.



These instructions will help you set up the project on your local machine or Colab.

Install these dependencies to run the project:

| Library       | Version  | Install Command                            |
|---------------|----------|---------------------------------------------|
| `openai-whisper` | latest   | `pip install -U openai-whisper`            |
| `transformers`   | 4.8.0    | `pip install transformers==4.8.0`          |
| `pandas`         | >=1.3.0  | `pip install pandas`                       |
| `scikit-learn`   | >=0.24   | `pip install scikit-learn`                 |
| `joblib`         | any      | `pip install joblib`                       |



3. Workflow

- Open the Colab Notebook Launch the Google Colab .ipynb file provided in the repository.

-Upload Your Audio File
 Upload a .wav or .mp3 file when prompted. This audio will be transcribed and analyzed.

-Run All Cells
 Execute all code cells sequentially. This will:

-Install necessary libraries (whisper, transformers, etc.)

-Transcribe and translate the audio using Whisper

-Classify the complaint using a zero-shot NLP model

Programmer
Your Name : Rohit Kumar Pali
GitHub: @your_username
Email: rohit09pali@gmail.com
