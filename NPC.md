---
name: NPC
slug: npc
pdf-page-style: multi-column
order: 6
include-in: all
---

# NPC

#### Aust Rothenel
Aust is moon elf noble. Aust family enjoyed traveling around the world. Intel one day the elven nobles asided Rothenel family a task to protect the Whispering Forest. Over time Aust family noticed the forest was more kept up. As Rothenel where born and died. They figured out three Great Trees where guarding a portal into the feywild. Over time Rothenel family started to do the same. Now Aust time has come to guard the portal relizing this must be the reason why his family was tasked to setal down.  Aust has a signet ring on his right ring finger, a set of fine clothes with a small silver spinning top that, when spun, endlessly spins until interrupted. Aust is also carring Moonblade +2 that comes with Gleaming that item never gets dirty.

Personality Trait - "I take great pains to always look my best and follow the latest fashions."

Ideal - "Responsibility. It is my duty to respect the authority of those above me, just as those below me must respect mine. (Lawful)"

Bond - "My house's alliance with another noble family must be sustained at all costs."

Flaw - "In fact, the world does revolve around me."

(print-column)

```Monster {.gray}
id: 
name: Aust Rothenel
slug: aust-rothenel
size: Medium
type: humanoid (elf)
alignment: lawful good
ac: 16 (breastplate)
hp: 9 (2d8)
speed: 30 ft.
str: 11
dex: 14
con: 11
int: 13
wis: 14
cha: 16
role: enemy
skills: Deception +5, Insight +4, Persuasion +5
senses: darkvision 60 ft., passive Perception 12
languages: Elvish, Goblin
challenge: 1/8
environments: forest, urban
image: 
token: 
traits:
  - name: Fey Ancestry
    description: "Aust has advantage on saving throws against being charmed, and magic can't put Aust to sleep."
  - name: Innate Spellcasting
    description: "Aust's spellcasting ability is Intelligence (spell save DC 11). It can innately cast the following spells, requiring no material components:"
  - name: At will
    description: "Minor Illusion"
actions:
  - name: Moonblade +2 (Longsword)
    description: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8 + 2) slashing damage or 7 (1d10 + 2) slashing damage if used with two hands."
reactions:
  - name: Parry
    description: "Aust adds 2 to its AC against one melee attack that would hit it. To do so, Aust must see the attacker and be wielding a melee weapon."
```

(print-page)

#### Rolen Galanodel (Moonwhisper) the Homesteader
Rolen Galanodel a wood elf homesteader (Scout), who has been accepted into the village community of Nealion. Rolen believes in the gods and the weak will pass, the strong will live on.

Personality Trait - I'm always picking things up, absently fiddling with them, and sometimes accidentally breaking them.

Ideal - Nature. The natural world is more important than all the constructs of civilization. (Neutral)

Bond - I will bring terrible wrath down on the evildoers who destroyed my homeland.

Flaw - Don't expect me to save those who can't save themselves. It is nature's way that the strong thrive and the weak perish.

(print-column)

```Monster {.gray}
id: 
name: Rolen Galanodel (Moonwhisper) the Homesteader
slug: rolen-galanodel-(moonwhisper)-the-homesteader
size: Medium
type: humanoid (elf)
alignment: neutral good
ac: 14 (leather armor)
hp: 16 (3d8 + 3)
speed: 35 ft.
str: 11
dex: 16
con: 12
int: 11
wis: 14
cha: 11
role: enemy
skills: Nature +4, Perception +6, Stealth +6, Survival +5
senses: darkvision 60 ft., passive Perception 16
languages: Elvish, Sylvan
challenge: 1/2
environments: forest
image: 
token: 
traits:
  - name: Fey Ancestry
    description: "Rolen has advantage on saving throws against being charmed, and magic can't put Rolen to sleep."
  - name: Keen Hearing and Sight
    description: "Rolen has advantage on Wisdom (Perception) checks that rely on hearing or sight."
  - name: Mask of the Wild
    description: "Rolen can attempt to hide even when they are only lightly obscured by foliage, heavy rain, falling snow, mist, and other natural phenomena."
actions:
  - name: Multiattack
    description: "Rolen makes two melee attacks or two ranged attacks."
  - name: Shortsword
    description: "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6 + 3) piercing damage."
  - name: Longbow
    description: "Ranged Weapon Attack: +5 to hit, ranged 150/600 ft., one target. Hit: 7 (1d8 + 3) piercing damage."
```