# Event Driven Architecture

## 1. Real-time Drawing Guessing Game

**Description:** Develop a game where players take turns drawing a given word while others try to guess what it is. The hub server moderates the game, assigns drawing turns, and broadcasts drawing updates to all players in real-time.

**Functionality:**
- Players connect to the hub server to join the drawing game.
- The hub server selects a player to draw and broadcasts the chosen word to all other players.
- The drawing player sketches the word while others guess in real-time.
- The hub server validates correct guesses, awards points, and updates the scoreboard for all players.
- The game continues with new rounds and different drawing players.

**Optional Features:**
- Implement a chat feature to allow players to communicate and interact during the game.
- Integrate with a drawing library to provide tools for players to create their drawings.

## 2. Real-time Multiplayer Quiz Game

**Description:** Create a multiplayer quiz game where multiple clients can join and compete against each other in real-time. The hub server will moderate the game, sending questions to clients and collecting their answers.

**Functionality:**
- Clients connect to the hub server to join the game.
- The hub server sends questions to clients and waits for their answers.
- Clients submit their answers, and the hub server checks them for correctness.
- Scores are updated in real-time, and the leaderboard is displayed to all clients.
- The game ends after a certain number of questions, and the winner is declared.

**Optional Features:**
- Use an API to fetch quiz questions from a database.
- Employ a message queue to ensure ordered delivery of questions and answers.
