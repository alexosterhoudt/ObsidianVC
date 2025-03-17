```statblock
name: Goblin Boss
size: Small
type: Fey
subtype: Goblinoid
alignment: Chaotic Neutral
ac: 17
hp: 21
hit_dice: 6d6
speed: 30 ft
stats: [10, 14, 10, 10, 8, 10]
skillsaves:
- Stealth: 6
senses: Darkvision 60ft, Passive Perception 9
languages: Common, Goblin
cr: 1
traits:
- [Nimble Escape, The goblin can take the Disengage or Hide action as a bonus action on each of its turns]
- ...
actions:
- [Multiattack, The goblin makes two attacks, using Scimitar or Shortbow in any combination.]
- [Scimitar, _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 5 (1d6 + 2) Slashing damage.]
- [Shortbow, _Ranged Attack Roll:_ +4, range 80/320 ft. _Hit:_ 5 (1d6 + 2) Piercing damage.]
- ...
reactions:
- [Redirect Attack, _Trigger:_ A creature the goblin can see makes an attack roll against it. _Response:_ The goblin chooses a Small or Medium ally within 5 feet of itself. The goblin and that ally swap places, and the ally becomes the target of the attack instead.]
- ...
```

```statblock
monster: Goblin
```
```statblock
name: Sildar Hallwinter
size: Medium
type: Humanoid
subtype: Human
alignment: Neutral Good
ac: 16
hp: 27
hit_dice: 5d8+5
speed: 30 ft
stats: [13, 10, 12, 10, 11, 10]
saves:
- Strength: 3
- Constitution: 3
skillsaves:
- Perception: 2
senses: Passive Perception 12
languages: Common
cr: 1
actions:
- [_**Multiattack**_, Sildar makes two Longsword attacks.]
- [_**Longsword**_, _Melee Weapon Attack:_ +3, reach 5 ft., One target. _Hit:_ 5 (1d8+1) slashing damage, or 6 (1d10+1) slashing damage is using both hands.]
- [_**Heavy Crossbow**_, _Ranged Weapon Attack:_ +2, range 100/400 ft., One target. _Hit:_ 5 (1d10) piercing damage.]
- ...
reactions:
- [_**Parry:**_, When an attacker Sildar can see would hit him with a melee attack, he can roll a d6 and add the number rolled to his AC against the triggering attack, provided he’s wielding a melee weapon.]
- ...
```


