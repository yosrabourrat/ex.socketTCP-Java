# 🔌 Projet Java – TCP Echo Client/Server

Ce projet implémente une communication client/serveur en Java en utilisant des **sockets TCP**.

## 🧠 Fonctionnement
- Le **serveur** écoute les connexions entrantes sur le port `1234`.
- Lorsqu'un client se connecte, les deux parties échangent des messages via la console.
- L'échange continue jusqu’à ce que le client envoie `***CLOSE***`.
  
## 📂 Fichiers
- TCPEchoServer.java : code source du serveur TCP
- TCPEchoClient.java : code source du client TCP

## 🛠️ Compilation
javac TCPEchoServer.java
javac TCPEchoClient.java
