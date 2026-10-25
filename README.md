# Desert Fishin — Quick Install

## Install

1. Extract the release package and copy the complete **Desert Fishin** folder into the game's `BepInEx\plugins` folder.
2. Confirm the installed files are arranged like this:

   
   Apocalypter\
   └─ BepInEx\
      └─ plugins\
         └─ Desert Fishin\
            ├─ DesertFishin.dll
            └─ Assets\
               ├─ rodassets
               └─ salmon
   ```

3. Start the game. BepInEx loads the plugin and creates `BepInEx\config\desertfishin.rodloottest.cfg`.

Keep the `Assets` folder beside the DLL; it contains the rod and Salmon model bundles.

## Optional settings

With the game closed, edit `BepInEx\config\desertfishin.rodloottest.cfg`:

- `ChancePercentPerItemRoll` adjusts the rod's loot chance.
- `SpawnRodKey` is unbound (`None`) by default. Bind a key only if you want the optional instant rod-spawn shortcut.

## Troubleshooting and removal

- If the mod does not load, check `BepInEx\LogOutput.log` for Desert Fishin errors.
- If a model is missing, verify that both files under `Assets` were copied with the plugin.
- To uninstall, close the game and remove `BepInEx\plugins\Desert Fishin`. Remove the config file only if you also want to discard your saved settings.
