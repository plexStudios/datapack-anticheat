# Datapack Anticheat

## Install
### Regular
After downloading the version that you want, simply move it into the datapacks folder located in
```
%appdata%/.minecraft/saves/{YOUR WORLD}/datapacks
```
Depending on your operating system this may differ.
### Command line
If you have git capabilities in your command line, you can use this method.
Open a terminal in the directory that you wish to clone to, then type
```
git clone https://github.com/Troned/datapack-anticheat/raw/master/anticheat%20-%20{VERSION}.zip
```
For instance, if I were to download version 0.4, I would type
```
/Troned/datapack-anticheat/raw/master/anticheat%20-%200.4.zip
```

If you are already on the world type 
```
/reload
```
Then follow any other steps.

To set up the anticheat in versions 0.3 and later, you must first type
```
/function ac:autochecks
```

## Features
* Jesus detection
* Flight detection
* Speed detection
* Xray detection
* Kilaura detection
* Nofall detection

* Enabling and disabling checks

## Changelog
### 0.4
* Fixed major issue where players could be teleported across the map
* Fixed minor issues such as players getting detected for nofall after landing on a slime block

### 0.3
* Added a feature to lag back players
* Added a feature to toggle checks

### 0.2
* Fixed issues with speed and killaura
