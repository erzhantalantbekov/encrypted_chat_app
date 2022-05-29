# encrypted_chat_app
The python chat creation is done using pyqt5 python and has a graphical interface. This project is implemented entirely in python using sockets, and the following modules: pyqt5, socket, rsa, and many others


This project is fully implemented in Python using asymmetric RSA encryption and is built on the Socket module with the generation of authentication files. Each node connects ONLY using the key file of the other node, which is generated in advance and transmitted between the chat participants. The entire process of correspondence is not saved on the computer and will be cleared after the program ends, since it is stored only in RAM.

The server is used only for transferring data between participants, while it is impossible to decrypt your messages on the server side. And yes, the server-client model is completely TCP-based.
