# Llama 3
Llama 3 is a LLM developed by Meta that comes with open source starter code and pre-trained weights for models with sizes ranging from 8 billion parameters to 70 billion parameters. This makes Llama 3 an accessible option to fine tune for unique functionalities. 

### What is fine tuning?
Fine tuning is further training an existing LLM on more data specific to a functionality. This could mean training on customer service conversations, legal documents, or any other set of documents. A fine tuned model performs better for a specific functionality than its base model, and training uses significantly less computing power. In most cases, a small model can be fine tuned on a laptop. 

### Getting started with Fine Tuning
Before fine tuning, a few dependencies need to be installed. First, create a python virtual environment with these commands:

Mac/Linux:
```bash
python -m venv [environment_name]
source [environment_name]/bin/activate
pip install -r requirements.txt
```

Windows:
```bash
python -m venv [environment_name]
[environment_name]/Scripts/activate
pip install -r requirements.txt
```

Be sure to replace [environment_name] with an appropriate name for your environment. This will install all the dependencies you need. Then navigate to the jupyter notebooks for further instructions.