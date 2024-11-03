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
