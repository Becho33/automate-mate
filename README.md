This Project is purly to automate my life
There will be a mix of bot tech. ai and machine learning, 
the goal of this project is to create more time and space for creating a  programming project project

This project will be successful when it can handele all the repetitive tasks of life

task number 1  is create a chat bot that deals with friends, and family in a way that they do not know they are talking to an ai machine

The Dependancies are as follows:

    Python 3.6 or newer. If your operating system does not provide a Python interpreter, you can go to python.org to download an installer.
    
    Flask. We will create a web application that responds to incoming WhatsApp messages with it.
    
    ngrok. We will use this handy utility to connect the Flask application running on your system to a public URL that Twilio can connect to. This is necessary for the development version of the chatbot because your computer is likely behind a router or firewall, so it isn’t directly reachable on the Internet. If you don’t have ngrok it installed, you can download a copy for Windows, MacOS or Linux.
    
    A smartphone with an active phone number and WhatsApp installed.
    
    A Twilio account. If you are new to Twilio create a free account now. You can review the features and limitations of a free Twilio account.
    
    enter the following code to create the virtual enviroment
    
    $ mkdir whatsapp-bot
$ cd whatsapp-bot
$ python3 -m venv whatsapp-bot-venv
$ source whatsapp-bot-venv/bin/activate
(whatsapp-bot-venv) $ pip install twilio flask requests


add bot.py to folder

cheack vertial env is up and running 

launch ngrock

enter url in the settings of twilo with / (name of file, in this case /bot.)
)

and your good to go






