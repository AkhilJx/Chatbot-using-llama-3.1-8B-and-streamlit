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

Refer to the langchain official documentation from https://python.langchain.com/docs/integrations/llms/ollama/

1. Install package
   
   %pip install -U langchain-ollama


2. For Linux/ubuntu users try the following code to install Ollama
   
   curl -fsSL https://ollama.com/install.sh | sh

   For other OS, download from: https://ollama.com/download


4. Select the model that we want to download and run the command: ollama pull name-of-model. 
   
![image](https://github.com/user-attachments/assets/7f15974d-cf93-490e-a8b1-5d0f457e4397)

Refer to the GitHub repo: https://github.com/ollama/ollama and the site: https://ollama.com/library for more details

On Mac, the models will be downloaded to ~/.ollama/models

On Linux (or WSL), the models will be stored at /usr/share/ollama/.ollama/models

4. To view all pulled models, use the command # ollama list
  
5. To chat directly with a model from the command line, use the command # ollama run <name-of-model>

6. Run the command # ollama help in the terminal to see available commands too.


A screenshot of the execution of the above steps is as follows:

![Screenshot from 2024-10-23 11-26-49](https://github.com/user-attachments/assets/c3eb01d1-fec5-4f15-974c-729d2d41b0bc)


Once this is done create a virtual environment and install the required libraries from the requirements.txt file

Finally, run the following code from the terminal: streamlit run llama_3.1_8B.py

A screenshot of the output is as shown below:

# Output1:

![Screenshot from 2024-10-24 14-37-53](https://github.com/user-attachments/assets/6db4cbe7-840e-428c-9212-05da144883ec)


# Output2:

![image](https://github.com/user-attachments/assets/2fbef1e0-77ed-49df-9f37-ab3823d1a5a7)


