# CONTEXTUAL-AI-CHATBOT

# Instructions

**CONTEXTUAL-AI-CHATBOTBot** is a context based chatbot which provides FAQs based on user as well as page context.

**CONTEXTUAL-AI-CHATBOTBot** is made with simple HTML,CSS and Javascript and Django as a framework. We have also used Chatterbot library (An AI/ML based training library) to train the chatbot so that it can also answer FAQ using chat input box. The API endpoints are made using Django-Rest Framework.

![Django](https://img.shields.io/badge/django%20-%23092E20.svg?&style=for-the-badge&logo=django&logoColor=white) ![HTML5](https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white") ![Javscript](https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![Chatterbot](https://img.shields.io/badge/Chatterbot-1.0.2-blue)


# Features!
  - Contextual Chatbot with NLP processing using Chatterbot library
  - Admin Page to add more FAQs
  - API support for all parts post, get and patch requests.
  - Easy Intergration
  - AJAX implementation


### More About Demo
This is a short gif to show how it is working. As you can see when we moved to Stocks page, it asked questions related to stocks.
So it uses page context and user context (if the user is logged in) to display relevant questions.

The UI is kept simple, as the chatbot functionality was the main focus.
We have also made a panel to edit and make new FAQs which is shown in the full demo.

Also, users can directly type questions in the chatbot and even if the question is not related to the current context, it will answer it, the chatbot is trained on all questions and can answer effectively.

### Installation

Install the dependencies and just start the server. (Then you are ready to run)

NOTE : Requires Python3.7

#### Method:
```sh
$ cd CONTEXTUAL-AI-CHATBOT_chatbot 
$ pip install -r requirements.txt
$ python -m spacy download en
$ python manage.py runserver
```

### Todos
 - Adding A dark theme
 - Improving CSS


License
----

MIT

**You can modilfy it or break it, do whatever you need**
