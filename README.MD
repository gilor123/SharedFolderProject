# Shared Folder Project 
Author: Gil Or

Date: 30/11/2022

### BACKGROUND
This project was made as part of Computer Networking course in the Open University of Israel

### OVERVIEW
The project is a Python based shared folder implemented using computer networking.
The server holds the single source of truth and all clients are mirroring the original folder in their local device.
Updates from the client are being sent to the server, then the server updates the original folder and sends the update for all other clients.

### INSTALLATION  
1. **Download** the packaged project and extract it to your local CPU
2. **Run** the following command from the folder of this project to install all dependencies:
```$ pip install -r requirements.txt```
3. **Open** the terminal from the project's folder and run the server by enter this command: ```python server.py``` 
   1. **Enter** the full path of your desired local shared folder
4. **Open** the terminal from the project's folder and run the server: ```python client.py```
   1. **Enter** the full path of your client's instance of the local shared folder
5. Redo 4 to create as many clients as you wish.
6. Make any change in the clients, and see how the server and the others client are being synchronized 
