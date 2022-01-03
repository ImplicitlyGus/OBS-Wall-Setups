# Wall OBS Setup

A drag-and-drop solution to easily setup OBS for use with Specnr's wall macro scripts

# Usage

Download either the **SixInstances** or **NineInstances** folder, depending on how many instances you are using for your wall. Six is recommended if you have 16GB RAM (or less) and/or have a lower-end CPU (almost anything Intel or lower-end AMD CPUs).

Navigate to your OBS scene folder in AppData - for me this is `C:/Users/Feinberg/AppData/Roaming/obs-studio/basic/scenes/` (replace Feinberg with your PC's username). Alternatively you can press `Windows + R`, then type `%appdata%/obs-studio/basic/scenes` which looks like this: ![run](https://user-images.githubusercontent.com/97056124/147978024-5c2560f4-96f2-4912-ad3f-fb9fed10b81e.png)

Then, drag and drop the two files in whichever folder you downloaded (a .json and .bak) into the scenes folder. Restart your OBS, then navigate to the Scene Collection button in the top left, as shown: ![obspic1](https://user-images.githubusercontent.com/97056124/147978847-41673bce-983b-46a9-8363-0c95db489e03.png)

Now all of our scenes are setup correctly for using the wall - including the default keybinds used with Specnr's macro `(Numpad 1-9, F12)`. Here is what your scenes will look like:
![obsscenes](https://user-images.githubusercontent.com/97056124/147979054-6ea510bc-1ce6-4409-bb51-0fc56a04420d.png)

The only thing left to do is setup the **main overlay scene** with all of your personal overlay items - chatbox, alertbox, webcam, audio devices, etc. The main overlay scene is present as a source in every other scene (except for the wall scene), so any changes you make to the main overlay scene will be apparent in every Minecraft instance that you play. If you already have a scene with these items from a different scene collection, I recommend downloading the [OBS Source Copy](https://obsproject.com/forum/resources/source-copy.1261/) plugin to copy and paste your scene from your old scene collection to the wall scene collection.

# Source Recording

While using the wall, for verification purposes you will need to record your wall at all times (to make sure that every loading screen for each instance is always being recorded). You can either use a second instance of OBS to achieve this, but a much easier way is to simply [Source Record](https://obsproject.com/forum/resources/source-record.1285/) the wall scene. Download the Source Record plugin from the link above, and then navigate to the **Filters** tab on the **Instance Wall** scene, as shown here:
![obsfiltertab](https://user-images.githubusercontent.com/97056124/147979685-8fac8635-f211-4517-ab90-ad59005891fa.png)


A Source Record filter might already exist - if not, then click the `+` in the bottom right and add a Source Record filter, as shown: ![obssource](https://user-images.githubusercontent.com/97056124/147979782-39ed5ab9-33b4-43cd-9188-a5b7284281b3.png)

Now, you'll have to configure the specific settings for the Source Record filter to record correctly. Here are the settings that I use: ![pog](https://user-images.githubusercontent.com/97056124/147980966-8269d1af-a24f-46c8-b38a-378ad9be5a41.png) 

I'd recommend using the same settings that I use - although you will **need to change** the Path under Record to whatever folder/drive you want to save your verification recordings to (I save them in the same place that I save regular OBS recordings, but add "verification" at the end to distinguish between the two.

Contact me on Discord with any questions - Feinberg#0001 :D

