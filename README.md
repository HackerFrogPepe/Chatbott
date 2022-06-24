# Chatbott
Chatbott README

Projects Aim:
This application was derived out university assessment, to create a chatbot implemented within a django application, this application is far from perfect but was created to show a range of skill sets both learned over time given, having been allocated three weeks to learn django and one week on how to create a basic chatbot not including the troubleshooting that occured.

Technologies used:
Pycharm
Django framework
Djoser framework
Rest framework
Amazon lex
Komunicate.io interface


Launch instructions:
1. Download files in to relevent program; pycharm reccomended
2. In terminal window input 'cd ChatBot'
3. In terminal window input 'python manage.py runserver'
4. access link provided by running the application

Useful endpoints: 
http://127.0.0.1:8000/admin/login/?next=/admin/ (to access admin)
http://127.0.0.1:8000/auth/users/ (to register as new user)


Side Note:
I have left an unimlemented code and tests for a possible lambda hooking function in python, simply put these in amazon lambda and they will output appropriate responses. These were not implemented in the current chatbot due to technical difficulties but prove technical ability when creating lambda functions. I have also attached the AmazonLex bot files in case of any errors that may occur during execution of the program as many libraries are dependent on each other proving that they were created and did work correctly on the AmazonLex service via AWS.



