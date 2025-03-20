
# Temtem Overlay by Antize (Updated)

## Last Version
**Antize Temtem (Ver.1.16)** 

Uses data from the official wiki so you don't have to update the overlay every time the game is updated.

**The overlay :**
- **Doesn't** read Temtem memory
- **Doesn't** intercept any Client-Server communication
- **Doesn't** automate any part of gameplay
- **Doesn't** do anything a player couldn't do themselves using Alt+Tab -> https://temtem.gamepedia.com/Temtem_Wiki

**Keep in mind**, this is not a cheat, it does nothing more than ALT+TAB and go to the wiki, it does not read memory or intercept network data!

## Preview
![Preview](Preview/Exemple02.png)

![Preview](Preview/Exemple01.png)

![Preview](Preview/Exemple03.png)

![Preview](Preview/Exemple04.png)

## Antize Temtem Overlay
A free Temtem overlay that lets you easily see all Temtem statistics and automatically checks which Temtem are on the enemy team.

Antize Temtem Overlay can be put over your game to get an overview of all temtem while playing, your game must be set in Borderless, you have a search box and voice search to find Temtem in the list.

**Voice commands : (Speech must be enabled in options)**
  - Internet + Temtem name = Open Temtem page on browser  
  - Open/Ouvrir + Temtem name = Open Temtem detail  
  - Close/Fermer + Temtem name = Close Temtem detail  
  - See/Voir + Temtem name = See Temtem on main window  
  - Open Left/Right Temtem & Ouvrir Temtem Gauche/Droite = Open Left/Right ennemy Temtem detail
  - Scan enemy Temtem/Scan Temtem ennemis = Start a scan of the enemy team

## Known issues
- If **Antize Temtem Overlay** is launched as admin, **Malwarebytes** may detect it as a false positive (common issue with C# software).
- **Windows defender (Smart screen)** may block it as an unrecognized app (choose Run anyway).
- **Avast may detect it as a false positive** (IDP Generic).
- **Antivirus may ask for microphone access**: The software requires access to the microphone for voice commands (this can be disabled if desired).

## How do I get started ?
  -  [Download Temtem-Overlay.](https://github.com/Antizea/MyTemtem/releases/)
  -  Extract files and run `MyTemtem.exe`.
  -  To keep Antize Temtem Overlay on top of your game, make sure your game is set to Borderless mode.
  -  The initial startup may take some time, as well as updating data.

Inside of package, you must have the following files:
- **MyTemtem.exe:** The main software
- **Settings.xml:** Configuration settings
- **TemtemList.xml:** Local Temtem data
- **Temp folder:** Stores local Temtem files
- **Tesseract.dll, x64 folder, x86 folder & tessdata folder:** OCR dependencies for automatic enemy Temtem detection
- **Resolutions.csv:** Resolution settings for OCR

Tactical Tracker Overlay for the Temtem game

## Prerequisite
Maybe **Net Framework 4.5**

## Authors
- Antize

## License
Copyright@2019 Antize all rights reserved.
