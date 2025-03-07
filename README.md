# Socket Communication: Client-Server Chat Application

A simple client-server chat application with file transfer capabilities, built using Python and sockets.

---

## Features
- Real-time text messaging between client and server.
- File transfer functionality (e.g., images, documents).
- Graceful connection termination.

---

## Project Contents
- **2 Codes**:
  - `server/main.py`: Server-side code.
  - `client/main.py`: Client-side code.

- **Programming Language**: Python.

- **Libraries Used**:
  - Built-in Python libraries: `socket`, `threading`, `os`, `shutil`.

---

## Server Functions
1. **Send Text**: Send text messages to the client.
2. **Receive Text**: Receive text messages from the client.
3. **Receive File**: Receive files (e.g., images, documents) from the client.

---

## Client Functions
1. **Send Text**: Send text messages to the server.
2. **Receive Text**: Receive text messages from the server.
3. **Send File**: Send files (e.g., images, documents) to the server.

---

## Important Notes
1. **Server Dependency**:
   - The client will not work if the server is not running. Ensure the server is functional before starting the client.

2. **Socket Issues**:
   - If the socket doesn’t close correctly, you may need to change the port number the next time you run the server and client.

3. **File Naming**:
   - When naming the new file during file transfer, include the file extension (e.g., `.jpg`, `.docx`, `.txt`).

4. **Server IP Address**:
   - The client needs to know the server’s private IP address. Replace the empty space between `''` in `client/main.py` with the server’s actual IP address.

5. **File Transfer**:
   - To send a file, type `send_file` in the client. The server will automatically receive the file.

6. **Purpose**:
   - This project is published mainly for **Hack Club** and for others to learn about socket programming in Python.

---

## How to Run

### Prerequisites
- Python 3.x installed on your system.
- Git (optional, for cloning the repository).

---

### Step 1: Clone the Repository
Open a terminal and run the following command to clone the repository:
```bash
git clone https://github.com/Abdo1713/socket-communication-python.git
cd socket-communication-python
