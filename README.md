PASSWORD GENERATOR AND MANAGER

This software automatically generates password when we give the number of letters, numbers and symbols.
The generated password can be stored in the password vault.
Password vault is a place where all the different types of password that we have entered for different apps having different usernames are stored.
Technologies Used: Tkinter,SQLite,hashlib,cryptography,uuid,pyperclip,random,base64. Algorithm used is SHA(Secure Hashing Algorithm).

Designed and implemented the GUI using Tkinter, allowing users to interact with the application.
Set up an SQLite database to securely store passwords and account information.
Implemented password hashing with SHA-256 using the hashlib library to securely store the master password.
Used the cryptography library (Fernet) for encrypting and decrypting stored passwords.
Generated secure random passwords using the random library based on user-defined criteria.
Integrated clipboard functionality with pyperclip to copy passwords and usernames.
Handled password recovery by generating and using unique recovery keys with the uuid library.
