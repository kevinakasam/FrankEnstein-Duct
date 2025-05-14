# User Mods

This repository is to share your Mods (Mods of my Mods are called Mods in the following). You can add them by submitting a pull request.
All my Mods have a sperate folder, that may include further subfolders, please sort your content as described below:

## Table structure

*Thanks to the [Voron_User](https://github.com/VoronDesign/VoronUsers) Repo for this table schematic! 
Update the following table with the information about your mod:
- Your name
- A link to your sub-folder
- A short description of your mod

like so:
`
| Creator | [Mod title](link) | Description | :x: | :x: |`

| Creator | Mod title | Description |
| --- | --- | --- |
| adamstorm | [Filament Sensor](<./adamstorm/Filament Sensor>)| A simple filament sensor in the extruder mount for Papilio/Sherpa mounting pattern extruders |
|           | [Camera Mount](<./adamstorm/Camera Mount>)| Add a nozzle camera to your Ender! |
|			| [Sprite Extruder Mount](<./adamstorm/Sprite Extruder Mount>)| Extruder mount for the Creality Sprite extruder |
| wight554 | [2510 Fan Dragon Mount](<./wight554/2510 Fan Dragon Mount>)| Hotend mount using 2510 fan for Dragon mount hotends |
|           | [5015 HF Ducts](<./wight554/5015 HF Ducts>)| 5015 fan ducts for "HF sized" hotends |
|           | [5015 UHF Ducts](<./wight554/5015 UHF Ducts>)| 5015 fan ducts for "UHF sized" hotends |
|           | [Extruder Mounts](<./wight554/Extruder Mounts>)| A bunch of alternative extruder mounts |
|           | [Klack HF](<./wight554/Klack HF>)| Klack dock and mount for "HF sized" hotends |
|           | [Klack UHF](<./wight554/Klack UHF>)| Klack dock and mount for "UHF sized" hotends |
|           | [PG7 Mount](<./wight554/PG7 Mount>)| PG7 Mount that's designed to be a bit more rigid |
| n4t3y | [AIO 5015 Duct](<./n4t3y/AIO 5015 Ducts>) | A combined mount for the 5015 fans with integrated duct instead of separately fixed |
| SampleMan | [Sample](./SampleMan/Sample) | This is a sample entry |

## How to create a pull request 

1. Create a fork of the repository
    - You can find a Button labeled `Fork` at the top right. Clinking on that creates a copy aka fork of this respository in your GitHub account.

2. Create a new folder
    - Navigate into the Mod folder you want to upload your Mod to.
    - Click on `Add file` -> `Create new file`. Then type `YourNickname/YourModName/README.md` to create your folder (click on `commit new file`).
    - If you plan to upload more than one Mod, add simply add more subfolders in your folder like `YourNickname/YourFirstModName/README.md` and `YourNickname/YourSecondModName/README.md` and so on. 
    - Please use short folder names.

3. Edit README and add your files
    - Click on the README.md and then on the pencil on the right top/center to edit the README. Add all required information as described below.
    - Click on `Add file` -> `Upload files` to upload all your Mod files.
    - The stock title of a commit is `Add files via upload` replace that with the title of your Mod.

4. Edit the main README.md of the Mod
    - Navigate back to the Mod folder you made your Mod for. Edit this file and add your mod to the alphabetic table by adding a new line with `| Creator | [Mod title](link) | Description | | :x: | :x: |`
    - The `link` for the `[Mod title](link)` should look like that: `./YourNickname/YourModName` just like you did above
    - Example: `| KevinAkaSam | [Modifius](./KevinAkaSam/Modifius) | Modifius adds ...  | :grey_question: | :grey_question: |`
    - Note `Modifius` is just an idea, yours may be called `Adaption to bearing size xy`

5. Submit the Pull Request
    - Navigate back to this repository (not the one you forked) and click on `Pull requests` next to `<> Code` `© Issues`
    - Click on the green square on the right `New pull request`
    - A new dialog/window opens and starts with:
        >Compare changes
        >
        >Compare changes across branches, commits, tags, and more below. If you need to, you can also `compare across forks`.
    - Click on the `compare across forks` and at the line below select your forked respository as `head respository`
    - Add you Mod name as title of the pull request, add the information to the form and click on  `Create Pull Request` at the very end.
    - If you did anything right we will merge your pull request :)
 
## Create a folder

To add your work create a folder that has the following structure:

    - Main repository `User-Mods` 
        - Nickname Subfolder eg. `KevinAkaSam`
            - Modname Subfolder eg. `Modifius`
            - Modname Subfolder eg. `Modimedi`
        - Nickname Subfolder eg. `hawk16zz`
            - Modname Subfolder eg. `Mod_A`
            - Modname Subfolder eg. `Mod_B`
