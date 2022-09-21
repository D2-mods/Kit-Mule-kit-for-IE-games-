Kit Mule

GitHub: https://github.com/D2-mods/Kit-Mule-kit-for-IE-games-


Info
- Installs a kit that learns every kit/class ability (including HLAs and mod-added ones)
- The ability table is built at install time and is based on your current install.
- usable with EEs and classic BG2


Installs under 3 classes:
- Fighter
- Bard
- Druid

NOTE: Install time may take a little longer than a normal kit mod


config.ini
- set max level/column to check in kit tables (default = 20)
- enable or disable scanning clab, hla, or mod files
- enable or disable installing fighter, bard, or druid kits

The "level" setting will accept values from 1-50. Any other number will default to 20.
Previous errors caused by uneven column numbers should no longer occur.



Notes:
- mod made with Notepad++, WeiDU, and Near Infinity
- uses ADD_KIT_EX function by Argent77 (https://github.com/Argent77/A7-add_kit_ex)
- uses 2DA_MISSING_COLS function by K4thos (https://github.com/K4thos/IE-code-repository)
- LibIconv (http://gnuwin32.sourceforge.net/packages/libiconv.htm)

v0.4
- added options to disable scanning clab, hla, or mod files
- kit now has 100 in Set Traps skill at level 1

v0.5
- added subcomponent: Use default settings (ignores config.ini but doesn't reset it)

v0.6
- config file: Level settings above 40 should no longer cause errors
- Note that this mod doesn't edit any existing 2da files (everything is done inlined)
