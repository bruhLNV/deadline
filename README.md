# Deadline by bruhLNV, a better fork of Presser.
## Features:
1. `Mass Create Channels`
2. `Mass Create Channels & Ping`
3. `Mass Create Roles`
4. `Delete All Channels`
5. `Delete All Roles`
6. `Delete All Emojis`
7. `Ban All Members`
8. `Kick All Members`
9. `Delete All Stickers`

# Requirements Before Set-up:

1. [Node.JS v16+](https://nodejs.org/en/) installed.
2. Code Editor: VSC(recommended), Sublime, Atom etc.

# Set-up: Bot

1. Go to your [Discord Developers Applications](https://discord.com/developers/applications) and create a new bot | You can use an existing one.
2. Go to the "Bot" section and scroll down till you see "Privileged Gateway Intents".
3. Select both **Presence Intent**, **Server Members Intent** and **Message Content Intents**. 


1. Extract the code in a folder, **Right Click** anywhere, click on **Open in Terminal**.
2. After opening write **npm init** then, spam **Enter**, until you see **Is this OK? (yes)** press Enter again.
3. Next, you'll have to install discord.js, in that same terminal type `npm install discord.js@13.1.0 chalk`, this will install discord.js and chalk.
4. Start the bot by typing `node .` or `node index.js`

# Set-up: Script

1. Navigate to the config folder, right click on the `config.json` file.
2. Open the file either on Notepad or a code editor i.e VSC (Visual Studio Code).
3. Make sure to add your ID for the commands to work.
3. Fill in ALL the gaps.
4. Save.

### Extra:
* `disableEveryone` | Default set to `true`, add your user ID | Makes sure no one else can use the tool. Set to `false` if you wish.  

## Start-up:

1. Navigate to the "src" folder, run the `deadline.bat` file.

# Disclaimer

This is tool was made for educational purposes and proof of concepts. I'm not accountable for any unlawful, unprecedented action and any violation of ToS administered by a third party.

## Tip
Also I'd recommend only mass pinging till the server reaches to 3k pings. Any more than that will result discord to lag or be rate limited for 30 mins - 2hrs ;)

root@deadline>_
