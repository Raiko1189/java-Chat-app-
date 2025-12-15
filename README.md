# Java Chat Application (Socket Programming)

A multi-client **Java Chat Application** built using **Java Socket Programming**.  
The project supports **real-time messaging**, **private chats**, **nickname colors**, and both **console-based** and **GUI-based** clients.

---

## 🚀 Features

- Multi-client chat using TCP sockets
- Console-based client
- Swing GUI client
- Real-time message broadcasting
- Private messaging using `@nickname`
- Nickname color change using hex codes
- User list display
- Emoji / smiley support
- Thread-based client handling

---

## 🛠 Technologies Used

- Java SE
- Java Sockets (`ServerSocket`, `Socket`)
- Multithreading
- Swing (GUI)
- I/O Streams

---

## 📁 Project Structure
java-Chat-app/
│
├── Server.java # Chat server (handles multiple clients)
├── Client.java # Console-based client
├── ClientGui.java # GUI-based client (Swing)
├── README.md
└── .gitignore

---

## ⚙️ How It Works

1. The **server** listens on a specific port.
2. Clients connect using a **nickname**.
3. Messages are broadcast to all connected users.
4. Each client runs on a **separate thread**.
5. Special commands are parsed on the server side.

---

## 💬 Chat Commands

| Command | Description |
|-------|------------|
| `@nickname message` | Send a private message |
| `#ff5733` | Change nickname color |
| `:) :D :( ;)` | Supported smileys |
| `↑ / ↓` | Recall previous messages (GUI client) |

---

## ▶️ How to Run

### 1️⃣ Compile the files
```bash
javac Server.java Client.java ClientGui.java
2️⃣ Start the Server
java Server


Server will start on:

Port 12345

3️⃣ Run Console Client
java Client

4️⃣ Run GUI Client
java ClientGui

🖥 GUI Preview

The GUI client provides:

Chat window

Online users list

Message input field

Connect / Disconnect controls

🔐 Networking Details

Protocol: TCP

Host: localhost

Port: 12345

🧠 Learning Outcomes

Socket programming in Java

Client-server architecture

Multithreading

GUI development with Swing

Input/output stream handling

📌 Notes

The server must be running before clients connect.

Multiple clients can connect simultaneously.

This project is intended for learning and academic purposes.

👤 Author

Raiko1189
Java & Backend Development Enthusiast

📄 License

This project is open-source and available under the MIT License.


---

## ✅ Next Steps (Recommended)
If you want, I can also:
- ✔ Improve your project structure (`src/` folders)
- ✔ Add screenshots to README
- ✔ Add a **JAR build guide**
- ✔ Review your code for best practices

Just tell me 👍
