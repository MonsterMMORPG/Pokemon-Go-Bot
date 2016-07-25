# Lvl 26+ Pokemon GO Accounts Giveaway Events: http://www.monstermmorpg.com/Pokemon-GO-Giveaways 
# www.pokemonpets.com free Pokemon MMO RPG
# www.monstermmorpg.com free Monster MMO RPG
# Original fork : https://github.com/NecronomiconCoding/NecroBot

<p>How to use?</p>
<p>You need to install Poke Miner if you want to use Pokemon Farming + Rare Pokemon Farming features</p>
<p>Poke Miner on reddit for more info : https://www.reddit.com/r/pokemongodev/comments/4tz66s/pokeminer_your_individual_pokemon_locations/</p>
<p>Pokem Miner github : https://github.com/modrzew/pokeminer</p>

<p>Once you setup your pokeminer, start agents around the location you will start farming your bot</p>

<p>In our application you have set the location of your Poke Miner db</p>
<p>In order to do so go to Logic.cs and find the function <b>funcReturnPokeLoc</b></p>
<p>In this funtion you will see    new SQLiteConnection(@"Data Source=C:\Python27\db.sqlite;Version=3;");</p>
<p>Modify the Poke Miner db location as you wish</p>

<p>For rare Pokemon Hunting list go to Client.cs and find the list lstPriorityPokemon</p>
<p>Modify the rare Pokemon IDs as you wish</p>

<p>It has a priority so put your most wanted pokemon into the beginning of the list</p>

<p>Feel free to ask any questions with opening issues</p>
