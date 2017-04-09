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

1. Randomize Treasure Contents
By having this selected, all treasures in the game (with the exception of Crown and Dragon Slayer spots) will have their contents changed to a random item. Each chest can be any item in the game, including Rings, Crosses, Shields, and even POISON. It is also possibly to get multiple of a certain item and none of another, all depending on what the RNG gives. 

2. Shuffle Vanilla Treasure Contents
This takes the treasure contents in Vanilla and shuffles them around. Each piece of equipment can only be found once now (originally, the Spike Shoes had 2 spots, but I removed one and replaced it with the Dragon Shield, which had 0 originally) and Crowns can now be in any chest. There are also 4 Crystals, 3 Elixirs, 1 Magic Potion, 3 Scrolls, 3 Keys, 3 Money Bags, 5 Magic Refills, and 26 Health Refills. The Dragon Slayer stays in its original position.

3. Shuffle Vanilla Treasure Contents with "Half Bread" options.
Takes the same treasure list from Vanilla, cuts the amount of of Bread in chests from 26 to 13, and the user can choose between either double equipment rate, or extra Money/Keys/Scrolls. Either choice makes the game a bit easier.

4. Randomize Character Stats
By having this selected, all 5 characters will have random Jump, Power, and Distance stats. Jump should be anywhere between 18 and 26, Strength anywhere between 1 and 3, and Distance anywhere between 8 and 32. This will be altered slightly in the future as a Jump of 26 is required just to get to the chest where Lyll's Crown is in vanilla. But for now, I placed a notice next to the checkbox saying that the knowledge of Pause-jumping would be highly recommended in case Lyll gets a low jump stat.

5. Normalize Character Stats
Sets all characters equal to each other in their stats with "Average" stats. Pause-jumping knowledge still may be required, depending on where the crowns are.

6. Super Character Stats
Sets all characters equal to each other in their stats with "Super" stats. Everyone is basically like Lyll but with Xemn's strength. This makes the game quite a bit more casual-friendly and decreases the difficult significantly.

Here is what I hope to do in future releases:

1. Randomize Shop Inventory & Prices
This could add quite a bit of difficulty to the game, which is why I have the "home shops".

2. Randomize Dungeon Music
Having this option would be cool, especially since there is an unreleased track that is pretty cool to listen to. 

3. Randomize or have selectable pallette changes.
Nothing big, but something that could be fun for a change.

4. Randomize chest locations
There are 64 chests in the game, one per scene. Currently, they are all in the same spot, but it is possible to move them to a different spot within the scene. I would probably limit to some certain spots since we don't want them stuck in a wall or anything like that.

5. Randomize character item usage (still looking into)
I believe I have seen data on this but until I test it I am unsure, but if possible, I would love to be able to change what character can use what item. Imagine Xemn using the Wings or Pochi using the DragonSlayer. Would make things different, but certain item sets would have to be the or close. For instance, the Wings would have to be on a character that can use a Key Stick and either Crossbow or Mattock just to be able to get through Meyna's Level. Consumables (Elixir, Crystal, etc) would still be used by all

6. Give option for MSX2 Layout
The MSX2 version of the game offers quite a few differences from the NES version in terms of layout. If you have ever played either, you will notice that Lyll's level is VERY much different between versions. 

7. Eliminate shortcuts
I could possibly give an option for a player to give themselves a challenge by cutting off certain shortcuts (like in Lyll's level which is possible to skip most of it just by using the Pause-jump glitch). May or may not try this.

8. Randomize Dungeon layouts
This would be the ultimate goal of the randomizer. Currently, it is beyond my knowledge on how to make the layout random without making an absolute mess, but this still would be the best thing I could hope for in the randomizer. 

9. Randomize which enemies appear in which scene
It is possible to change enemy groups in each area. Doing so, it is possible to have the strong enemies from Pochi's dungeon in the very first scene. Could make certain parts of the game more difficult than need be, but who doesn't like a challenge?

10. Randomize Dragonslayer Location
This would be an option, but would make the game very easy as you could finish the game as soon as you find it without having to do all the crowns (unless the Dragonslayer was still in its original spot).

11. Randomize Portrait teleports
I am not sure if this is possible at all, but it would be interesting if the program could make the portrait warps take you somewhere else. It would give quite a bit of a challenge, especially for those familiar with the game already.

Known Bugs

-None yet-

Special Thanks goes to DarkwingDuckSDA, deranged_squirrel_fighter, PanzerDave, and DragonarchSDA for offering to test and play the randomizer. The feedback is greatly appreciated!

VERY Special Thanks to Serria for putting up with me banging my head against my computer trying to figure out how to get a program to do what I want it to.
