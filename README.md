# <center>Film Buddy</center>

<center><img src="https://i.imgur.com/M7w9RuH.png" width=400></center>

Presenting **Film Buddy**, a fully functional, visually appealing bot that streamlined entertainment information access for **500+** discord users in **100+** servers.

# Commands

1. `/movie` 
	- Fetches movie information.
	- For example,
	`/movie The Conjuring`
	<img src="https://cdn.discordapp.com/attachments/933210547460128804/951373814133043250/The_Conjuring.jpg?ex=6876a528&is=687553a8&hm=9f2d3471138726f6cccb01a42120536c095cb49a562b731c586c6f2bdcf18f23&" width=500>
2. `/show`
	- Fetches TV Shows or Series Information.
	- For example,
		`/show Brooklyn 99`
		<img src="https://cdn.discordapp.com/attachments/933210547460128804/951370970227167252/Brooklyn_Nine-Nine.jpg?ex=6876a282&is=68755102&hm=740bf2d5592de7f8dbc6791835ebd86f68f529f78fd0e00520a9d4acfe507e61&" width=500>
3. `/currentres`
	- Shows the current resolution of the images (1 to 4).
4. `/setres`
	- Sets a new resolution for the images.
	- Has 4 levels of quality, 1 being the lowest and 4 being the highest.

## Tools and Frameworks used to develop Film Buddy

|Tools|Description  |
|--|--|
| discord.py | An discord API Wrapper in python used for developing discord bots. |
|Pillow | A Python Module for manipulating and processing images. |
|TMDB API | An API used to fetch information from TMDB.|
|Firebase | A Cloud Database service from Google for storing key data.|
|Python |The main programming language used in the majority of the project.  |


## Installation

1. Make a new directory in your local PC and clone the repository using the command:
	- `git clone https://github.com/anand-murthy-r/FilmBuddy-Reborn.git` and then 
	- `cd {directory_name}` to enter into the directory.
2. In the **credential.json** file, replace wherever there is written *CLASSIFIED* with your own Firebase, TMDB and Discord Bot credentials.
3. Film Buddy needs to meet some requirements before running the bot. In your terminal, type
	`pip install -r requirements.txt` to install the necessary modules and packages.
4. Finally, run the command `python main.py` to run the bot.

---
