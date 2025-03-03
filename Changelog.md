Relevant Milestone: [SEUT 1.1.0](https://github.com/enenra/space-engineers-utilities/milestone/29)

# Changelog
* Added [#13](https://github.com/enenra/space-engineers-utilities/issues/13): Animation support. Create and export animations with Blender and SEUT to use with the [Animation Engine by Math0424](https://steamcommunity.com/sharedfiles/filedetails/?id=2880317963). (Alpha 1)
* Added [#345](https://github.com/enenra/space-engineers-utilities/issues/345): Ability to select existing `HKT`-file as a collision instead of creating your own. (Alpha 1)
* Added [#359](https://github.com/enenra/space-engineers-utilities/issues/359): Error checking and handling for character modding. (Alpha 2)
* Improved: Moved internal materials to `SEUT.blend` in assets folder. (Alpha 2)
* Improved: Error detection in custom materials. (Alpha 2)
* Improved: Better input validation for SubtypeId. (Alpha 2)
* Improved: Many changes to streamline the Planet Editor Interface. (Alpha 2)
* Improved: Clarified error message for `E035`. (Alpha 2)
* Improved: Added many more PlanetGeneratorDefinition `SBC` elements to the interface. (Alpha 2)
* Changed [#354](https://github.com/enenra/space-engineers-utilities/issues/354): SEUT now treats `TIF`, `TGA` and `PNG` equally as source files but conversion still defaults to `TIF`. (Alpha 2)
* Fixed [#152](https://github.com/enenra/space-engineers-utilities/issues/152): Various issues with character import. (Alpha 2)
* Fixed: `FBX` import would import models with inverted Y-axis facing. (Alpha 2)
* Fixed: Planet Editor did not output `GroupId` nor `ModifierId` for Environment Items. (Alpha 2)
* Fixed: `Texture Conversion` in some cases converted unneeded files. (Alpha 2)
* Fixed: Inaccurate description for `Remap Materials`-operator. (Alpha 2)
* Fixed: Empty drift on character export. (Alpha 2)
* Fixed: Rare issue when patching `BLEND`-files. (Alpha 2)
* Fixed: Bone positions being wrong on character / animation import. (Alpha 2)
* Fixed: Numerous fixes to Planet Editor `SBC` output. (Alpha 2)
* Fixed: Planet Editor Biome Map output was highly inaccurate.(Alpha 2)
* Fixed: If Planet Editor was set to `No SBC`, export would fail. (Alpha 2)
* Fixed: In some cases, the Planet Editor did not recognize a Mod Path as valid and prevented export. (Alpha 2)
* Fixed: The username not getting correctly overwritten in the log in some cases. (Alpha 2)
* Fixed: Log output formatting for paths in header missing tabs. (Alpha 2)
* Fixed: In some cases, `Distribution Rules` would not correctly be associated with new `Environment Items`. (Alpha 1)
* Fixed: Numerous items not persisting across BLEND file loads. (Alpha 1)

# Installation
Refer to the [install guide](https://semref.atlassian.net/wiki/spaces/tutorials/pages/131411/SEUT+Installation+Guide).

# How to Update
## Manually
1. Open a new, empty, file in Blender.
2. Go to `Edit --> Preferences... --> Add-ons` and remove `Modding: Space Engineers Utilities`.
3. Click `Install...` and select the newly downloaded `space_engineers_utilities_***.zip`.
4. Re-enter the paths in the addon's preferences.
5. Restart Blender.

## With BAU
Closely follow the instructions inside the BAU menu, including restarting Blender after the update is complete.