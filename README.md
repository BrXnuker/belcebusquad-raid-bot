# belcebusquad-raid-bot
https://discord.gg/belcebusquad


# Raider

### A discord bot to delete all channels , roles , custom emojis and ban all members from a discord server. In short raiding a server.

<br>

## *Disclaimer:*
```This is for educational purposes only. Use this only if you have the consent of the server owner. I am not responsible for any damage done by this bot.```

<br>

## Setup
- Make sure you have [Python](https://www.python.org/) and [Git](https://git-scm.com/)
- Create a new app on the [Developer Portal](https://discord.com/developers/applications)
- Make sure to enable the `Members` intent of the portal
- Download repo using `git clone https://github.com/BrXnuker/belcebusquad-raid-bot.git`

- Open the raider folder 
- Open the `install.bat` file
- Let him finish installing the requirements
- Open the `start.bat`
- When it starts, it will prompt you to place the bot token. copy and paste it.
- Enter, you will have the bot online.
https://media.discordapp.net/attachments/1089591287667249252/1093559109237878804/image.png 

Make sure you are on our discord! --> https://discord.gg/belcebusquad
and my shop --> https://discord.gg/brxshop

## Install Dependencies
### With virtual environment
- Install virtualenv module `pip install virtualenv` (only required for using virtual environments)
- Create a new virtual environment with `virtualenv venv` (optional)
- Activate with `.\venv\Scripts\activate` for windows
- Activate with `source ./venv/bin/activate` for macOS and linux
- Follow Steps for w/o env

### Without virtual environment
- Install dependecies with `pip install -r requirements.txt` or `pip3 install -r requirements.txt`
- Run the bot using `python bot.py` or `python3 bot.py`

## Use the bot
- Invite the bot to the server with the invite link printed out in the console. *Note: This requires you to have the `Manage Server` permissions on the server* 

- Grant all permissions the bot requires or else some operations of the bot may fail

- Find the role for your bot (same as bot username) in `Server Settings >> Roles`

- Move it up to the highest possible position in the role hiearchy

- Give any other necessary roles to the bot to view channels etc.

- Wait for you or anyone else to type the trigger message in any of the channels and let the bot do its work

## Deploying to [Heroku](https://heroku.com)
- Only use this if you want your bot to be online at all times
- In the project folder create a `Procfile` without any file extensions or use the one included
- Open the file and copy the following text: `worker: python bot.py` and paste it in.
- Create a new application on Heroku and follow the steps on the deploy tab.


## License
### [MIT](https://choosealicense.com/licenses/mit/) 
