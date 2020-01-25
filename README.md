# Information Security News Telegram Bot
This is the code that powers [@ISNewsBot](https://t.me/ISNewsBot) for [Information Security News](https://t.me/InformationSecurity)


## ready
* Install Python and run `pip install python-telegram-bot --upgrade`
* Create 1 Bot, 1 Group and 1 Public Channel

## Configuration
Open `config.json` and configure
```
{
    "Admin": 0, // Administrator user ID (usually 8-9 digits)
    "Token": "", // Bot's Token from [@BotFather](https://t.me/BotFather)
    "Group_ID": 0, // The Moderation Group, should be private or anyone can press approve 
    "Publish_Channel_ID": "" // Channel ID where approved posts will go (eg: @channel or numeral value)
}
```
Enter `/setgroup` in the group you want to use to review posts

## run
```
python main.py
```

## How to interact
### Contributions
Send the message to the robot, only text, or your message will be ignored

### Moderators 
Approve or Reject the message, its that simple

This is a modified version of [/Netrvin/](https://github.com/Netrvin/)'s [telegram-submission-bot](https://github.com/Netrvin/telegram-submission-bot), the biggest change is translation into EN-US
