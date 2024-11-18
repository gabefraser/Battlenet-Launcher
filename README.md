# Battlenet Steam Overlay Launcher


Launcher utility to help start battle.net games with the steam overlay.

Thanks to dafzor / https://github.com/dafzor/bnetlauncher for making the original version years ago. Sadly they don't seem to maintain the original anymore, nor does launchpad work due to depreciated / dead dependancies. 

This is a continutation using my previous origin-launcher / fortnite launcher framework as a more reliable / futureproof method (assuming Blizzard doesn't change Battle.net's launch parameters.)


## Usage

If your Battle.net isn't installed at the default location, add the full path to Battle.net.exe as a launch parameter. ie; "C:/PROGRA~2/Battle.net/Battle.net.exe"

1. Extract the included exe to any location you want (ex: steam folder)
2. Add the exe to steam as a non-steam game shortcut
3. On the shortcut properties add one of the following parameters:

| game          | launch code                                                  |
| ------------- | ----------------------------------------------------- |
|Blizzard Arcade Collection | rtro|
|Call of Duty HQ| codhq|
|Call of Duty: Black Ops 4 | codbo4|
|Call of Duty: Black Ops Cold War | codbocw|
|Call of Duty: Modern Warfare | codmw2019|
|Call of Duty: Modern Warfare 2 Campaign Remastered | codmw2cr|
|Call of Duty: MWII / WZ2.0 | codmw2|
|Call of Duty: Vanguard | codvg|
|Crash Bandicoot 4: It's About Time | cb4|
|Diablo 2: Resurrected | d2r|
|Diablo 3 | d3|
|Diablo 3 Public Test Realm | d3ptr|
|Diablo 4 | d4|
|Diablo Immortal | di|
|Hearthstone | hs|
|Heroes of the Storm | hots|
|Heroes of the Storm Public Test Realm | hotsptr|
|Overwatch | ow|
|Overwatch Public Test Realm | owptr|
|Starcraft 2 | sc2|
|Starcraft Remastered | scr|
|Warcraft 1: Orcs & Humans | w1|
|Warcraft 1: Remastered | w1r|
|Warcraft 2: Battle.net Edition | w2|
|Warcraft 2: Remastered | w2r|
|Warcraft 3: Reforged | w3|
|World of Warcraft | wow|
|World of Warcraft Classic | wowclassic|
|World of Warcraft Public Test Realm | wowptr|


The result should look something like the example below:

`"G:\Steam\Battlenet-Launcher.exe" ow`

## World of Warcraft Classic - Season of Discovery

Not currently supported, I'm looking into how to fix it. ♥
