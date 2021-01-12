# PB 'n' Jamming Example Addon
An example addon for H3VR mod [PBnJamming](https://github.com/Maiq-The-Dude/PBnJamming) to add specific malfunction configs for custom items.

## Example
1. Create a json for each item you are configuring. For this example, we have created [`customguns.json`](https://github.com/Maiq-The-Dude/PBnJamming.ExampleAddon/blob/main/mod/customguns.json) and [`custommagazines.json`](https://github.com/Maiq-The-Dude/PBnJamming.ExampleAddon/blob/main/mod/custommagazines.json).
2. Configure each newly create json with the desired failures and failure rates.
3. Create a [`manifest.json`](https://github.com/Maiq-The-Dude/PBnJamming.ExampleAddon/blob/main/mod/manifest.json) to tell Deli how to load our changes.
4. Zip the files and rename the extension from from `.zip` to `.deli` and drop it into your H3VR `mods` folder.
