### Changelog

[v1.2.2 - 14.07.2019](https://github.com/igromanru/Dark-Souls-III-Cheat-Engine-Guide/releases/download/1.2.2/DS3_v1.2.2_2019.rar)
- Added Rebirth Menu function call.
- Fixed BonfireWarp in "Helpers" header.
- Fixed Organization around the table, namely the Camera header
- Changed the name of the Stat Checker for clarity on what it does.
- Updated the table info (FAQ) with more information.

[v1.2.0 - 25.05.2019](https://github.com/igromanru/Dark-Souls-III-Cheat-Engine-Guide/releases/download/1.2.0/DS3_The-Grand-Archives_v1.2.0_2019.zip)  
The Grand Archives table changelog (anything un-credited is done by Loki)  
v1.1.9-fix 05/05/2019:
 - Added fix for ItemGib only giving 1 arrow/bolt at a time
 - Added some missing Goods IDs to ItemGib's dropdown
 - Fixed Perseverance Warmth PP script
by ametalon:
 - Session Info and ChrAsm now retrieve localized names with upgrade level for weapons/protectors/accessories, this requires CE 6.8.2+
by Gáté:
 - PP Classes expanded: WetAspectParam, Ceremony, ObjActParam, UpperArmParam, BonfireWarpParam, MapMimicryEstablishmentParam
 - PP version of Upgrades Need No Materials added under Param Patcher > All IDs patch
by Lucifer:
 - PP script to replace the models and icons of various weapons with cut content
 
v1.1.9-fix 01/25/2019:
 - ApplyEffect added to Helpers
 - Some more updates to ItemGib's dropdown
 - Quantity in ItemGib can no longer give multiple weapons/protectors/accessories, only goods
 - Discardable items script in Param Patcher v2.0.5 > Goods lets you discard gestures, key items and Storm Ruler from your inventory
 - ItemLotParam class and some fixes to EquipParamProtector class in Param Patcher
 - a bunch of minor stuff
 
v1.1.9-fix 12/09/2018:
 - ItemGib infusions and upgrade levels separated from the item dropdown
 
v1.1.9-fix 10/25/2018:
 - Param Toggles in Params header, you can disable params here
 - AddSoul added to Helpers, you can give yourself specified amounts of souls directly with this, should be safe?
 - BonfireWarp added to Helpers, you can warp from anywhere with it
 - PP Classes expanded: ShopLineupParam, ClearCountCorrectParam, CharaInitParam, RoleParam, PhantomParam
 - Access All Shop Inventory (PP version) added to All IDs patch category in param patcher
 - fixed ItemGib dropdown, again
by ametalon:
 - added disableMemrec function and used it in autodisabling records
 - added scripts to Find Address that jump to the memory areas
 - one form for help messages (Table Info etc)
 - removed README
 - entries in "Find Address" helper open "Memory view" window at selected address
 - added "How to" in "Find Address"
 - improved Copy Steam Profile scripts
 
v1.1.9-fix 10/10/2018:
 - Updated ItemGib dropdown, by purplE#7507
 
v1.1.8-fix 08/17/2018:
 - Table Info updated
 - AOB scans in open script and some others replaced with static addresses
 - Old AOB scans moved to deprecated
 - Some changes/fixes to Param Patcher classes
 - Invalid Crash Protection added to Scripts, by Coinsworth
 - Item Gib added to Helpers, Item Swap moved to deprecated, by Coinsworth
 
v.1.1.8-fix 05/15/2018:
 - Helper offsets expanded
 - Helper header mess removed
 - Last Spell Highlighted restored
 - Equipped Spells restored to non-messy
 - A bunch of sorting changes
 - Unnecesssary extra chrasms removed
 - World Flags no longer requires a script
 - Deprecated PP1 merged into PP2 compatibility
 - possibly other things I forgot
* [v1.1.9 - 07.10.2018](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/1fe25471974b5b53c56d541a1525256e/DS3_Reverse-Souls_v1.1.9.zip)
  * Removed: Unused items from Dropdowns
* [v1.1.8 - 09.02.2018](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/b4652e1062781d4d1a5712c6ccb70799/DS3_Reverse-Souls_v1.1.8.zip)
  * Fixed: Crash with CE 6.7
  * Added: Hero->Movement and Animations->Better Animation Cancel (by Pavuk)
  * Added: Hero->Load Start Character ID (by Pavuk)
  * Added: Scripts->ASM->Fps Disconnect (by Pavuk)
  * Added: Scripts->ASM->Map Collision (by Pavuk)  
  * Fixed: Helpers->Bullet, Effect, Goods, Attack, Behavior->Find Address->Attack AOB (by Pavuk)
  * Updated: Helpers->Bullet, Effect, Goods, Attack, Behavior->Attack Helper (by Pavuk)
  * Updated: Helpers->Targeted Entity Info (by Pavuk)
* [v1.1.7 - 11.10.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/7410eed93be981c970b40c0ffe8bf6bb/DS3_Reverse-Souls_v1.1.7.zip)
  * Added: Scripts->ASM->PvP Signs Cooldown (by Pavuk)
  * Added: Helpers->Highlighted->Accessory->Current Covenant in Slot (by Pavuk)  
  * Replaced: Helpers->Highlighted->Accessory->Last Accessory Highlighted (by Pavuk)
  * Added: Helpers->Highlighted->Goods Highlighted (by Pavuk)
  * Replaced: Helpers->Highlighted->Last Spell Highlighted (by Pavuk)
  * Added: Helpers->Highlighted->Sword Art Highlighted (by Pavuk)
  * Added: Helpers->Highlighted->Weapon Art Effect (by Pavuk)
  * Added: Hero->Movement and Animations->Moveset Swap (by Pavuk)
  * Added: Hero->Movement and Animations->Current Animation Name (by Pavuk)
  * Added: Hero->Movement and Animations->Jump Mod (by Pavuk)
  * PPv2:
    * Added: ObjectParamClass class (by Pavuk)
    * Added: BonfireWarpParam class (by Pavuk)
    * Added: HitSfxClass class (by Pavuk)
    * Added: ShopLineupParam class (by Pavuk)
    * Added: ItemLotParam class (by Pavuk)
    * Added: Several methods to AtkParam_Pc, EquipParamGoods, SpEffectVfxParam (by Pavuk)
* [v1.1.6 - 09.09.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/f1b6ea92777df709dab746773fc09bcb/DS3_Reverse-Souls_v1.1.6.zip)  
  * Fixed: Scripts->ASM->Item Vac (by Pavuk)
* [v1.1.5 - 07.09.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/9c20293bd5316dbf4c0c098747a68ce2/DS3_Reverse-Souls_v1.1.5.zip)  
  * Added: Scripts->ASM->Item Vac (by Pavuk)
  * Fixed: Hero->Movement and Animations->Gestures->Gestures Pointer (by Pavuk)
  * Fixed: Scripts->ASM->Access All Bonfires (by Pavuk)
* [v1.1.4 - 25.07.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/1fdb5fd37d3194817fa7d9f5fc7b92ea/DS3_Reverse-Souls_v1.1.4.zip)
  * Added: Hero->Character Equipment 2 (by InuNorii, Pavuk)
  * Added: Hero->ChrAsm 2 (by InuNorii, Pavuk)
  * Added: Param->Param Patcher->AtkParam_Pc->Sets damage of sacred flame (by Pavuk)
  * Added: Helpers->SpEffectVFX Helper
  * Improved: Noclip (by Autopilot)
  * PPv2 Fixed: AttackParam_PC renamed to AtkParam_Pc (by Pavuk)
  * PPv2 Added: SwordArtsParam, EquipParamAccessory and SpEffectVfxParam classes (by Pavuk)
* [v1.1.3 - 12.07.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/fb1bb3927979545072d406f45ab699a0/DS3_Reverse-Souls_v1.1.3.zip)
  * Added: Param->Param Patcher->Bullets->113 Turret (by Igromanru)
  * Added: Param->Param Patcher->Helper->Find address by ID in a param (by Igromanru)
  * Added: Scripts->Lua->Log taken damage (by Igromanru)
  * Added: Statistics->Last Bonfire->more Bonfires (by Pavuk)
  * Added: Statistics->ESC menu (by Pavuk)
  * Added: Statistics->PhantomParam (Color) (by Pavuk)
  * Added: More World Flags (by Pavuk)  
  * PPv2, Added: BehaviorParam_PC and AttackParam_PC classes
* [v1.1.2 - 03.07.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/408ce46362a348f8ca458ea6d17f66c8/DS3_Reverse-Souls_v1.1.2.zip)
  * removed some hotkeys
  * IgroWidgets, Added: methods enableRecordById, enableByDescription, disableRecordById, disableByDescription
  * PPv2, Added: BaseParamClass methods to read values
* [v1.1.1 - 29.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/ab255881526a0d7446b06174f76d5f36/DS3_Reverse-Souls_v1.1.1.zip)
  * Improved: Scripts->Lua->Prevent Autopilot (credits to PhokZ)
  * Added: Param->Param Patcher->Helper->ThrowParam Helper
  * Added: Param->Param Patcher->Helper->... (more helper functions)
  * PPv2 Fixed: Bullets spEffectId0 offset
  * PPv2 Fixed: method paramDepatcher
  * PPv2 Added: methods isEmpty and isNotEmpty
  * PPv2 Added: methods printParams, printParamsIds and getParamAddress
* [v1.1.0 - 27.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/40915d13aec7c4cc5b23ddf929876b6d/DS3_Reverse-Souls_v1.1.0.zip)
  * Reorganization: Moved related features under proper headers
  * Fixed: Custom Types: Armor ID, Ring ID and Spell and Goods ID
  * Named: WeaponArtIf offset in the SwordArtsParam
  * Improved: Hero->Movement and Animations->Gestures->Gesture walk script, now works as expected (by Igromanru)
  * Improved: Hero->Movement and Animations->Gestures->Gestures pointer (by Igromanru)
  * Moved: Param Patcher Initializer to WIP->Deprecated
  * Added: Statistics->Target Bonfire (by Pavuk)
  * Added: Flags->Misc->isCollisionEnabled (by Pavuk)
  * Added: Offsets description for +228 and +198 in Last Weapon Highlighted (by Bonzay0 and Rhino)  
  * Added: Scripts->Lua->Auto Revive (by Igromanru)
  * Added: Scripts->Lua->Prevent Autopilot (by Igromanru)
  * Added: Scripts->Lua->Pickup warning system (by Igromanru)
  * Added: Scripts->Lua->Stats warning system (by Igromanru)
  * Added: Hero->Appearance->FaceData->Save / Restore to/from file (by Igromanru)
  * Added: Param->Param Patcher v2.0 Beta  (by Igromanru)
* [v1.0.11 - 13.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/d7421a9c538f91ced982dbe56a269f4c/DS3_Reverse-Souls_v1.0.11.zip)
  * Changed: Last Weapon Highlighted->spAtkcategory to 2 byte
  * Added: Helpers->Effect Helper->Offsets: frostPattackPower, darkDamageCutRate, darkDifferenceRate, darkAttackPower, registFrostChange (thanks to Ainsley Harriott)
  * Added: Perserverence Warmth script
  * Added: BehaviorParam_PC (by PhokZ)
  * Added: SwordArtsParam (by PhokZ)
  * Added: patchAllSwordArts function to ParamPatcherUtils.
* [v1.0.10 - 06.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/59e5e5b14b846128fb55124d29bbbec9/DS3_Reverse-Souls_v1.0.10.zip)
  * Fixed: Offsets in new Helpers headers
* [v1.0.9 - 05.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/4610b7453bce567f65809c6e632f6f5e/DS3_Reverse-Souls_v1.0.9.zip)
  * Upgraded and Fixed: DropdownAdder and DropdownRemover (by Igromanru)
  * Replaced: Item Swap->Dropdown with Dropdown adder.
  * Removed: Custom Type "Item ID Rounder"/"Weapon ID Rounder"
  * Added: Param Patcher Initializer->All IDs patching->All bullets gives Bonfire & Budding Green Moss on Hit
  * Update: IgroWidgets
  * Added: Dropdown to Hero->Equipped Spells->(all) (by Igromanru)
  * Added: Dropdown to Hero->Character Equipment->(all) (by Igromanru)
  * Added: Custom Types for Armor, Rings, Goods and Spells (by Igromanru)
* [v1.0.8 - 03.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/e26069942da2a989be03cca1c31577ee/DS3_Reverse-Souls_v1.0.8.zip)
  * Fixed: pointer from Enable ChrAsm. (by Monarch)
  * Fixed: Effect Helper CycleOccurence and AtkOccurence offsets.
  * Reorganized: Moved some helpers offsets into headers.
* [v1.0.7 - 01.06.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/c96ce6025c684328ec0dc69a5936c07b/DS3_Reverse-Souls_v1.0.7.zip)
  * Added: Disable Backread Toggle, Toggle Draw and No update offset update (provided by Monarch)
  * Added: Hero->Character Equipment->Primary Arrows (by RBT)
  * Improvement: Free cam, Omnission mode fixed (by Phokz)
  * Fixed: uncaterocized in debug stuff (by Phokz)
  * Added: FPS boost to camera scripts for players (by Phokz)
  * Upgraded: Helpers to Phokz latest Helpers
  * Added: Helpers->Entity Control Helper (by Phokz)
  * Added: Statistics->Increase LockOn Range from Phokz table
  * Replaced: ForefrontTheX's gestrue walk with original from Phokz/Zullie
  * Added: More Param Patcher Tutorial scripts
  * Added: Session Info->Current Online Session->Add All Phantoms to the Black Separation Crystal (by igromanru)
  * Added: Param Patcher->All IDs patching->... (by igromanru)
  * Added: ReadParamIdTable function to Param Patcher (by igromanru)
* [v1.0.6 - 14.05.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/cf661b143f37d899acab0e07da98efef/DS3_Reverse-Souls_v1.0.6.zip)
  * Moved: Byte Array Converter to Open->Tools
  * Added; Float to Byte Array Converter (by igromanru)
  * Added: Movement and Animations->Gestures->Gestures Pointer (by igromanru)
  * Added: Wold Flags->Bosses->Demon Prince (by RBT)
  * Added: Wold Flags->Non-respawning enemies->Minibosses more flags (by RBT)
  * Added: Wold Flags->Non-respawning enemies->NPCs more flags (by RBT)
  * Added: World Flags NPC's (by Pavuk)
  * Fixed: Movement and Animations->Gestures->Gesture walk (by igromanru)
  * Fixed: Access All Bonfires (by Phokz)
  * Updated: few Tutorial scripts
* [v1.0.5 - 06.05.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/e703e94d76595e224d703cc9fc3af905/DS3_Reverse-Souls_v1.0.5.zip)
  * Added: Scripts->Kill all mobs in the area (by /u/MajinCry)
  * Added: Byte Array Converter (by igromanru)
  * Fixed: Helpers->Last Spell Highlighted->Bullet 3 Offset (by Rhino)
  * Added: World Flags->Non-respawning enemies (by RBT)
  * Added: World Flags->Doors and Shortcuts->Farron stuff (by RBT)
  * Added: World Flags->Gestures->My thanks (by RBT)
* [v1.0.4 - 05.05.2017](https://gitlab.com/igromanru/Dark-Souls-III-tables/uploads/9e9290ee0d836056f3c393d390bd6b50/DS3_Science-Souls_v1.0.4.zip)
  * Added: Auto code backup and restore for some scripts (by igromanru)
  * Added: Param Patcher->Tutorials Script->Pyromancy Flame cast everything
  * Fixed: Targeted Entity Info on disable crash (by igromanru)
  * Fixed: Last Hit Entity Info on disable crash (by igromanru)
  * Improved: Unlock summoning limit, it's now setting the player count to 1. (by igromanru)
  * Added: Param Patcher Initializer->Restrict Malicious Effects->Restrict All Malicious Effects (by igromanru)
  * Hotkeys: Set Alt+1 also for Restrict All Malicious Effects
  * Added: 41-44 and 48-54 Offsets names in Last Spell Highlighted (by Rhino)
* [v1.0.3 - 26.04.2017](https://mega.nz/#!DYdFHbya!saVVcHXv2hoUjq_wHoFRSnzD0FBD9YZ4Meq7E-E85Tw)
  * Added: DLC Bonfire Flags (by Aerthas Veras)
  * Added: Movement and Animations->Gesture walk (by igromanru)
  * Added: Movement and Animations->Animation Cancel  (by Autopilot)
* [v1.0.2.0 - 23.04.2017](https://mega.nz/#!XRsw2BYR!8tOcLa8-BuGzW51lHgB2_C_svDf6UrDYmt9g62FPd-Y)
  * Added: Helpers->Targeted Entity Info->Model ID (by Zullie the Witch)
  * Added: Helpers->Last Hit Entity Info->Model ID (by Zullie the Witch)
  * Added: Scripts->Unlock summoning limit (by igromanru)
  * Added: Session Info->World->Players count (by RBT)
  * Added: Max Reinforce Level (ban warning)
* [v1.0.1.0 - 20.04.2017](https://mega.nz/#!PFk1kbaD!gO5Njjl8JEDW0da4ZoaYZVHQ97vyh5mC6kfUMu7XUbw)
  * Added: New idle animations
  * Added: Hotkey to reset idle animations
  * Moved: Address assist scripts into group
  * Reorganized: Weapon helper values
  * Renamed: Some values for better understanding
* [v1.0.0.0 - 19.04.2017](https://mega.nz/#!fUkTXJyY!ZG45UAjklUXHHAdD-22qyKDmaxj_PTcQjRwATeLrULQ)
  * Assigned a version to the table, it begins with v1.0.0.0.
  * Fixed: Noclip script, it will now be enabled on check.
  * Added: Updater Script
  * Hotkeys: Unlimited iFrame is Alt+1 now
* [18.04.2017](https://mega.nz/#!mB1RlbQD!nRBEfo0iACZG7Pfs-aHReMIfC_3Rj73-ThcSCOy_PbI)
  * Added: few Hotkeys (see table Extras)
  * Added: Param Patcher->Tutorial scripts (by Aerthas Veras)
  * Added: Param Patcher->Restrict Malicious Effects->Restrict "Malicious Effects"->Manual Control
  * Added: Movement and Animations->Idle Animation
  * Rearranged: Hero->Attributes (by Ace of Fours)
  * Removed: Assorted scripts
* [14.04.2017](https://mega.nz/#!TZUkha6J!A5IkEQMTw2vmhQu6xLTLeG5md4eBzZzU5kOGoTxdvQ8)
  * Fixed script syntax: Access All Bonfires (sorry my bad)
* [13.04.2017 second release](https://mega.nz/#!Xct2hTba!giX6TfKbYDbkvMUXdzZbx38rI24BcHfXogCHQKQpg4M)
  * Fixed: Access All Bonfires (by Autopilot)
  * Fixed: No Durability Damage (by Autopilot)
* [13.04.2017](https://mega.nz/#!nI9klQKI!yjymWUHRKV7wPjZJsRjpgZsWYNOSaVBSW2fGAkLHyDY)
  * Fixed: No Goods Consume (by Autopilot)
  * Fixed: Param Patcher Initializer (by igromanru)
  * Still broken: No Durability Damage
* [12.04.2017](https://mega.nz/#!LA9wlTiK!YAqdxwtoSfZWMn5tc40n0gZoFuq9g9RQWaUqdGJlvig)
  * Fixed: mislabeled ring IDs (by Lance)
  * Fixed: Last Weapon Highlighted with correct addresses (by Lance)
  * Changed: some descriptions (by Lance)
* 09.04.2017 second release
  * Fixed: Recently Played With (by terenceyao)
  * Fixed crash: No Durability Damage (by igromanru)
  * Added: Spears of the Church covenants to Session Info (by igromanru)  
* 09.04.2017
  * Fixed: Last Hit Entity Info (by igromanru)
  * Fixed: Targeted Entity Info crash on uncheck (by igromanru)
  * Still need a fix: No Durability Damage
* 08.04.2017 third release
  * Reorganized the table (by Ace of Fours)
  * Added: new boss flags (by Ace of Fours)
  * Added: Last 5 Bullets Fired (by Science Souls Discord)    
* 08.04.2017 second release
  * Fixed: Targeted Entity Info (by Autopilot & igromanru)
* 08.04.2017:
  * Fixed: Invasion Type (by Malcolm Reynolds)
  * cause crash after a while: No Durability Damage
* 07.04.2017:
  * Fixed: Param Patcher (by igromanru)  
* 04.04.2017:  
  * Added: Line of Sight LockOn Deactivate Time (Hero>Statistics) (by dec1337)
  * Added: Spears of Church covenant (Hero>Covenants) (by dec1337)
  * Fixed: Find Item with ID (by dec1337)
* 30.03.2017:  
  * Fixed: Auto-Save (by dec1337)
  * Fixed: Last Bonfire (by dec1337)
  * Fixed: Save Slot (Hero>Statistics) (by dec1337)
  * Fixed: Unlock All Bonfires script (by dec1337)    
* 26.03.2017:  
  * Fixed: Fall Death Camera (by terenceyao)
  * Fixed: Hero -> Base Stats -> Speed Modifier (by terenceyao)
  * Fixed: Character Flags -> No Goods Consume (by terenceyao)
