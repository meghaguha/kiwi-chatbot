# kiwi-chatbot
The Kiwi-chatbot is a project I made that utilizes Google's DialogFlow to create a seamless food ordering and order tracking experience for users. This project has been developed with the goal of addressing the sometimes hard to navigate food ordering platforms. 

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

run :python -m uvicorn main:app --reload
before executing enter the db_password and root
To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
