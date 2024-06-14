The Fray is a reactive timing system throughout the game, influencing other core mechanics, such as [[Combat]] and [[Dialogue]]. It can be affected in or out of Combat, and is the main system that the time aspect will interact with.

The Fray is client-side, meaning that unless players are in the same battle, they will rarely interact with the same Fray.

The Fray's mechanics are divided into two categories, [[#Rhythm]] and [[#Genre]].

# Rhythm

Rhythm is the means of tracking how closely the player’s [[Note|Notes]] match the [[Tempo]] and [[Time Signature|Time Signatures]] of a [[Bar]]. Keeping Rhythm does not require attacking exactly on the [[Beat]] of the Fray, but following the Rhythm rewards a bonus to [[Mana Regeneration]] and [[Gel Viscosity Damage]].

Rhythm's mechanics include:
- [[Beat|Beats]]: One turn of Combat
- [[Bar|Bars]]: One round of Combat
- [[Tempo]]: Speed of Beats

# Genre

Genre is the style of combat taking place, affecting both the note patterns of combatants and the applicable actions they can take.

Genre's mechanics include:
- [[Note|Notes]]: Individual actions combatants may take
- [[Time Signature]]: Patterns that Beats may follow

# Polyrhythms

Having different [[Time Signature|Time Signatures]] synchronized according to single Bar is considered a Polyrhythm. A Polyrhythm audible in the Fray denotes a battle for ownership *over* the Fray.

An example of a polyrhythm would be when one player has a Time Signature of 4/4 and a Tempo of 30 BPM, and another player is in 6/4 at 45 BPM, such that the length of their Bars is the same (8 seconds).

# Fighting Off-Rhythm

Fighting Off-Rhythm serves the purpose of shifting control of the Fray. If you attack an opponent Off-Rhythm, it can force them to respond in ways that shake them into fighting in a different [[Time Signature]] or [[Tempo]] than they would be when fighting in or controlling the Fray. The more an opponent fights Off-Rhythm, the more they lose control of the Fray. After reaching a certain threshold, this will transfer control to the next most Rhythmic combatant. This makes those who do not have a good sense of Rhythm out of play still serve an important role in shaking up the battlefield.

# Implementation Details

Midis provide a flexible and customizable way to add music.