# Random Graion Magic

This mod features various spell-related tweaks by Graion Dilach for games on the Infinity Engine.

## __COMPATIBILITY DISCLAIMER AND GENERAL INSTALL ORDER SUGGESTIONS__

For the best result, components which are compatibility fixes and/or tweak specific spells can be installed anytime after their dependencies are already in place and generally assume to be installed directly after them. (Immediately after Spell Revisions for SR-specific components, immediately after IWD spells for components covering an SR+IWD case, etc.).

Unless specifically mentioned; Spell Revisions Revised isn't supported and results aren't guaranteed. The SR+IWD Spells ccomponents assume Spell Revisions was installed first.

Components tagged as ClassSpellTool are pure spell additions and require to be installed after all kitmods. They are also incompatible with platforms where UI modding isn't available (iOS, Android).

Due to the requirements can lead to the mod being installed in multiple passes, the Project Infinity ordering metadata will remain vogue. This is not a bug.

## List of components:

### Component 100: Add back Spell Immunity against Spell Revisions \[ClassSpellTool\]

This component installs Spell Immunity as an additional spell, while leaving the Spell Revisions Dispelling Screen untouched. Spell Immunity scrolls will appear in all shops where thhe Dispelling Screen scroll is available.

### Component 115: Add back vanilla True Sight as a level higher spell against Spell Revisions \[ClassSpellTool\]

This component installs the unnerfed True Sight as level 6 True Vision spell, available to all priests and mages. True Vision scrolls will appear in all shops where the Mass Invisibility scroll is available.

This component also grants a charge of True Vision innates on every eighth levelup to Inquisitors from the 9th level onwards.

### Component 120: Maximize Cure Wounds' effect in Spell Revisions

This component changes the Cure ? Wounds spells so that they always roll the maximum on their dice.

### Component 125: Install Spell Revisions standard Conjure Water Elemental when IWD spells from IWDification/SCS are installed

When Spell Revision is installed before the IWD spells from the above mods, the IWD spell library will recognize the SR level 6 elemental additions and skips generating their own from the level 5 counterpart spells. However, because SR does not install water elementals at all, the level 6 Conjure Water Elemental spell never gets created, but because this spell is still expected by the default SCS AI settings, the user caan end up with occasional Not_found warnings during installation of the Smarter Mages component and the advanced AI components derived from it.
This component installs handcrafted variants of the water elementals, following Spell Revisions rules and using the IWD2 water elemental artwork. Level 6 Conjure Water Elemental scrolls will appear in all shops where the level 6 Conjure Fire Elemental scroll is available.