# Blog Generator using Streamlit and Langchain using LLAMA2
## Overview:
This code snippet demonstrates how to use Streamlit, a popular Python library for building web applications, along with Langchain, a library for natural language processing tasks, to generate blogs based on user input.

## Technologies Used:
#### Streamlit: Used for creating the web interface and handling user inputs.
#### Langchain: Specifically, the CTransformers class for interacting with the llama2 model for generating blog content based on prompts.
## How It Works:
#### Input: Users provide a blog topic, the desired number of words, and select a style for the blog (e.g., Researchers, Data Scientists, Common People).
#### Prompt Template: A prompt template is constructed based on the user's input. This template is used to guide the llama2 model in generating the blog content.
#### Model Generation: The llama2 model is used to generate blog content based on the provided prompt.
#### Output: The generated blog content is displayed to the user using Streamlit.

## Usage:

### Install the necessary libraries using pip:
```bash
pip install -r requirements.txt
```
### Run the Streamlit app:

```bash
streamlit run app.py
```
Enter the blog topic, select the style, and specify the number of words for the blog.

Click the "Generate" button to generate the blog content.

## Note:
Downlaod The LLAMA2 model https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
