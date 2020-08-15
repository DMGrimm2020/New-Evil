---
name: Monsters
slug: monsters
pdf-page-style: multi-column
order: 2
---

# Monsters

```Monster {.gray}
id: 
name: Dwarven Citizen
slug: dwarven-citizen
size: Medium
type: humanoid (dwarf)
alignment: lawful good
ac: 16 (scale mail, shield)
hp: 26 (4d8 + 4)
speed: 25 ft.
str: 13
dex: 11
con: 14
int: 11
wis: 10
cha: 9
role: enemy
resistances: poison
senses: darkvision 60 ft., passive Perception 10
languages: Common, Dwarvish
challenge: 1 
environments: hill, mountain, underdark
image: 
token: 
traits:
  - name: Dwarven Resilience
    description: "The dwarf has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed."
actions:
  - name: Battleaxe
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands."  
  - name: Handaxe
    description: "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d6 + 1) slashing damage."
```
This is your everyday dwarven citizen. Environments: Hill, Mountain, Underdark

```Monster {.gray}
id: 
name: Elven Citizen
slug: elven-citizen
size: Medium
type: humanoid (elf)
alignment: chaotic good
ac: 14 (studded leather armor)
hp: 13 (3d8)
speed: 30 ft.
str: 10
dex: 14
con: 10
int: 11
wis: 11
cha: 11
role: enemy
skills: Perception +2, Stealth +4
senses: darkvision 60 ft., passive Perception 12
languages: Common, Elvish
challenge: 1/4
environments: forest, underdark
image: 
token: 
traits:
  - name: Fey Ancestry
    description: "The elf has advantage on saving throws against being charmed, and magic can't put the elf to sleep."
actions:
  - name: Shortsword
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 55 (1d6 + 2) piercing damage."  
  - name: Longbow
    description: "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit: 6 (1d8 + 2) piercing damage."
```
This is your everyday elven citizen. Environments: Forest, Underdark

(print-page)

```Monster {.gray}
id: 
name: Gnomish Citizen
slug: gnomish-citizen
size: Small
type: humanoid (gnome)
alignment: neutral good
ac: 16 (chain shirt, shield)
hp: 16 (3d6 + 6)
speed: 25 ft.
str: 15
dex: 13
con: 14
int: 12
wis: 10
cha: 9
role: enemy
skills: Investigation +3, Perception +2
senses: darkvision 60 ft., passive Perception 12
languages: Common, Gnomish
challenge: 1/2
environments: hill, forest, underdark
image: 
token: 
traits:
  - name: Gnome Cunning
    description: "The gnome has advantage on Intelligence, Wisdom, and Charisma saving throws against magic."
actions:
  - name: Shortsword
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."  
  - name: Hand Crossbow
    description: "Ranged Weapon Attack: +3 to hit, range 30/120 ft., one target. Hit: 4 (1d6 + 1) piercing damage."
```
This is your everyday gnomish citizen. Environments: Hill, Forest, Underdark

```Monster {.gray}
id: 
name: Infant Remorhaz
slug: infant-remorhaz
size: Medium
type: monstrosity
alignment: unaligned
ac: 11 (natural armor)
hp: 27 (5d8 + 5)
speed: 20 ft., burrow 10 ft.
str: 12
dex: 13
con: 13
int: 2
wis: 10
cha: 3
role: enemy
immunities: cold, fire
senses: darkvision 30 ft. tremorsense 30 ft., passive Perception 10
languages: — 
challenge: 1/4
environments: arctic
image: 
token: 
traits:
  - name: Heated Body
    description: "A creature that touches the remorhaz or hits it with a melee attack while within 5 feet of it takes 3 (1d6) fire damage."
actions:
  - name: Bite
    description: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 8 (2d6 + 1) piercing damage plus 3 (1d6) fire damage."  
```
The heat secretion of a remorhaz, thrym, is valuable as a component for heat-related magical items and can be sold to alchemists for 5-10 gold pieces per flask. The remorhaz will contain 10 flasks worth of thrym per Hit Die. Environments: Arctic

(print-page)

```Monster {.gray}
id: 
name: Ancient Remorhaz
slug: ancient-remorhaz
size: Gargantuan
type: monstrosity
alignment: unaligned
ac: 20 (natural armor)
hp: 402 (23d20 + 161)
speed: 30 ft., burrow 20 ft.
str: 30
dex: 13
con: 25
int: 5
wis: 10
cha: 6
role: enemy
immunities: cold, fire
senses: darkvision 60 ft. tremorsense 60 ft., passive Perception 10
languages: — 
challenge: 20
environments: arctic
image: 
token: 
traits:
  - name: Heated Body
    description: "A creature that touches the remorhaz or hits it with a melee attack while within 5 feet of it takes 21 (4d6) fire damage."
actions:
  - name: Bite
    description: "Melee Weapon Attack: +16 to hit, reach 5 ft., one target. Hit: 59 (9d10 + 10) piercing damage plus 21 (4d6) fire damage. If the target is a creature, it is grappled (escape DC 20). Until this grapple ends, the target is restrained, and the remorhaz can't bite another target."  
  - name: Swallow
    description: "The remorhaz makes one bite attack against a Large or smaller creature it is grappling. If the attack hits, that creature takes the bite's damage and is swallowed, and the grapple ends. While swallowed, the creature is blinded and restrained, it has total cover against attacks and other effects outside the remorhaz, and it takes 28 (8d6) acid damage at the start of each of the remorhaz's turns." 
  - description: "If the remorhaz takes 40 damage or more on a single turn from a creature inside it, the remorhaz must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, which fall prone in a space within 15 feet of the remorhaz. If the remorhaz dies, a swallowed creature is no longer restrained by it and can escape from the corpse using 15 feet of movement, exiting prone."  
```
The heat secretion of a remorhaz, thrym, is valuable as a component for heat-related magical items and can be sold to alchemists for 5-10 gold pieces per flask. The remorhaz will contain 10 flasks worth of thrym per Hit Die. Roll (1d100) with 25 percent chance of a mate and with (1d2) eggs. The eggs value are at 500 gp. Environments: Arctic