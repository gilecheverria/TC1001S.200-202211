# TC1001S - Herramientas Computacionales
Sample code for the Computer Tools course challenge

Author: Gilberto Echeverria

Original games code from: http://www.grantjenks.com/docs/freegames/index.html
Games included:
- Paint
- Snake
- Pacman
- Cannon
- Memory

## Installing the Freegames module

1. Make sure Python 3 is installed in your computer, and that you can call
   it from a terminal
2. Download the pip installer from: https://bootstrap.pypa.io/get-pip.py
3. Run the installer:
```
python3 get-pip.py
```
4. Install the module:
```
pip install freegames
```

### Installing on MobaXterm (Windows)

To install the required software, run the following commands:

1. apt-get install python3
2. apt-get install python3-tkinter
3. apt-get install python3-pip
4. pip3 install freegames

## Github workflow for branches

**Modifying the personal branch**

1. `git checkout main`
2. `git pull origin main`
3. `git checkout -b <your-branch>`
4. Make some changes to a file in the working directory
5. `git add <file>`
6. `git commit -m "<message>"`
7. `git push origin <your-branch>`
8. Back on the Github website, click on the button `Compare & pull request`

**Merging into `main` branch**

1. `git checkout main`
2. `git pull`
3. `git merge <your-branch>`
4. Solve any conflicts by editing the files and keeping the correct code
5. `git push origin main`
