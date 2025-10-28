# BBMenu
*The first mod menu for Generation 1 Pokemon Games*

---

## 📷 Screenshots
<p align="center">
  <img src="Shots/bbmenu1.jpg" width="200"/>
    <img src="Shots/bbmenu2.jpg" width="200"/>
  <img src="Shots/bbmenu3.jpg" width="200"/>
  <img src="Shots/bbmenu4.jpg" width="200"/>
</p>
<p align="center">
  <img src="Shots/bbmenu5.jpg" width="200"/>
    <img src="Shots/bbmenu6.jpg" width="200"/>
  <img src="Shots/bbmenu7.jpg" width="200"/>
</p>

---

Compatible with Pokémon Red, Blue and Yellow english versions, as well as VC releases. 

BBMenu can be installed inside your savegame using Arbitrary Code Execution, thus it can run in **original copies**, unlike any other ROMhacks!

## ✅ What BBMenu allowes you to do:
- Use constant effects like Running, Walking through Walls, Pokemon Beast Mode, Trainer avoidance etc.
- Get any Item, Pokémon or Moveset. 
- Instantly encounter any Pokémon or Trainer (yes, OAK is included!).
- Instantly get max Money, Coins, Badges etc.
- Launch custom mini-games like Snake!
- All from an in-game menu, with a simple press of Select button!

---

## ✅ Requirements
- A Gameboy console, a 3DS console or a compatible emulator (BGB recommended).
- An original copy of English Pokémon Red, Blue or Yellow, a VC release or an original ROM file.
- TimoVM's [modernized ACE](https://glitchcity.wiki/wiki/Guides:TimoVM%27s_gen_1_ACE_setups) setup.
- Latest version of [TimOS](https://glitchcity.wiki/wiki/Guides:Nickname_Writer_Codes) environment.

---

## 🔗 Installation

After setting up TimOS environment (required), you need to insert all the hex code parts in the same way you did in the above guides.
- Copy and paste the code from part1 in the [converter](https://timovm.github.io/NicknameConverter/).
- Write all nickname codes in nickname writter one by one and press start in the verification screen of the last one to run it.
- If you did everything correctly the game does not crash and you can make a save. In different case, reset and repeat.
- Do the same thing until every part is installed. Parts from no.3 and on do not require saving the game, since they install the payloads directly into the save file.
Warning! During the installation process DO NOT PRESS SELECT button while in the overworld. BBMenu needs to be fully installed, otherwise a crash is guaranteed (at least if parts 1-3 are missing).
---

### 🔧 How it works:
Pokemon Generation 1 games encapsulate a big amount of unused data in their save files. By using ACE, BBMenu is stored in there and injects its kernel, upon the moment the game is loaded. The kernel is responsible to run every constant effect payload in the backround or trigger the menu on demand.
Every payload is fetched into WRAM before is run, so that VC releases are totally compatible, since they cannot execute code directly from the save file.  

---

## 💬 Contact

Feel free to fork, reuse, or propose new modules!
For personalised requests and collaborations contact me.

---

## 🧠 Credits

- Pret for [Red](https://github.com/pret/pokered) and [Yellow](https://github.com/pret/pokeyellow) disassemblies, which allowed me to reverse engineer crucial game's logic and make the menu functional.
- [RGBDS](https://rgbds.gbdev.io/), which allowed me to develop [QuickRGBDS wrapper](https://github.com/M4n0zz/QuickRGBDS) and make this super complicated project easier to build and maintain.
- My mentor TimoVM from [Glitch City Research Institute](https://glitchcity.wiki/wiki/Main_Page) and his [ACE guides](https://glitchcity.wiki/wiki/Guides:TimoVM%27s_gen_1_ACE_setups).
- Everyone in [GCRI Discord channel](https://discord.gg/EA7jxJ6). Thank you guys for your motivation and support!

