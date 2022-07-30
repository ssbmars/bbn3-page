---
layout: page
title: Changelog
permalink: /changelog/en/
---
[![Tango link](../bbn3gettango.png)](https://tangobattle.com/){:target="_blank"}
## Alpha 0.1 (Aug 2021)

This changelog is a combined list of all of the updates to date, in addition to the latest changes.  
The log is split into 4 sections: "universal", "pvp-exclusive changes", "singleplayer version", and "misc. bugfixes & adjustments".  
Universal changes apply to all versions of the patch. PVP-exclusive changes only apply to the pvp patch. Singleplayer version changes only apply to the pve patch.  
While the previous 3 sections contain documentation for the differences between BBN3 and vanilla BN3, the fourth section, "misc. bugfixes & adjustments", details the differences between this BBN3 update and the previous update.  

# BBN3 changes (universal)

- Spanish translations have been implemented thanks to the hard work of the MNTWFL Translations group. The main download now includes a "Spanish" folder which contains Spanish versions of all of the existing BBN3 patches.
- When you have a trap equipped, you can view which one it is on your side. To your opponent it still shows up as "????".
- While in the Custom Screen, pressing Select will allow you to see any traps that you or your opponent have equipped.
- Shield ability input (B←)  is rebound to Select. The original input no longer works.
- Universal invis duration inflicted by "flashing" chips reduced to 60f.
- Wind attacks remove Barriers and Auras. This effect pierces intangibility and AntiDmg, but is blocked by shields.
- Damage is applied to barriers and auras even if Megaman is intangible when hit. 
- Added support for making an attack push MegaMan the maximum possible distance in one direction. This effect is referred to as BigPush.
- SuperArmor no longer defends against drag statuses (SmallPush/BigPush).
- MegaMan temporarily receives superarmor while stunned. This does not apply to vine Tangle status.
- MegaMan can now be pushed and pulled by wind gusts while stunned.
- The status effects that inflict push and pull can now move characters onto broken panels if the character has airshoes installed.
- TimeFreeze Parry's active window is increased to 6 frames. The cooldown for TFP is reset each time Megaman is hit, allowing for all hits of a multihit moves to potentially be parried. Reminder: TFP is activated by pressing Left before you are hit by an attack during timefreeze. If done successfully, it halves the damage of that hit.
- The back column on either player's side cannot be stolen.
- Objects are no longer instantly destroyed when hit by a breaking attack. Instead they receive 10 additional damage for each breaking hit.
- When you enter the Custom Screen without having used all the chips in your hand, those chips will not be deleted if you use the ADD function instead of selecting new chips.
- The bonus damage granted by elemental panels is now null element. This prevents the bonus damage from being multiplied additional times.
- The charge time for all Charge Shots has been slightly sped up.
- Shields have increased cooldown before they can be used again, but their cooldown is sharply decreased if they block anything. This also applies for the Block NCP.
- DarkChip attacks that are used without a DarkHole or DarkLicense will have their attack value reduced to 1/4 instead of poofing. DarkAura will activate and last for 4 seconds instead of poofing.
- The Giga chips and exclusive Styles from both White and Blue version are freely available to use.
- The 11th chip glitch has been fixed.
- Most of the Navi Customizer Programs have had their size shrunk. All NCPs come with their compressed shapes by default. Some have alternative shapes that can be toggled by hovering over them and pressing Select before they are placed on the Navi Cust.
- HP+ Part NCPs are changed to +50/+100/+200/+400 to go along with their significant size reduction.
- The WeaponLevel stat now scales with the buster atk stat. Every +2 Atk increases WeaponLvl by 1. This effect works without the need for installing the WeaponLvl NCP, however they still work normally in addition to this new effect.
- Introduced a new tier of armor known as LiteArmor. When equipped, it applies SuperArmor only while in the middle of an attack. While idle or in normal movement, MegaMan is vulnerable to being flinched. Currently it is not available as an individual NCP.
- HubBatch no longer halves HP. It instead sets a flat 300 HP reduction that is unaffected by BugStop. HubBatch grants the following effects: LiteArmor, AirShoes, Shield, Custom+1, BreakBuster, BreakCharge, UnderShirt.
- The NCP version of FastGauge (and its bugged effect, SlowGauge) will apply a speed that is slightly less intense than the chip variants. Each turn, the gauge's speed will increment slightly to get closer to the default speed. When a gauge chip overwrites the effect of the gauge NCP, the speed at the time of it being overwritten will be restored when the chip expires.
- When the FastGauge and SlowGauge NCPs go up against each other in pvp, they will cancel each other out and the battle will begin with normal gauge speed.
- Fixed a bug in vanilla pvp that caused the text for your chip to disappear when your opponent entered an attack animation.
- TimeFreeze chips fade in and out slightly faster.
- Many chips and NCP descriptions have been rewritten so they make more sense. There are also emojis to represent elements and dark chips now.
- Disabled Pause button during pvp.
- HP visually updates faster while taking damage or healing.
- MegaByte values are much smaller and only indicate useful info. Values range from 2-9. Regular chip capacity is 5, but can be increased up to 8 with the MB+ Navi Customizer Programs.
- For certain types of battles that are impossible to run from (pvp, sparring with navis, final boss fight), it will no longer give the option to run away from battle.

### Chips and Abilities (universal)

- A large amount of real-time chips have had their framedata significantly sped up. The attacks for some chips come out faster, but the majority of saved time comes from reducing the recovery frames on the end of moves. The exact values of these framedata changes will not be reiterated in this log, but that data can be found in the Preview 2 changelog.
- Many chips used to incur a state called "chip lag" in which Megaman would finish the attack animation and could move or fire the buster, but would not be able to use another chip until the chip lag ended. There was a heavy amount of chip lag on a lot of moves, resulting in chips that felt clunky and seriously limited the way you were allowed to play the game. This type of lag has been sharply reduced for nearly all chips.
- Anubis and Poison Pharaoh no longer pierce invis with their poison. The poison mask series still do.
- The Magnum series will now crack occupied panels instead of leaving them untouched.
- HolyPanel spawns directly under the player who uses it.
- NorthWind now pierces shields.
- The Sensor series of chips have had their duration time reduced by 3 seconds. When first spawned, Sensor will wait 60 frames before firing.
- DarkHole is no longer affected by the object limit and will not delete existing objects when spawned.
- FastGauge and SlowGauge only last for 3 turns. Once their turn limit is up they will reset the gauge speed.
- GrabBack and GrabRevenge return stolen panels and push the opponent back. The hit no longer pierces shields.
- FolderBack restores a max of 7 standard chips. Only attack chips are able to be restored, excluding Friendly Viruses and chips that can recover HP.
- GaiaSword/GaiaBlade will only consume the damage from wood element chips. Any chips that are not eligible to be consumed will not be deleted from your hand.
- AntiNavi no longer steals the following Giga chips: Bass, Bass+, Serenade, DeltaRay, and both AlphaArms. (These chips are still compatible with other effects that only work for "navi" chips.)
- Shadow and Mole grant an intangibility duration that scales with the speed of the custom gauge at the time of activation. During slowgauge their effects will last longer, during fastgauge their effects will expire quicker.
- Rush will no longer trigger AntiSword.
- AirSword can push cubes just like AirShot.
- You can mash the A button to use DeltaRay's command code.
- AntiRecov now reduces HP by 1x the recovery amount just like later games.
- AntiDmg will throw the star much earlier when triggered. The chip version now waits for MegaMan's current animation to finish before popping. The NCP version no longer removes other traps when it's used, it also gives the opponent no visible indicator when it's active.
- Reduced BodyGuard's kunai count from 18 to 9. Changed the timing so the kunais can combo into each other. 
- GutsPunch and GutsImpact cause BigPush (non-command input versions).
- The hit from AirSword applies BigPush.
- ElecSword inflicts stun.
- Throwable Bombs (Mini/Single/Double/Triple) cause flinching.
- Team1 and the Shake chips no longer cause flashing.
- The Needler chips no longer cause flinching or flashing.
- Some summoned objects have had their HP adjusted:
	- Rook  300
	- Meteors  210
	- Needlers  150
	- Team1  150
	- PoisonMask  40 (This is the HP of the mask while using the PoisonFace/PoisonMask chip.)
	- Prism  500 (Will not spread the damage from the attack that destroys it. Prism used to have infinite HP.)

# PVP-exclusive changes

- Most chips have had their atk values adjusted in addition to chip codes, classes, & elements. There are too many of these types of changes to list individually. Instead, the best way to view this information is to look at the chips in-game.
- Here is a list of chips that have had their damage values adjusted but do not display their atk value in-game:
	- LavaStage  50 → 25 (per panel)
	- Zcanon2  60 → 70
	- Zcanon3  80 → 90
	- Zstep1  130 → 200
	- ElemSwrd  150 → 160 (per hit)
	- TimeBom+  500 → 600
- CustomSword's atk value is changed to a linear increase relative to the custom gauge. The atk value stays maxed out while the gauge is fully filled.
- Muramasa's max atk is capped at 500.
- Some multihitting chips have had their atk value hidden. This makes them no longer able to be boosted by Atk+ chips. These chips still declare their atk value via the chip description.
- When selecting New Game on the title screen, you will load into a 100% pvp-ready game state.
- The universal damage multiplier for elemental weaknesses is now 1.5x instead of 2x.
- The damage multiplier for Elec element attacks on ice panels is now 1.5x instead of 2x.
- You can cycle quickly through every style with the "Style Change" option. The Navi Customizer Programs OilBody/Fish/Battery/Jungle will set your style to their respective element when ran on the command line. You can then remove them and their effect will persist until you change your style again.
- Custom Style has a passive Custom+3 boost.
- Team Style has a passive MegaFolder+2 and Custom+1 boost.
- Shield style's shield heal ability is reduced to healing 5% of max HP. This value scales with HP+ parts.
- Chips have individual limits for how many copies can be added to the folder. The quantity value to the right of each chip directly shows the max limit for how many of that chip can be in the folder.
- Error codes can be fixed by entering a completely blank code.
- EX Codes are highly abbreviated, ranging from 1-3 characters long. An in-game email explains all of the available EX Codes.
- There are new emails in Lan's inbox that explain important details about the game. The emails with the most important info will appear as unread when you start a new save file.
- Auras expire roughly twice as fast compared to vanilla.
- BeastMan no longer has the command input that allowed him to hit more than 3 times.
- Friendly viruses have had their atk system modified. They can no longer be fed and their stats cannot be redistributed. Most friendly viruses have had their atk values adjusted to have a more dramatic swing in possible damage output, with the weakest rolls being weaker and the strongest rolls being much stronger. They are essentially a gambling minigame that might reward you with high damage output but also might flop. To view the exact damage values of a friendly virus chip, check with the Progs in the virus breeder.
- The GutsMachineGun no longer inflicts flinching or flashing on any of its hits.
- RandomMeter, HoleMeteor, ShotMeteor, and Meteors no longer inflict flashing.
- Lava panels no longer inflict flashing.
- These chips have been disabled or replaced.
	- Metagal 2 & 3
	- Mole 2 & 3
	- Jealousy
	- BassGS
	- PlantMan & Flashman versions 1-4
	- every other Navi versions 3-5

### [PvP] misc. Quality of Life

- The chips in your backpack are infinite. The chip quantity indicator has been repurposed to show you how many copies of that chip can be added to your folder.
- Random virus encounters are disabled.
- Serenade's Time Trial battles don't switch to your xtrafolder. The Time Trial fights now feature the Omega versions of Navis. These fights can be used for testing folders.
- Lan's dog house as well as Tamako's kiosk will now take you directly to Secret Area.
- You can jack out of Secret Area by pressing R. The panel that used to jack you out will now teleport you to Secret Area 3.
- The ProtoMan Time Trial fight is replaced with Bass. Protoman can still be fought at Hades Isle
- The BowlMan fight accessible in the DNN netbattling machine is now a MistMan fight.
- Time Trial Navis will now display unique mugshots.
- The bosses that follow typical flinch behavior will now mimick the way MegaMan flinches. While already flinching, getting hit again will not refresh the flinch duration. This should allow for combo practice that better represents the timing required to combo real players. 

# Singleplayer version

- Keep in mind that any change listed under the "PVP-exclusive changes" section does not apply to the Singleplayer version of the game.
- Made GroundStyle possible to be acquired through normal gameplay.
- All Styles reach max level in 100 battles. It takes only 50 battles to obtain a new Style.
- Opposite-version gigas can be obtained through various methods, mostly via shops.
- Punk's chip can be obtained.
- Your Regular Memory is calculated differently. It begins at 2MB and caps at 5MB. Each RegUp you collect brings you closer to your next RegMem increase, but each increase requires multiple RegUp pieces before you see any effect. Keep in mind that you're essentially beginning the game with 20MB, so it shouldn't be surprising that it takes awhile to see the value increase.
- After receiving the Press NCP from Cossak, you will immediately gain the permanent ability to walk over press paths. Installing the NCP is not required.
- The Energychange NCP is always applied automatically.
- When starting a new save, the Mistman chips will be added to your library.
- The tutorial is skipped at game start.
- The ElemBody NCPs work normally, but they also set your next style's element to their respective element. 
- If the navicust is ran without an ElemBody NCP, your next style's element will be rerolled.
- Right outside the room with the final boss fight, Chaud will give you the DeltaRay Z giga and also restore the internet to its colorful palette when you talk to him.

# misc. bugfixes & adjustments

- Fixed visual error with the endlag of Block NCP always showing the sprite for Custom Style.
- Fixed exploit that allowed for extended invincible stalling while using AntiDmg with Slasher or PoisonFace/Mask.
- Fixed glitch that allowed Shake's damage to be overwritten by a different chip. This glitch can still be done in the Singleplayer version because it's a fun strat and we don't care if pve is unbalanced in a fun way.
- Fixed the bug in vanilla which would cause the Panic chip to freeze the game if used in an emulator that wasn't using BIOS. 
- Lowered the prices of opposite version gigas.
- Serenade's Time Trial will now reward the player with both the DarkAura and Serenade gigas.
- Wind now removes bubblewrap, plantman no longer takes damage from the wind hit that removes his leafshield
- Cleaned up the Chip Library so it accurately shows how many chips and PA memos are available.
- Reduced the amount of menus you have to navigate through in the comm menu.
- Fixed compatibility with the BN3 randomizer.
- Fixed some typos in the story.
- Made the reduced elemental bonus multiplier exclusive to pvp.
- Fixed the mistake where the buff to TimeBom's damage was applied to TimeBom+, which significantly nerfed the PA.
- Fixed a softlock that could occur with folderback.
- Fixed the bug where puffball viruses could one-hit-delete Megaman if he collided with their mask.
- Refactored the way press paths check if you can use them so that they can work without the Press NCP being installed. This will be important later.
- Lots of changes have been made under the hood in order to make BBN3 work with rollback netcode. 
