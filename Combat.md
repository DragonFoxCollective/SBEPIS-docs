A generated event involving at least one aggressor, one target, and a combat goal. Combat participation is optional. Combat will begin when initiated by a single party, and combatants involved will be assigned depending on various traits. See Combatant. Combat will not be restricted to Event Chunks, but will aim to fit within them. When an entity becomes Aware of an aggressor, they will be prompted to Strife or Abscond.

[The Fray](https://github.com/Dragon-Fox-Collective/SBEPIS/wiki/The-Fray) will inform how combat is approached by setting the pace and difficulty of a battle. The Fray will have both Tempo and Metre. Enemies will tend to attack on Meter, although they may have different Tempos. Swarmers will adjust the Speed of Tempo according to factional relationships. Commanders can set the Metre of Tempo for the Swarmers they lead, such as Waltz Time or Common Time. 

Projectile weapons will use Ammo if available, but you can also get an upgrade to create Ammunition from your Grist stores. Projectile weapons only shoot when using piercing attacks. Directional attacks would be swinging the gun. (Edge case I got caught up on: A rocket launcher will shoot when using a non-directional attack. Projectiles can change course– But this would be described elsewhere, not determined actively by the player.) Imagine directly hitting someone vs happening to hit someone indirectly.

## Momentum/Movement
Recoil, knockback, slides, and more. Innate movement encompasses running, sprinting, jumping, crouching, and sliding… Satisfactory-style crouch bhopping is also innate. Niche movement abilities will be supported, but optional in the form of alchemized gear, including dashing. Special body parts such as wings would be considered gear for this purpose.

## Attack Types
Every weapon has light, heavy, and special attacks.
+ Special attacks are used when weapons are not locked on to a target (reloads, special attacks, other misc actions) Uses your current movement to do a certain attack.
+ Piercing attacks are from the camera forwards– IE, non directional movement. Imagine a sword jab vs an arced attack. Instead of calculating armor, you’re looking for weak points/unarmored points. 
+ Light attacks (for projectiles, this is shooting), they’re always forward facing/ cannot be directional
+ Heavy attacks will be directional. They can influence direction while attacking, unlike special attacks, which only account for direction, not change it.
+ Combinations of bits will assign a weapon a strife specibus type, which thus determines the function of light/heavy/special attacks

## Accuracy
+ Directional Attacks- 27 variations (Forward, Backward, Left, Right, Up, Down, All Diagonals and Not Moving)
+ Parts have Gel Viscosity that can be depleted to deal a crit. If a crit on a 0 GV part kills the target, a gib system will be activated.
+ “Lock on” function will lock on to target closest to center of screen, prioritizing Boss > Commander > Swarmer
+ Which hit box do you hit, and how close to the center of the hit box are you? 
+ A directional attack is more likely to chop off vs a non directional attack, which is more likely to pierce through
+ Armour and parts will have directional weak points, IE, a carapacian with an armored head would be more resistant to downward directional attacks.

## Enemies
# Commander
The Commander is, for all intents and purposes, a boss within a combat scenario. Because bosses will be diverse, the play style efficiency will depend on the boss. Commanders within an event chunk will have levels of importance. Lower importance means lower chances of successfully commanding a swarm. High importance increases likelihood of command success, but also… Commander tactics in battle will be determined by:
+ Genre (The Fray system)
+ Personal Goals
+ Politics
+ Team #s or Ratios
# Swarmers
Swarmers will be the bulk of enemy teams. The Metre of Swarmers is controlled by the Commanders controlling them, although the Speed is usually dictated by Factional Relationship to PC. Swarmers will form clouds of AI groups. When in Combat, Swarmers will tend to group together. If a Commander is present, Swarmer AI will be dependent on Commander Tactics. Limited AI with seeded randomness
+ Imps do not carry items but will have mutations. Faction leader is the Denizen.
+ Basilisks, Liches, Giclopses, Ogres
+ Carapacians - Equipment loadouts AND mutations
+ Consorts do not mutate without Commander Intervention. Carry items and equipment loadouts.

## Combat Loop
Combat begins when both parties are aware of an encounter. Teams are generated depending on the initiate parties.
# Strife choice 
Key choice made by evaluation of enemies, factions, power, tempo, etc

Abjure - What’s the goal of abjuration?
+ Dialogue - Dialogue abjuration will involve a defensive playstyle and quick dialogue choices. The goal of this must also be determined, but it can usually be assumed the goal is non-violent resolution and higher relationship and factional relationship.
+ Knockout - Goal of this is non-lethal defeat of enemies. Enemies will not be killed when defeated. This can be for a variety of tactical reasons.
Abscond - Tactical escapes, enemies will give chase! What’s the best way to leave?
+ Will the enemy type give chase? Are you a target?
+ What abilities do enemies have compared to players? Teleports?
+ Is there a team looking for you now? Will this affect factional relationships? Regular relationships? Increase importance?
Strife - The goal is to kill, the question is how?
+ Team #s - Are we outnumbered? By how much?
+ Presence of Commanders - Will the commanders also be killed? (combat stance related,) Are the enemies organized or disorganized?
+ Enemy types– What types of damage will be most effective?
A combat event will conclude with an end condition, either the death of the aggressor party or target party, the satiation of the aggressor party (calmed) or the target party (spared), fleeing, knock-out
+ Fleeing - Extra damage against fleeing targets
+ Knocked Out - Attacks kill knocked out targets


## Teams and Combatants
Teams are created on battle start, but are also dynamic within an event chunk. Team placement will depend on various factors, such as faction relationships, player relationships, strife choice, and targets of attack. 
Combatants involved in a combat event will be determined by how many combatants are within the event chunk. The event chunk will read the Time value depending on the combatants within the chunk and their time-related abilities. When an event chunk contains no combatants that have time-related abilities, only the SCT time will be read.
Teams will include aggressor parties and target parties initially, and each of these teams will have defined intents to kill. 