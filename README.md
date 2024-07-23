# Space Invaders Project
## Universidad Central del Ecuador
### Programación I
#### Members
* Usiña Jonathan
* Karen Sandoval

## Space Invaders in Python 🎮

![image](https://github.com/user-attachments/assets/f97fbc66-dabb-4878-ae06-53d7629ab903)


#### Description 📜
Welcome to Space Invaders in Python! This project is an implementation of the classic game Space Invaders using Python and Pygame. Below you will find all the information about the project.

#### Game Overview🕹️
Considered by many experts to be the video game that popularized the industry, Space Invaders was born from the imagination of Toshihiro Nishikado, a young Japanese designer from Taito Corporation, in June 1978. Nishikado, who had already designed (with less significance) Soccer in 1972 –an arcade game very similar to Pong– remembers having been inspired by none other than HG Wells and War of the Worlds by giving its aliens that came down from space an octopus-like appearance, with matching tentacles. The game, which is still perfectly playable 40 years later, is notable in several ways.

Nishikado designed a very effective proto-narrative game environment based on a very playable and fun interface with all its material limitations (a side-scrolling joystick and two buttons) and working with an 8-bit Intel 8080 microprocessor. created using Python and the Pygame library.

In this version of Space Invaders, the player controls a spaceship that moves from left to right and for each alien he kills the game will accumulate 5 points and loses to the three attacks of the enemy ship, the one who manages to make the most points wins or the Let him kill all the enemies.

### Functional Requirements 🎯

#### Game Start 🚀

- The game must start with a main menu allowing the user to start a new game, view the high score, or exit the game.

#### Main Menu 🏠

- There must be an option to start a new game.
- There must be an option to view the high score.
- There must be an option to exit the game.

#### User Interface 🖥️

- The game must display the current score on the screen during the game.
- There must be a clear visualization of the game board with pieces (tetrominoes) and empty spaces.

#### Game Controls ⌨️

- The user must be able to move the friendly ship from left to right and with the letter space attack

#### Scoring 🏆

- The game must calculate and show the score for each enemy eliminated, which will increase by 5 by 5. Once the enemy ship dies, the score obtained will be shown and compared with those of other users in order to calculate the place obtained in the game.

#### Game Over 💔

- TThe game will end when the user decides to close the game or when the user manages to eliminate all enemies

#### Levels and Difficulty ⚙️

- The game may increase difficulty by speeding up the falling pieces as more lines are cleared.

#### Collision Detection 🚧

- The game must detect two collisions, when the friendly ship eliminates an alien or when the friendly ship is attacked.

#### Line Clearing 🧹

- The game will restart once the previous user finishes their lives or when they win. The moment this happens, it gives way to another player and the aliens will appear randomly again.

### Non-Functional Requirements ⚙️

#### Performance 🚀

- The game must run smoothly without significant delays or performance drops, ensuring a responsive experience during gameplay.

#### Usability 🌟

- The interface must be intuitive and user-friendly, allowing players to easily understand controls and game mechanics.
- Menus and options should be clearly labeled and accessible.

#### Portability 🌍

- The game should be compatible with multiple operating systems that support Python, including Windows, macOS, and Linux.

#### Scalability 🔧

- The codebase should be modular and extensible, making it easy to add new features or make improvements in the future without major overhauls.

#### Aesthetics 🎨

- The game should have a clear and visually appealing design, ensuring that the game board and pieces are easy to distinguish and interact with.

#### Documentation 📚

- The code must be well-documented, including comments and explanations, to facilitate understanding and maintenance by other developers.
- User documentation should be provided to guide players on how to play the game and use its features.

#### Reliability 🔒

- The game should handle errors gracefully and not crash unexpectedly.
- It must ensure data integrity, such as saving high scores correctly.

#### Testing 🧪

- The game must be thoroughly tested to identify and fix bugs, including functional tests (e.g., controls and scoring) and usability tests (e.g., user interface and experience).

#### Security 🔐

- The game should protect user data.

### Requirements 📋

- **Python 3.x**
- **Pygame**

### Features ✨

- **Classic Tetris Game**: Includes traditional Tetris features such as falling pieces, piece rotation, and line clearing.
- **Intuitive User Interface**: Designed with Pygame for a user-friendly experience.
- **Pause and Resume**: Players can pause and resume the game.
- **Scoring System**: Keeps track of the player's score.

### Game 🎮
<div align="center">
  <img src="https://github.com/user-attachments/assets/a51e6280-23d6-4072-be82-3f8371f109c7" width="300" />
  <img src="https://github.com/user-attachments/assets/3ac3d8d3-fe13-4d2b-9f7b-52d3c89b62dd" width="300" />
  <img src="https://github.com/user-attachments/assets/b5ccbdf7-9b4c-495d-b63a-5484956e26f9" width="300" />
</div>

### Installation 🛠️

1. **Clone the repository**:
   ```sh
   git clone https://github.com/mateo1011s/TetrisProject.git
   cd TetrisProject
2. **Install the required dependencies**:
   ```sh
   pip install -r requirements.txt

### Usage
1. **Run the main game file**:
   ```sh
    python main.py

### Game Controls

- **Left Arrow**: Move the piece left.
- **Right Arrow**: Move the piece right.
- **Down Arrow**: Accelerate the piece's fall.
- **Up Arrow**: Rotate the piece.
- **ctrl**: Pause/Resume the game.
  

