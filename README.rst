=========================
Chatbot project using Django Python
=========================

This project is created during my internship at Enqura Information Technologies, Istanbul - Turkey.

It is a web based chatbot project using Python ChatterBot library and Django. 

Documentation
-------------

To start using this app you should follow these steps if you are using PyCharm: 
- Project requires python 3.7. 
- After opening the project in PyCharm, a new interpreter should be created by selecting python 3.7. 
- A new configuration should be added by selecting python from the configuration list. 
-- Inside the script path you should specify: (your project folder name)\django_app\manage.py
-- For parameters you can use: runserver 127.0.0.1:8000, or whatever you like. 
-- As the interpreter your new interpreter should be selected. 
-- For working directory you should select: (your project folder name)\django_app
- Packages specified inside requirements file in django_app folder should be installed. 
- Using terminal run the code: python -m spacy download en_core_web_sm
- Find venv\lib\site-packages\chatterbot\tagging.py folder and change line 13 to self.nlp = spacy.load(self.language.ISO_639_1.lower() + "_core_web_sm")

Your project is ready to run. 
You can run the configuration you added and click the link generated on console. 


.. _Example code found from: https://github.com/gunthercox/ChatterBot
.. _Python ChatterBot documentation: http://chatterbot.readthedocs.io/en/stable/django/index.html
