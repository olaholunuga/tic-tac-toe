#
<h3 align="center">TIC-TAC-TOE</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> A TIC-TAC-TOE game with an AI player built with the Minimax Algorithm 
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Features](#features)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
A console-based Tic-Tac-Toe game engine with an unbeatable AI using the **Minimax algorithm**.  
Built with only the Python standard library. Inspired by [Real Python’s tutorial](https://realpython.com/tic-tac-toe-ai-python/).

## Features <a name = "features"></a>

- Console front end with human, random, and minimax (AI) players  
- Pluggable game logic and clean separation of concerns  
- Standard library only — no external dependencies  
- Extensible for GUIs, web, or other interfaces 

## 🏁 Getting Started <a name = "getting_started"></a>

## Installation

Clone and install the library in editable mode:

```bash
git clone https://github.com/olaholunuga/tic-tac-toe.git

cd tic-tac-toe

python3 -m venv venv

source venv\bin\activate

pip install --editable library/
```

## 🎈 Usage <a name="usage"></a>
```
python -m console -X <playerX> -O <playerO>
```
## Player types

- human → human input from console

- random → random move generator

- minimax → optimal AI


```
# Human vs Human
python -m console -X human -O human

# Human vs Random
python -m console -X human -O random

# Human vs Minimax (AI)
python -m console -X human -O minimax
```

## ✍️ Authors <a name = "authors"></a>
- [@olaholunuga](https://github.com/olaholunuga) - Idea & Initial work

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- Inspired by [Real Python’s tutorial](https://realpython.com/tic-tac-toe-ai-python/)