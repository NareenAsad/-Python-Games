# -Python-Games
A selection of amusing and educational Python games. The games are created for experimentation and adjustments and are made in straightforward Python programming. There are streamlined variations of some vintage arcade games.

1) Features
• Fun to play!
• Simple Python code
• Easy to install
• Designed for education
• Depends only on the Python Standard Library
• Developed on Python 3.7
• Tested on CPython 2.7, 3.4, 3.5, 3.6, and 3.7
• Tested on Windows, Mac OS X, Raspbian (Raspberry Pi), and Linux
• Tested using Travis CI and AppVeyor CI

2) Quickstart
Installing Free Python Games is simple with pip:
$ python -m pip install freegames

Free Python Games supports a command-line interface (CLI). Help for the CLI is available using:
$ python -m freegames --help

The CLI supports three commands: list, copy, and show. For a list of all games run:
$ python -m freegames list

You can play any of the games in the list by running the Python module from the command line. Add "freegames" to the end of the game's name to refer to the Python module. To play the "snake" game, for instance, run:
$ python -m freegames.snake

Games can be modified by copying their source code. The copy command will create a Python file in your local directory which you can edit. For example, to copy and play the “snake” game run:
$ python -m freegames copy snake
$ python snake.py

Python includes a built-in text editor named IDLE which can also execute Python code. To launch the editor and make changes to the “snake” game run:
$ python -m idlelib.idle snake.py

You can also access documentation in the interpreter with Python’s built-in help function:
>>> import freegames
>>> help(freegames)
