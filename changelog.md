## v2.0.1

## Changes

- Elite opfor pilots now get 10% damage reduction, and ace pilots get 20% damage reduction.
- Increase damage buff for + and ++ variants of PPC Capaci(ta)tor to 25% and 35% respectively.
- Reduce the number of X-tier units that will be encountered in non-elite missions.
- Impose a C-bill penalty for taking excessive tonnage into a mission, courtesy of the Drop Tonnage Reward and Limit on Difficulty mod.
  - The rating of your lance can be up to 1 skull higher than the skull rating of the mission. Going beyond that imposes a cost of 5000 C-bills per excess ton. Be warned that this means you can make a _loss_ if your lance is heavy enough.
  - In-game, we can assume that the employer normally covers various mission-related expenses behind the scenes. Normally these expenses go unmentioned, but if the company tries to drop too much tonnage above what's considered reasonable, the employer will now refuse to pay an excessive amount.
  - Out-of-game, this is to discourage taking an all-assault lance into a low-skull mission and stomping the opfor.
  - This is only enabled if Elite Arsenal is turned on, as one of its objectives is to increase the challenge. Otherwise, feel free to drop 400 tons into a 1-skull mission.
- Add + and ++ variants for Thunderbolt missiles, doing more damage and (except for the Thunderbolt 5) weighing less.
- Add the Thunderbolt Missile Carrier, an S-tier vehicle mounting 3 ++Thunderbolt 20s.
- Some other mechs and vehicles have also been modified to mount Thunderbolts and Guardian ECM pods.

## Bug fixes

- Swap the torso locations of the Intercept System and Passive Defensive Matrix in the Vapor Eagle X and S.
- Fix some lancedefs that were erroneously spawning Elite Arsenal vehicles instead of mechs.
- Fix issue with stock contracts requiring a dynamic difficulty fire lance.
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
