# FAQs

## I want to create my own Sprite Pack, How can I do this

It's great that you are interested in making new themes for this program, thanks
feel free to share them with the community by sharing them on this site by creating a pull request yourself, or by asking someone else to do it.

To extract the .xnb file
1. Click [this link](https://drive.google.com/file/d/1z5kLzT6r_F685V_qAf0ZNj1TaukU4CSN/view?usp=sharing) and unzip the folder
2. Locate the .xnb file that should be in `C:\Program Files (x86)\Samperson\Desktop Meadow\Content\Graphics`
3. Copy that file and paste it into the folder marked `PACKED`
4. Run `UnpackFiles.bat`
5. Go into the folder marked `UNPACKED` and you should see 2 files, NatureSheet.png and NatureSheet.yaml
6. You can now freely modify the .png file (as long as the sprites stay within the [Boundries](), these can't be changed yet)

To convert it back to a .xnb format
1. Go into the `UNPACKED` folder and make sure that both the .png and .yaml are in there and are named `NatureSheet`
2. Run PackFiles.bat
3. Go into the folder marked `PACKED`
4. Copy and paste that file into `C:\Program Files (x86)\Samperson\Desktop Meadow\Content\Graphics`
5. Ensure the file is called `NatureSheet.xnb`
6. Restart the program and you should have your own custom sprites
feel free to share them with the community by sharing them on this site by creating a pull request yourself, or by asking someone else to do it.

*These steps are likely to change when a new update is released*

## I want to change the default "Mail In" Background

1. go to `C:\Program Files (x86)\Samperson\Desktop Meadow\FormContent` and edit the file named `StationaryGreen`
2. Make the modifications that you want (Make sure that the .png stays the same size of 64 x 90)
3. Restart your meadow and wait for a new piece of mail to be delivered, and the background should have changed to your new custom one

*At the moment you are unable to change the "Mail out" design*

## I have this font that I want to use however once I changed the font the program wouldn't load

A this point in time the program both looks at the file name however it also looks inside the .ttf file
the next update should fix this
there is a way of getting around this however it is not worth it yet
if you *Really* want the the font now, [here](https://drive.google.com/file/d/1dXz7SouZmQ-jo_grLvVn9jPhxsdXOnFR/view?usp=sharing) is a step by step list on how to modify your own font to be compatible with the garden
