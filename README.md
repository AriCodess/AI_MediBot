# AI-MediBot

# 🚀 How to run?
### STEPS:

Clone the repository

```bash
git clonehttps://github.com/entbappy/Build-a-Complete-Medical-Chatbot-with-LLMs-LangChain-Pinecone-Flask-AWS.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### 📂 Project Structure

```
.
├── app.py                          # Main Flask application
├── store_index.py                  # Script to store embeddings to Pinecone
├── setup.py                        # Setup configuration
├── requirements.txt                # Python dependencies
├── Dockerfile                      # Docker configuration
├── LICENSE                         # License file
├── README.md                       # Project documentation
├── template.sh                     # Template shell script
│
├── data/                           # Data directory
│   └── Medical_book.pdf            # Medical reference document
│
├── src/                            # Source code directory
│   ├── __init__.py                 # Package initialization
│   ├── helper.py                   # Helper functions
│   └── prompt.py                   # Prompt templates
│
├── templates/                      # Flask HTML templates
│   └── chat.html                   # Chat interface template
│
├── static/                         # Static files
│   └── style.css                   # CSS styling
│
├── research/                       # Research and experimentation
│   └── trials.ipynb                # Jupyter notebook for trials
│
└── .github/                        # GitHub configuration
    └── workflows/
        └── cicd.yaml               # CI/CD workflow
```

### 🛠️ Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone

**Arijeet Dutta**

Email : arijeetdutta501@gmail.com
[LinkedIn](https://www.linkedin.com/in/arijeetd/)



