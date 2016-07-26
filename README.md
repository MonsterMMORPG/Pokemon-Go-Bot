# Original fork [read description and FAQ there!] : https://github.com/NecronomiconCoding/NecroBot
# Lvl 26+ Pokemon GO Accounts Giveaway Events: http://www.monstermmorpg.com/Pokemon-GO-Giveaways 
# www.pokemonpets.com free Pokemon MMO RPG
# www.monstermmorpg.com free Monster MMO RPG

## Features? 
- More advanced Pokemon hunting by Poke Miner
- Rare Pokemon priority hunting by Poke Miner
- Auto switch between Pokemon hunting and PokeStop farming according to Poke Ball count
- Full scale account details logging. The details file is saved in the folder where you run your console.exe
- Perfectly stable can run over 24 hours
- I am farming 8 accounts right now. So, i am making changes as necessary as a farmer :D
- Never gets soft banned because it always do human walking with the speed limit you have defined

## Why separate project?
- I started as a separate project since i am still a total noob of GitHub code management system
- I have never collaborated previously with any other developers. Thus, I have to improve my skills
- In future this project may discontinue if the all features here get added to Original Project

## How to use?
<p>Set your location around a place where there are PokeStops. I suggest you to farm in your city.</p>
<p>You need to install Poke Miner if you want to use Pokemon Farming + Rare Pokemon Farming features</p>
<p>Poke Miner on reddit for more info : https://www.reddit.com/r/pokemongodev/comments/4tz66s/pokeminer_your_individual_pokemon_locations/</p>
<p>Poke Miner github : https://github.com/modrzew/pokeminer</p>

<p>Once you setup your pokeminer, start agents around the location you will start farming your bot</p>

<p>In our application you have set the location of your Poke Miner db</p>
<p>In order to do so go to <b>Logic.cs</b> and find the function <b>funcReturnPokeLoc</b></p>
<p>In this funtion you will see <b>new SQLiteConnection(@"Data Source=C:\Python27\db.sqlite;Version=3;");</b></p>
<p>Modify the Poke Miner db location as you wish</p>

<p>For rare Pokemon Hunting list go to <b>Client.cs</b> and find the list <b>lstPriorityPokemon</b></p>
<p>Modify the rare Pokemon IDs as you wish</p>

<p>It has a priority so put your most wanted pokemon into the beginning of the list</p>

### Poke Miner installing instructions : https://www.reddit.com/r/pokemongodev/comments/4tz66s/pokeminer_your_individual_pokemon_locations/d5ljx7h

## Common errors and solutions
- Make sure you have installed visual studio 2015
- Open the app once and if you get error restart again and check nuget packages
- Set console app as start up project
- Make sure you have correctly set the Poke Miner database file location
- Make sure you edit the settings from App.config file rather than UserSettings window
- Right click and check installed nuget tools for all the projects
- Delete all text files in your debug folder and restart the app
- Check the thread on owned core which has many answers of many problems : http://www.ownedcore.com/forums/pokemon-go/pokemon-go-hacks-cheats/564208-pokemon-rare-hunting-bot-based-necronomicons-bot-utilizes-poke-miner-project.html

## What is the logic behind the Pokemon and Rare Pokemon farming
- It reads the live data from the Poke Miner database
- Then calculates the shortest distance having Pokemon to your current location and go for hunting it
- However, if you have setup priority list and if there is a priority Pokemon, instead of going to shortest distance Pokemon, first it goes to priority Pokemon
- Then from that location, it scans the database and goes after the shortest location pokemon to you. 
- Unless, if there is an another priority Pokemon :)
- If you get under total 25 Poke Balls, it starts priority farming the PokeStops until you get over 100 Poke Balls

## Don't forget to set pre-defined PokeStops locations and your starting location
- If the bot can not find any nearby Pokestop, it moves to next pre-defined Poke Stop location
- You can modify the locations inside <b>Client.cs</b>
- The pre configured list name is <b>lstPokeStopLocations</b>
- I suggest putting different poke stop locations in a close range area like 5 km radius or 10
- Do not worry, it will not jump but walk to the next location with the speed you have defined in your app settings
- Start location file is saved in <b>App.config</b> under <b>RocketAPI.Console project</b>

## Multiple Instance Farming
- For multiple instance farming, copy entire debug folder and paste it into another folder
- Each time you made changes, do the same operation for changes to be updated
- It will not ask you to enter your password everytime you update the app :) So don't worry to make changes

## What is lack?
- Still cannot incubate eggs

## Screenshot from the best giveaway account farming :) 
### You can reach up to 50k exp per hour without lucky egg based on how well the PTC servers working and how good area you farm

![Pokemon Go Bot Screen!](Static/pokemon-go-bot.png)


<p>Feel free to ask any questions with opening issues</p>

<p>Thank you for reading</p>

