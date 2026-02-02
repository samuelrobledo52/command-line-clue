# Command Line Clue 🕵️‍

Mystery in the Small Town is a command-line investigation game designed to practice basic Linux terminal navigation and file exploration skills.

##  Objective
Solve a crime by identifying:
- The suspect
- The weapon
- The location of the crime

All clues are distributed across directories and text files. The crime occurred in an empty room.

---

## etup Instructions

Clone the repository and navigate into it:

```bash
git clone git@github.com:samuelrobledo52/command-line-clue.git
cd command-line-clue
Generate a new game:

bash
Copiar código
python3 clue.py
This will create a game/ directory containing the mystery.

 How to Play
Navigate through the town using basic terminal commands:

ls – list directory contents

cd – move between directories

cat – read text files

Check every location for:

persons.txt

objects.txt

clue.txt

If a person or object is found in a room, it is eliminated as a suspect or weapon.

Use notebook.md to keep track of eliminations.

 Solving the Case
Once all clues are analyzed, make an accusation from inside the game directory:

bash
Copiar código
python3 accuse.py "Suspect" "Weapon" "Location"
 Final Solution
Suspect: The Journalist


Weapon: Letter Opener

Location: art room

The accusation was verified successfully using the accuse.py script.

<img width="1146" height="662" alt="Juego terminado" src="https://github.com/user-attachments/assets/177cf042-15d4-45a3-98b7-894f4b2c41d5" />
