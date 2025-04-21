# ChatBot
This project uses the Mistral API to create a conversational agent. Below is an overview of how to set up and use the code provided in this repository.

## Configuration

1. **Installation of Mistral Package**:
   ```python
   !pip install mistralai
   ```
   This section installs the Mistral package, which is necessary for interacting with the Mistral API.

2. **API Key Retrieval**:
   ```python
   from mistralai import Mistral
   from google.colab import userdata

   # Retrieve the API key from Google Colab's secret section
   api_key = userdata.get('Mistral_API_key')
   ```
   The API key is securely retrieved from Google Colab's secret management.

3. **Model Initialization**:
   ```python
   model = "mistral-small-latest"
   client = Mistral(api_key=api_key)
   ```
   The model to be used for the chatbot is defined and the Mistral client is initialized.

## Getting Started

1. Open the notebook using the link below:
   [Open In Colab](https://colab.research.google.com/github/PlayfulDevBit/ChatBot/blob/main/ChatBot.ipynb)

2. Make sure to replace the placeholder for the API key with your own Mistral API key in the Google Colab secret management.

3. Run the notebook cells to install the necessary packages, initialize the chatbot, and start chatting
