# NLP_MediBot
This project is a Question-Answering Chatbot with a PyQt5 GUI that uses NLP to provide real-time answers from medical descriptions. It processes text data and returns the most relevant answers to user queries.

LLM_MediBot/
│
├── data/
│   └── medicine_description.csv   # Dataset of medical descriptions
│
├── models/
│   └── chatbot_model.h5           # Trained model
│
├── src/
│   ├── chatbot.py                 # Main chatbot application
│   ├── train.py                   # Training script for the chatbot model
│   ├── preprocess.py              # Data preprocessing
│   └── text_processing.py         # NLP utilities and QA pipeline
│
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation

