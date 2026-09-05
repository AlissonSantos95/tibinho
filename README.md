# Tibinho

⚔️ Tibia Cooldowns & Shortcuts and MORE — Real-Time Overlay
Invisible floating overlay for Tibia that displays spell and rune cooldowns in real-time, featuring drag & drop, an integrated TibiaWiki scraper, and data persistence.


**Donate to help with the project or send TC to Phorz if you wish

[![Donate with PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?business=4XY2W8VTUVSAJ&no_recurring=0&item_name=Donate+for+Tibinho+project&currency_code=BRL)


Note for international donors: The currency is set to BRL (Brazilian Reais) due to local regulations, but PayPal will automatically convert the amount from your local currency at checkout. For reference, 5 BRL is roughly 1 USD, the money will be used to easy the development.





📋 Description
An application developed in Python that acts as a transparent overlay over the Tibia game client, allowing you to track spell and rune cooldown times in an automated and customizable way.
Built in Python; AI was used to understand the libraries below and for UI design since I do not have advanced knowledge in PYTHON.


<img width="567" height="183" alt="image" src="https://github.com/user-attachments/assets/001f4b7a-ddcc-42dd-8d71-36f25c1060ea" />



✨ Features
🎯 Invisible Floating Overlay (Chroma Key)
The interface uses native transparency (-transparentcolor), making the background completely ignored by Windows. Only the icons, progress bars, and descriptions remain visible on top of the game.
Shortcut: CTRL + SHIFT + ALT + Q — Opens the settings menu

🙈 Smart Auto-Hide
The script monitors the active system window. If Tibia is in focus, the overlay appears; when you Alt+Tab to your browser or Discord, it automatically disappears.

🖱️ Dynamic Slot Manager (Drag & Drop)
Organize spells and potions by dragging them from the category tabs (Knight, Sorcerer, Druid, Paladin, Monk, and Runes) directly into the active slots. Add as many slots as you want with the + Add Slot button.

🌐 Integrated TibiaWiki Scraper
With a single click, the program automatically fetches official spell and rune icons, converting them to the optimal format. It also extracts the minimum level, mana cost, and official description, updating automatically with every game update or via forced sync.

💾 Data Persistence (JSON)
All slot choices, shortcuts, and preferences are saved to:
overlay_config.json
When you reopen the program, everything will be exactly where you left it.

🔔 Tray Icon Integration
The program runs hidden in the notification tray with a quick-access menu and maintains a presence on the Windows taskbar.

🔒 Locked Mode and Control Bar
Floating bar featuring:

    Drag handle (≡)

    Settings button (⚙)

    Security padlock (🔓 / 🔒) — locks position to prevent accidental clicks

    Quick close button (✕)

🗺️ Roadmap

    [x] Spell Cooldown — The cooldown bar below the floating bar icons must reflect the cooldown of the specific spell placed in the shortcut, not the global cooldown.

    [x] Visual Global Cooldown — 2s global cooldown: turn all icons gray while active, with a 2s + milliseconds counter displayed on top of the image (without covering it; the image will turn gray).

        [ ] Make the icon stay grey and counting the spell cooldown not only the 2 sec GD and remove the botton cooldown bar, while mantaining the 2sec gray and counter on tohers icons.
        
        [x] Make resizeble icons so can make bigger ones
    
        [x] OCR with DW WINDOW for mirroring

    [x] Clean Overlay — Show only the image icon. No details, mana, level, or any other information.

    [x] "Sync" Button — Rename the icon update button to "Sync". When clicked, forces icon synchronization with GitHub Pages.

    [x] Movement Lock — When activated, hide all icons except the abilities and the cooldown. Options, close, and move buttons disappear.

    [x] Spell and Rune Icon Updates - auto update from github acttions

    [x] Language Menu on startup (will be supported pt-BR, Eng, Esp)

        [ ] Wiki Scrap on other languages too.
    
    [ ] Details Tooltip — When "show details" is active in the settings, hovering over a spell displays its details.

    [ ] Linux Support

    [ ] Settings Menu — Separate settings into tabs:
    
        [ ] Language Menu

        [ ] Overlay Spells/Icons — Current shortcut settings

        [ ] Sync Character for Hunts — Synchronize character for hunts

        [ ] Hunts

            [ ] Pre-checked checkbox "Sync with character" — fetches hunts only for the logged-in character's class and level

            [ ] Field to type character name — pulls data from the official Tibia website with an option to overlay hunt data

            [ ] Hunt filter by XP, loot, XP/hr, etc.
            
            [ ] Hunt Analyzer by json (compare your actual hunt with the last and have a peak at overall hunt)
            
    [ ] Integrated wiki - right click copy on item and a pop-up detailed with a pre-market value on your world from tibiamarket.com
      
           [ ] Search on Wiki - CTRL+ALT+SPACE to open a search engine to get info from wiki (**WILL BE PRE-BUILT ONCE A MONTH ALL WIKI INFO FROM GLOBAL WILL NOT DOWNLOAD INFO ON THE SPOT**) showing all detailed                          information needed on a floating window with links to open more details
        
           [ ] Wiki info language - Wiki will show the info on the respective language chossed or marked on configuration.

    [ ] Monitoring with Notification — Character Bazaar monitoring with notification

    [ ] Expanded Mini-MAP


V-0.0.2:

<img width="915" height="399" alt="AnimaçãoMover" src="https://github.com/user-attachments/assets/157ab515-0b5b-4226-be9b-44f52f5b5f28" />
