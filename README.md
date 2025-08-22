# FUTURE_CS_03
# Secure File Sharing System

A simple secure file sharing application that allows users to register, log in, upload files with encryption, and download decrypted files securely.

## Features

- User registration and login with JWT authentication
- AES-256-GCM encryption of files before storing on the server
- Decryption of files on download
- File upload and download via a user-friendly web interface

## Setup

1. Clone the repository  
2. Run `npm install` to install dependencies  
3. Create a `.env` file with:  

PORT=3000
AES_SECRET_KEY=your_32_byte_key_here
JWT_SECRET=your_jwt_secret_here
4. Start the server with `node server.js`  
5. Access the app at `http://localhost:3000`

## Usage

- Register a new user  
- Log in to get access  
- Upload files securely (they are encrypted)  
- Download files which are decrypted for you  

## Security

- Files are encrypted on the server with AES-256-GCM  
- JWT tokens protect upload and download endpoints  
- Passwords are hashed using bcrypt  

## License

For educational purposes.

---
