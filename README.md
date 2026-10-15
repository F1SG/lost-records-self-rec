# Self-Rec mod

Self-Rec adds a selfie mode to the camcorder in Lost Records: Bloom & Rage (PC/Steam). You need to own a copy of the game on Steam to use this mod.

Unofficial fan mod. Not made, supported or endorsed by DON'T NOD. Install at your own risk.

## Back up your saves

Saves shouldn't be affected by this mod at all, but it's always worth having a backup anyway, just to be safe.

With the game and Steam closed, paste this into the Explorer address bar:

```
%LOCALAPPDATA%\Bloom&Rage\Saved\SaveGames
```

Then copy the `SaveGames` folder somewhere safe.

## Install

1. Close the game.
2. In Steam, right-click the game > Manage > Browse local files.
3. Go to `UNI\Content\Paks` and make a new folder called `~mods`.
4. Download the zip from [Releases](../../releases) and copy the 3 files into `~mods`:
   - `BSides_SelfRec_P.pak`
   - `BSides_SelfRec_P.utoc`
   - `BSides_SelfRec_P.ucas`
5. Start the game as normal.

No other mod tools (like UE4SS) are needed for this mod.

## Uninstall

Close the game and delete the 3 files from `~mods`. Your existing clips will remain as captured.

## Controls

Raise the camcorder, then press **T** (keyboard) or **LB / L1** (controller) to turn Self-Rec on or off. Everything else uses the game's normal camcorder controls.

Recording works like normal, so your Self-Rec clips get saved with your other camcorder clips.

## How it works

The game loads pak files from `~mods` as updates on top of its own files. When the game loads the camcorder HUD, the mod's version loads instead and adds the Self-Rec option. On top of that it adds a pose for Swann holding the camcorder towards herself, and some changes to the controls while Self-Rec is on.

It doesn't change any game files and doesn't touch your saves, story choices or achievements. It's single-player only and doesn't touch anything online.

## Known limitations

- **Crouching:** Swann doesn't have an animation for walking crouched while filming herself, so she can't move while crouched. If you press a move key, she stands back up first and then walks. Crouch again if you want to.
- The zoom resets each time you switch.
- It SHOULD only work when you're free to walk around. Cutscenes, conversations and menus should block it, like the normal camcorder.
- Built and tested on Steam build 19317136. A game update could break it.

Expect bugs. I've tested a few scenes and it works fine, but some scenes could break it.

## Bugs and ideas

If something goes wrong, open an issue here or message me and I'll look at fixing it when I can. Ideas and improvements are welcome too.

## Disclaimer

This mod is provided as is, with no warranty of any kind. I'm not responsible for anything that goes wrong from using it, including lost or broken saves, crashes or any other problems with your game or PC. There's no guaranteed support or updates; I'll help when I can, but I can't promise anything.

Lost Records: Bloom & Rage and everything in it belong to DON'T NOD. This is an unofficial fan project, not made, supported or endorsed by DON'T NOD. Please don't contact DON'T NOD about problems with this mod.
