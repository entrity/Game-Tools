# Steam Speedup on Linux

## Omit `steamwebhelper`

Open steam with these command line options
```bash
steam -no-browser -console +open steam://open/minigameslist
```

_**LEGO: The Hobbit** was working alright for weeks but suddently became unplayable, and no amount of restarts would help. I did this and also tried 'force compatibility mode' and chose an earlier Proton when running **LEGO: The Hobbit**. I don't know what the contributing difference was but it went from unplayable to better than before._

## `PROTON_NO_ESYNC`

In a game's Preferences > General > Launch Options, declare the variable `PROTON_NO_ESYNC=1`. This is said to make frame rates worse in most cases but can prevent crashes if cutscenes are a problem.
