# Multiplayer Battleships Game

A Java-based network implementation of the classic Battleships game, designed for real-time play between two instances over TCP. The application supports both server and client modes, utilizing a custom text-based communication protocol for shot synchronization and move validation.

The application accepts command-line arguments to specify the connection details and fleet layout:

1. Compile the source files and ensure you are in the root directory of the project.
2. Run the application using the following parameters:
   - `-mode [server|client]` – set the operation mode.
   - `-port N` – communication port.
   - `-map map-file` – path to the fleet layout file.
   - `-host hostName` – (client mode only) the server's address.

**Command Example:**
`java game.GameStart -mode server -port 12345 -map map1.txt`

---

*This project was developed as part of the “Programming in Java” course on the 5th semester.*
