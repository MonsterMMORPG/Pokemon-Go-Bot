# Original fork [read description and FAQ there!] : https://github.com/NecronomiconCoding/NecroBot
# Lvl 26+ Pokemon GO Accounts Giveaway Events: http://www.monstermmorpg.com/Pokemon-GO-Giveaways 
# www.pokemonpets.com free Pokemon MMO RPG
# www.monstermmorpg.com free Monster MMO RPG
## Features? 
** More advanced Pokemon hunting by Poke Miner**
** Rare Pokemon priority hunting by Poke Miner**
** Auto switch between Pokemon hunting and PokeStop farming according to Poke Ball count**
** Full scale account details loggin. The details file is saved in the folder where you run your console.exe**

<p>How to use?</p>
<p>Set your location around a place where there are PokeStops. I suggest you to farm in your city.</p>
<p>You need to install Poke Miner if you want to use Pokemon Farming + Rare Pokemon Farming features</p>
<p>Poke Miner on reddit for more info : https://www.reddit.com/r/pokemongodev/comments/4tz66s/pokeminer_your_individual_pokemon_locations/</p>
<p>Pokem Miner github : https://github.com/modrzew/pokeminer</p>

<p>Once you setup your pokeminer, start agents around the location you will start farming your bot</p>

<p>In our application you have set the location of your Poke Miner db</p>
<p>In order to do so go to <b>Logic.cs</b> and find the function <b>funcReturnPokeLoc</b></p>
<p>In this funtion you will see <b>new SQLiteConnection(@"Data Source=C:\Python27\db.sqlite;Version=3;");</b></p>
<p>Modify the Poke Miner db location as you wish</p>

<p>For rare Pokemon Hunting list go to <b>Client.cs</b> and find the list <b>lstPriorityPokemon</b></p>
<p>Modify the rare Pokemon IDs as you wish</p>

<p>It has a priority so put your most wanted pokemon into the beginning of the list</p>

<p>Feel free to ask any questions with opening issues</p>

<p>Thank you for reading</p>
