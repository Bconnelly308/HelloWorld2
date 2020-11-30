# HelloWorld2
Assignment for Software Architect and Design - Fall 2 2020

> In this lab, you will develop a simple Hello World Django app. The app consists of one route and returns a JSON object with Hello World message. Response JSON should look like below:\
\
> {“Message”: “Hello World!”}\
\
> Create a git repo in GitHub, and push your entire Django project directory into GitHub, also, make sure to include a README file describing how to run/start your webapp and how to access the Hello World JSON response in a browser.
\
## How to Run in Linux
- Open the terminal
- Make a directory for the project ```mkdir lab5test```
- Go to directory ```cd lab5test```
- Clone the repository ```git clone https://github.com/Bconnelly308/HelloWorld2.git```
-View the current directory ```pwd```
- Create a virtual environment ```python3 -m venv *insert pwd result*```
- Activate the virtual environment ```source venv/bin/activate```
- Install Django ```pip install django```
- Change your directory ```cd HelloWorld2/helloworld ```
- To Run ```python manage.py runserver```
- Open Browser, and enter ```http://localhost:8000/hello/```
