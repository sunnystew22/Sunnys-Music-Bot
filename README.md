# WARNING!
Please read this until the end as there is a node_modules.zip file that you have to extract so you get the full stuff. This is required as GitHub can't handle
uploading 100 file at the same time.

# Sunny's Music Bot

A simple music bot written in discord.py using youtube-dl. Use this as an example or a base for your own bot and extend it as you want. 

Adapted from this [gist](https://gist.github.com/vbe0201/ade9b80f2d3b64643d854938d40a0a2d), Copyright (c) 2019 Valentin B.

### Pre-Setup

If you don't already have a discord bot, click [here](https://discordapp.com/developers/), accept any prompts then click "New Application" at the top right of the screen.  Enter the name of your bot then click accept.  Click on Bot from the panel from the left, then click "Add Bot."  When the prompt appears, click "Yes, do it!" 
![Left panel](https://i.imgur.com/hECJYWK.png)

Then, click copy under token to get your bot's token. Your bot's icon can also be changed by uploading an image.

![Bot token area](https://i.imgur.com/da0ktMC.png)

### Setup

Create a file named `.env`

Add `TOKEN=<your bot token>`

Your .env file should look something like this:

```
TOKEN=<Bot token>
```

### Uptime

To keep your bot alive you need to make this repl into a webserver. The way you do that is that you `import keep_alive` (file included this repl) and call it `keep_alive()`.

Now that this repl is a server, all you have to do to keep your bot up is setup something to ping the site your bot made every 5 minutes or so.

Go to [uptimerobot.com](https://uptimerobot.com/) and create an accout if you dont have one.  After verifying your account, click "Add New Monitor".

+ For Monitor Type select "HTTP(s)"
+ In Friendly Name put the name of your bot
+ For your url, put the url of the website made for your repl.
+ Select any alert contacts you want, then click "Create Monitor" 
![Uptime robot example](https://i.imgur.com/Qd9LXEy.png)

Your bot should now be good to go, with near 100% uptime.

# Is this bot open-source?
Yes of course it is. You can download the source code off of the GitHub page. If you have Git installed on your system, open Git Bash on Windows or open Terminal on Linux. Then navigate to the directory you want to have the source code folder. Then type this command and wait until the process is finished.

`$ git clone https://github.com/sunnystew22/Sunnys-Music-Bot`

# Why isn't there a node_modules folder?
There is a node_modules.zip file which you have to extract.
