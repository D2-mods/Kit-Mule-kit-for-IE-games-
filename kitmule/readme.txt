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

You can set max level to anything, but an error will occur if it tries 
to read an entry that doesn't exist (due to uneven column numbers).



Notes:
- mod made with Notepad++, WeiDU, and Near Infinity
- uses ADD_KIT_EX function by Argent77 (https://github.com/Argent77/A7-add_kit_ex)
- LibIconv (http://gnuwin32.sourceforge.net/packages/libiconv.htm)

v0.4
- added options to disable scanning clab, hla, or mod files
- kit now has 100 in Set Traps skill at level 1

v0.5
- added subcomponent: Use default settings (ignores config.ini but doesn't reset it)
