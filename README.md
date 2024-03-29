# Simple Socket Communication Project

This project implements a basic client-server communication system using Python's socket library.

## Description

This project includes two Python scripts that demonstrate the fundamental client-server network communication using TCP sockets. The server listens for incoming connections and can respond to client requests, while the client can send commands to the server and display the server's response.

### Dependencies

* Python 3.11.4
* No external libraries are required.

### Installing

No installation is needed. Just clone the repository and run the scripts.

```bash
git clone https://github.com/Rwfroeschl/server.git
cd server
```

## Getting Started

Run the server script  
```python 
python server.py
```
In a separate terminal write and run the client script  
```python 
python client_application.py
```
## Commands

Register User  
```bash
REGISTER <username> <password>
```
Login  
```bash
LOGIN <existing username> <existing password>
```

Who - displays who is registered  
```bash
WHO
```
Message  
```bash
MESSAGE <exisiting user> <message>
```

## Bug

When you message a user it will not show until the corresponding user enters a command.
