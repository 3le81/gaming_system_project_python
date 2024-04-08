# PlayMaster Gaming System

**Project for HyperionDev Software Engineering Bootcamp**

Hey there! 👋 Welcome to PlayMaster, a gaming system crafted especially for primary schools to bring a dash of excitement to computer lessons. This project is part of my learning journey at HyperionDev Software Engineering Bootcamp, and it stands proudly as a valuable addition to my portfolio for upcoming opportunities..✨

## Project Overview

### The Challenge

My mission was to create PlayMaster, a gaming system that simulates a game of personal choice, packed with features to elevate the gaming experience:

- **User Profiles:** Users can create profiles, login, and validate passwords.
- **Game Features:** Creation, pausing/resuming, and viewing past games.
- **Scoring and Ranking:** A system to track scores and rank users.

## Project File Structure

To keep things organized, I structured the project with the following layout:

- `main.py`: The main script to kick off the gaming system.
- `user_data/`: A directory holding essential user account information.
- `saved_games/`: Where game states are saved and loaded.
- `leaderboards/`: A directory (future enhancement) for storing game leaderboards.
- `user_details.txt`: A text file to store user data.
- `words.txt`: A text file containing a list of words for the Hangman game.

## Development Checklist

1. **Login System:**

   - [x] Users can register new accounts.
   - [x] During registration, users enter a username, password, and confirm the password.
   - [x] The system checks if passwords match before adding a new user.

2. **Menu:**

   - [x] Implemented a dynamic menu displaying various options.
   - [ ] Options include starting a new game, resuming a game, viewing leaderboards, and more.

3. **Gameplay:**

   - [x] Choose one of two classic games (went with Guess the Number and Hangman).
   - [x] Added a scoring mechanism to make things competitive.

4. **Pause and Resume:**

   - [ ] Users can pause a game at any point.
   - [ ] Implement a mechanism to save the current game state for later resumption.

5. **Game History:**
   - [x] Users can view a comprehensive history of their played games.
   - [x] Displayed scores achieved in each game.

### Advanced Challenge

- [ ] Implement support for multiple games, each with its own leaderboards.

## How to Run PlayMaster

- **Follow the on-screen instructions to register, login, and dive into the gaming world.**

![Welcome](./images/welcome.png)

![Main Menu](./images/menu_game.png)

![View Scores](./images/scores.png)

![Hangman](./images/hangman.png)

## Installation

Follow these steps to install and run the PlayMaster gaming system:

1. **Clone the Repository**: Clone the PlayMaster repository to your local machine using Git:

```bash
   git clone https://github.com/3le81/gaming_system_project_python.git
```

2. **Navigate to the Directory**: Open your terminal or command prompt, and navigate into the playmaster directory:

```bash
cd playmaster
```

3. **Run the Program**: Execute the main script to start the PlayMaster gaming system:

```bash
python main.py
```

4. Follow the on-screen instructions to register, log in, and start playing!

---

## Notes

- Make sure you have Python installed to run the program.
- Ensure that you enter the correct username and password during registration and login.
- If a user doesn't exist, register first before attempting to log in!

## Future Enhancements

Here are other exciting plans for the future:

- **Leaderboards:** Showcasing the top players.
- **Game Expansion:** Expect more games with additional challenges.
- **Pause and Resume Feature:** _To be implemented!_ Enhance the gaming experience with the ability to pause and resume the games.

Happy gaming! 🎮
