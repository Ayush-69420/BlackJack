# BlackJack
A simple Blackjack game in Python
Here’s a `README.md` file tailored to your Blackjack game code:

---

# Blackjack Game

## Description
This is a Python-based Blackjack game built using the `tkinter` library for the graphical user interface (GUI). The game includes features like hitting, standing, doubling down, and splitting hands. It also incorporates sound effects and a modern color scheme for an immersive gaming experience.

The game is designed to simulate a real Blackjack experience, complete with a dealer, player hands, and betting functionality. It supports splitting hands and includes sound effects for actions like dealing cards, winning, losing, and hitting a blackjack.

---

## Features
- **Modern GUI**: Built with `tkinter` for a clean and user-friendly interface.
- **Sound Effects**: Includes sound effects for dealing cards, winning, losing, and hitting a blackjack.
- **Gameplay Features**:
  - Hit, Stand, Double Down, and Split functionalities.
  - Automatic dealer play (dealer hits until reaching 17 or higher).
  - Blackjack detection and insurance option.
- **Wallet System**: Players can place bets, add funds, and track their wallet balance.
- **Card Images**: Uses card images for a visually appealing experience (requires card images in the `cards` folder).

---

## Requirements
- Python 3.x
- Libraries:
  - `tkinter` (included with Python)
  - `PIL` (Pillow) for image handling
  - `pygame` for sound effects

Install the required libraries using pip:
```bash
pip install pillow pygame
```

---

## Installation
1. Clone the repository or download the source code:
   ```bash
   git clone https://github.com/your-username/blackjack-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd blackjack-game
   ```
3. Install the required libraries (if not already installed):
   ```bash
   pip install -r requirements.txt
   ```
4. Ensure the following folders exist in the project directory:
   - `cards`: Contains card images (e.g., `2_of_Hearts.png`, `Ace_of_Spades.png`, etc.).
   - `sounds`: Contains sound files (e.g., `deal.wav.mp3`, `win.wav.mp3`, etc.).
5. Run the game:
   ```bash
   python blackjack.py
   ```

---

## How to Play
1. **Place a Bet**: Enter your bet amount in the input field and click "Place Bet."
2. **Gameplay**:
   - **Hit**: Draw another card.
   - **Stand**: End your turn and let the dealer play.
   - **Double Down**: Double your bet and receive one more card.
   - **Split**: If you have two cards of the same value, split them into two separate hands.
3. **Dealer's Turn**: The dealer will automatically play after you stand.
4. **Winning**:
   - Beat the dealer without exceeding 21 to win.
   - A blackjack (21 with two cards) pays 3:2.
   - If the dealer busts (exceeds 21), you win.

---

## Folder Structure
```
blackjack-game/
├── cards/                  # Folder for card images
│   ├── 2_of_Hearts.png
│   ├── Ace_of_Spades.png
│   └── ...
├── sounds/                 # Folder for sound effects
│   ├── deal.wav.mp3
│   ├── win.wav.mp3
│   └── ...
├── blackjack.py            # Main game script
├── README.md               # This file
└── requirements.txt        # List of required libraries
```

---

## Customization
- **Card Images**: Replace the images in the `cards` folder with your own card designs. Ensure they follow the naming convention: `{value}_of_{suit}.png` (e.g., `2_of_Hearts.png`).
- **Sound Effects**: Replace the sound files in the `sounds` folder with your own. Supported formats: `.mp3` or `.wav`.
- **Color Scheme**: Modify the `BG_COLOR`, `BUTTON_COLOR`, and other color variables in the code to change the UI theme.

---

## Known Issues
- If the `cards` or `sounds` folder is missing, the game will display a warning and create the folders automatically. However, you need to add the required files for the game to function properly.
- The game assumes standard Blackjack rules. Custom rules (e.g., dealer hitting on soft 17) are not implemented.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Screenshots
(You can add screenshots of the game here if available.)

---

Enjoy playing Blackjack! If you have any questions or suggestions, feel free to open an issue or contribute to the project.

---

Let me know if you need further adjustments!
