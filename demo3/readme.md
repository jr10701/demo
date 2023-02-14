# Introduction

This is a simple API built using the Representational State Transfer (REST) architecture.

At the moment, this API only handles the GET method.

# Requirement

It is recommended to activate a Python virtual environment.

## Client

The client.py requires the "click" and "requests" libraries.

## Server

The API server requires the "Flask" library.

# Installation

## Client

python -m venv client

source client/bin/activate

To install Flask, run the command "pip install click requests".

Place "publication_cli.py" and "client.py" in the client directory.

## Server

python -m venv server

source server/bin/activate

To install Flask, run the command "pip install Flask".

Place "app.py" and "publications.py" in the server directory.

# Execution

## Client

Please run the command "python client.py"

## Server

Please run the command "python app.py"





