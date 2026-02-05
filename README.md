# Regarding Youtube Channel
## Hey everyone, just letting you know that I won't be able to upload videos for while, Life's gotten pretty busy...

# Limbus Company Dialogue Boxes for Enemies & Identities! UPDATED TO v1.98.0, PM has Updated how Speech Bubbles Work, Added LCE EGO Lamp Gregor & The Pinky Apperentince Sinclair!

### This mod adds speech bubbles for all characters with battle voicelines! (Including Untranslated Lines!)

# Do NOTE That The Untranslated Voicelines are Unofficial Can Be Wrong at times!
<img src="Screenshot/Hehehaha.png" alt="Hehehaha"/>
<img src="Screenshot/LaShangure.png" alt="LaShangure"/>
<img src="Screenshot/Shooting.png" alt="Shooting"/>

## Installation Warning
### ~~Whenever a new UPDATE happens, PLEASE DISABLE the mod!!! and wait for a new update on this repository. (or else you would face issues like [softlocking](https://www.youtube.com/watch?v=nHrCFfdBMAA))~~
### As of 13th Nov, 2025, You now need to not update on every single new localization content update. Now you ONLY need to update when there are new identities so you can add Speech Bubbles on them. (New Story Enemies too, cause they might not have their speech bubble by PM since this replaces the Speech Bubble file.)
### Some users faced problems when their PC Language wasn't set to English, it will cause errors in-game like these [Issues](https://www.youtube.com/watch?v=nHrCFfdBMAA)
## Installation - PC
1. Click **Code** → **Download ZIP** on this GitHub repository.
2. Open or Extract the ZIP file.
3. Navigate to your Limbus Company folder, and open the 'LimbusCompany_Data' folder
Ex.`C:\Program Files (x86)\Steam\steamapps\common\Limbus Company\LimbusCompany_Data`
      <img src="Screenshot/Browselocalfiless.png" alt="Browselocalfiless"/>
      <img src="Screenshot/datass.png" alt="datass"/>

5. Drag the "Lang" folder from the ZIP file into the "LimbusCompany_Data" folder.
      <img src="Screenshot/Likethis.png" alt="Likethis"/>

5. Launch the game, click on "Select Custom Language," choose **SpeechDialogBoxesEN - NotherWael**, and restart the game.  
   - If it’s already selected, you can skip this step.
   <img src="Screenshot/SelectTL.png" alt="SelectTL"/>
6. Enjoy the mod!

- To update, Delete `SpeechDialogBoxesEN - NotherWael` in the `Lang` folder, and put in the new one.
  (This will remove your custom fonts, so add them back)
- To disable this mod, simply remove the Lang Folder and restart the game, or Select "-" in "Select Custom Langauge" at the start menu, and restart the game.

## Installation - Mobile (ANDROID ONLY)
### Note: This method directly replaces the speech bubble localization file, and is not a custom language mod since it's not implemented on mobile, Do it on your own risk!
### Note: Everytime you launch Limbus after doing step 6, Limbus will redownload its own file, and will replace the modifed one, so you have to do it all over again everytime you launch Limbus.
1. Connect your Android phone to a PC. (or you can do this directly on your phone if you know how to do it, from using something like ZArchiver.)
2. Download [BattleSpeechBubbleDlg.json](https://github.com/NotherWael/LimbusDialogueBoxes_EN/blob/main/Lang/SpeechDialogBoxesEN%20-%20NotherWael/BattleSpeechBubbleDlg.json)
3. Rename `BattleSpeechBubbleDlg.json` to `EN_BattleSpeechBubbleDlg.json`
4. Access your phone files, and navigate to `Internal storage\Android\data\com.ProjectMoon.LimbusCompany\files\Assets\Resources_moved\Localize\en`
5. Launch the game Limbus Company, and Touch to Start.
6. As soon as you see the loading screen (Dante staring at the star), Replace the `EN_BattleSpeechBubbleDlg.json` file with the one you downloaded and renamed.
   - (This is to bypass Limbus's auto download that replaces modified files with their own correct one.)
   - You HAVE to do this before getting to Lobby screen, or else it will NOT work and you gotta restart and do it again.
7. The mod should work now, Enjoy!

## Custom Font Styles Instructions
1. Click **Code** → **Download ZIP** on this GitHub repository.
2. Open or Extract the ZIP file.
3. Navigate to your Limbus Company folder, and open the 'LimbusCompany_Data' folder
4. Open the 'Lang' folder and then 'SpeechDialogBoxesEN - NotherWael' folder
5. Delete the 'Font' Folder
6. From the ZIP file, Open 'Custom Fonts' folder & Choose a Style.
7. Open the folder of the style you choose and copy the 'Font' folder
8. Paste the 'Font' folder in the 'SpeechDialogBoxesEN - NotherWael' folder
9. Done! & Restart the game if open.

## Q&A
1. Is this safe? is it bannable?
   - It’s safe and not bannable. it's a custom language mod implemented by PM, It just changes the localization files.
   - PM stated "Please note that, modification of the game client beyond the language text files, such as modification of client images or in-game data could be met with legal action or bans without prior warning" [Link For the Notice](https://store.steampowered.com/news/app/1973530/view/533220039674824558)

   - But then again it's outside the intented use, cause it's not a different language, so PM may not like this kind of use for the custom language implementation, so it's kinda of a grey area at the moment.
   - **PM Recently Announced that they're gonna post new guidelines for modding and fanwork, so they might say something about this mod, if they'll allow it or not.**
   
   - As for the Mobile method, do it on your own risk! since you directly replace the files, it's kinda similar to current visual modding, where no one has gotten banned yet but could get banned at any time. (but then again this is only modifying the text files, so in the end idk)

2. How is this done?
   - Using the file `BattleSpeechBubbleDlg.json` you can add your own speech bubble text! (just needs the Voiceline ID and the text.)
   - So the mod is only a localization file to add speech bubbles, there isn't any bepinex dll plugins or asset modification or anything like that.

## Downsides & Issues
### This covers every battle voiceline in the game!!! So there might be a few characters missing lines if I've missed them, or if I've put the wrong voiceline ID, LMK if there are any!

- PC language may require to be set to English, though this might not apply to all languages.
- Some voicelines cannot display speech bubbles (e.g., Devyat's Polu or Full-stop Heathcliff in Overwatch state).  
- ~~Font may not match the base game... (like Mikodacs Font, not having Letter Spacing from the base game.) but you can use your own custom fonts!~~
- **Added the correct letter-spacing Mikodacs Font! as of 30th Oct 2025**
- A green icon appears in the top-right corner during battle or story, indicates you are using a custom language mod.  
- Game start-up screen menu loading may take ages! (though it might be cause of my weak device... so i'm not sure) 
- Speech bubbles stay longer than they have to blocking visibility on skills during combat.
- ~~Speech bubbles can end early because of the previous speech bubble before it.~~
- **As of 5th of Feb 2026, PM Has Made Speech Bubbles more dynamic where it finishes much faster as soon as the voiceline ends which can make slow readers miss out on some words on voicelines with long text but short spoken korean, and on mulitple voicelines it slowly transitions to the next Speech Bubble which causes about 0.7 second delay to see what the text is as the voiceline plays. (It also happens when the Speech Bubble first appears i think)**
- Retreating IDs VLs move their Speech bubbles to the Substituted ID.

## Known Voicelines That Do Not Work
- Devyat North Sinclair & Rodion All Poludnitsa Lines (Except the death ones cause i can fit it in with their death lines.)
- Overwatch Assignment Full-stop Heathcliff Combo Voicelines (He's not in battle, i could try to put it with FS Hong Lu's line, but his line has two variants so... i guess i'll put both!)
- N Corp Ryoshu and Yi Sang Skill Combo I Shall Fire // Anytime (Yeah the speech bubble just doesn't want to appear above her head at all, and yes i did check if it's the correct ID.)
- ~~Bloodfiend Trio Stage Turn Start VLs Don't Work Except for The Priest. (Their Skill VLs work tho... and some of these turn start voicelines do work on their respective stages.)~~
- All BOSSES Turn Start Voicelines Don't Work Sometimes...? (Their VLs during Combat Phase work tho... no idea what's causing this...)

## Credits
Goliath for telling me how to do this, they make a Russian translation custom langauge mod.
https://github.com/Divine-Company/DivineCompany_RussianTranslationDepartment
