#WIP bullet phase

## Ticks

- Ticks are an abstracted unit of time for measuring how much time actions take to perform, and keep track of what every character in a conflict is doing at a given time.
- A tick represents around 1 second of in-game time

## Conflict Overview

- The basic structure of a conflict is as follows:
	1. Notice which character's Tick marker is furthest back. In the case of a tie, the character with the highest Agility acts first
	2. Allow that character to decide which action to take, and place their Standard and Incidental Action markers on the relevant actions. This acts as a reminder of what they are doing, the specifics should be remembered by that character.
	3. Determine how many Ticks those actions will take, adding together the Tick cost of their Standard and Incidental actions
	4. Move their marker up that many Ticks
	5. Notice which character's Tick marker is furthest back, and resolve their actions, rolling any necessary checks
	6. Repeat to step 2
- Characters who are surprised start at Tick 4 by default, characters who took the initiative to start the conflict (ie opening the door into combat) go at Tick 0, everyone else at Tick 2. Characters who are being surprised get to roll a Reflex + Perception(Alertness) raw check to see if they are surprised and delayed those two Ticks, with the difficulty of course being up to the GM.
- There are many different actions that can be taken, and three different way to use each action
	- Standard Action: The main thing a character is doing on their turn, taking up most of their attention. These actions are the slowest to take and so usually cost the bulk of a given turn's Ticks. They are also the most effective.
	- Incidental Action: These actions are things characters can perform without their full attention. Some of these actions only exist as incidental actions, while others have a stronger Standard Action version and a weaker but faster Incidental Action version.
	- Spontaneous Action: These are actions that a character can perform to react to the actions taken by another character. Characters have the choice to take Spontaneous Actions when another character announces what their next actions will be. Some Talents also allow you to take Spontaneous Actions in the middle of the resolution of another character's actions. In order to perform these, the character must first make a roll to determine if they are fast enough to interrupt what they are currently doing. The specific attributes or skills that go into that roll are specified by the action, but it will always include Reflex. When taking a Spontaneous Action, resolve the effect of the action immediately, but move the character's Tick marker forward a number of Ticks equal to the Tick cost of the Spontaneous Action. The Tick marker is moved forward whether or not the initial roll actually succeeded, potentially costing the character precious time in their attempts at reacting to the heat of battle. Some Standard or Incidental Actions have Spontaneous versions, but the majority of Spontaneous Actions come from Talents.

## List of Actions

- **Move**
	- Standard Action (X Ticks + Y Stamina): Move from one zone to another. Each zone has a different Tick cost from 1 to 3 which represents how difficult it is to move through. You must pay the cost of both the zone you're entering and the one you're leaving. You may spend Stamina to make this action go quicker, down to a minimum of 2 Ticks.
	- Incidental Action (1 Tick): Engage or disengage with an Entity or item in your Zone
	- Spontaneous Action (3 Ticks + X Stamina, Reflex + Agility): As with the Standard Action, but must always spend 3 Ticks AND spend Stamina equal to the amount of Ticks it would normally cost. You don't need to spend the Stamina if your spontaneous action check failed.
- **Cast Spell**
	- Standard Action (4+ Ticks): You spend the Mana on the spell as soon as this action is selected, but it only goes into effect once this action resolves, at which point it continues indefinitely, with an effectiveness proportional to how much mana was spent. Each mana burst spent on the spell adds an additional Tick.
	- Spontaneous Action (2 Ticks, Reflex + Focus): As with the Standard Action, but the effects of the spell resolve immediately, you may not spend more than 2 Mana, and you may not spend a mana burst.
- **Attack** - Standard Action (X Ticks): Make an attack using a weapon. The ticks necessary are specified in the weapon used. The process is outlined in Wounds
- **Defend**
	- Standard Action (3+ Ticks): While you are taking this action, any time an enemy makes an attack against you, you may make a Strength/Agility + Defense roll. Subtract the number of successes from the incoming Fatigue. This action has no effect upon resolution. You may extend the duration of this action.
	- Incidental Action (2 Ticks): As with standard action, but your roll is a pure Defense roll.
- **Use Item** - Depends on the item
- **Use Skill** - Depends on the skill action
- **Assist** - Incidental Action (1 Ticks): If your standard action is Attack, Use Item, or Use Skill choose another friendly Entity that is performing the same standard action as you. If you're using an item or a skill, they must be using the same gear class item or the same skill. When their action resolves, they gain an advantage for that action equal to however many ticks you were assisting that action for. #WIP determine if this is too much fuss to track