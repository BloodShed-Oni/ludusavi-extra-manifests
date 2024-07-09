# Ludusavi-extra-manifests
Extra manifests for [Ludusavi](https://github.com/mtkennerly/ludusavi).

[**BS_ex-manifest.yaml**](https://github.com/BloodShed-Oni/ludusavi-extra-manifests/blob/main/BS_ex-manifest.yaml) contains game-save location data for games with (currently) no entry on [PCGamingWiki](https://www.pcgamingwiki.com), or source ports.

[**BS_software-manifest.yaml**](https://github.com/BloodShed-Oni/ludusavi-extra-manifests/blob/main/BS_software-manifest.yaml) kind of goes against the main purpose of Ludusavi, but expands the utility of it by adding location data for a selection of software configs (ex. TrenchBroom map editor).


## How to use
* Open Ludusavi gui (type 'ludusavi' in Windows Run or command prompt).
* Press the 'Other' button.
* Under the 'Manifest:' section ensure the line is set to 'URL' and not 'File'.
* Add one of the following URL's:

  
  Game saves: https://raw.githubusercontent.com/BloodShed-Oni/ludusavi-extra-manifests/main/BS_ex-manifest.yaml 

  Software: https://raw.githubusercontent.com/BloodShed-Oni/ludusavi-extra-manifests/main/BS_software-manifest.yaml
  
* (Optional) press the '+' button to add a new line and repeat the 2 previous steps as needed.
* When you're done, press the reload button (next to 'Manifest:). If done correctly you should see timestamps for 'Checked:' and 'Updated:'

## Want a game or software added to the manifest?
Open an issue with the "Add game" or "Add software" label and provide game/software name and info where the save/config files are located.
