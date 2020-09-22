
<p align="center">
  <img  src="icon.png">
</p>

# Welcome to LeagueBot 

  * League of legends bot is a pixel bot for League Of Legends 10.19, written in C# .NET using image processing (image & text recognition), Interop and scriptting engine.
  * This software is opensource and free feel free to create a pull request!
  * It's a good way to raise your account level 30 without having to play or simply to win blue essences.

  > Version: League of Legends 10.19

  This product is used to work with other program/service (League of Legends) so you take full responsibility for breaking their Terms of Service and full responsibility for the accounts that you’re using with this bot and agree to use it at your own risk.

  [<p align="center"><img src="discord.png"></p>](https://discord.gg/cB8qtcE)

# Current Features
  * Start a Coop Game
  * Follow the strongest Ally
  * Cast spells on champions and minions
  * Back and buy items when weak
  * End game, earn experience
  * Loop 👨‍🌾🐿️
  <p align="center">
  <img  src="https://i.imgur.com/kM8nDoh.png">
</p>
  

## Download 
   * For non developpers, You can download LeagueBot updater [here](https://github.com/Skinz3/League-Of-Legends-BOT/raw/master/Updater.zip) to automatically get the binaries and automatically download updates ! 🤫
## Installation

   Requirements :
   * League Of Legends client in english
   * a League of legends account
   * a monitor with a **1920 * 1080** screen resolution.
   * .NET framework 4.7 installed on computer.

   Before launch the bot, you need to follow setup instructions bellow : 

   [Setup instructions](https://github.com/Skinz3/League-Of-Legends-BOT/wiki/How-to-make-it-work)

	 
# Contact

   Join the discord server : [![Discord](https://discordapp.com/api/guilds/700654362841579571/widget.png)](https://discord.gg/cB8qtcE)

# LeagueBot Wiki

   FAQ, Api documentation... some good stuff :wink:

   [Here is the wiki](https://github.com/Skinz3/League-Of-Legends-BOT/wiki) 

# Author

   * **Skinz** - [Skinz#1128](https://github.com/Skinz3)

# Todo List

   Only pull requests concerning these subjects will be accepted

   * Dont use dynamic operator in ```LCU``` , use classes definitions of ```LCU``` instead.
   * Object architecture of ``` ApiMembers<> ```, MainPlayer property are defined in ```MainPlayer.cs ``` and ``` Coop.cs``` (dead field for example. Thats sucks)
   * Use ```Task<T>``` and Parallelism instead of ``` GameLoop()``` in Coop.cs
   * Optimize pixel searching ? it is possible faster than ```FastBitmap.cs (LockBits)``` ? (see ``` ImageHelper.GetColorPosition(Point point) ``` )
   * Make a solo in game pattern (we dont need an ally!)
   * Update Git API References
   * Add functionality to ``` Coop.cs ```.

