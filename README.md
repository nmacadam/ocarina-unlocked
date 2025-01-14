<p align="center">
  <img src="https://github.com/nmacadam/ocarina-unlocked/assets/37878073/05ec7437-d904-4167-94c6-6e76e70c01e7" height="300px"/>
</p>
<hr>
A ROM hack of <i>The Legend of Zelda: Ocarina of Time</i> that opens up the progression of the game by making minimal changes to the overworld, dungeon puzzles, and how the game directs the player.
The goal of this hack is to allow the player to more easily complete dungeons outside of the intended order. </p>

This isn't intended to be a massive revision of the game but rather to show how a few small changes could shift how linear the game is.
The idea for this hack came about when we were playing through the game while trying to complete dungeons out of order.
We found that while it was very possbile (and even accounted for with unique dialogue), most first-time or even returning players wouldn't go to the lengths required to play the game this way.
This is because they would need to partially complete dungeons, leave once they have the item (bombs, bow), and then go start another dungeon.

With this hack the player is now able to access dungeons earlier and complete them as soon as they can access them!

We have a full breakdown of the why behind this hack available [here](https://github.com/nmacadam/ocarina-unlocked/wiki)!


<p align="center">
  <img src="https://github.com/nmacadam/ocarina-unlocked/assets/37878073/56b9736e-dd53-4a5f-ada8-5e84563c87cc" />
</p>

Short Changelist:
- Remove the bomb-able boulders at the entrance of Zora's River, allowing Jabu-Jabu to be completed before starting Dodongo's Cavern
- Replace the 2 bow targets in the Water Temple with crystal switches
- The Nocturne of Shadow cutscene no longer requires the Water Medallion
- Small changes to cutscenes and dialogue to point the player at the newly accessible dungeons
- The map screen shows all currently accessible dungeons

A more detailed breakdown of each change, the reasoning behind them, and  their implementation are available on [the wiki](https://github.com/nmacadam/ocarina-unlocked/wiki/Changes)!

### Patching a ROM
Requires the Legend of Zelda: Ocarina of Time v1.0 NTSC-U ROM (the file extension should be `.z64`).

1. Download the latest [Ocarina Unlocked patch](https://github.com/nmacadam/ocarina-unlocked/releases)
2. Load the OoT NTSC-U v1.0 ROM into your patching software of choice ([here's an online patcher](https://www.marcrobledo.com/RomPatcher.js/)), and patch using the downloaded Ocarina Unlocked `.bps` patch file

Ocarina Unlocked is not currently compatible with other OoT ROM hacks.

### Tools

- [OoT Decompiled](https://github.com/zeldaret/oot)
- [ZZRTL-WAAS](https://github.com/jaredemjohnson/zzrtl-audio)
- [SceneNavi](https://github.com/xdanieldzd/SceneNavi)
- [Zelda's Letter](https://cloudmodding.com/applications/zeldas-letter/)

### References

- [CloudModding](https://wiki.cloudmodding.com/oot/Main_Page)
- [TCRF: Master Quest Debug ROM](https://tcrf.net/Proto:The_Legend_of_Zelda:_Ocarina_of_Time_Master_Quest)
- [HylianModding](https://hylianmodding.com)
- [z64Tools](https://github.com/z64tools)
