# RAG BASED SYSTEM FOR QA BOT 

Description: This Project is based on RAG(Retrieval-Augmented Generation) Technology which aims to retreive the data from an given knowledgebase from an user, So that LLM's can be More generalized on Users
data rather than using its known pretrained knowledge. It aims to Create an QA Bot which is specifically on Custom data without needing to be finetune an LLM Which is an expensive process. It also solves 
the knowledgebase limitation of LLM because each and every data cannot be trained on an LLM so any targeted data of our use can be easily Retreieved-trained and Outputted by our RAG System. 

# Project Setup:

# STEP 1: CLONING THE REPO OR DIRECTLY DOWNLOADING THE .ipynb notebook
```bash
 https://github.com/Priyy08/QA_RAG_System.git
```

# STEP 2: SETTING UP API KEYS:
To run this Project We have to obtain several API Keys from various platforms so these API KEYS are as follows:
   1) HUGGINGFACE API KEY: Make an account on huggingface.co website and after that go to "settings" and select on "Access Tokens" Option, After that create your own API KEY and allow desired permissions.
   2) PINECONE API: Make an account on pinecone.com and setup your index there and then go to API KEYS Section to Get your API Keys.
   3) GROQ API KEY: Make an account on groq cloud and from there go to api keys section and generate an new api key.
Final step: After obtaining all of the keys setup an .env file and set the variables as specified in ipynb notebook code for example for groq api key i have set name as "GROQ_API_KEY" variable in my .env file so
you can change the names of variable according to your needs.

# STEP 3: Installing all required packages:
Download or access the requirements.txt file from repo to know all of the packages reuqired to run this notebook.

# STEP 4: USAGE
This notebook is an demonstration of work of RAG Based System so you can use your own unstructured data to chat with the system. So you have to place your input data into "documents" folders this directory 
structure helps to upload more than one file at once to serve as an knowledgebase of our LLM. Then run all of the cells one by one and make sure all api keys are properly setted up and have properly configured 
in your code.

# STEP 5: RAG Technology Overview and explanation:
If you wish to know further about RAG Technology please refer to this link ```bash https://www.cohesity.com/glossary/retrieval-augmented-generation-rag/ ```

If you have any difficulty regarding any aspects from this project so please feel free to contact me , I will surely help As soon As Possible. Thanks for Visiting This Repo!
