# Network-Based-Pattern-Searching
# 📌 Project Overview

This project demonstrates a client-server network application for searching patterns/words inside a text file. The system is designed with a multithreaded server that handles multiple clients simultaneously. Clients can request the server to search for a word in a given file, and the server responds with the matching lines in JSON format.
# ⚙️ Features

Multithreaded server for handling multiple clients.

Pattern/word search using regular expressions.

Clean preprocessing of text (removes special characters).

Search results returned as structured JSON.

Client-friendly display of line numbers and text.

# 🚀 How It Works

## Client

Sends filename and word to the server.

Receives and displays JSON response.

## Server

Accepts request from client.

Uses Search class to find matching lines.

Converts results to JSON and sends back.

Search Module (search.py)

Reads file content.

Cleans text using regex.

Finds lines containing the word.

# ▶️ How to Run

## Clone repository:

git clone https://github.com/G-Go-p/Network-Based-Pattern-Searching
cd network-pattern-search


## Start the server:

python server.py


## Run the client:

python client.py


Input filename & word → get results.

# 🛠️ Tech Stack

Python (socket, threading, json, regex)

Client-Server Architecture

Text Processing with Regular Expressions

# 📌 Future Enhancements

Support for multiple word searches at once.

Case-sensitive or insensitive search options.

GUI-based client for better user experience.

REST API version using Flask/FastAPI.
