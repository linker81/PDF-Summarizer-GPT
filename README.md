# PDF-Summarizer-GPT
A simple Proof of Concept to summarize a PDF file using OpenAI APIs.

For each page of the PDF file, this script summarizes the page using some sentences. 

- Set the Environment Variable OPENAI_API_KEY to your OpenAI API key
- Launch the Notebook setting the value of filename variable with the complete path of the PDF file

The script does not work applied to PDF that requires the OCR.

The following parameters modify the behavior of the script:
- max_dim: maximum number of words (similar to tokens) that are considered in the source text.
- max_sentences: maximum number of sentences to use to summarize a page
- temperature: temperature parameter 

An interesting course on ChatGPT Prompt Engineering is:
https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/
