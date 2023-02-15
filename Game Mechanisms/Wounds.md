#WIP VERY EARLY bullet phase

## Proposed Approach:

1. Roll for attack: Need two successes by default
2. Fatigue Phase: Your attack would hit, but the target can still avoid taking a wound. You will remove stamina by dealing fatigue to the target. Additional successes increase fatigue, target's Armour decreases fatigue. If the target is defending, their successes further reduce fatigue. If any fatigue isn't successfully soaked, go to wound phase
3. Wound Phase: There are two kinds of wounds
	1. Ability created wounds (done through talents or weapons that look for special dice results) create wounds the effects of which are specified in the relevant talent or weapon
	2. For wounds coming from unsoaked fatigue, determine the deadliness of the instigating talent or weapon, and look at the Wound Severity table to determine the effect
4. Healing: Once a day, as an action, you may make a Strength + Endurance (Fatigue) roll and restore stamina equal to the number of successes. You may do this two more times this day, but the second time takes 10 minutes and the third time takes a night's sleep.

## Other Approaches

L5R approach:
- roll to hit always target number of 2 successes, if you succeed you deal damage, which is then reduced by target's armour
- If damage is leftover, it deals fatigue, and when the target has too much fatigue and cannot take any more, it turns into a critical hit
- If any damage gets through, it is automatically a critical strike and the amount of damage doesn't really matter at that point
- Weapons have a damage number and a severity number. Some weapons are good at tiring someone out, some are good at killing them off afterwards
- Once a critical strike happens, the target makes a roll to determine how much they can lower the severity of the crit. Finally, you look at a table and see what the effect is for the given severity. The last level of this table is instant death
- The real danger here is the fact that once you've been dealt enough damage and gained enough fatigue, every hit is a potential crit
- TODO look into healing

Genesys Approach:
- Each character has a "soak" value which reduces incoming damage. Excess damage past that counts as "wounds" and each character has a "wound threshold" after which they fall unconscious and suffer an automatic crit
- When making the attack roll, there are positive and negative dice. More successes than fails means it hits, and if you get enough net opportunity dice results, you may trigger your weapons' critical rating and inflict a critical injury.
- Critical Injuries involve an old-school style d100 table, which can be modified by some talents
- Each time a critical injury happens, it has some minor setback but then also gives a +10 for the severity of future crits. This means the first crit can't be worse than a temporarily impaired limb, but after 5 or so crits, it's possible to straight up die, and after more, it becomes inevitable
- Death is difficult because either the character must take 2x HP in wounds or get enough crits. Much more likely the character will just go unconscious and be temporarily incapacitated. Fair enough
- Strain also exists but is separate
- Healing naturally is brutally slow. Each day heals one wound (ouch!) and each week gives a chance of healing one crit. A medically trained character can provide muuuuch higher wound recovery, but can only add one extra chance at healing a crit per week.

Numenera Approach:

- Each character has three pools: Might, Speed and Intellect
- Players can use these pools to efficiently lower the DC of checks they make
- Different kinds of damage drain the different pools
- After the Might pool (most frequently attacked, since most physical attacks drain it) is fully drained, Speed is drained next, then Intellect
- Each time a pool is depleted, they move down the damage track, taking them from Hale to Impaired to Debilitated to Dead.
- Some rare effects move a character down the damage track independent of the pools
- Impaired characters use their pools less effectively, and cannot get neat bonuses from rolling 19s or 20s
- Debilitated characters are basically just crawling around unable to do much of anything
- To regenerate pools, you must rest. Each time you rest in a given day it take more time. Resting gives a small amount of points back which you may distribute amongst your pools
- First rest can be done as an action in combat. Neat! Next rest is 10 minutes, then an hour, then a full night.
- Once a pool goes from 0 to 1, you recover in the damage track. Simple enough!

Shadowrun Approach:

- Character A attacks character B. They both roll their buckets of dice, with some funny stuff about who has an edge. Edge comes from advantages and you can spend it for fun stuff
- If A has at least 1 hit and at least as many hits as B does, they deal weapon damage, plus additional damage for every net hit above the defense roll
- B makes another roll to soak up incoming damage, based on a separate Body attribute
- After that, you basically just reduce the HP. Boring