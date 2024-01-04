# LLAMA2-Medical-Chatbot
This is a medical bot built using Llama2 and Sentence Transformers. The bot is powered by Langchain and Chainlit. The bot runs on a decent CPU machine with a minimum of 16GB of RAM.


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/SunilKumar-ugra/LLAMA2-Medical-Chatbot.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medi_bot python=3.8 -y
```

```bash
conda activate medi_bot
```


### STEP 02- Install the requirements
```bash
pip install -r requirements.txt
```
### STEP 03- Download the model
```
goto https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin
and Download it
```
### STEP 04- Run the command    
```bash 
# Finally run the following command
python data_ingest.py 
chainlit run medi_bot.py -w
```

Now,
```bash
http://localhost:8000 #Open this url in the browser
```

# Demo
https://github.com/SunilKumar-ugra/LLAMA2-Medical-Chatbot/assets/45965583/268f2934-2f80-4829-a120-6b6b3502f990



