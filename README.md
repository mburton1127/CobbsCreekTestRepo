## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.


Instructions for installing a Python Virtual Environment on a fresh linux machine:
(assuming your version of linux is up-to-date)

1) Open the terminal
2) Install Python, type 'python3' or 'pip3'
3) Create the virtual environment, type 'python3 -m venv venv'
4) Activate the virtual environment, type 'source venv/bin/activate'
5) Install dependencies, type 'pip install .'
6) Run the application, type 'uvicorn main:app --host 0.0.0.0 --port 8000'
7) Access the application via LAN IP, type the IP address into a web browser (ex. http://192.168.1.42:8000)

Repo Link: https://github.com/mburton1127/CobbsCreekTestRepo