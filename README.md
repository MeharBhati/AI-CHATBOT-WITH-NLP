# AI-CHATBOT-WITH-NLP

Company : CODETECH IT SOLUTIONS

Name : Bhati Mehar Mansoor Akhtar

Intern ID : CT04DH2154

Domain : Python

Duration : 4 weeks

Mentor : Neela Santosh

*****************************************************************


**Task 3 – AI Chatbot with Natural Language Processing (NLP)**

In Task 3 of my CODTECH Python internship, I developed an **AI-powered chatbot** capable of understanding and responding to user queries using **Natural Language Processing (NLP)** techniques. The goal was to simulate real-world chatbot applications, such as customer support bots or interactive assistants, where natural and context-aware communication is essential.

The project began with **planning the chatbot’s purpose and scope**. I decided to design a chatbot that could answer frequently asked questions, respond to greetings, and provide relevant information based on predefined intents.

**1. Text Preprocessing**
Since human language can be inconsistent due to variations in spelling, punctuation, and grammar, I first implemented preprocessing steps using **NLTK** (Natural Language Toolkit) and **spaCy**. These steps included:

* **Tokenization** – Splitting sentences into words or tokens.
* **Lowercasing** – Ensuring uniformity by converting all text to lowercase.
* **Stopword Removal** – Removing common words like “is,” “the,” “and” that do not add meaning.
* **Lemmatization** – Converting words to their base form (e.g., “running” → “run”).

This processing ensured the chatbot could better match user inputs with predefined patterns.

**2. Intent Recognition and Pattern Matching**
I defined a set of **intents**, each with example patterns and possible responses. For example:

* *Greeting Intent* → “Hello”, “Hi”, “Good morning” → Response: “Hello! How can I help you today?”
* *Information Intent* → “What is Python?” → Response: “Python is a high-level programming language…”

Using NLTK’s text similarity features and token matching, the chatbot identified the closest intent to the user’s query and selected the most appropriate response.

**3. NLP Model Enhancement**
To improve accuracy, I explored **spaCy**’s language models for better entity recognition (e.g., detecting names, dates, locations). This made the chatbot more adaptable, allowing it to understand specific details in user inputs and respond accordingly.

**4. User Interaction**
The chatbot was built as a Python script running in a command-line interface, where users could type their queries and instantly receive responses. I also integrated **looping and exit commands** so users could have continuous conversations until they typed “bye” or “exit.”

**5. Error Handling and Unknown Queries**
Not every question could be matched perfectly, so I added a default fallback response:

> “I’m sorry, I didn’t understand that. Could you rephrase?”
> This ensured smooth interaction even when the chatbot was unsure of the answer.

**Tools and Technologies Used:**

* **Python** – primary programming language.
* **NLTK** – for tokenization, lemmatization, and stopword removal.
* **spaCy** – for advanced NLP tasks and entity recognition.
* **JSON** – for storing intents, patterns, and responses.
* **Random Module** – for selecting varied responses for the same intent.

By completing this task, I gained practical experience in **natural language understanding, conversational AI, and text preprocessing**. I learned how structured datasets of intents power chatbot logic and how NLP libraries make language interpretation possible.

****Output****





If you want, I can now prepare **Task 4** in the same professional 500-word style so your internship report is fully consistent. Would you like me to proceed?
