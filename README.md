# Lvl 26+ Pokemon GO Accounts Giveaway Events: http://www.monstermmorpg.com/Pokemon-GO-Giveaways 
# www.pokemonpets.com free Pokemon MMO RPG
# www.monstermmorpg.com free Monster MMO RPG
# Original fork : https://github.com/NecronomiconCoding/NecroBot

<p>How to use?</p>
You need to install Poke Miner if you want to use Pokemon Farming + Rare Pokemon Farming features
Poke Miner on reddit for more info : https://www.reddit.com/r/pokemongodev/comments/4tz66s/pokeminer_your_individual_pokemon_locations/
Pokem Miner github : https://github.com/modrzew/pokeminer

Once you setup your pokeminer, start agents around the location you will start farming your bot

In our application you have set the location of your Poke Miner db
In order to do so go to Logic.cs and find the function funcReturnPokeLoc
In this funtion you will see    new SQLiteConnection(@"Data Source=C:\Python27\db.sqlite;Version=3;");
Modify the Poke Miner db location as you wish

For rare Pokemon Hunting list go to Client.cs and find the list lstPriorityPokemon
Modify the rare Pokemon IDs as you wish

It has a priority so put your most wanted pokemon into the beginning of the list

Feel free to ask any questions with opening issues
