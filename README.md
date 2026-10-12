# ✊ Rock Paper Scissors Game

A simple, interactive **Rock Paper Scissors game built with Python**. Play against the computer, enjoy ASCII art for each choice, and see who wins!

## 📌 Project Overview

This project is a command-line implementation of the classic Rock Paper Scissors game. The player selects Rock, Paper, or Scissors, and the computer randomly chooses one of the three options. The program then determines the winner based on the game rules.

## ✨ Features

- 🎮 Interactive command-line gameplay
- ✊ ASCII art for Rock, Paper, and Scissors
- 🤖 Random computer selection
- ✅ Input validation to accept only Rock, Paper, or Scissors
- 🔄 Case-insensitive input support
- 🏆 Automatic winner detection
- 🤝 Draw detection when both choices match
- 🐍 Built using Python's built-in `random` module

## 🛠️ Technologies Used

- **Language:** Python
- **Module:** `random`
- **Interface:** Command Line Interface (CLI)

## 📂 Project Structure

```text
Rock-Paper-Scissors/
│
├── main.py
└── README.md
```

> `main.py` contains the game logic. If your Python file has a different name, replace `main.py` with your actual filename.

## ⚙️ Requirements

- Python 3.8 or later
- A terminal or command prompt
- No external libraries required

## 🚀 Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/rock-paper-scissors.git
```

### 2. Navigate to the Project Folder

```bash
cd rock-paper-scissors
```

### 3. Run the Game

```bash
python main.py
```

On some systems, you may need to use:

```bash
python3 main.py
```

## 🎯 How to Play

1. Run the Python program.
2. Enter `Rock`, `Paper`, or `Scissors`.
3. The computer randomly selects its choice.
4. Both choices are displayed using ASCII art.
5. The program announces whether you win, lose, or draw.

**Important:** Invalid inputs are rejected, and the program asks you to enter a valid choice again.

## 📜 Game Rules

| Your Choice | Computer's Choice | Result |
|---|---|---|
| Rock | Scissors | You Win |
| Rock | Paper | You Lose |
| Paper | Rock | You Win |
| Paper | Scissors | You Lose |
| Scissors | Paper | You Win |
| Scissors | Rock | You Lose |
| Same choice | Same choice | Draw |

## 💻 Example Output

```text
Choose Rock, Paper, or Scissors: rock

Your choice:

    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)

Computer's choice:

    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)

You win!
```

*Note: The computer's choice and the result will vary each time you play.*

## 🧠 Concepts Practiced

This project helps beginners practice:

- Variables and strings
- Dictionaries
- User input with `input()`
- Conditional statements (`if`, `elif`, `else`)
- Loops (`while`)
- Input validation
- Random selection with `random.choice()`
- String methods (`strip()` and `lower()`)
- ASCII art and formatted output

## 🔮 Future Improvements

Possible enhancements include:

- Add a score counter.
- Allow multiple rounds.
- Track wins, losses, and draws.
- Add a replay option.
- Create a graphical user interface (GUI).
- Add difficulty levels or game statistics.

## 👨‍💻 Author

**Ritu Raj**  
Data Science & AI Developer

## 📄 License

This project is open for educational and personal use. You may modify and improve the code for learning purposes.

---

⭐ **If you like this project, consider giving the repository a star on GitHub!**

