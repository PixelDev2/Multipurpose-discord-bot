# Public Bot and Discord Server!
[📢 Join our Discord server!](https://discord.gg/whpAuajamK)

# Important notes
PROJECT IS NOT MAINTAINED ANYMORE 😥

# Installation Guide 🔥
# Hosting Requirements
<details>
  <summary> Click to expand</summary>

 - nodejs version 16.6 or higher, I recommend the latest STABLE version
 - python version 3.8 or higher, to install the database enmap (better-sqlite3)
 - A VPS would be advised, so you don't need to keep your PC/laptop/RasPi 24/7 online!
 - Check out my recommended Host: BERO-HOST and use code milrato for cheap OP VPS (kvm)
  
</details>


# 🤖 Bot Requirements
<details>
  <summary> Click to expand</summary>

- Download the Source Code
- Either by: git clone https://github.com/PixelDev2/Multipurpose-discord-bot
- downloading it as a zip from the releases tab or a branch.

</details>


# 🎶 Music Requirements
<details>
  <summary> Click to expand</summary>

  - To allow your Bot to play music, you need to connect it to a LavaLink station! There are many public ones out there for example lava.link An example for a public configuration will be listed down below.
  1 - Make sure Java 11 is installed on your system!
  2 - Download Lavalink.jar
  3 - Download application.yml
      - Download my example, it's the configuration for the lavalink.jar file!
  4 - Now put application.yml and Lavalink.jar in the same folder and start it
  - To start LavaLink type: java -jar Lavalink.jar
  - Make sure to keep your terminal Open!
  - If you want to use something like npm i -g pm2 to host it without keeping your terminal open type: pm2 start java -- -jar Lavalink.jar
  5 - The settings like password in application.yml and port must be provided in the botconfig/config.json of the Bot
    - If you used the default settings, than no adjustments are needed and it should look like this:
    `{
   "clientsettings": {
       "nodes": [
           {
               "host": "localhost",
               "port": 2333,
               "password": "youshallnotpass"
           }
       ]
   }
}`
