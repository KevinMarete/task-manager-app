# TASK MANAGER APP

Task Manager App is built using Frontend(React) and Backend(FastAPI, MongoDB).

---

## Requirements

For development, you will only need Python 3.5+, NodeJs and a python global package such as pip, installed in your environment. Follow this guide on [Youtube](https://www.youtube.com/watch?v=OzUzrs8uJl8).

## Install

Follow this guide to install [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/) on Mac

    $ git clone https://github.com/KevinMarete/task-manager-app
    $ cd task-manager-app

## Running the Backend

    $ cd backend
    $ python3 -m venv task-manager-venv
    $ . task-manager-venv/bin/activate
    $ pip install -r requirements.txt
    $ uvicorn main:app --reload

## Running the Frontend

    $ cd frontend
    $ npm start

## Building the Frontend

    $ cd frontend
    $ npm run build