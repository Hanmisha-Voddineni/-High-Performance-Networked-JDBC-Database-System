# -High-Performance-Networked-JDBC-Database-System
PROJECT DESCRIPTION:
My Java UI project communicates, exchanges and syncs data in client/server fashion. In other words it builds a client/server system that reads data from a DB into an object and sends the object to the server.

ABOUT PROJECT:
The aim for our Java UI project is to communicate, exchange and sync data in client/server fashion. In other words our project should build a client/server system that reads data from a DB into an object and sends the object to the server.

We are using SQLite3 as the database for this project and we plan to implement two main java files, one for the client interface and one for server interface. The server interface should be able to handle multiple client interfaces where the concept of multithreading will be applied. These two databases will be interacting with each other using networking. One instance of ServerInterface will be able to handle multiple client interfaces. Clients should be able to load the database, open a socket connection to the server and send multiple objects across using the same connection. Server should be able to handle multiple clients using multithreading and receive objects from all these clients over the socket connection and then enter those objects into its database and then view them in the text area.

Please refer to      for the project readme instructions
