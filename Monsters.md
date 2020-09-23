---
name: Monsters
slug: monsters
pdf-page-style: multi-column
order: 5
include-in: all
---

# Monsters

#### Dwarven Citizen
Dwarven citizen living their lifes day to day. Environments: Hill, Mountain, Underdark

```Monster {.gray}
id: 
name: Dwarven Citizen
slug: dwarven-citizen
size: Medium
type: humanoid (dwarf)
alignment: lawful good
ac: 16 (scale mail, shield)
hp: 26 (4d8 + 8)
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
    description: "The dwarf has advantage on saving throws against poison, and has resistance against poison damage."
actions:
  - name: Battleaxe
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands."  
  - name: Handaxe
    description: "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d6 + 1) slashing damage."
```

(print-column)

#### Elven Citizen
Elven citizen living their lifes day to day. Environments: Forest, Underdark

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
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."  
  - name: Longbow
    description: "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit: 6 (1d8 + 2) piercing damage."
```

(print-page)

#### Gnomish Citizen
Gnomish citizen living their lifes day to day. Environments: Hill, Forest, Underdark

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

(print-column)

### Aging NPC's
| Age | Str | Dex | Con | Int | Wis | Cha |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Infant    | +2 | +0 | +2 | +0 | +0 | +0 |
| Young     | +2 | +0 | +2 | +0 | +0 | +0 |
| Adult     | +2 | +0 | +2 | +0 | +0 | +0 |
| Middle    | -2 | +0 | +1 | +1 | +1 | +1 |
| Old       | -2 | +0 | +1 | +1 | +1 | +1 |
| Venerable | -2 | +0 | +1 | +1 | +1 | +1 |

For those that want to have differnt race's age's. Go two size's down off the original creature's stats.

*Examples are Infant Orc, Young Orc, Adult Orc is found on MM p.246, Middle Orc, Old Orc, & Venerable Orc.*

#### Orc Life Stages
Environments: Arctic, Forest, Grassland, Hill, Mountain, Swamp, Underdark

**Infant Orc.** Infant orc entering the world.

**Young Orc.** Young orc just starting out in life. At this stage the young orc goes out with older orcs in raiding parties.

**Middle Orc.** Middle age orc. The middle orc that have made it to this life stage being to be someone in their tribe.

**Old Orc.** Old age orc. The older orc have learned how the real world works just beyound their raiding lands.

**Venerable Orc.** Venerable age orc. The venerable orc that make it to this stage will teach their young that want to list.

(print-page)

```Monster {.gray}
id: 
name: Infant Orc
slug: infant-orc
size: Tiny
type: humanoid (orc)
alignment: chaotic evil
ac: 11 (natural armor)
hp: 3 (1d4 + 1)
speed: 20 ft.
str: 12
dex: 12
con: 12
int: 7
wis: 11
cha: 10
role: enemy
skills: Intimidation +2
senses: darkvision 60 ft., passive Perception 10
languages: Common, Orc
challenge: 1/8
environments: arctic, forest, grassland, hill, mountain, swamp, underdark
image: 
token: 
traits:
  - name: Aggressive
    description: "As a bonus action, the orc can move up to its speed toward a hostile creature that it can see."
actions: 
  - name: Bite
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 2 (1 + 1) piercing damage."
```

(print-column)

```Monster {.gray}
id: 
name: Young Orc
slug: young-orc
size: Small
type: humanoid (orc)
alignment: chaotic evil
ac: 13 (hide armor)
hp: 5 (1d6 + 2)
speed: 25 ft.
str: 14
dex: 12
con: 14
int: 7
wis: 11
cha: 10
role: enemy
skills: Intimidation +2
senses: darkvision 60 ft., passive Perception 10
languages: Common, Orc
challenge: 1/4
environments: arctic, forest, grassland, hill, mountain, swamp, underdark
image: 
token: 
traits:
  - name: Aggressive
    description: "As a bonus action, the orc can move up to its speed toward a hostile creature that it can see."
actions:
  - name: Javelin
    description: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
```

(print-page)

```Monster {.gray}
id: 
name: Middle Orc
slug: middle-orc
size: Medium
type: humanoid (orc)
alignment: chaotic evil
ac: 12 (hide armor)
hp: 13 (2d8 + 4)
speed: 30 ft.
str: 14
dex: 12
con: 15
int: 8
wis: 12
cha: 11
role: enemy
skills: Intimidation +2
senses: darkvision 60 ft., passive Perception 11
languages: Common, Orc
challenge: 
environments: arctic, forest, grassland, hill, mountain, swamp, underdark
image: 
token: 
traits:
  - name: Aggressive
    description: "As a bonus action, the orc can move up to its speed toward a hostile creature that it can see."
actions:
  - name: Greataxe
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 8 (1d12 + 2) slashing damage."  
  - name: Javelin
    description: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
```

(print-column)

```Monster {.gray}
id: 
name: Old Orc
slug: old-orc
size: Medium
type: humanoid (orc)
alignment: chaotic evil
ac: 13 (hide armor)
hp: 13 (2d8 + 4)
speed: 25 ft.
str: 12
dex: 12
con: 14
int: 9
wis: 13
cha: 12
role: enemy
skills: Intimidation +3
senses: darkvision 60 ft., passive Perception 11
languages: Common, Orc
challenge: 
environments: arctic, forest, grassland, hill, mountain, swamp, underdark
image: 
token: 
traits:
  - name: Aggressive
    description: "As a bonus action, the orc can move up to its speed toward a hostile creature that it can see."
actions:
  - name: Greataxe
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 7 (1d12 + 1) slashing damage."  
  - name: Javelin
    description: "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 4 (1d6 + 1) piercing damage."
```

(print-page)

```Monster {.gray}
id: 
name: Venerable Orc
slug: venerable-orc
size: Medium
type: humanoid (orc)
alignment: chaotic evil
ac: 13 (hide armor)
hp: 11 (2d8 + 2)
speed: 20 ft.
str: 10
dex: 12
con: 13
int: 10
wis: 14
cha: 13
role: enemy
skills: Intimidation +3
senses: darkvision 30 ft., passive Perception 12
languages: Common, Orc
challenge: 
environments: arctic, forest, grassland, hill, mountain, swamp, underdark
image: 
token: 
traits:
  - name: Aggressive
    description: "As a bonus action, the orc can move up to its speed toward a hostile creature that it can see."
actions:
  - name: Greataxe
    description: "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 6 (1d12) slashing damage."  
  - name: Javelin
    description: "Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 3 (1d6) piercing damage."
```

(print-column)

#### Remorhaz
The heat secretion of a remorhaz, thrym, is valuable as a component for heat-related magical items and can be sold to alchemists for 5-10 gold pieces per flask. The remorhaz will contain 10 flasks worth of thrym per Hit Die. Environments: Arctic

**Ancient Remorhaz.** Roll (1d100) with 25 percent chance of a mate and with (1d2) eggs. The eggs value are at 500 gp.

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

(print-column)

#### Skeleton
Something or someone had it where the resting place was disturbed.

**Dwarven Skeleton.** Environments: Hill, Mountain, Underdark

**Elven Skeleton.** Environments: Forest, Underdark

**Gnomish Skeleton.** Environments: Hill, Forest, Underdark

**Orc Skeleton.** Environments: Arctic, Forest, Grassland, Hill, Mountain, Swamp, Underdark

```Monster {.gray}
id: 
name: Dwarven Skeleton Citizen
slug: dwarven-skeleton-citizen
size: Medium
type: undead (dwarf)
alignment: lawful evil
ac: 17 (scale mail, shield)
hp: 26 (4d8 + 8)
speed: 25 ft.
str: 13
dex: 13
con: 14
int: 7
wis: 10
cha: 5
role: enemy
vulnerabilities: bludgeoning
damageImmunities: cold, poison
conditionImmunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands Common, Dwarvish but can't speak
challenge: 3
environments: hill, mountain, underdark
image: 
token: 
traits:
actions:
  - name: Battleaxe
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with two hands."  
  - name: Handaxe
    description: "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 4 (1d6 + 1) slashing damage."
```

(print-page)

```Monster {.gray}
id: 
name: Elven Skeleton Citizen
slug: elven-skeleton-citizen
size: Medium
type: undead (elf)
alignment: lawful evil
ac: 15 (studded leather armor)
hp: 13 (3d8)
speed: 30 ft.
str: 10
dex: 16
con: 10
int: 7
wis: 11
cha: 7
role: enemy
vulnerabilities: bludgeoning
damageImmunities: cold, poison
conditionImmunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands Common, Elvish but can't speak
challenge: 2
environments: forest, underdark
image: 
token: 
traits:
actions:
  - name: Shortsword
    description: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6 + 3) piercing damage."  
  - name: Longbow
    description: "Ranged Weapon Attack: +5 to hit, range 150/600 ft., one target. Hit: 7 (1d8 + 3) piercing damage."
```

(print-column)

```Monster {.gray}
id: 
name: Gnomish Skeleton Citizen
slug: gnomish-skeleton-citizen
size: Small
type: undead (gnome)
alignment: lawful evil
ac: 17 (chain shirt, shield)
hp: 16 (3d6 + 6)
speed: 25 ft.
str: 15
dex: 15
con: 14
int: 8
wis: 10
cha: 5
role: enemy
vulnerabilities: bludgeoning
damageImmunities: cold, poison
conditionImmunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands Common, Gnomish but can't speak
challenge: 1
environments: hill, forest, underdark
image: 
token: 
traits:
actions:
  - name: Shortsword
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) piercing damage."  
  - name: Hand Crossbow
    description: "Ranged Weapon Attack: +4 to hit, range 30/120 ft., one target. Hit: 5 (1d6 + 2) piercing damage."
```

(print-page)

```Monster {.gray}
id: 
name: Orc Skeleton
slug: orc-skeleton
size: Medium
type: undead (orc)
alignment: lawful evil
ac: 14 (hide armor)
hp: 15 (2d8 + 6)
speed: 30 ft.
str: 16
dex: 14
con: 16
int: 3
wis: 11
cha: 6
role: enemy
vulnerabilities: bludgeoning
damageImmunities: cold, poison
conditionImmunities: exhaustion, poisoned
senses: darkvision 60 ft., passive Perception 10
languages: understands Common, Orc but can't speak
challenge: 1
environments: arctic, forest, grassland, hill, mountain, swamp, underdark
image: 
token: 
traits:
actions:
  - name: Greataxe
    description: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 9 (1d12 + 3) slashing damage."  
  - name: Javelin
    description: "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 6 (1d6 + 3) piercing damage."
```

(print-column)

#### Hippogriff
The hippogriff eggs are worth 1,000 gp. As the hipporgriff gets to infant stage in life can be worth 2,000 gp. When raising a infant hipporgriff. It will need to be taught how to fly when it gets to the younger stage in life. Young hipporgriff can be worth 3,000 gp. When the hippogriff get to adult age. The hippogriff can be more trouble then it is worth.
Environments: Grassland, Hill, Mountain

```Monster {.gray}
id: 
name: Infant Hippogriff
slug: infant-hippogriff
size: Small
type: monstrosity
alignment: unaligned
ac: 11 (natural armor)
hp: 3 (1d6)
speed: 20 ft.
str: 13
dex: 13
con: 11
int: 1
wis: 12
cha: 6
role: enemy
skills: perception +2
senses: passive Perception 12
languages: —
challenge: 1/8
environments: grassland, hill, mountain
image: 
token: 
traits:
  - name: Keen Sight
    description: "The hippogriff has advantage on Wisdom (Perception) checks that rely on sight."
actions:
  - name: Beak
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d4 + 1) piercing damage."  
  - name: Claws
    description: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d4 + 1) slashing damage."
```

(print-page)

```Monster {.gray}
id: 
name: Young Hippogriff
slug: young-hippogriff
size: Medium
type: monstrosity
alignment: unaligned
ac: 11 (natural armor)
hp: 11 (2d8 + 2)
speed: 30 ft., fly 40 ft.
str: 15
dex: 13
con: 12
int: 2
wis: 12
cha: 7
role: enemy
skills: perception +2
senses: passive Perception 12
languages: —
challenge: 1/2
environments: grassland, hill, mountain
image: 
token: 
traits:
  - name: Keen Sight
    description: "The hippogriff has advantage on Wisdom (Perception) checks that rely on sight."
actions:
  - name: Multiattack
    description: "The hippogriff makes two attacks: one with its beak and one with its claws."
  - name: Beak
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8 + 2) piercing damage."  
  - name: Claws
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 7 (2d4 + 2) slashing damage."
```

(print-column)

```Monster {.gray}
id: 
name: Pseudodragon
slug: pseudodragon
size: Tiny
type: dragon
alignment: neutral good
ac: 13 (natural armor)
hp: 7 (2d4 + 2)
speed: 15 ft., fly 60 ft.
str: 6
dex: 15
con: 13
int: 10
wis: 12
cha: 10
role: enemy
skills: perception +3, stealth +4
senses: blindsight 10 ft., darkvision 60 ft., passive Perception 13
languages: understands Common and Draconic but can't speak
challenge: 1/4
image: 
environments: coastal, desert, forest, hill, mountain, urban
token: 
traits:
  - name: Chameleon Skin
    description: "The pseudodragon has advantage on Dexterity (Stealth) checks made to hide."
  - name: Keen Senses
    description: "The pseudodragon has advantage on Wisdom (Perception) checks that rely on sight, hearing, or smell."
  - name: Limited Telepathy
    description: "The pseudodragon can magically communicate simple ideas, emotions, and images telepathically with any creature within 100 feet of it that can understand a language."
  - name: Magic Resistance
    description: "The pseudodragon has advantage on saving throws against spells and other magical effects."
actions:
  - name: Bite
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) piercing damage."  
  - name: Sting
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one creature. Hit: 4 (1d4 + 2) piercing damage, and the target must succeed on a DC 11 Constitution saving throw or become poisoned for 1 hour. If the saving throw fails by 5 or more, the target falls unconscious for the same duration, or until it takes damage or another creature uses an action to shake it awake."
```

(print-page)

>**VARIANT: PSEUDODRAGON FAMILIAR**
>
>Some pseudodragons are willing to serve spellcasters as a familiar. Such pseudodragons have the following trait.
>
>**Familiar.** The pseudodragon can serve another creature as a familiar, forming a magic, telepathic bond with that willing companion. While the two are bonded, the companion can sense what the pseudodragon senses as long as they are within 1 mile of each other. While the pseudodragon is within 10 feet of its companion, the companion shares the pseudodragon's Magic Resistance trait. At any time and for any reason, the pseudodragon can end its service as a familiar, ending the telepathic bond.