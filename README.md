# Chatbot-using-llama-3.1-8B-and-streamlit

This is a LLM chatbot that uses Llama 3.1 8B model for processing the results. The Llama 3.1 8B is an open-source LLM Model developed by Meta. The Llama 3.1 is a new state-of-the-art model from Meta available in 8B, 70B, and 405B parameter sizes. we have used the 8B model which is 4.7 Gb in size. 

![image](https://github.com/user-attachments/assets/8d3d47d6-b064-41d1-a29f-add6ec6fdf28)

If we have huge storage and if we need higher accuracy, then we can go ahead with the Llama 3.1 405B model.


![image](https://github.com/user-attachments/assets/359c10e6-2d8a-4d0e-8051-b1ef7c7ce32e)

The size and parameters of various llama 3.1 models are as follows: 

![image](https://github.com/user-attachments/assets/d18fb95d-f8f5-42d6-b18e-a388f44191c4)

![image](https://github.com/user-attachments/assets/cd2e594a-0cb4-400c-aa9a-d985b57fa576)

For the webApp, I have tried the Streamlit app. 

For Loading the llama3.1, I have used ollama under langchain.

# INSTALLATION SETUP OF OLLAMALLM:

refer to the langchain official documentation from https://python.langchain.com/docs/integrations/llms/ollama/

1. Install package
   
   %pip install -U langchain-ollama


2. For Linux/ubuntu users try the following code to install Ollama
   
   curl -fsSL https://ollama.com/install.sh | sh


3. Select the model that we want to download.
   
![image](https://github.com/user-attachments/assets/7f15974d-cf93-490e-a8b1-5d0f457e4397)

Refer to the GitHub repo: https://github.com/ollama/ollama and the site: https://ollama.com/library for more details

