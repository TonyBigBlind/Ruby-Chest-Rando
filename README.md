# Ruby-Chest-Rando
Raider Kid and the Ruby Chest Randomizer

This is a guide for how to use the current version of the Raider Kid and the Ruby Chest Randomizer Mod.

This Mod uses a Manual Archipelago as the way that it randomizes the game, as well as a custom wrote mod to take in the spoiler log data of the manual Archipelago to randomize the game.

# Setup Instructions

1.) Download and Install the Latest Version of Archipelago, https://github.com/ArchipelagoMW/Archipelago/releases 

2.) Download the RubyRandoZip File Found in this github and extract it. Inside will be both the archipelago file and the mod file and the yaml file also for archipelago.
<img width="617" height="98" alt="image" src="https://github.com/user-attachments/assets/f4079bd6-d61d-4fdb-ba0c-0fe2500862ee" />



3.) After Archipelago is Installed run the manual_raiderkidandtherubychest_tonybigblind.apworld file using archipelago to open it

<img width="393" height="282" alt="image" src="https://github.com/user-attachments/assets/5e953a00-4ee8-4abe-8409-c3f6c97acf44" />
<img width="414" height="157" alt="image" src="https://github.com/user-attachments/assets/ccec7a21-db18-49f6-9ea0-c6ec23d50b3c" />


4.) After the apworld finishes installing, next we will install the raider kid mod. Find your install of Raider Kid and the Ruby Chest, commonly found by opening steam and going to the game in your library and then selecting the cog on the right followed by manage and browse local files
<img width="320" height="329" alt="image" src="https://github.com/user-attachments/assets/d77afc32-a439-4c6c-907a-117deae63037" />

5.) Navigate into Ruby_data and then Managed. In this folder is where you will place the Assembly-CSharp.dll found in the RubyRandoZip, make sure to click replace the current file.

6.) Now that the mod is installed there is one other thing that we have to do which is randomize the game and place it into our saves folder for the game. Start by Opening Archipelago and go to browse files
<img width="804" height="621" alt="image" src="https://github.com/user-attachments/assets/a223d431-435b-40d6-ab6d-1c945ec84edf" />

7.) Then in the Players Folder is where you will put the Manual_RaiderKidandtheRubyChest_TonyBigBlind.yaml file
<img width="671" height="253" alt="image" src="https://github.com/user-attachments/assets/2e0dc469-4d36-4de8-86ff-fdbc08444e31" />

<img width="761" height="219" alt="image" src="https://github.com/user-attachments/assets/0e9916e1-8bdd-4c0e-b90a-e2b7e4dfc2ad" />

8.) Back In archipelago select the Generate button which will generate a new seed for the rando.
<img width="776" height="587" alt="image" src="https://github.com/user-attachments/assets/b3c2d00c-4a60-43de-9b24-9eddd9140de7" />

9.) Once the Command Prompt window closes that means it is done generating. Back in the Archipelago Files there is an Output Folder, inside of this folder should be a zip which is the randomized seed. Unzip this File
<img width="765" height="235" alt="image" src="https://github.com/user-attachments/assets/ba3aa486-9409-4c69-a076-3393ad960968" />
<img width="692" height="168" alt="image" src="https://github.com/user-attachments/assets/035960f0-eca0-48d0-b7c6-2eaa11941096" />
<img width="696" height="138" alt="image" src="https://github.com/user-attachments/assets/7e2d0ca0-7f8a-4163-adb8-7da0327aac29" />

10.) In this File you will see a couple files. The one we need is the AP_<numbers>_spoiler, it is the text file. Rename this file to randolog.
<img width="705" height="142" alt="image" src="https://github.com/user-attachments/assets/7a4cc710-e236-424b-b767-f9002ba64d27" />
<img width="701" height="155" alt="image" src="https://github.com/user-attachments/assets/a47a7af2-8170-4baf-a876-6efe6edc2473" />

11.) Now we need to find our saves folder for Raider Kid and the Ruby Chest, this can generally be found at C:\Users\<Username>\AppData\LocalLow\Cacareco\RubyChest, Simply drag and drop the randolog file into this folder.
<img width="704" height="187" alt="image" src="https://github.com/user-attachments/assets/9daeb75a-7d1d-467e-ac62-88af98f8e704" />

12.) Launch the Game Delete your old save file and start a new game and Enjoy.


# Changes to the Game

-All Collectible Items, Chests, And Ruby Key Part Chests Have been shuffles

-Your Game Saves when you collect Any Item

-After you pick up an item as long as you dont manually save at a save location if you select "Back to Title" and then "Continue" you will be placed back into the starting room. You will need to do this at least one time to get the enemies to spawn properly. If you want to hit a manual save to get your health back you still can but you if you want to go back to the starting position you need to collect any item first so that the game autosaves, this can be a carrot or javelin resupply that the enemies drop.

-If you interact with the stone panel puzzle it is automatically solved even if you do not have all of the stone panels.


# Reverting the Mod
-If you wish to uninstall the mod simply go into steam and Verify the Integrity of the Game Files for the game






