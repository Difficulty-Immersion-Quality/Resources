# 🔥Patch #8/Hotfix #36 - More performant, more polished, more balanced, more big DIQ.🔥

### ✅Don't forget to endorse the collection if you enjoy it! 😘 You can support the continued development of DIQ via my [Kofi](https://ko-fi.com/baldursgoonsack)!💖

***

- Read!📜Follow [updating instructions](https://gitlab.com/Difficulty-Immersion-Quality/Difficulty-Immersion-Quality/-/wikis/04-Updating)!
- [BG3MM](https://github.com/LaughingLeader/BG3ModManager) version [1.0.12.9](https://github.com/LaughingLeader/BG3ModManager/releases/tag/1.0.12.9).
- Get updated configs and load order [here](https://www.nexusmods.com/baldursgate3/mods/9784) or in the [Discord](https://discord.com/invite/baldursgoonsacks).
- Save safe!✅**BUT**, updating instructions must be followed and the following must actually be read.

***

- ❗️This revision is not entirely save safe! Best practice is to view all instances with a ❗️ below, and follow the updating instructions to a T.
- [Hit Dice RAW](https://www.nexusmods.com/baldursgate3/mods/22898) \
  \- ❗️If updating mid-playthrough, you might need to respect once updated to Revision 148+, even though (following best practices) you would have already done it prior. Otherwise you might not have the resources allocated from the level 1 progressions.
- [Many More Monsters](https://www.nexusmods.com/baldursgate3/mods/11639) \
  \- ❗️If updating mid-playthrough, the scale of these changes will surely cause some weird ongoings for the existing level(s) in your game.
- [Fade's Equipment Distribution (FED)](https://www.nexusmods.com/baldursgate3/mods/13824) *Fade's Equipment Distribution - FED - Osi*.\
  \- Swapped from *Fade's Equipment Distribution - FED - SE* to *Fade's Equipment Distribution - FED - Osi*, as the SE version is now deprecated.\
  \- ❗️If updating mid-playthrough, his change in distribution method will likely result in duplicate item spawns for the existing level(s) in your game.
- New games are totally fine, and updating from Revision 148 to 149-150 is no big deal either.

***

All the warnings out of the way, I'm actually VERY happy with how performant this update is. I don't notice any stuttering, being in windowed fullscreen is buttery smooth, things are just crispy and they'll only continue to get better. The reasons for why is a bit of a mix:

- Not using unoptimised script heavy mods that are vibe coded or otherwise just abusing pcalls and the like
- Taking an interest in optimising my own khn functions, refactoring my library
- Many other authors in the Baldur's Goonsacks community doing much the same, having their functions return early or ignoring items on their auras.

Something else worth highlighting is that [Many More Monsters](https://www.nexusmods.com/baldursgate3/mods/11639) shouldn't feel jarring to play with anymore. The encounters are much more balanced relative to vanilla ones, or encounters from other mods. Additionally, Cahoot and I resolved a great deal of bugs and laid groundwork to do more.

This revision has been the sum of hundreds of hours of development, it's a big step for making DIQ as good as it can be.

***

# Removed ([DIQ Archive](https://next.nexusmods.com/baldursgate3/collections/yif5lj?tab=changelog)) 🗑

### Spells:✨

- [Shadowheart Cantrip Night Piercer](https://www.nexusmods.com/baldursgate3/mods/1560) *Night Piercer SE*.\
  Overpowered, too accessible, destroys class identity; and I kept saying I'd patch it but just never did, so it's yeeted for now.

### Feats:💪

-

### Classes and class features:📊

- [Smart Cunning Action](https://www.nexusmods.com/baldursgate3/mods/8906) *SmartCunningAction*.
- [Riposte Enhanced](https://www.nexusmods.com/baldursgate3/mods/13143) *Riposte Enhanced 1.2.0*.\
  \- Riposte is now overhauled in [Goon's Fighter Overhaul](https://www.nexusmods.com/baldursgate3/mods/17926).

### Gameplay:🧌

- [WASD Character Movement](https://www.nexusmods.com/baldursgate3/mods/781) *WASD*.\
  \- Replaced by [BG3WASD Camera Follow (Fork) - Smooth Camera Modes](https://www.nexusmods.com/baldursgate3/mods/23413).
- [Native Camera Tweaks](https://www.nexusmods.com/baldursgate3/mods/945) \
  \- Replaced by [Native Camera Tweaks with GUI](https://www.nexusmods.com/baldursgate3/mods/22892).
- [Difficulty Immersion Quality Collection - Misc Files](https://www.nexusmods.com/baldursgate3/mods/9784) *Native Mod Configs*.\
  \- Wasn't updated to support the above mods, they're just working out of the box for now.&#x20;
- [Critical Miss Has Consequences](https://www.nexusmods.com/baldursgate3/mods/1883)&#x20;
- [Critical Miss Has Consequences FIXED](https://www.nexusmods.com/baldursgate3/mods/6050) \
  \- Both replaced by [Goon's Attack of Opportunity Overhaul with Optional Critical Miss AoO](https://www.nexusmods.com/baldursgate3/mods/23861) + [War Caster (2014 and 2024)](https://www.nexusmods.com/baldursgate3/mods/5822) *Critical Miss Retaliation*.
- [Use Highest Modifier in dialogue](https://www.nexusmods.com/baldursgate3/mods/2171) *Use Highest Modifier Mod*.
- [Use Best Sleight of Hand](https://www.nexusmods.com/baldursgate3/mods/5036) *BestLockpicking.zip*.\
  \- Both replaced by [Best in Party Skills](https://www.nexusmods.com/baldursgate3/mods/20091); cleaner, and multiplayer compatible.
- [Rebalance - Common Effects](https://www.nexusmods.com/baldursgate3/mods/5755)&#x20;
- [Rebalance - Nerfs](https://www.nexusmods.com/baldursgate3/mods/5712) *Rebalance - Nerfs (Common Effects)*.\
  \- While not directly replaced exactly, these are mods my own mods such as [Goon's Condition and Surface Overhaul](https://www.nexusmods.com/baldursgate3/mods/17320) are going to barge into at some point.
- [Impactful Backgrounds](https://www.nexusmods.com/baldursgate3/mods/8941) *Impactful Backgrounds 1.7.0*.\
  \- While I really like the concept of giving backgrounds more tangible stuff, it's some power creep I feel is best done away with for now.&#x20;
- [Features from DnD 5E Planescape](https://www.nexusmods.com/baldursgate3/mods/12096) *Features from DnD 5E Planescape - Nexus* + *Optional adjustments and nerfs*.\
  \- Critical bug with the current folder structure (2.2.1). The content isn't integrated as cohesively as [Features from DnD 5E Spelljammer](https://www.nexusmods.com/baldursgate3/mods/13195), so it's been a somewhat pending removal for a while.
- [Stackable ASI Feats - Uncapped Feat Selection and Ability Score Increases](https://www.nexusmods.com/baldursgate3/mods/13238) *Stackable ASI Feats - Planescape Patch*.
- [Deity Domains and Alignment](https://www.nexusmods.com/baldursgate3/mods/16607) *Deity Domains Planescape Patch*.

### Items:⚔️

- [Wifi potions v2 tm](https://www.nexusmods.com/baldursgate3/mods/5080) *Wifi\_potions\_2.0.4.0*.\
  \- Replaced by [Wye Fey Potions](https://www.nexusmods.com/baldursgate3/mods/23323); isn't exploitable, also gives support for [Grit and Glory - Injuries Exhaustion and Madness - MCM](https://www.nexusmods.com/baldursgate3/mods/14863)'s Injury Kits.
- [Tomes and Manuals](https://www.nexusmods.com/baldursgate3/mods/12914) \
  \- Power creep and bugs.
- [Vest of Investiture](https://www.nexusmods.com/baldursgate3/mods/13591) *Tough Vest*.
- [Soul Knife Equipment](https://www.nexusmods.com/baldursgate3/mods/13717)&#x20;
- [Barbarian of our Heart - Endgame Barbarian Legendaries](https://www.nexusmods.com/baldursgate3/mods/13929) *New Vendor Locations*.\
  \- [Cordelliia](https://www.nexusmods.com/baldursgate3/users/4780564)'s stuff tends to be OP.
- [JWL Discordant Instruments for Patch 7](https://www.nexusmods.com/baldursgate3/mods/17536) \
  \- Replaced by my WIP [Difficulty Immersion Quality Collection - Misc Files](https://www.nexusmods.com/baldursgate3/mods/9784) *JWL Discordant Instruments Enhanced Revamped*.

### Dialogue and cutscenes:🤗

- [Platonic Halsin - No Confession or Shy Halsin Versions](https://www.nexusmods.com/baldursgate3/mods/18583) *ShyHalsin*.\
  \- Folk appeared to be having issues romancing Halsin at all, even when meeting all the criteria the mod lists. I investigated it in a cursory fashion, but came up short so it's just removed for now.&#x20;

### UI:💻

- [Item Prefix for Sorting (add Tag)](https://www.nexusmods.com/baldursgate3/mods/21566) \
  \- Performance concerns around excessive use of pcalls in the lua, etc.

### Visuals:📸

- [P4 Patches](https://www.nexusmods.com/baldursgate3/mods/353) *Patches\_for\_VFX\_Heads*.\
  \- Made redundant by [Head VFX Universal Automatic Patcher (UAP)](https://www.nexusmods.com/baldursgate3/mods/22716).
- [Astarion's pre-patch 4 restored skin](https://www.nexusmods.com/baldursgate3/mods/3973) *Astarion's pre-patch 4 skin fix*.\
  \- Replaced by [Galestarion](https://www.nexusmods.com/baldursgate3/mods/23900).
- [More Abs Karlach](https://www.nexusmods.com/baldursgate3/mods/13981) \
  \- Replaced by [ABSolutely Companions](https://www.nexusmods.com/baldursgate3/mods/19073) *ABSolutely Karlach*.
- [Mystra Midnight Lover](https://www.nexusmods.com/baldursgate3/mods/8694) \
  \- Replaced by [Mystra Edits - The Mother of All Magic](https://www.nexusmods.com/baldursgate3/mods/17954).

### Character customisation:👗

- [Elledwyn Hairstyles - Autosnapping hair with custom physics (WIP) - DELETED](https://www.nexusmods.com/baldursgate3/mods/17842) *Elledwyn Hairstyles (WIP)*.\
  \- Replaced by [Elledwyn Hairstyles (Reupload)](https://www.nexusmods.com/baldursgate3/mods/23172).

### Other:🔍

-

***

# Moved 📨

### Moved to optional mods: 💯

-

### Moved from optional mods to main list: 💯

-

### Moved to [DIQ Extras](https://www.nexusmods.com/games/baldursgate3/collections/k3zucg): 👔

- [Ellian's Hair](https://www.nexusmods.com/baldursgate3/mods/1394)&#x20;
- [Ellian's heads](https://www.nexusmods.com/baldursgate3/mods/2939) *Ellian's Heads (no requirements)*.
- [Midnight Lover Set (Body 1 and 2) - DELETED](https://www.nexusmods.com/baldursgate3/mods/8665) *BW\_Midnight\_Lover\_Set*.

### Moved from [DIQ Extras](https://www.nexusmods.com/games/baldursgate3/collections/k3zucg) to [DIQ](https://next.nexusmods.com/baldursgate3/collections/pns4qv): 👔

- [Durge's mangled head - Dark Urge Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/9702)&#x20;
- [Crystal Crown Pearl - Gem Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/13329)&#x20;
- [Rathgor - Reforged head - Dark Urge Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/10343)&#x20;
- [Pearl - Seadragon - Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/10761)&#x20;
- [Vexa - Dark Urge Slayer Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/11622)&#x20;
- [Dragonborn Extra Tabs - Horns and Hair](https://www.nexusmods.com/baldursgate3/mods/12876)&#x20;
- [Reforged Assets - Dark Urge Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/13313)&#x20;
- [Durge's Horns - Dark Urge Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/13315)&#x20;
- [Seadragon Assets - Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/13324)&#x20;
- [Slayer Assets - Dark Urge Dragonborn CC](https://www.nexusmods.com/baldursgate3/mods/13525)&#x20;
- [Quil to Pearl - NPC Dragonborn replacer](https://www.nexusmods.com/baldursgate3/mods/15717)&#x20;

### Moved to [DIQ Horny](https://www.nexusmods.com/games/baldursgate3/collections/1uysmm): 🥵

-

### Moved from [DIQ Horny](https://www.nexusmods.com/games/baldursgate3/collections/1uysmm) to [DIQ](https://next.nexusmods.com/baldursgate3/collections/pns4qv): 🥵

-

***

# Added 📦

### Spells:✨

- [One Levelled Spell Per Turn](https://www.nexusmods.com/baldursgate3/mods/23218) *One Levelled Spell Per Turn - 2014 RAI*.\
  \- This is a significant overhaul to the action economy, and a bold step towards establishing a meta that reflects the source material.\
  \- This coupled with me addressing multi-attack spells abusing damage riders and other triggers in [Goon's Gear and Throwing Overhaul](https://www.nexusmods.com/baldursgate3/mods/15126), as well as other plans such as making Flurry of Blows require you take the attack action prior to use in [Goon's Monk Overhaul](https://www.nexusmods.com/baldursgate3/mods/17706) is going to allow the power ceiling to be brought way down; and by extension the game can be kept difficult without giving a careless buffet of buffs to enemies, that can hinder immersion and cohesion.
- [Familiar Casting and Fixes](https://www.nexusmods.com/baldursgate3/mods/6149) *Mage Hand Support*.
- [Sights of the Seelie Overhaul](https://www.nexusmods.com/baldursgate3/mods/23318)&#x20;
- [Animating Spores Nerf](https://www.nexusmods.com/baldursgate3/mods/23275)&#x20;
- [Wish Spell](https://www.nexusmods.com/baldursgate3/mods/23446) *Wish*.

### Feats:💪

- [War Caster (2014 and 2024)](https://www.nexusmods.com/baldursgate3/mods/5822) *Critical Miss Retaliation*.\
  \- Huge thanks to [wesslen](https://www.nexusmods.com/baldursgate3/users/89809) for creating this so it functions alongside [Goon's Attack of Opportunity Overhaul with Optional Critical Miss AoO](https://www.nexusmods.com/baldursgate3/mods/23861).
- [Essential Feats](https://www.nexusmods.com/baldursgate3/mods/5623) \
  \- I need to fix some semi-botched patching for this one, expect that in Revision 151.
- [Feats Overhaul](https://www.nexusmods.com/baldursgate3/mods/15044) *FeatsOverhaul HitDicePatch* & *FeatsOverhaul TavernBrawlerPatch*.

### Classes and class features:📊

- [Hit Dice RAW](https://www.nexusmods.com/baldursgate3/mods/22898) \
  \- ❗️If updating mid-playthrough, you might need to respect once updated to Revision 148+, even though (following best practices) you would have already done it prior. Otherwise you might not have the resources allocated from the level 1 progressions.
- [DnD 5R - Eldritch Knight - War Magic and Improved War Magic PHB 2024](https://www.nexusmods.com/baldursgate3/mods/12070) *DnD 5R War Magic and Improved War Magic - Strict*, *Level 20 Progression Patch*, & *DnD 5R War Magic - Replacer Patch*.\
  \- This just makes Eldritch Knight so much less tedious to play.
- [Way of the Boulder - A Hardy Monk Subclass](https://www.nexusmods.com/baldursgate3/mods/21015) *Way of the Boulder*.
- [Huffman's Pugilist - A Streetfighting Class with Swagger to Spare](https://www.nexusmods.com/baldursgate3/mods/22635) *The Pugilist - Grappling Extension*.
- [The Paragon](https://www.nexusmods.com/baldursgate3/mods/23169) *Paragon*.\
  \- Long time coming this one! Sorry for the late inclusion [CatDude55](https://www.nexusmods.com/baldursgate3/users/142645943)! 😭

### Gameplay:🧌

- [Early Access Nautiloid](https://www.nexusmods.com/baldursgate3/mods/23007) \
  \- The walkway after the first imp combat can get pretty wonky with the camera, but it's too cool to let that stop me including it for now.
- [Many More Monsters](https://www.nexusmods.com/baldursgate3/mods/11639) *Many More Monsters - Modified*.\
  \- A patch for rebalancing and integration with [Ultimate NPC Stat Overhaul (UNSO)](https://www.nexusmods.com/baldursgate3/mods/15535).
- [Fall of the Valorous](https://www.nexusmods.com/baldursgate3/mods/23901) \
  \- [JL935JL](https://www.nexusmods.com/baldursgate3/users/73194838)'s latest adventure is here! Only Act I currently, but with plans to expand it further.
- [Goon's Attack of Opportunity Overhaul with Optional Critical Miss AoO](https://www.nexusmods.com/baldursgate3/mods/23861) *Goon's Attack Of Opportunity Overhaul*.
- [Ultimate NPC Stat Overhaul (UNSO)](https://www.nexusmods.com/baldursgate3/mods/15535) *Ultimate NPC Stat Overhaul - Core* & *Ultimate NPC Stat Overhaul - Core - Extras*.\
  \- We refactored it to reduce redundancy, but it's currently split into a bunch of not very descript files.
- [No Combat or Dialogue Saving - SE](https://www.nexusmods.com/baldursgate3/mods/24548) *NoCombatOrDialogueSaving*.\
  \- Works great with [Combat Extender](https://www.nexusmods.com/baldursgate3/mods/5207) having problems with mid-combat loading.\
  \- Currently configured to only prevent combat saving, not dialogue like the name suggests.&#x20;
- [Harvest Companion Tadpoles](https://www.nexusmods.com/baldursgate3/mods/24639)&#x20;
- [End-turn Exploit Fix](https://www.nexusmods.com/baldursgate3/mods/24413) *EndTurnExploitFix*.
- [Traps Force Turn Based](https://www.nexusmods.com/baldursgate3/mods/24151)&#x20;
- [Alternate Humans](https://www.nexusmods.com/baldursgate3/mods/23875) *Alternate Human*.\
  \- A flavourful rebalance for player character humans.
- [Mazzle and Moxi's Group Climbing Fix (SE Edition)](https://www.nexusmods.com/baldursgate3/mods/23194) *Mazzle Group Climbing 1.5.1*.

### Items:⚔️

- [Sensible Visible Shields (Patch 8)](https://www.nexusmods.com/baldursgate3/mods/24888) *SensibleVisibleShields*.
- [Custom Smart Containers](https://www.nexusmods.com/baldursgate3/mods/24742) *CustomSmartContainers*.
- [Difficulty Immersion Quality Collection - Misc Files](https://www.nexusmods.com/baldursgate3/mods/9784) *JWL Discordant Instruments Enhanced Revamped*.
- [Starting Equipment Restored](https://www.nexusmods.com/baldursgate3/mods/22309)&#x20;
- [Missing Starting Equipment Fixed](https://www.nexusmods.com/baldursgate3/mods/24295)&#x20;
- [Wye Fey Potions](https://www.nexusmods.com/baldursgate3/mods/23323)&#x20;
- [Vampire Lord's Attire](https://www.nexusmods.com/baldursgate3/mods/24169) *HT\_VampireLordsAttire*.
- [Psychotter's Goth Dyes](https://www.nexusmods.com/baldursgate3/mods/7329) *Psychotter's Goth Dyes - Gold - Tutorial Only*.
- [Worn Traveler's Attire](https://www.nexusmods.com/baldursgate3/mods/20762) *Elle Worn Traveler's Attire*.
- [Consort's Ensemble](https://www.nexusmods.com/baldursgate3/mods/23539)&#x20;
- [Lovely Dresses](https://www.nexusmods.com/baldursgate3/mods/16161) *BW\_Lovely\_Dresses*.

### Dialogue and cutscenes:🤗

- [Best in Party Skills](https://www.nexusmods.com/baldursgate3/mods/20091) \
  \- The toggles for stealth and sleight of hand are patched out.
- [Dark Urge Isobel Reward Fixed](https://www.nexusmods.com/baldursgate3/mods/24625)&#x20;
- [Beached Bodies Restored](https://www.nexusmods.com/baldursgate3/mods/24239)&#x20;
- [Look At This Photograph - Isobel Dialogue Unlocker](https://www.nexusmods.com/baldursgate3/mods/22759)&#x20;
- [Never Dark Again - Give Arabella Komira's Locket (And Other Act 2 Tweaks)](https://www.nexusmods.com/baldursgate3/mods/23834) *Never Dark Again - Arabella Act 2 Tweaks*.
- [Lie to Glut - Sovereign Glut Quest Tweaks and Bugfixes](https://www.nexusmods.com/baldursgate3/mods/23846) *Lie to Glut - PAK*.
- [Companion Combat Death Reactivity](https://www.nexusmods.com/baldursgate3/mods/24022) *Companion Combat Death Reactivity - PAK*.
- [Dark Urge Voice Toggle](https://www.nexusmods.com/baldursgate3/mods/24147) *Dark Urge Voice Toggle - Story Based*.
- [Camp Night Position Fixer](https://www.nexusmods.com/baldursgate3/mods/24550)&#x20;
- [Player Voiced Scenes Priority](https://www.nexusmods.com/baldursgate3/mods/24564)&#x20;
- [Follow Astarion - New Endgame Cutscene](https://www.nexusmods.com/baldursgate3/mods/23767) *HT\_FollowAstarion*.
- [Embrace Shart - Hug Shadowheart in Act 2](https://www.nexusmods.com/baldursgate3/mods/23610) *HT\_EmbraceShart*.
- [Gale's Betrayal - Restored From Early Access](https://www.nexusmods.com/baldursgate3/mods/18561) *HT\_GalesBetrayal*.
- [Endgame Lae'zel has Githyanki egg](https://www.nexusmods.com/baldursgate3/mods/23488) *Laezel has Githyanki Egg*.

### UI:💻

- [Sensible Mod Info](https://www.nexusmods.com/baldursgate3/mods/24614)&#x20;
- [Photo Mode Category Sorter](https://www.nexusmods.com/baldursgate3/mods/24015)&#x20;
- [Tav's Clock](https://www.nexusmods.com/baldursgate3/mods/19886) *Tav's Clock 1.4.1*.
- [Exclusive Dice](https://www.nexusmods.com/baldursgate3/mods/24525) + *Exclusive Dice - Illithid Purple* & *Exclusive Dice - Xanathar's Barter Remake*.
- [Christmas Dice Set](https://www.nexusmods.com/baldursgate3/mods/14335)&#x20;

### Visuals:📸

- [Outfits Dummy Auto-Patcher (UAP)](https://www.nexusmods.com/baldursgate3/mods/24419)&#x20;
- [Race CC Universal Automatic Patcher (UAP)](https://www.nexusmods.com/baldursgate3/mods/22551) *Race CC Universal Automatic Patcher (UAP) 1.2.0*.
- [Head VFX Universal Automatic Patcher (UAP)](https://www.nexusmods.com/baldursgate3/mods/22716) *Head VFX Universal Automatic Patcher (UAP) 1.0.0*.
- [Vanilla Eye Band Aid](https://www.nexusmods.com/baldursgate3/mods/24317) *Vanilla Eye Band-Aid* & *Vanilla Eye Band Aid - Flame Blindness Edition*.
- [Lae'zel's Cage Trap Fixed](https://www.nexusmods.com/baldursgate3/mods/24454) *Cage Trap Fixed*.
- [Blood And Dirt Splatter Overhaul](https://www.nexusmods.com/baldursgate3/mods/24701) *Splatter Overhaul*.
- [NPC Portrait Fixes](https://www.nexusmods.com/baldursgate3/mods/24173)&#x20;
- [The Hallowleafs - Dynamic Appearances](https://www.nexusmods.com/baldursgate3/mods/24062) *Hallowleafs Dyanmic Appearances*.
- [Gather Your Allies - No Casual Fridays](https://www.nexusmods.com/baldursgate3/mods/24136) *Gather Your Allies- No Casual Friday*.
- [Mystra Edits - The Mother of All Magic](https://www.nexusmods.com/baldursgate3/mods/17954)&#x20;
- [Lady Jannath Edits - Patron of the Arts](https://www.nexusmods.com/baldursgate3/mods/23565)&#x20;
- [Auntie Ethel Redux - The Caretaker](https://www.nexusmods.com/baldursgate3/mods/24004)&#x20;
- [ABSolutely Companions](https://www.nexusmods.com/baldursgate3/mods/19073) *ABSolutely Karlach*.
- [Galestarion](https://www.nexusmods.com/baldursgate3/mods/23900)&#x20;
- [Clean Mattresses Now](https://www.nexusmods.com/baldursgate3/mods/23793)&#x20;
- [Sandal Straightener](https://www.nexusmods.com/baldursgate3/mods/24797)&#x20;
- [Fixed Dwarven Splintmail](https://www.nexusmods.com/baldursgate3/mods/24656) *Fixed Dwarven Splintmail - Intended Colors*.
- [Blackguard's Plate Texture Fix](https://www.nexusmods.com/baldursgate3/mods/10186) *Blackguard's Plate Texture Fix 3.0*.

### Character customisation:👗

- [Clansong - Speaking Dragonborns CC Heads](https://www.nexusmods.com/baldursgate3/mods/19947)&#x20;
- [Crimson Hair Catalog Part 1](https://www.nexusmods.com/baldursgate3/mods/21659) *Hair Catalog Part 1*.
- [Crimson Hair Catalog Part 2](https://www.nexusmods.com/baldursgate3/mods/22589) *Hair Catalog Vol2*.
- [Crimson Hair Catalog Part 3](https://www.nexusmods.com/baldursgate3/mods/23257) *Hair Catalog Part 3*.
- [Elledwyn Hairstyles (Reupload)](https://www.nexusmods.com/baldursgate3/mods/23172) *Elledwyn Hairstyles*.

### Other:🔍

- [SE Console Command Atlas](https://www.nexusmods.com/baldursgate3/mods/24447) *SEConsoleCommandAtlas*.\
  \- The power of commands at the fingertips of the masses, a revolutionary mod!
- [Missing Starting Passives Fixed](https://www.nexusmods.com/baldursgate3/mods/23623)&#x20;
- [Goon's Inheritance Fixes](https://www.nexusmods.com/baldursgate3/mods/23439)&#x20;
- [Backstabbing-Flanking Framework](https://www.nexusmods.com/baldursgate3/mods/11741) *Backstabbing Framework*.
- [Lighty Lights and Photo Mode stuff](https://www.nexusmods.com/baldursgate3/mods/14364) *Gobos and garbage* & *Light Probes*.\
  \- *Light Probes* is set as a BG3 Loose "Mod Type", but it has a meta.lsx and goes in the BG3MM load order as a green "Editor Project".
- [Edited AnimationBlueprint for Dani Mode](https://www.nexusmods.com/baldursgate3/mods/24269) *Edited Animation Blueprint For Dani Mode*.
- [Mazzle's Level Directory](https://www.nexusmods.com/baldursgate3/mods/23322) *Mazzle Level Directory*.
- [Fricken FreeCam](https://www.nexusmods.com/baldursgate3/mods/22888) *FreeCam 2.0.2*.
- [Baldur's Gate 3 Mod Manager - BG3ModManager (BG3MM)](https://github.com/laughingleader/bg3modmanager)\
  \- Included as a tool for testing, the installation instructions continue to make no mention of BG3MM being included inside of Vortex.

### Added to optional mods: 📦

- [Native Camera Tweaks with GUI](https://www.nexusmods.com/baldursgate3/mods/22892) *NativeCameraTweaksGUI*.\
  \- Can access the configuration via the **DEL** key.
- [BG3WASD Camera Follow (Fork) - Smooth Camera Modes](https://www.nexusmods.com/baldursgate3/mods/23413) *BG3WASD CameraFollow V1.2.0*.\
  \- **F6** - Toggle Mouse Steering.\
  \- **F7** - Toggle Camera Follow. (This might not work due to conflict with [Native Camera Tweaks with GUI](https://www.nexusmods.com/baldursgate3/mods/22892) *NativeCameraTweaksGUI*.)\
  \- **F11** - Reload BG3WASD.toml after editing it.\
  \- **Caps Lock** - Freecam / camera movement override.\
  \- **Q / E / Middle Mouse** - Manual camera control.

***

## Updated 🔧

> 📌It's recommended to respec characters making use of the following mods into level 1 Barbarians, and deactivate/remove all toggles you're able to.

### Spells:✨

- [More Spell Choices and Slots - MCM](https://www.nexusmods.com/baldursgate3/mods/13472) *More Spell Choices and Slots*.
- [Goon's Spell Overhaul](https://www.nexusmods.com/baldursgate3/mods/15481) *Goon's Spell Overhaul - Cantrips*, *Goon's Spell Overhaul - Level 1*, *Goon's Spell Overhaul - Level 2*, *Goon's Spell Overhaul - Level 3*, *Goon's Spell Overhaul - Level 7*, & *Goon's Spell Overhaul - Misc*.
- [Chiz's 5e Spells Adjustments](https://www.nexusmods.com/baldursgate3/mods/19247)&#x20;
- [5eSpells and Expansion Patch](https://www.nexusmods.com/baldursgate3/mods/22565) *5eSpells and Expansion Level 13-20 Patch*.
- [5e Spells](https://www.nexusmods.com/baldursgate3/mods/125) *5eSpells*.\
  \+ *5e Spells* renamed to *5eSpells*.
- [Advanced Tabletop Spells](https://www.nexusmods.com/baldursgate3/mods/14429) *AdvancedTTSpells.7z*.
- [Spells of Exandria](https://www.nexusmods.com/baldursgate3/mods/18441) *SpellsOfExandria.7z*.
- [Valkrana's Spellbook - 17 New Necromancy Spells](https://www.nexusmods.com/baldursgate3/mods/1258) *Valkrana's Spellbook* + *Valkrana's Spellbook Limited Lists*.\
  \+ Mod formerly named *Valkrana's Spellbook - 15 New Necromancy Spells*.
- [Mirror Blade](https://www.nexusmods.com/baldursgate3/mods/480)&#x20;
- [Pernicious Thread - Necromancy Spell](https://www.nexusmods.com/baldursgate3/mods/8733) *Pernicious Thread*.
- [Swap Places Common Action](https://www.nexusmods.com/baldursgate3/mods/13120)&#x20;

### Feats:💪

- [Universal Feat Every X Level(s) - MCM](https://www.nexusmods.com/baldursgate3/mods/13193) *Feat Every x Level(s)*.
- [Feats Overhaul](https://www.nexusmods.com/baldursgate3/mods/15044) *FeatsOverhaul*.\
  \+ *FeatsOverhaul\_GWMPatch* renamed to *FeatsOverhaul GWMPatch*.
- [Arcanist Feat](https://www.nexusmods.com/baldursgate3/mods/1087) *Arcanist Feat SE*.
- [Valkrana's Skeleton Crew - Over 60 Random Undead Allies](https://www.nexusmods.com/baldursgate3/mods/4496) *Valkrana's Skeleton Crew Feat*.
- [War Caster (2014 and 2024)](https://www.nexusmods.com/baldursgate3/mods/5822) *War Caster*, *More Upcasting*, & *5e Spells Support*.
- [Lone Wolf Feat - SE](https://www.nexusmods.com/baldursgate3/mods/14351)&#x20;

### Classes and class features:📊

- [Expansion Level 13-20 (Configurable)](https://www.nexusmods.com/baldursgate3/mods/279) *Expansion*.
- [Goon's Barbarian Overhaul](https://www.nexusmods.com/baldursgate3/mods/17654)&#x20;
- [5e Barbarian Subclasses Combined](https://www.nexusmods.com/baldursgate3/mods/15141) *BarbarianSubclasses5eCombined.zip*.
- [Goon's Bard Overhaul](https://www.nexusmods.com/baldursgate3/mods/17658)&#x20;
- [Automatic Magical Secrets Extender](https://www.nexusmods.com/baldursgate3/mods/20247) *AutomaticMagicalSecretsExtender*.
- [Goon's Cleric Overhaul](https://www.nexusmods.com/baldursgate3/mods/17471)&#x20;
- [5e Cleric Subclasses Combined](https://www.nexusmods.com/baldursgate3/mods/16007) *ClericSubclasses5eCombined.zip*.
- [Druid Wild Shape Overhaul](https://www.nexusmods.com/baldursgate3/mods/1148)&#x20;
- [Goon's Fighter Overhaul](https://www.nexusmods.com/baldursgate3/mods/17926)&#x20;
- [5e Fighter Subclasses Combined](https://www.nexusmods.com/baldursgate3/mods/15060) *FighterSubclasses5eCombined.zip*.
- [Echo Knight Fighter Subclass](https://www.nexusmods.com/baldursgate3/mods/3939) *Echo Knight*.
- [Goon's Monk Overhaul](https://www.nexusmods.com/baldursgate3/mods/17706)&#x20;
- [5e Monk Subclasses Combined](https://www.nexusmods.com/baldursgate3/mods/15907) *MonkSubclasses5eCombined.zip*.
- [Way of Steel - An Armoured Monk](https://www.nexusmods.com/baldursgate3/mods/19427) *Way of Steel*.
- [Way of the Forge - A Monk Subclass](https://www.nexusmods.com/baldursgate3/mods/17398) *Way of the Forge*.
- [Goon's Paladin Overhaul](https://www.nexusmods.com/baldursgate3/mods/17535) + *No Divine Smite for Oathbreakers*.
- [Oath of the Watchers - Paladin Subclass Lv20 Expansion](https://www.nexusmods.com/baldursgate3/mods/18306) *Oath of the Watchers - Paladin Subclass* & *OPTIONAL) 5e Spells Compatibility\_Add On*.\
  \+ Mod formerly named *5e Oath of the Watchers - Paladin Subclass Lv20 Expansion*.
- [Oath of Glory - Paladin Subclass Lv20 Expansion](https://www.nexusmods.com/baldursgate3/mods/19027) *Oath of Glory - Paladin Subclass*.\
  \+ Mod formerly named *5e Oath of Glory - Paladin Subclass Lv20 Expansion*.\
  \+ *5e Oath of Glory - Paladin Subclass* renamed to *Oath of Glory - Paladin Subclass*.
- [Control Undead Complete - Oathbreaker](https://www.nexusmods.com/baldursgate3/mods/7532) *Control Undead Complete*.
- [Goon's Sorcerer Overhaul](https://www.nexusmods.com/baldursgate3/mods/17657)&#x20;
- [Draconic Bloodline Expanded](https://www.nexusmods.com/baldursgate3/mods/13563) \
  \- Shoutout to [Backburner26](https://www.nexusmods.com/baldursgate3/users/19603604) for following through on including all my adjustments I kept bugging them with lol.
- [Goon's Rogue Overhaul](https://www.nexusmods.com/baldursgate3/mods/17612)&#x20;
- [Goon's Coffee Lock - Use Warlock Spell Slots First](https://www.nexusmods.com/baldursgate3/mods/17634) *Goon's Coffee Lock - Decaf*.
- [The Necrobroker Patron - Warlock Subclass](https://www.nexusmods.com/baldursgate3/mods/19848) *Necrobroker Patron*.
- [Goon's Wizard Overhaul](https://www.nexusmods.com/baldursgate3/mods/17659)&#x20;
- [Valkrana's Necrobroker - Wizard Subclass](https://www.nexusmods.com/baldursgate3/mods/17919) *Valkrana's Necrobroker*.
- [Command Undead - Necromancy Subclass Feature](https://www.nexusmods.com/baldursgate3/mods/6291) *Command Undead Level 14*.
- [Mesmerist - Pathfinder 1e Class Conversion](https://www.nexusmods.com/baldursgate3/mods/11854) *Mesmerist*.
- [Commoner Class](https://www.nexusmods.com/baldursgate3/mods/12581)&#x20;
- [Huffman's Pugilist - A Streetfighting Class with Swagger to Spare](https://www.nexusmods.com/baldursgate3/mods/22635) *The Pugilist*. \
  \+ Mod formerly named *The Pugilist - A Streetfighting Class with Swagger to Spare*.
- [Huffman's Magus - A Class of Spell and Steel](https://www.nexusmods.com/baldursgate3/mods/17765) *The Magus*.
- [Inquisitor Class](https://www.nexusmods.com/baldursgate3/mods/18318) *Inquisitor*.
- [Marksman - A Gunslinger class](https://www.nexusmods.com/baldursgate3/mods/20477) *The Marksman class*.

### Gameplay:🧌

- [Many More Monsters](https://www.nexusmods.com/baldursgate3/mods/11639) \
  \- I did a top to bottom overhaul with some assistance from Cahoot. Many, many bugs fixed, loads of polish.\
  \- ❗️If updating mid-playthrough, the scale of these changes will surely cause some weird ongoings for the existing level(s) in your game.
- [Psychic Armory](https://www.nexusmods.com/baldursgate3/mods/14476) \
  \- [JL935JL](https://www.nexusmods.com/baldursgate3/users/73194838) added a bunch of console commands for if you get yourself stuck with quest steps etc.
- [Features from DnD 5E Spelljammer](https://www.nexusmods.com/baldursgate3/mods/13195) *Features from DnD 5E Spelljammer - 1.1.1*.\
  \+ *Features from DnD 5E Spelljammer - Nexus* renamed to *Features from DnD 5E Spelljammer - 1.1.1*.
- [Valkrana's Undead Encounters - New Bosses Fights Items and Allies - Including Act 3](https://www.nexusmods.com/baldursgate3/mods/9024) *Valkrana's Undead Encounters*.
- [Valkrana's Skeletal Challenge - Difficulty Mod](https://www.nexusmods.com/baldursgate3/mods/5920) *Valkrana's Skeletal Challenge*.\
  \- Reminder that this is set to a 1% spawn chance, and that if you're getting gangbanged by skeletons you just didn't install configs properly.
- [Ultimate Cut Content Restoration Mod](https://www.nexusmods.com/baldursgate3/mods/20353)&#x20;
- [Languages of the Sword Coast](https://www.nexusmods.com/baldursgate3/mods/17594)&#x20;
- [Aylin Always Summons Moonlight Slivers](https://www.nexusmods.com/baldursgate3/mods/18079) *Always Moonlight Sliver No Bulwark*.\
  \- Swapped from *Aylin Always Summons Moonlight Slivers* to *Always Moonlight Sliver No Bulwark* for better balancing.
- [Necromancy Reanimated (Formerly Animate Dead Plus Plus)](https://www.nexusmods.com/baldursgate3/mods/642) *Necromancy Reanimated*.
- [Goon's Companion Protection](https://www.nexusmods.com/baldursgate3/mods/14396) \
  \- Did some needed rebalancing here so Minthara isn't annoying with 3 DR, and Jaheira is a bit more beefed up for the Moonrise fight.&#x20;
- [Grit and Glory - Injuries Exhaustion and Madness - MCM](https://www.nexusmods.com/baldursgate3/mods/14863) *Grit and Glory - Injuries Exhaustion and Madness*.
- [Goon's Condition and Surface Overhaul](https://www.nexusmods.com/baldursgate3/mods/17320)&#x20;
- [Ultimate NPC Stat Overhaul (UNSO)](https://www.nexusmods.com/baldursgate3/mods/15535) *Ultimate NPC Stat Overhaul - CX* & *Ultimate NPC Stat Overhaul - CX - Extras*.\
  \+ *Ultimate NPC Stat Overhaul renamed* to *Ultimate NPC Stat Overhaul - CX*.\
  \+ *Ultimate NPC Stat Overhaul - Extras* renamed to *Ultimate NPC Stat Overhaul - CX - Extras*.
- [Goon's Short Legs Overhaul - Full Movement for Short Races](https://www.nexusmods.com/baldursgate3/mods/17616) *Goon's Short Legs Overhaul - UNSO*.
- [Goon's Slayer Overhaul](https://www.nexusmods.com/baldursgate3/mods/17963)&#x20;
- [Buff Exploit Fix - MCM](https://www.nexusmods.com/baldursgate3/mods/13652) *Buff Exploit Fix*.
- [Origin Gods SE - MCM](https://www.nexusmods.com/baldursgate3/mods/20583) *Origin Gods SE*.\
  \- In the DIQ configs: Lae'zel now falls back to Tiamat instead of Free Thinker, should she cease to worship Vlaakith. Wyll now worships Tyr, and Minsc worships Mielikki, instead of them just being Faithful. Karlach is now Faithless instead of Faithful.
- [Better Dialogue Controls - SE](https://www.nexusmods.com/baldursgate3/mods/20908) *Better Dialogue Controls*.
- [Attitude Adjuster - Approval Gains SE](https://www.nexusmods.com/baldursgate3/mods/20933) *Attitude Adjuster*.
- [Summon Initiative Fixer](https://www.nexusmods.com/baldursgate3/mods/8692)&#x20;
- [Absolute's Laboratory - NPC and Combat Inspector and Mutator](https://www.nexusmods.com/baldursgate3/mods/16217) *Absolute's Laboratory*.
- [Automated Summons](https://www.nexusmods.com/baldursgate3/mods/10922) *Automated Summons SE*.
- [Unlock Summon Skills](https://www.nexusmods.com/baldursgate3/mods/5660)&#x20;
- [Configurable Party Limit](https://www.nexusmods.com/baldursgate3/mods/11172) *Configurable Party Limit 1.2.2*.\
  \+ *Configurable Party Limit 1.2.1* renamed to *Configurable Party Limit 1.2.2*.
- [Post-Combat Cleanup](https://www.nexusmods.com/baldursgate3/mods/21777) *Post-Combat Cleanup 1.2.0*.\
  \+ *Post-Combat Cleanup 1.1.0* renamed to *Post-Combat Cleanup 1.2.0*.
- [Auto Send Food To Camp](https://www.nexusmods.com/baldursgate3/mods/6086) \
  \+ *Auto Send Food To Camp 2.4.0* renamed to *Auto Send Food To Camp*.
- [Configurable Fall Damage](https://www.nexusmods.com/baldursgate3/mods/15849) *Configurable Fall Damage 1.1.1*.\
  \+ *Configurable Fall Damage 1.1.0* renamed to *Configurable Fall Damage 1.1.1*.
- [I Surrender](https://www.nexusmods.com/baldursgate3/mods/19112)&#x20;

### Items:⚔️

- [Goon's Gear and Throwing Overhaul](https://www.nexusmods.com/baldursgate3/mods/15126) \
  \+ Mod formerly named *Goon's (Gear and) Throwing Overhaul*.\
  \- Got to do a partial refactor of the mod, you'll see a lot of armour has wildshape support now, especially footwear.
- [Markoheshkir Expanded](https://www.nexusmods.com/baldursgate3/mods/15396)&#x20;
- [DIQ Patches - Treasure Tables and More](https://www.nexusmods.com/baldursgate3/mods/9095) + *DIQ Clothing Patches*, *DIQ Miscellaneous Item Patches*, *DIQ Starting Equipment*, *DIQ Starting Equipment - Minthara Less Magic Items Patch*, & *No Cosmetics Patch*.
- [Awakened Spear of Shar](https://www.nexusmods.com/baldursgate3/mods/13833)&#x20;
- [Awakened Spear of Selune](https://www.nexusmods.com/baldursgate3/mods/13832)&#x20;
- [Awakened Blood of Lathander](https://www.nexusmods.com/baldursgate3/mods/12628)&#x20;
- [The Hand of Vecna](https://www.nexusmods.com/baldursgate3/mods/12600) *Hand of Vecna*.
- [Fade's Equipment Distribution (FED)](https://www.nexusmods.com/baldursgate3/mods/13824) *Fade's Equipment Distribution - FED - Osi*.\
  \- Swapped from *Fade's Equipment Distribution - FED - SE* to *Fade's Equipment Distribution - FED - Osi*, as the SE version is now deprecated.\
  \- ❗️If updating mid-playthrough, his change in distribution method will likely result in duplicate item spawns for the existing level(s) in your game.
- [Beast and Bow - Ranger Equipment](https://www.nexusmods.com/baldursgate3/mods/12016)&#x20;
- [Chaos and Control - Sorcerer Equipment](https://www.nexusmods.com/baldursgate3/mods/15116)&#x20;
- [Faith and Fortitude - Cleric Equipment](https://www.nexusmods.com/baldursgate3/mods/9415)&#x20;
- [Grove and Growl - Druid Equipment](https://www.nexusmods.com/baldursgate3/mods/10304)&#x20;
- [Might and Metal - Fighter Equipment](https://www.nexusmods.com/baldursgate3/mods/14894)&#x20;
- [Oath and Order - Paladin Equipment](https://www.nexusmods.com/baldursgate3/mods/15236)&#x20;
- [Pact and Power - Warlock Equipment](https://www.nexusmods.com/baldursgate3/mods/14327)&#x20;
- [Rage and Resilience - Barbarian Equipment](https://www.nexusmods.com/baldursgate3/mods/14744)&#x20;
- [Song and Steel - Bard Equipment](https://www.nexusmods.com/baldursgate3/mods/14078)&#x20;
- [Unarmed and Upgraded - Monk Equipment](https://www.nexusmods.com/baldursgate3/mods/7254)&#x20;
- [Veil and Venom - Rogue Equipment](https://www.nexusmods.com/baldursgate3/mods/14586)&#x20;
- [Wands and Weave - Wizard Equipment](https://www.nexusmods.com/baldursgate3/mods/13829)&#x20;
- [Fade's Assorted Treasure Expansion - FATE](https://www.nexusmods.com/baldursgate3/mods/20745)&#x20;
- [Secret Scrolls for 5e Spells](https://www.nexusmods.com/baldursgate3/mods/2145) *SecretScrolls-5eSpells.zip*.
- [Auto Wares - MCM](https://www.nexusmods.com/baldursgate3/mods/18924) *Auto Wares*.
- [Heavy Weapons RAW](https://www.nexusmods.com/baldursgate3/mods/19028) *Heavy Weapons RAW - 5.5e*.
- [Psychotter's Goth Dyes](https://www.nexusmods.com/baldursgate3/mods/7329) *Psychotter's Goth Dyes - Dark - Tutorial Only* & *Psychotter's Goth Dyes - Silver - Tutorial Only*.\
  \+ Swapped from *Psychotter's Gothic Dyes - Dark Metal Version* to *Psychotter's Goth Dyes - Dark - Tutorial Only*.\
  \+ Swapped from *Psychotter's Gothic Dyes - Bright Metal Version* to *Psychotter's Goth Dyes - Silver - Tutorial Only*.
- [Asymmetrical Shadowheart Concept Outfit](https://www.nexusmods.com/baldursgate3/mods/6578) *Concept Art Shadowheart*.
- [Agile Armor](https://www.nexusmods.com/baldursgate3/mods/14565) *AgileArmor*.

### Dialogue and cutscenes:🤗

- [Stomp that Tadpole](https://www.nexusmods.com/baldursgate3/mods/17485)&#x20;
- [Zethino Love Test Buff Fix](https://www.nexusmods.com/baldursgate3/mods/19530) *Zethino Love Test Buff Fix - Status*.
- [Wyll's Act 3 Romance Tweaks](https://www.nexusmods.com/baldursgate3/mods/11442) *Wylls Act 3 Romance Tweaks - PAK*.\
  \- No longer an override mod, now lives in the active load order.
- [Early Access Scenes Restored](https://www.nexusmods.com/baldursgate3/mods/16830) *HT\_EA-Restored*.
- [No Wound Flares During Party Banter](https://www.nexusmods.com/baldursgate3/mods/22614) *HT\_NoWoundFlaresDuringPartyBanter*.
- [Companion Gale Can Consume Shadow Weave](https://www.nexusmods.com/baldursgate3/mods/16877) \
  \- Let me know if this doesn't work, because the file structure has me guessing.
- [Wyll - Theo Solomon Banter](https://www.nexusmods.com/baldursgate3/mods/19832) *Wyll - Theo Solomon Banter (.pak file)*.

### UI:💻

- [ImpUI\_P8\_Fork (ImprovedUI)](https://www.nexusmods.com/baldursgate3/mods/16649) \
  \+ *ImpUI\_P8\_Fork* renamed to *ImpUI\_P8\_Fork - 8.0.5*.
- [Mod Configuration Menu (MCM)](https://www.nexusmods.com/baldursgate3/mods/9162) *Mod Configuration Menu*.\
  \+ *Mod Configuration Menu 1.40.1* renamed to *Mod Configuration Menu*.
- [Tooltip Manager - Highlight Everything SE - MCM](https://www.nexusmods.com/baldursgate3/mods/18208) *Tooltip Manager*.
- [Records - A Party Statistics Tracker](https://www.nexusmods.com/baldursgate3/mods/19021) *Records*.
- [Progression Preview - Full Class Progressions Shown Ingame](https://www.nexusmods.com/baldursgate3/mods/20193) *ProgressionPreview*.
- [Respec Tadpoles - Integrated UI](https://www.nexusmods.com/baldursgate3/mods/20538) *Respec Tadpoles*.
- [Dice Roulette](https://www.nexusmods.com/baldursgate3/mods/20857) \
  \- Better support for holiday dice! Something we'll be making good use of in the future. (I totally forgot to update the config for the [Christmas Dice Set](https://www.nexusmods.com/baldursgate3/mods/14335).)
- [Mazzle's EZ-Documentation (MazzleDocs)](https://www.nexusmods.com/baldursgate3/mods/18883) MazzleDocs 2.7.1.\
  \+ *MazzleDocs 2.4.1* renamed to *MazzleDocs 2.7.1*.
- [Tav's Journal](https://www.nexusmods.com/baldursgate3/mods/19332) *Tav's Journal 2.2.0*.\
  \+ *Tav's Journal 2.1* renamed to *Tav's Journal 2.2.0*.
- [Illithid Powers Consolidated (compatible with IPO2)](https://www.nexusmods.com/baldursgate3/mods/16671)\* Illithid Powers Consolidated\*.

### Visuals:📸

- [Unsoiled](https://www.nexusmods.com/baldursgate3/mods/22472)&#x20;
- [Marcus Falgor Edits - The Betrayer](https://www.nexusmods.com/baldursgate3/mods/17318) \
  \+ Mod formerly named *Marcus Filgor Edits - The Betrayer*.
- [Mayrina and Brothers Edits](https://www.nexusmods.com/baldursgate3/mods/20674)&#x20;
- [Barcus Wroot - Dynamic Appearances](https://www.nexusmods.com/baldursgate3/mods/21518)&#x20;
- [Various NPCs Restyled](https://www.nexusmods.com/baldursgate3/mods/13937) *All in One Version (seperate paks)*.\
  \- \[FILE REPLICATION] Removed *LadyJannath\_Restyled\_a09560f1-2b86-ab4a-f2f9-f07d2a0afed6.pak* & *TheHallowleafs\_Restyled\_V2\_2ba50661-8286-c5ba-776f-1544289685c9.pak*.
- [Shadowheart Concept Art Tattoos](https://www.nexusmods.com/baldursgate3/mods/18629) *ShadowheartTattoos\_AIO*.
- [Nightwarden Minthara](https://www.nexusmods.com/baldursgate3/mods/22156) *Nightwarden Minthara - Adytum*.
- [Distinctive Arrows of Slaying](https://www.nexusmods.com/baldursgate3/mods/20199)&#x20;
- [Creature Photo Mode Fix](https://www.nexusmods.com/baldursgate3/mods/18997)&#x20;
- [Faerun Fashionistas Mega Pose Pack](https://www.nexusmods.com/baldursgate3/mods/19829) *FF Mega Pose Pack*.
- [Faerun Fashionistas Mega Pose Patch](https://www.nexusmods.com/baldursgate3/mods/20159) *FF Mega Patch*.
- [ZillionZ of Expressions by Echo](https://www.nexusmods.com/baldursgate3/mods/21610)&#x20;

### Character customisation:👗

- [Armory - Auto-Transmog Vanity Outfit Manager](https://www.nexusmods.com/baldursgate3/mods/14717) *Armory*.
- [Character Preset Framework (CPF)](https://www.nexusmods.com/baldursgate3/mods/19805) *Character Preset Framework 1.8.0*.\
  \+ *Character Preset Framework 1.7.0* renamed to *Character Preset Framework 1.8.0*.
- [Tav's Nightly Hairdo](https://www.nexusmods.com/baldursgate3/mods/21259)&#x20;
- [Shadowheart's Nightly Hairdo](https://www.nexusmods.com/baldursgate3/mods/21060)&#x20;
- [jerinski's BT1 and BT3 Heads](https://www.nexusmods.com/baldursgate3/mods/16985) *BT1 - BT3 Heads*.
- [P4 Bangs Bangs Everywhere (a Fringes and Extra Hair mod)](https://www.nexusmods.com/baldursgate3/mods/4681) *Patch 8 - P4 Bangs Bangs Everywhere*.

### Other:🔍

- [Baldur's Gate 3 Script Extender (BG3SE)](https://www.nexusmods.com/baldursgate3/mods/2172) *Baldur's Gate 3 Script Extender*.
- [Goon's Library - Passives Functions Spells and More](https://www.nexusmods.com/baldursgate3/mods/12834) *Goon's Library*.\
  \- Refactoring my khn functions was a significant rabbit hole for this revision. They should all be about as performant as I can make them, it might even be the case that the more my functions are used instead the more performant the game becomes, improved even relative to vanilla.&#x20;
- [Difficulty Immersion Quality Collection - Misc Files](https://www.nexusmods.com/baldursgate3/mods/9784) *DIQ Misc Patches* & *DIQ Misc Patches - Overrides*.
- [Quick Small Animation Thingy (QSAT)](https://www.nexusmods.com/baldursgate3/mods/17737) *QSAT*.
- [Lighty Lights and Photo Mode stuff](https://www.nexusmods.com/baldursgate3/mods/14364) *Dani Lighty Lights*.\
  \+ *Lighty Lights* renamed to *Dani Lighty Lights*.
- [Object Character Support](https://www.nexusmods.com/baldursgate3/mods/3940)&#x20;
- [Passive Boost Deduplicator](https://www.nexusmods.com/baldursgate3/mods/19523)&#x20;
- [Cat's Library](https://www.nexusmods.com/baldursgate3/mods/17245)&#x20;
- [Move Rotate and Scale Anything Gizmo](https://www.nexusmods.com/baldursgate3/mods/21922) *EZ-Manipulator GizmoLib*.\
  \+ Mod formerly named *EZ-Manipulator - Object Move-Rotate-Transform Gizmo*.
- [MazzleLib](https://www.nexusmods.com/baldursgate3/mods/18231) *MazzleLib 1.9.4*.\
  \+ *MazzleLib 1.6.1* renamed to *MazzleLib 1.9.4*.
- [Vendor Stock Control](https://www.nexusmods.com/baldursgate3/mods/21896) \
  \+ *Vendor Stock Control 1.0.0* renamed to *Vendor Stock Control*.
- [Volition Cabinet](https://www.nexusmods.com/baldursgate3/mods/7676) *VolitionCabinet 1.17.0*.\
  \+ *VolitionCabinet 1.16.0* renamed to *VolitionCabinet 1.17.0*.
- [AnimationUnlocker](https://www.nexusmods.com/baldursgate3/mods/16058) \
  \- Has been moved in the load order right near the bottom so that it predictably functions. This mod is kinda black magic to me, and something I gotta figure out in the future.

### Updated optional mods: 🔧

- [Absolute Wrath](https://www.nexusmods.com/baldursgate3/mods/5552) \
  \- Grim's brought in a new boss, some interesting loot for them, and folded a lot of my bug fixing into the official release.
- [Text Chat](https://www.nexusmods.com/baldursgate3/mods/10353) *BG3-Text-Chat-Mod*.\
  \- Has had a lot of QoL features added, to a point where I now have it in the active load order by default, because it won't be glued to the screen.&#x20;
- [Immersive World Textures](https://www.nexusmods.com/baldursgate3/mods/18252) *Immersive World Textures - Loose files version*.
- [Auto-Knockout Story NPCs](https://www.nexusmods.com/baldursgate3/mods/22662)&#x20;
- [Sandi's Waypoint Only Fast Travel](https://www.nexusmods.com/baldursgate3/mods/19884) *Sandi's Waypoint Only Fast Travel - No UI*.

***

## Metadata changed 🔧

- [Roah Moonglow Always Escapes](https://www.nexusmods.com/baldursgate3/mods/22529) *Roah Escapes*.\
  \+ Mod formerly named *Roah Moonglow Escapes*.
- [Icon and Race Patches for Tav's Hair Salon](https://www.nexusmods.com/baldursgate3/mods/3346) *THS Icon Patch*.\
  \+ Mod formerly named *Icon Patches for Tav's Hair Salon*.
- [Cullenite's Odds and Ends - BG3](https://www.nexusmods.com/baldursgate3/mods/14041) *Edited Draconic Face Scales 4k*.\
  \+ Mod formerly named *Odds and Ends for Lani*.