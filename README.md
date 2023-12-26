# Trust-Bank-Customer-Support-ChatBot-Using-Llama-2

Generative AI Hackathon Project (LLMs)

![Alt text](<AI Hackathon Work Flow.png>)

## Steps To Run The Project

## Steps

### 1. Clone the repository

```bash
git clone https://github.com/Mohammedashkan/Trust-Bank-Customer-Support-ChatBot-Using-Llama-2.git
```

### 2. Create a conda environment after opening the repository

```bash
conda create -n csupportchatbot python=3.11 -y
```

Activate the environment using this command in your terminal or cmd :
Activate the environment:

```bash
conda activate csupportchatbot
```

Install all required packages by running:

```bash
pip install -r requirments.text
```

To train the model, run the following code in your terminal or cmd after you have installed all necessary libraries and dependencies:

### 3. Create a .env file in the root directory and add your Pinecone credentials as follows

```bash
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### 4. Download the quantize model from the link provided in model folder & keep the model in the model directory

```bash
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin
```

```bash
## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

### 5. run the following command

```bash
python store_index.py
```

### 6. Finally run the following command

```bash
python app.py
```

### 7. Open up the Localhost

```bash
localhost 8080
```

### Used Tech Stack

```bash
Python
LangChain
Flask
Meta Llama2
Pinecone
```
