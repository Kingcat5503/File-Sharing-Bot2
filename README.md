### CONFIGS VARIABLES

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `FILE_AUTO_DELETE` File auto delete, value in seconds
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DB_URL` Your mongo db url
* `DB_NAME` Your mongo db session name
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot, use HTML and <a href='https://github.com/JishuDeveloper/File-Sharing-Bot/blob/main/README.md#start_message'>fillings</a>
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding



### EXTRA VARIABLES

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/JishuDeveloper/File-Sharing-Bot/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False
* `BOT_STATS_TEXT` put your custom text for stats command, use HTML and <a href='https://github.com/JishuDeveloper/File-Sharing-Bot/blob/main/README.md#custom_stats'>fillings</a>
* `USER_REPLY_TEXT` put your text to show when user sends any message, use HTML



### DEPLOYEMENT SUPPORT

<summary>Deploy To Koyeb</summary>
<p>
<br>                 
<a target="/blank" href="https://app.koyeb.com/deploy?type=git&repository=github.com/JishuDeveloper/File-Sharing-Bot&branch=main&name=file-sharing-bot" >
  <img src="https://www.koyeb.com/static/images/deploy/button.svg" alt="Deploy">
</a>
</p>

<summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/JishuDeveloper/File-Sharing-Bot">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>



### FEATURES
- Fully customisable.
- Auto Delete Added.
- 3 Branch Available.
- main Branch Means 1 force subs.
- 2-force-subs Means 2 force subs.
- 4-force-subs Means 4 force subs.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.
- Deploy to Koyeb + Heroku + Railway.
- Developer Service 24x7.



### SETUP

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub


### FILLINGS
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

#### CUSTOM_STATS

* `{uptime}` - Bot Uptime


### ALL COMMANDS

```
start - start the bot or get posts
batch - create link for more than one posts
genlink - create link for one post
id - To check user id
users - view bot statistics
broadcast - broadcast any messages to bot users
stats - checking your bot uptime
```
