Kit Mule kit (L'accumulateur)

GitHub: https://github.com/D2-mods/Kit-Mule-kit-for-IE-games-


Info
- Ce kit apprendra toutes les capacités spéciales des classes et des kits présentes dans le jeu, y compris les capacités de haut niveau ainsi que celles ajoutées par les mods.
- La table des capacités est construit au moment de l'installation et est basé sur votre installation actuelle.
- Peut être installer sur les Enhanced Editions et sur BG2 original

v1.0
- Added component: Recreate abilities table
- This lets you update kit abilities at any time (more info below)


Ce kit s'installe pour les 3 classes suivantes :
- Guerrier
- Barde
- Druide

REMARQUE : L'installation peut prendre un peu plus de temps que pour un kit plus ordinaire.


Fichier "config.ini"
- définir le niveau (level) maximum / les colonnes à contrôler dans les tables des kits (default = 20)
- active ou désactive l'analyse des fichiers clab, hla ou des mods
- active ou désactive l'installation des kits de guerrier, barde, ou druide

Le paramètre "level" acceptera des valeurs de 1 à 50. Tout autre nombre sera par défaut égal à 20.
Les erreurs précédentes causées par des numéros de colonne inégaux ne devraient plus être un problème.


////////////////////////////////////////////////////////////

Informations sur les composants :

1. Composant principal
	- Option 1 : Utiliser le fichier de configuration (config.ini)
	- Option 2 : Utiliser les paramètres par défaut (ignore le fichier de configuration mais ne modifie pas vos choix pour ce même fichier (config.ini)
2. Recréer la table des capacités
	- Peut être réinstallé à tout moment (n'apparaît pas dans weidu.log)
	- Ce composant met à jour UNIQUEMENT la table des capacités du ou des kits.
	- Il ne peut pas modifier les kits installés
	- Si "Utiliser le fichier de configuration" a été choisi, ce composant utilisera le fichier "config.ini" présent dans le dossier principal "kitmule".

////////////////////////////////////////////////////////////


Notes:
- mod made with Notepad++, WeiDU, and Near Infinity
- uses ADD_KIT_EX function by Argent77 (https://github.com/Argent77/A7-add_kit_ex)
- uses 2DA_MISSING_COLS function by K4thos (https://github.com/K4thos/IE-code-repository)
- LibIconv (http://gnuwin32.sourceforge.net/packages/libiconv.htm)

v0.4
- added options to disable scanning clab, hla, or mod files
- kit now has 100 in Set Traps skill at level 1

v0.5
- added subcomponent: Use default settings (ignores config.ini but doesn't undo edits)

v0.6
- config file: Level settings above 40 should no longer cause errors
- Note that this mod doesn't edit any existing 2da files during the scanning process (everything is done inlined)

v1.0
- Added component: Recreate abilities table
	- This component can be reinstalled at any time after the main component is installed
	- It allows you to update the kit's abilities without needing to reinstall everything
	- It does not appear in weidu.log and can't be uninstalled (but doesn't need to be)
	- All mod files are removed from the override if the main component is uninstalled
- reorganized install folder files
