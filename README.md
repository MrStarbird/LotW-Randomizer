# LotW-Randomizer
Game Randomizer for Legacy of the Wizard v0.3b

DISCLAIMER: By using this Randomizer, you assume all risks involved and do not hold me liable for any damages or file corruptions that may happen. USE AT YOUR OWN RISK!!!

Thank you for taking the interest in viewing the Legacy of the Wizard randomizer. The code is written in vb.net so there may possibly be some issues with compatibility on the .NET Framework.

USING THE RANDOMIZER

0. Download the .zip file and run setup.
1. Select what options you want to have
2. Enter in any number from 0 to 99999999 (optional) into the "Seed #" field
3. Click on the "Save Path" button and choose the location and file name you wish to save to
4. Choose your options, click on the "Randomize Rom" button and choose your ORIGINAL Rom file.
5. The Randomized Rom of Legacy of the Wizard will be saved to your chosen location and file name and the program will be CLOSED

NOTE: Though there is a validation process in the program to validate the rom, it only checks the first 32 bytes of the file to see if it compares. It also so far ONLY accepts Roms with an NES header on it, so if you try using a file that doesn't have the header, you will get an Invalid Rom notification. If that happens, please let me know. My twitch ID is MrStarbird and I am on in some form nearly daily.

It is also possible that other NES roms have the same first 32 bytes as LotW. If this happens, please let me know.

Version History:

4/10/2017 - version 0.5b

-Added options to Shuffle or Randomize Shops

-Added option to randomize enemy groups in each area

-Fixed a bug where the files were not saving as .nes by default

-Fixed a bug where treasures were not getting shuffled properly.

4/9/17 - version 0.41b

-Minor update to clean up code and form. Form is no longer resizable.

-Added a 2nd option for Half Bread, allowing for either double equipment OR extra money, keys, and scrolls.

-Gave myself credit on the form. (finally)

4/8/17 - version 0.4b

-Added a Seeding process. Not sure how perfect it will work but time will tell how buggy it is. As of now, it works from what I can see.

-Added a "Half Bread" option for Treasure randomization. This takes the same Vanilla chest list, cuts the amount of bread drops from 26 to 13, doubles the amount of equipments in chest, adds a 2nd Magic Potion and a 4th Elixir.

-Added two new stat changes. Not really randomized at all, more or less just stat mods. One to normalize all character stats (which makes each stat the average of all 5 characters) and another for "Super" stats (which basically gives Lyll's Jump/Distance and Xemn's Strength. 

-Fixed a bug where Pochi's distance was not getting randomized properly and was always ending up at 8.

4/6/17 - version 0.3b

-Added a process that creates a new copy from the original file and writes to the copy.

-Added a rom validation check

-Added a "Shuffle" feature which takes the vanilla chest contents and shuffles them around. This means that the Crowns can be located in any chest. Removed 1 Spike Boot from the list and replaced it with a Dragon Shield. The Dragonslayer is still in the same spot.

-Changed 3 shops in the game: The Home Shop, the Shop to the far right of the top row in Level 1, and the Hidden Shop above the Dragon Portrait. The Home shop contains the Mattock and Power Glove, the Level 1 Shop contains the Wings and Spring Shoes, and the Hidden Shop contains the Crossbow and Key Stick. Each item sells for 70 Gold and are there because those are technically all the "required" items needed to get through all dungeons completely. With those shops, there should be no instances of being unable to finish the game.

Here is what the Randomizer currently does:

1. Change Treasure Contents
*User can randomize treasure contents entirely. Rings, Crosses, Shields, and Poison can be in chests and you could possibly find multiple of certain items or none at all. Crowns and the Dragonslayer will remain in their original spots.

*User can shuffle the contents of the original game treasure list (slightly modified to add a shield) or from a list that halves the amount of bread in the list and replaces it with other items. The Dragonslayer will remain in the same spot.

Original list (modified) is as follows: 26 Bread, 5 Magic Refill, 3 Money Bag, 3 Keys, 3 Scrolls, 4 Crystals, 4 Crowns, 3 Elixirs, 1 Magic Potion, 1 Wing, 1 Armor, 1 Spike Shoes, 1 Spring Shoes, 1 Mattock, 1 Glove, 1 Crossbow, 1 KeyStick, 1 Power Knuckle, 1 Fire Rod, and 1 Shield.

Half Bread, 2x Equipment list is as follows: 13 Bread, 5 Magic Refill, 3 Money Bag, 3 Keys, 3 Scrolls, 4 Crystals, 4 Crowns, 4 Elixirs, 2 Magic Potion, 2 Wing, 2 Armor, 2 Spike Shoes, 2 Spring Shoes, 2 Mattock, 2 Glove, 2 Crossbow, 2 KeyStick, 2 Power Knuckle, 2 Fire Rod, and 2 Shield.

Half Bread, More Money/Keys/Scrolls list is as follows: 13 Bread, 5 Magic Refill, 7 Money Bag, 8 Keys, 7 Scrolls, 4 Crystals, 4 Crowns, 3 Elixirs, 1 Magic Potion, 1 Wing, 1 Armor, 1 Spike Shoes, 1 Spring Shoes, 1 Mattock, 1 Glove, 1 Crossbow, 1 KeyStick, 1 Power Knuckle, 1 Fire Rod, and 1 Shield.

NOTE: If any of the treasure options are selected other than default, then as a safety there are three easily accessible shops that contain all the items needed to possibly beat the game for a slightly high price. This feature may be removed in the future, but for now there should be no possible situations where the game cannot be beaten.

2. Change Character Stats
*User can randomize the stats of each character between certain values. Jump can be anywhere from 18-28, Power can be anywhere from 1-3, and Distance can be anywhere from 8 to 32 (these match the minimum and maximum stats in vanilla). Knowledge of Pause-Jumping is recommended.

*User can set each character's stats the same as an average of each character stats. Jump is 20, Power is 2, and Distance is 22. Knowledge of Pause-Jumping is recommended.

*User can set each character's stat to be the highest possible from vanilla stats without use of enhancing items. Jump is 26, Power is 3, Distance is 32. This option makes the game quite a bit easier and is recommended for those new to the game, not just the randomizer.

3. Change Shops
*User can randomize what each shop holds and the price that they sell for. Prices range anywhere from 5 to 95 Gold.

*User can shuffle the shops contents and prices from vanilla around the map. 

NOTE: If the user chooses to keep the default treasure contents and chooses to change the shops, then the Home Shop, Level 1 Shop, and Dragon's Portrait hidden shop (which I had set to specific items for 70 gold a piece as a safety) will instead be added to the randomization or shuffle.

Here is what I hope to do in future releases:

4. Randomize Enemy Groups
*User can choose to randomize what enemies appear in each area. The damage these enemies deal do NOT differ (think of it more or less as a sprite swap), though hopefully the option to change damage will be added for later versions).

1. Randomize Dungeon Music
Having this option would be cool, especially since there is an unreleased track that is pretty cool to listen to. This is a bit trickier than original intended as there is a 2nd byte somewhere in each scene that controls something else, so this option will be delayed a bit more.

2. Randomize or have selectable pallette changes.
Nothing big, but something that could be fun for a change.

3. Randomize chest locations
There are 64 chests in the game, one per scene. Currently, they are all in the same spot, but it is possible to move them to a different spot within the scene. I would probably limit to some certain spots since we don't want them stuck in a wall or anything like that.

4. Randomize character item usage (still looking into)
I believe I have seen data on this but until I test it I am unsure, but if possible, I would love to be able to change what character can use what item. Imagine Xemn using the Wings or Pochi using the DragonSlayer. Would make things different, but certain item sets would have to be the or close. For instance, the Wings would have to be on a character that can use a Key Stick and either Crossbow or Mattock just to be able to get through Meyna's Level. Consumables (Elixir, Crystal, etc) would still be used by all.

5. Give option for MSX2 Layout
The MSX2 version of the game offers quite a few differences from the NES version in terms of layout. If you have ever played either, you will notice that Lyll's level is VERY much different between versions. 

6. Eliminate shortcuts
I could possibly give an option for a player to give themselves a challenge by cutting off certain shortcuts (like in Lyll's level which is possible to skip most of it just by using the Pause-jump glitch). May or may not try this.

7. Randomize Dungeon layouts
This would be the ultimate goal of the randomizer. Currently, it is beyond my knowledge on how to make the layout random without making an absolute mess, but this still would be the best thing I could hope for in the randomizer. 

8. Randomize Dragonslayer Location
This would be an option, but would make the game very easy as you could finish the game as soon as you find it without having to do all the crowns (unless the Dragonslayer was still in its original spot).

9. Randomize Portrait teleports
I am not sure if this is possible at all, but it would be interesting if the program could make the portrait warps take you somewhere else. It would give quite a bit of a challenge, especially for those familiar with the game already.

Known Bugs:

There is a SLIGHT possibility that the seed generator could be different between users using the same seed number. I believe this has to do with users working on different versions of the .NET Framework, but for now it is possible.

Special Thanks goes to DarkwingDuckSDA, deranged_squirrel_fighter, PanzerDave, EunosXX, and DragonarchSDA for offering to test and play the randomizer. The feedback is greatly appreciated!

VERY Special Thanks to Serria for putting up with me banging my head against my computer trying to figure out how to get a program to do what I want it to.
