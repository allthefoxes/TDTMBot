
# DeltaBot

[![forthebadge](http://forthebadge.com/images/badges/uses-badges.svg)](http://forthebadge.com)

DeltaBot is a score keeping reddit bot originally designed for [/r/changemyview](http://reddit.com/r/changemyview). If you are thinking about using this code for your own subreddit, or any other purpose, we advise that you use a token that makes sense to you. The delta is an appropriate symbol that was chosen for /r/changemyview because it is often used to represent *change*.

This bot works by reading a subreddit and looking for specific tokens that denote that a point should be awarded. If it finds one, it acts accordingly by carrying out various jobs that can be found at http://www.reddit.com/r/changemyview/wiki/deltabot. 
=======
# TDTMBot

TDTMBot is a fork of [DeltaBot](https://github.com/alexames/DeltaBot). 

## Usage

1. Make sure you have Python and PRAW installed.
2. Create the file `config.json` and fill in the appropriate fields using `config.json.example` as a template.
3. Linux/Mac users: Run `runbot.sh`. Windows users: Run `winrun.bat`. CLI: Type `python deltabot` from the root folder of the program.

Make sure whatever account you're using to run the bot is a moderator of your subreddit and has permission to edit flair and the wiki.

## Contribute

If you're a developer visit the developer subreddit [/r/DeltaBot](http://reddit.com/r/DeltaBot)

Check out requirements_doc.txt to get an idea of what DeltaBot needs to do. To see new features that have not been implemented yet, check the Issues page.

[Join us on IRC!](http://webchat.snoonet.org/DeltaBot) (Snoonet #DeltaBot)
