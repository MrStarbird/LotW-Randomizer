Legacy of the Wizard Randomizer v1.0
by: MrStarbird
Date: November 7, 2017

Contents:
1. Version History
2. About the Legacy of the Wizard Randomizer
3. Features and Options
4. Known Issues
5. Thanks

1. Version History

11/7/2017 - version 0.8

-Added option to change the entire dungeon layout to represent the MSX Version of the game.
-Changed Randomizer Layout Design to be a bit simpler.
-Flags now change upon changes in options, and options are now selected when Flags are entered and the "Flags" button is used.
-Added option to create a spoiler text file that shows what items are in each chest.
-Consolidated Enemy Stat randomization into one option
-Removed (for now) damage randomization for Enemy Stats
-Pochi can no longer get the Crown or Dragonslayer if Equipment is randomized.

4/27/2017 - version 0.7

-Added options to change Enemies' HP, Damage, and Speed.
-Added option to block the shortcut in Lyll's Area to prevent use of Pause-jumping to the area where the Crown is in original game. Adds a bit of challenge.
-Added option to randomize music in each zone.

4/19/2017 - version 0.61b

-Added a small "Sanity Check" for a chest in Meyna's area that is guarded by 3 powerful monsters, a ton of doors, and a spike. There is always a small chance that a crown could be in that chest and the three enemies that guard it are immune to damage until touched, and when touched deal 30 damage. This is way too difficult and can make a seed nearly unbeatable. By removing the spikes and replacing it with a solid block, it removes the need for wings at that spot and allows for you to hold onto a different item. This should balance the difficulty without too much change for now. This fix will most likely be temporary.

4/13/2017 - version 0.6b

-Added an option to randomize character equipment.
-Added Flags.
-Added Mouseover Tool tips.
-Cleaned up some code.
-Cleaned up the form a bit

4/11/2017 - version 0.51b

-Changed a value in the coding to (hopefully) remedy the graphical bug from the Randomize Enemy Group option.

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

2. About the Legacy of the Wizard Randomizer

The LotW Randomizer was designed to change the game so that it would feel like a different game every time you played it.

3. Features and Options
By mousing over each option, you can see a "brief" tooltip about what the option does and any notes or issues about said option.

Treasure Randomization:
Treasures in the game can be completely randomized or shuffled. If they are randomized, than the Crown and Dragonslayer will be located in their original spots. If they are shuffled, than the Crowns are also thrown into the pool of treasures. You can also choose between two half-bread options for shuffling. To keep from potential soft-locks at this point, the home shop and the two level 1 shops contain key items.

Shop Randomization:
Just like treasures, shops can have a randomized inventory and prices, or the shops can be shuffled around to be in different spots. If there are no treasure randomization option selected, then the first three shops will have their inventories randomized as well.

Character Stat Randomization:
Each Character can have stat changes given to them. They can either have each of their three stats randomized, or each of their stats can match in either an average setting (where each stat is averaged between each character and then given to each character) or can be given super stats (the strongest stat from each character are given). Pochi's invulnerability is not randomized and still remains on Pochi.

Enemy Randomization:
Enemies groups can be randomized in each section (though this part is cosmetic and listed as Enemy Groups) and their Speed and Health can be randomized.

Equipment Randomization:
What items a character can use can be randomized. To keep from any softlock potential, one character will be given a Mattock/Jump Shoe combo, one a Crossbow/Wing combo, and one a Glove. Only one person will be given use of the Crown and Dragonslayer. Pochi cannot use the Crossbow, Mattock, Glove, Crown, or Dragonslayer.

Music Randomization:
Though still in early stages, each section of the game gets a different music track. It is designed to be on a per-area basis, but sometimes each section will get a different track by accident. This is still being worked on, but should still work alright.

MSX-Style Dungeon:
The game's dungeon can be altered to completely to (somewhat) match the style used in the original MSX version of the game. Treasures are different and boxes can be in different locations. Many of the sections have completely different designs. Overall, this form of the dungeon is a LOT harder.

Spoiler Option:
By checking this option, you will recieve a text file in the same location as the randomized rom and with the same name. This will tell you what treasure is in what area.

4. Known Issues

-There is a slight possibility that the randomizer could give different outcomes and still have the same seed and flags if two different people use it. This most likely is an issue with different versions of the .NET Framework.

5. Thanks

THANKS: Big Thanks goes to NetBrian for finding many of the values needed to make this randomizer possible.

Special Thanks goes to DarkwingDuckSDA, deranged_squirrel_fighter, PanzerDave, EunosXX, DragonarchSDA, and many others of the Randomizer Central community for offering to test and play the randomizer. The feedback is greatly appreciated!

VERY Special Thanks to Serria for putting up with me banging my head against my computer trying to figure out how to get a program to do what I (think I) want it to.