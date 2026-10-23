
# 💬 Chat Application Using C

A client-server chat application developed in C that demonstrates the fundamentals of network communication and message exchange between connected users.

The project explores how a client establishes a connection with a server and communicates through a structured networking workflow.

## 🎯 Project Objectives

- Understand client-server architecture.
- Learn how network communication works in C.
- Implement message exchange between a client and server.
- Explore socket programming and network connections.
- Practise writing, compiling, testing, and debugging C programs.

## ✨ Features

- Client-server communication.
- Message sending and receiving.
- Network connection between client and server.
- Command-line interaction.
- Lightweight implementation using C.
- Separate client and server components, if implemented.

## 🛠️ Technologies Used

- **Programming Language:** C
- **Networking:** Socket Programming (if implemented)
- **Communication Protocol:** TCP or UDP, depending on the code
- **Compiler:** GCC or another compatible C compiler
- **Development Tools:** VS Code, Git, GitHub

## ⚙️ How It Works

1. The server starts and waits for a client connection.
2. The client initiates a connection to the server.
3. The server accepts the connection, if supported.
4. The client sends a message through the connection.
5. The server receives and processes the message.
6. The response is returned to the client, if implemented.
7. The communication continues until the connection is closed.

## 🔄 Application Workflow

`Client → Socket Connection → Server → Message Processing → Response`

## 📁 Project Structure

```text
Chat-application-using-C/
├── client.c       # Client-side logic (if present)
├── server.c       # Server-side logic (if present)
├── main.c         # Main program (if present)
└── README.md      # Project documentation
```

*Adjust the filenames above to match your repository.*

## ▶️ How to Run the Project

### Prerequisites
- A C compiler such as GCC.
- Git installed on your system.
- A terminal or command prompt.

### 1. Clone the Repository

```bash
git clone https://github.com/mansi99100/Chat-application-using-C.git
cd Chat-application-using-C
```

### 2. Compile the Program

For a single-file program:

```bash
gcc main.c -o chat
```

### 3. Run the Program

On Windows:

```bash
chat.exe
```

On Linux/macOS:

```bash
./chat
```

If your project contains separate client and server files, compile and run them separately according to your implementation. Socket-based programs may also require platform-specific networking libraries.

## ⌨️ Keyboard Shortcuts

No custom keyboard shortcuts are documented. Standard terminal shortcuts can be used where supported.

## 📚 What I Learned

- Fundamentals of C programming.
- Understanding client-server architecture.
- Basics of network communication.
- Working with input, output, and message handling.
- Compiling and debugging C programs.
- Understanding how applications communicate over a network.

## 🚀 Future Improvements

- Support multiple simultaneous clients.
- Improve connection and error handling.
- Add usernames and user identification.
- Introduce private messaging, if not already implemented.
- Add timestamps and chat history.
- Improve message validation and security.
- Create a graphical user interface.

## 🧪 Sample Interaction

The following is an illustrative example of a text-based chat session.

```text
Chat Application
----------------
Enter your message: Hello!
Message sent: Hello!

Received message: Hi there!
Connection closed.
```



## 👩‍💻 Author

**Mansi Rawat**




