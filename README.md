# Reversi Online

Simple room-based Reversi game that uses Firebase as a backend. All the game data is synced with Firebase Realtime Database.

## How to play

Connect to the GitHub pages URL, pick a username and create a room. Once a room is created, the room ID will be generated and you can tell your friend to connect to it.
<img width="1069" height="370" alt="Empty room" src="https://github.com/user-attachments/assets/724e999c-6775-4027-8c03-f8467c5950d3" />

Once you're in a room, you can join as either black or white. When both players are present, the white player can start placing the tiles.

At the end of the game (when no more tiles can be placed), the player with more tiles wins the game.

## TODO

Currently the game is connected to the Firebase account associated with my Tallinn University Google account, so it will stop working soon.
I'm planning to change it to my own Google account so the games continue working.

The game currently doesn't have authentication set up, so with the correct credentials, anyone can theoretically connect and fill the database with invalid data.
Once I change the account, I will implement anonymous authentication and take care of this problem.
