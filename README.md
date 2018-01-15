# discord-HathorBot
User-friendly and easy to use music bot for your discord server. This project is still a Work In Progress and is not a finished product. Add me at Mesmaroth#4335 on discord for any questions, guide to help set it up, or to help me make this bot better.

Library: [Discord.js](https://discord.js.org)

## Installation:

### Windows
  - Install [Node.JS](https://nodejs.org/en/) 6.0 or greater
  - Install [Python v2.7.x](https://www.python.org/downloads/)
  - Install [Visual C++ Build Tools](http://landinghub.visualstudio.com/visual-cpp-build-tools) using **Default Install**
  - Install [node-gyp](https://github.com/nodejs/node-gyp) (Open command prompt and enter `npm install -g node-gyp`)
  - Install [FFMPEG static build](https://ffmpeg.zeranoe.com/builds/) to PATH. [Tutorial to install FFMPEG on Windows](http://www.wikihow.com/Install-FFmpeg-on-Windows)
  - Run `install.bat` to install required modules from the NPM framework
  - Enter bot token and other keys in `botLogin.js`
  - Run `run.bat` to start the bot


## Commands:

### Admin Commands
  - `listgroup`: List groups that have admin access
  - `addgroup [group_name]`: Add a group to use admin access
  - `remgroup [group_name]`: Remove a group from admin access
  - `setusername [NAME]`: Set a username for the bot
  - `setavatar [URL]`: Set a avatar for the bot to use
  - `setgame [name]`: Sets the name of the game the bot is playing
  - `setinit [command]`: Sets the initial command the bot needs to enter commands e.g The "." in ".play"
  - `exit`: disconnects bot from discord  

### General
  - `about`: About this bot
  - `uptime`: Uptime of the bot
  - `source`: Source link
  - `invite`: Get invite link for your bot
  - `setvc`: set the default voice channel this bot joins when ever the bot connects
  - `join`: Bot joins your voice channel

### Music
  - `queue` or `playing`: To view songs in queue
  - `play [YT_URL]`: Plays a song from a youtube link
  - `play [index_number]` : Plays a song from a file that has been saved to the bot
  - `play [search key term]`: Plays the first result of youtube search
  - `play [playlist_name or playlist_index]`: Loads a playlist to queue
  - `play`: Plays song in queue if it has been stopped  
  - `stop`: Stops the song from playing
  - `skip`: Skips to the next song
  - `replay`: Stops and replays song from the start
  - `readd`: Adds the current song back into queue
  - `loop`: Loops the entire queue, putting the current song back into queue
  - `local`: Displays all the songs saved by the bot
  - `remove [index_number]`: Removes a specific song from queue
  - `remove [#,#,#]`: Removes specific songs from the queue using it's index numbers seperated by commas
  - `save [YT_URL]`: Saves a song from youtube and stores it
  - `save`: Saves current song to local instead of downloading it from YT (faster)
  - `remlocal [index_number]`: Removes a song that has been saved locally
  - `playlist`: List all playlist
  - `playlist [playlist_index]`: List the songs of a playlist
  - `playlist save [playlist_name]`: Saves everything that is queued into a playlist
  - `playlist remove [playlist_index]`: Removes a playlist
  - `playlist remove [playlist_index] [playlist_track_index]`: Removes a playlist track from specified playlist
  - `playlist add [playlist_index] [YT_URL]`: Adds YouTube track into a playlist without having it queued
  - `playlist rename [playlist_name or playlist_index] [new_playlist_name]`: Renames a playlist
