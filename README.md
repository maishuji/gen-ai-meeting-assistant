# AI-powered Meeting Assistant

## Introduction

This repository builds a generative AI-powered meeting assistant leveraging the capabilities of the Llama 2 large language model (LLM).
App for transcribing and summarizing discussions
- Transcribe the discussions accurately
- Summarize the discussions effectively, highlighting key points and action items

## Learning Objectives
- Create a Python script to generate text using a model from the Hugging Face Hub, identify some key parameters that influence the model's output, and have a basic understanding of how to switch between different LLM models.
- Use OpenAI's Whisper technology to convert lecture recordings into text, accurately.
- Implement IBM Watson's AI to effectively summarize the transcribed lectures and extract key points.
- Create an intuitive and user-friendly interface using Hugging Face Gradio, ensuring ease of use for students and educators.



## Prepare the environment

Create an virtual environment
```shell
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env
```

Install project dependencies
```shell
# installing required libraries in my_env
python -m pip install -r requirements
```

Install `ffmpeg` needed for the project
On linux : 
```shell
sudo apt update
sudo apt install ffmpeg -y
```



## Components 

- Automatic speech recognition (ASR) to convert spoken language into readable text
- Large language models (LLMs) to comprehend and summarize the text efficiently