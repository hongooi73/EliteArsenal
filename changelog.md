## v4.0.1

### New equipment

Add +/++ versions of the following weapons:
- ER medium pulse laser (clan)
- ER large pulse laser (clan)
- Binary large laser
- Medium X-pulse laser
- Large X-pulse laser
- MML3/5/7/9
- Silver Bullet rotary Gauss rifle

Add +++ versions of the following weapons:
- PPC
- ER PPC
- Heavy PPC
- Light PPC
- ER PPC (clan)

### New mechs and vehicles

Mechs:
- Archangel X/S
- Banshee X2/S2
- Cephalus X/S
- Griffin X2/S2
- Hellbringer X2/S2
- Hunchback X3/S3
- Huron Warrior X/S
- Longbow X4/S4
- Mad Cat X2/S2
- Mad Dog X2/S2
- Marauder II BX/BS
- Marauder IIC X/S
- Osteon X1/X2/S1/S2
- Preta X/S
- Septicemia X/S
- Zeus YX/YS

Vehicles:
- Behemoth S2
- Heavy MML carrier S
- Myrmidon X2/S2

### Mech rebalancing

Several mechs have had their hardpoint totals changed:

- As part of the hardpoint changes from Expanded Arsenal, many elite clan mechs have had their hardpoint totals reduced. See the [Expanded Arsenal changelog](https://github.com/hongooi73/ExpandedArsenal/blob/main/changelog.md) for more information.
- Conversely, some S-tier mechs (mostly Inner Sphere ones, but also a few clan mechs) have had their hardpoint totals increased, to make them more competitive. As a guideline, all S-tier assaults should have at least 10 non-support hardpoints, and smaller mechs should have 8.

### Other significant changes

- All S-tier mechs now have 75 innate heatsinking, equivalent to having engine double heatsinks plus the 15 bonus for S-tier. This affects only IS mechs (all clan mechs have engine double heatsinks by default).
- Increase the damage for +/++ clan medium and large pulse lasers.
- All upgraded Gauss weapons can now explode on a critical hit. This affects the + and ++heavy Gauss, and all HAGs.


## v4.0.0

### Changes

New in this release are upgrades for non-weapon items: Guardian ECM, active probe, anti-missile system, Nova CEWS, void signature system, and MASC. This goes together with the revisions to the stock items in the base Expanded Arsenal mod.

The Guardian ECM suite confuses enemy targeting and tracking systems, thereby increasing a mech's hit defense and reducing incoming damage. Note that the ECM suite is a useful upgrade in isolation, rather than simply cancelling out enemy offensive electronics like in the tabletop game.
- +Guardian ECM: +2 defense, 10% damage reduction
- ++Guardian ECM: +3 defense, 10% damage reduction

The active probe enhances a mech's ability to detect and track enemies. It increases passive and active sensor range, reduces active sensor cooldowns, and improves weapon accuracy.
- +active probe: enhanced probe (300m range, 3 turn cooldown), +20% sensor range, +1 accuracy
- ++active probe: enhanced probe (400m range, 2 turn cooldown), +30% sensor range, +2 accuracy

The anti-missile system is a laser-based point-defense mechanism that disables and destroys incoming missiles. Missiles that are not shot down outright are liable to have their fuzing and guidance systems scrambled, reducing their lethality.
- +AMS: +5 defense and 20% damage reduction vs missiles
- ++AMS: +6 defense and 25% damage reduction vs missiles

The void signature system combines a self-only form of the stealth capability of the X-1 EW suite with the enhanced defenses of the Guardian ECM suite. The result is a sophisticated electronic warfare package that greatly enhances a mech's survivability.
- +VSS: +3 defense, 10% damage reduction
- ++VSS: +4 defense, 10% damage reduction

The Nova CEWS gives a mech the ability to hook into the sensors of its lancemates. This improves situational awareness, allowing the pilot to more easily anticipate enemy movements and attacks. More advanced variants can feed the combined data back into the network, boosting the weapon accuracy of the entire lance.
- +Nova CEWS: +1 evasion, 10% damage reduction, +1 accuracy, +15% weapon optimal range
- ++Nova CEWS: +1 evasion, 10% damage reduction, +1 accuracy, +30% weapon optimal range, +1 lancewide accuracy (stacking)

MASC is a retrofitted musculature control pack that significantly boosts a mech's movement speed, with the downside of increased heat generation. More advanced variants reduce the waste heat output.
- +MASC: +5% heat generated
- ++MASC: +0% heat generated

A number of X- and S-tier mechs have been modified to mount these items.


### Bug fixes

- Fix tags for several Clan mechs to match their tonnage. This should result in fewer instances of heavy and assault mechs showing up in low-skull missions.
- Add jump capability back to the S-tier Annihilator chassis.


## v3.0.0

### Changes

- Elite and ace opfor pilots now get 10% and 20% damage reduction respectively when Elite Arsenal is enabled.
- Increase damage buff for + and ++ variants of PPC Capaci(ta)tor to 25% and 35% respectively.
- Reduce the number of X-tier units that will be encountered in non-elite missions.
- Impose a C-bill penalty for taking excessive tonnage into a mission, courtesy of the Drop Tonnage Reward and Limit on Difficulty mod.
  - The rating of your lance can be up to 1 skull higher than the skull rating of the mission. Going beyond that imposes a cost of 5000 C-bills per excess ton. Be warned that this means you can make a _loss_ if your lance is heavy enough.
  - In-game, we can assume that the employer normally covers various mission-related expenses behind the scenes. Normally these expenses go unmentioned, but if the company tries to drop too much tonnage above what's considered reasonable, the employer will now refuse to pay an excessive amount.
  - Out-of-game, this is to discourage taking an all-assault lance into a low-skull mission and stomping the opfor.
  - This is only enabled if Elite Arsenal is turned on, as one of its objectives is to increase the challenge. Otherwise, feel free to drop 400 tons into a 1-skull mission.
- Add + and ++ variants for Thunderbolt missiles, doing more damage and (except for the Thunderbolt 5) weighing less.
- Add the Thunderbolt Missile Carrier, an S-tier vehicle mounting 3 ++Thunderbolt 20s.
- Add the Griffin X and S, elite variants of the GRF-3M.
- Some other mechs and vehicles have also been modified to mount Thunderbolts and Guardian ECM pods.
- Some adjustments to opfor lance composition in regular and elite missions.

### Bug fixes

- Swap the torso locations of the Intercept System and Passive Defensive Matrix in the Vapor Eagle X and S.
- Fix some lancedefs that were erroneously spawning Elite Arsenal vehicles instead of mechs.
- Fix issue with stock contracts that call for a dynamic difficulty fire lance.
- Fix Orion IIC S to have ++ATMs.


## v2.0.0

### Major changes

- Revamped structure to mitigate the difficulty spike in the early game, as well as provide more of a challenge in the late game:
  - Introduce new "elite" versions of contracts which are denoted by a `(+)` in the mission title. These are the same as regular contracts but feature an opfor heavy with S-tier and X-tier elite mechs. They have a 50% higher C-bill payout and slightly more salvage picks.
  - Elite contracts are now the only place where you can encounter S-tier mechs. X-tier can still be met in regular missions, or bought in shops.
  - Base buildings in elite missions will also have more health, to let them survive longer than one round against S-tier firepower.
- The AI should now be somewhat more aggressive and unpredictable, and has a chance to reserve its turn.
- Mission Control is now a dependency. The extra support lances that can spawn are always regular lances (with a chance to include Elite Forces and X-tier units), not elite.
- Elite Forces is now enabled by default, while Elite Arsenal remains an opt-in mod for now.

### New content

- Add PPC capaci(ta)tor + and ++, for less heat and more damage. Existing mechs that use the PPC cap have been updated to use the improved variants (Annihilator X and S, Phoenix Hawk S, Warhammer X and S).
- Add Short-Range EW Suite as a new item, which gives a defense bonus at short range and melee damage reduction. This is intended to improve survivability for melee and brawler builds. Existing melee mechs have been updated to include this (Valiant X and S, Hatchetman X and S, Hatamoto-Chi S).
- Add Axman X and S.
- Add Gargoyle X and S.
- Add Orion IIC X and S.

### Other changes

- Fix ++clan ERSL stats and tooltip. +10 damage was an error, now gives +25% crit chance over the regular and + variant.
- Fix Bane S loadout to have ++HAG/20s.
- Fix stability values for several mechs.
- Fix internal structure values for several vehicles.
- Fix number of jumpjets for Hellhound X and S.
- Buff the opfor for the final Heavy Metal minicampaign flashpoint to account for Elite Arsenal powercreep.
