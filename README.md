# AncibleCore
Multiplayer/MMO library

I wrote this project as a way for me to have a good starting point whent developing Multiplayer/MMO games. It doesn't include any pieces to actually put players in a World but does include a solid outline for getting that started. Since account creation and authentication are already setup, you can start coding the world you want by using Services, Objects, and Traits.

Inlcudes 3 different projects:

AncibleCoreCommon - Common library that the server and client shares
AncibleCoreServer - Server library used for creating the world, objects, and communicating with the client
AncibleCoreServerConsole - Default console project for starting the server up

Uses Telepathy library.

Includes my own implemention of a MessageBus which is used for communicating information between server and client along with communicating with services and objects internally on the server.

Server library is setup to accept a client connection, authentication, and sending updates.
