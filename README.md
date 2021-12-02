# Rock-Paper-Scissor

## Table of contents
* [Oerview](#overview)
* [Technologies](#technologies)
* [Setup](#setup)


## General info
The project is a sample rock-paper-scissor game.
The project is about building a game and understanding how the game can be built from scratch. While developing the game I learnt about how server and client communicate over the network at the core level and how data are transferred and updated at both server and client end.

## Technologies
* python 3.7.6
* pygame
* socket programming
## Setup

To run this project by follow these steps. 
1. Clone [this](https://github.com/NKGUPTA26/rock-paper-scissor) in your local machine.
```bash
git clone https://github.com/NKGUPTA26/rock-paper-scissor
```
2. Change the directory to cloned repo folder.
```bash
cd rock-paper-scissor
```
3. Use the package manager [pip3](https://pip.pypa.io/en/stable/)
4. Create a virtual environment so that the dependencies version required for this project don't affect your other project dependencies.
5. To create a virtual environment run the following command
```bash
virtualenv "name of you want to give to your virtual environment"
e.g :- virtualenv venv
```
6. To install the dependencies run the following command
```bash
pip3 install -r requirements.txt
```
7. Note:- You will need the ipv4 address of your network to know that type
```bash
#window
ipconfig

#mac/linux
ifconfig
```
Assign this value to variable 'server' in server.py and network.py files.

8. First run the server.py in one instance of the terminal. It's a two-player game you need to run at least two clients to play this game. So run one client.py in the terminal and again run client.py in another terminal.

```bash
#In terminal one
python3 server.py

#In terminal two(player1)
python3 client.py

#In terminal Three(player2)
python3 client.py
```
![image](https://drive.google.com/file/d/13bTsuOxlTKv3ktARJ4sK0Q0uaR5aZQcm/view?usp=sharing)

You can run as m players you want.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.