### v 2.1.1
- fix top navigation
- make display name of surrounding grid items configurable
- add optional "undo last move button" (#1)

### v 2.1.0
- compatibility with minecraft 1.13
- better defaults with Arrows in the navigation button names

### v 2.0.0
- update to gamebox v2
- updated config and lang files
- changed id!
  - '2048' -> 'twoofoureight'
#

### v 1.3.1
- check inventory title length if GB flag is set

### v 1.3.0
- push GB dep to 1.5.0
  - now compatible with /gba reload

### v 1.2.0
- centralised more code to GameBox
  - use static main-key from GUIManager (GameBox) for guis
  - chat color in Main class
  - Sounds
  - use ItemStackUtil from GameBox to load ItemStacks
- create lang folder when not finding lang_en.yml
- removed deprecated methods and variables (now depends on GB version 1.3.0)
- replace all non numbers in GB version
- correct lang_en


### v1.1.1
- checking for bad nav matData and handling it
- give link to gamebox when outdated
- added chinese language file
- improved default lang file
- improved default config and added more explanation