# GO-Bot
Automation platform (auto farmer, bot, etc.) for the popular game Pokemon GO. This project is in it's infancy stages and continuing to evolve as time goes on.

Discord chat: https://discord.gg/6AV6x8b

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3WXQX4UE94MWY)

## Features
- Loot Pokestops for XP and items
- Catch Pokemon
- Human like walking algorithm
- Transfers duplicate Pokemon
- Contributes to the distance required to hatch eggs
- Customizable latitude/longitude as default location
- Configuration screen for things such as sending duplicate Pokemon, evolving, minimum CP/IV, etc.
- More to come!

## Requirements
Windows operating system with .NET 4.5 or higher installed. Mac users will have to use a Windows virtual machine (recommend Virtualbox).

## Usage
For those who want the standalone application and not the source you can download the latest release from the releases tab at the top. Direct link: https://github.com/AnthonyOSX/GO-Bot/releases

![alt tag](https://i.gyazo.com/1313a2121266352b1510ea7c038b6221.png)

![alt tag](https://i.gyazo.com/bbe43e2574f85b18a21ede0c1177e987.png)

![alt tag](https://i.gyazo.com/108520afef24eded5906a2e4b9df59d1.png)

## FAQ
Q: Where do I download the bot?  
A: Head over to https://github.com/AnthonyOSX/GO-Bot/releases and download the latest version.

Q: The program won't start!  
A: You may not have net framework. Download and install net framework 4.6.1 and run the bot as admin.

Q: Why can't I login?  
A: There may be two reasons for this. 
First, make sure you are using a PTC account and not a google play account. You can sign up for PTC here: https://club.pokemon.com/us/pokemon-trainer-club/sign-up/
If you are using PTC to login but it still doesn't work, put your Latitude/Longitude with a "," instead of ".". 

Q: Can I run this program on MacOS or Linux?  
A: Short answer, no. But you can use virtual box or virtual machines to run windows while on your MacOS or Linux. Here is a tutorial for MacOS: https://www.youtube.com/watch?v=PL7Dh6drlBw

Q: I'm not catching any pokemon!  
A: Check your inventory, your bag may be full of potions, and revives. Throw them out with the trashcan icon on the top right side of each items. If this doesn't fix the problem, it may be your location or soft-ban. More about soft-bans below.

Q: I'm not getting any item or exp from Pokestops & all pokemons are fleeing!  
A: You were soft-banned. This means while you can login and walk around, you can not interact with gyms, pokestops and pokemons. You can still walk around to hatch your eggs but for 10-20min (may vary, but usually lasts 10~20min). More about tips on not getting soft-banned below.

Q: I keep getting soft-banned, what should I do?  
A: Soft-bans are caused from location jumping. This means you moved too far in a very short period of time. When you want to move from one place to another, try waiting couple of minutes before changing your location. I've found that this always works: Google map your current location and the location you want to be. Google map will tell you how long it takes to get there with a car. Divide that time by 0.75 and wait that long before changing your location.

Q: Can I login while the bot is running?  
A: Yes! I've logged in numerous times and have never been soft banned. I'm not sure if this is needed but I always turn off my location on my device when logging in.

Q: Stop button doesn't work!  
A: This is a weird one. For some people, it works perfectly fine and for some, they have to wait a couple of minutes after pressing "Stop". But from my experience, I've always just turned off the bot without pressing "Stop" and experienced no issues whatsoever.

Q: Will I be perm-banned in the future if I use this bot?  
A: No one knows for sure. Botting is a risky action no matter what, so please bot at your own risk!

Q: What is a safe walking speed (KM/HR)?  
A: There probably is a "sweet spot" but at the moment, no one really has a answer for this. However, eggs can only hatch if you "walk" under 20MPH, which is around 32km/hr. I suggest keeping it under 30km/hr.

Q: What is a good Latitude/Longitude for LOTSOFPOKEMON?!?!  
A: There are many places. SM pier, Central Park, Downtown in any city, etc... Just head over to http://www.latlong.net/ and type in a crowed place and enter those numbers!

Q: I can't read the log fast enough, can you slow it down?  
A: All log messages are saved to a text file on your computer at "C:\Users\{Your username}\GO Bot\Logs\Output\output.txt".

Q: The bot keeps crashing on startup?  
A: This is something I can't solve within the bot. Please follow the instructions within the answer here: http://stackoverflow.com/questions/17980178/cannot-load-counter-name-data-because-an-invalid-index-exception. If that doesn't work, delete the folder "C:\Users\{Your username}\GO Bot".

Q: I have more questions!  
A: Head over to the discord chat and ask away on #help! https://discord.gg/6AV6x8b

## Credits
Huge thanks to FeroxRev as without his work on PokemonGO.RocketAPI this would not be possible.
