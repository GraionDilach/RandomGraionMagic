# Random Graion Magic

This mod features various spell-related tweaks by Graion Dilach for games on the Infinity Engine.

## __COMPATIBILITY DISCLAIMER AND GENERAL INSTALL ORDER SUGGESTIONS__

This mod is only compatible with the Enhanced Edition version of the games.

For the best result, components which are compatibility fixes and/or tweak specific spells can be installed anytime after their dependencies are already in place and generally assume to be installed directly after them. (Immediately after Spell Revisions for SR-specific components, immediately after IWD spells for components covering an SR+IWD case, etc.).

Unless specifically mentioned; Spell Revisions Revised isn't supported and results aren't guaranteed. The SR+IWD Spells components assume Spell Revisions was installed first.

Components tagged as ClassSpellTool are pure spell additions and require to be installed after all kitmods. They are also incompatible with platforms where UI modding isn't available (iOS, Android).

Due to the requirements can lead to the mod being installed in multiple passes, the Project Infinity ordering metadata will remain vague. This is not a bug.

## List of components

### Component 100: Add back Spell Immunity against Spell Revisions \[ClassSpellTool\]

This component installs Spell Immunity as an additional spell, while leaving the Spell Revisions Dispelling Screen untouched. Spell Immunity scrolls will appear in all shops where the Dispelling Screen scroll is already available.

### Component 115: Add back vanilla True Sight as a level higher spell against Spell Revisions \[ClassSpellTool\]

This component installs the unnerfed True Sight as level 6 True Vision spell, available to all priests and mages. True Vision scrolls will appear in all shops where the Mass Invisibility scroll is already available.

This component also grants a charge of True Vision innates on every eighth levelup to Inquisitors from the 9th level onwards.

### Component 120: Maximize Cure Wounds' effect in Spell Revisions

This component changes the Cure ? Wounds spells so that they always roll the maximum on their dice.

### Component 125: Install Spell Revisions standard Conjure Water Elemental when IWD spells from IWDification/SCS are installed

When Spell Revision is installed before the IWD spells from the above mods, the IWD spell library will recognize the SR level 6 elemental additions and skips generating their own from the level 5 counterpart spells. However, because SR does not install water elementals at all, the level 6 Conjure Water Elemental spell never gets created, but because this spell is still expected by the default SCS AI settings, the user can end up with occasional Not_found warnings during installation of the Smarter Mages component and the advanced AI components derived from it.

This component installs handcrafted variants of the water elementals, following Spell Revisions rules and using the Icewind Dale II water elemental artwork. Level 6 Conjure Water Elemental scrolls will appear in all shops where the level 6 Conjure Fire Elemental scroll is already available.

## Changelog

### Version 0.1

Initial release featuring components #100, #115, #120 and #125.

## Acknowledgements

Thanks for Spell Revisions for providing the inspiration for many of these components.

Thanks to OlvynChuru for the ClassSpellTool library, which allows to ensure restoring vanilla variants of spells with a lot less spell compatibility issues.

Thanks to argent77 for additional code snippets. Thanks to Bozerg for pointing out the Not_found errors, leading to component 125.

## Disclaimer

This mod is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC. This mod is also not developed, supported, or endorsed by BioWare, Black Isle Studios, Interplay Entertainment Corp., Overhaul Games or Beamdog. All other trademarks and copyrights are property of their respective owners.
