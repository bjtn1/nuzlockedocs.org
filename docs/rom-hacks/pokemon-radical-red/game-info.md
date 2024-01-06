---
description: "Information about the rom hack, how to install it, how to update it, where to ask for help, and more"
---
# Game Information

## What is Pokemon Radical Red?
:::info
Originally written by _GobouLePoissonBoue_ and _soupercell_
:::
Pokémon Radical Red is an enhancement hack of Pokémon Fire Red created by [soupacell](https://twitter.com/soupacell?lang=en) and [koala4](https://www.pokecommunity.com/members/koala4.146484/) 

This is a difficulty hack, with massive additional features added to help you navigate through this game.

This hack utilises the [Complete Fire Red Upgrade Engine (CFRUE)](https://github.com/Skeli789/Complete-Fire-Red-Upgrade) and [Dynamic Pokemon Expansion (DPE)](https://github.com/Skeli789/Dynamic-Pokemon-Expansion) built by [Skeli789](https://github.com/Skeli789), [Ghoulslash](https://github.com/ghoulslash), and others. It's responsible for most of the significant features in the hack.

### List of features (most of them provided by CFRUE and DPE):
- Much higher difficulty, with optional modes to add or mitigate difficulty
- Built-in Randomizer options (Pokémon, Abilities and Learnsets)
- Physical/Special split + Fairy Typing
- All Pokémon up to Gen 9 obtainable (with some exceptions, see further down)
- Most Moves up to Gen 9
- Updated Pokémon sprites
- Mega Evolutions & Z-Moves
- Most Abilities up to Gen 9
- All important battle items (with some exceptions)
- Wish Piece Raid Battles (with Dynamax)
- Mystery Gifts
- Reusable TMs
- Expanded TM list
- Additional move tutors
- EV Training Gear and NPCs
- Ability popups during battle
- Party Exp Share (can be disabled)
- Hidden Abilities
- Day, Dusk and Night cycle (syncs with RTC)
- DexNav, which allows you to search for Pokémon with hidden abilities and more
- Even faster turbo speed on bike and while surfing
- Abilities like Magma Armor, Static, or Flash Fire have overworld effects like in recent generations
- Destiny Knot, Everstone have updated breeding mechanics
- Lots of Quality of Life changes
- ... and more!

## Installation & updating

### Requirements
1. An original *Fire Red 1.0 ROM* like `1636 - Pokemon Fire Red (U)(Squirrels).gba` with `CRC32:DD88761C`
2. Real hardware or one of the [recommended emulators](#recommended-emulators)

### Steps to patch your original Fire Red 1.0 ROM
Here's a [video tutorial](https://www.youtube.com/watch?v=bMRePJ_b7P8) on following these steps

1. Go to https://patch.radicalred.net/
2. Drag & drop OR choose your original Fire Red 1.0 ROM `1636 - Pokemon Fire Red (U)(Squirrels).gba`
3. Click on "Apply Patch"
4. Download the patched `.gba` file
5. Open the file in your preferred emulator
<details>
<summary>
Successful patch of Radical Red
</summary>
![Successful patch of Radical Red showing a green checkmark next to the CRC32 tag](/img/successful_patch.png)
</details>
<details>
<summary>
Failed patch of Radical Red
</summary>
![Failed patch of Radical Red](/img/failed_patch.png)
</details>

### Updating RadicalRed
Updates will be announced in the `updates` channel of the [official RadicalRed Discord server](http://discord.gg/radicalred) along with instructions

#### Steps to update (without having to start over)
1. Save your progress using the in-game save (***not "save state"***)
2. Close your game
3. ***Delete your patched file*** which should be named `<some_name> (patched).gba`
:::info
In general, the file will be named `<some_name> (patched).gba` where `<some_name>` is the name of your original Fire 1.0 ROM

If you followed the steps from [above](#steps-to-patch-your-original-fire-red-10-rom), the file will be called `1636 - Pokemon Fire Red (U)(Squirrels) (patched).gba`
:::
4. Obtain the `.ups` update file (most likely from the [official Radical Red Discord server](http://discord.gg/radicalred))
5. Patch ***your original Fire Red 1.0 ROM*** using [Marc Robledo's Rom Patcher](https://www.marcrobledo.com/RomPatcher.js/)
:::info
You will drag & drop (or choose) the `.ups` file that you got from step 4 into the `Patch File` section
:::
6. Move the ***newly patched file*** that you got from step 5 into the ***same folder*** that your previous version was in
:::note
If `Radical_Red_v3.gba` was in `~/roms/GBA/Pokemon - Radical Red Version/`, this means that I will now move `1636 - Pokemon Fire Red (U)(Squirrels) (patched).gba` into `~/roms/GBA/Pokemon - Radical Red Version/`
:::
7. Open your newly patched `.gba` file in your preferred emulator
8. Load your save

### Recommended emulators
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
<TabItem value="macos" label="MacOS">

- [mGBA](https://mgba.io/)

</TabItem>
<TabItem value="windows" label="Windows">

- [mGBA](https://mgba.io/)
- [VBA](https://visualboyadvance.org/)

</TabItem>
<TabItem value="android" label="Android">

- [MyBoy](https://play.google.com/store/apps/details?id=com.fastemulator.gba&hl=en_US&gl=US&pli=1)

</TabItem>
<TabItem value="ios" label="iOS">

- [Delta](https://github.com/rileytestut/Delta)

</TabItem>
</Tabs>

:::warning
**DO NOT** use [Eclipse](https://eclipseemu.me/) or [Twilight](https://emulation.gametechwiki.com/index.php/TWiLight_Menu%2B%2B) emulators. You _will not_ be able to complete the game if you use either of these emulators.
:::
