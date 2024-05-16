```statblock
name: Fell
size: medium
type: Celestial
alignment: Lawful Neutral
ac: 12
hp: 44
hit_dice: 8d8 + 8
speed: 20 ft., fly 30 ft. (hover)
stats: [8, 14, 12, 16, 15, 14]
saves:
  - INT: +5
  - WIS: +5
skillsaves:
  - Insight: +4
  - Perception: +6
condition_immunities: exhaustion
senses: darkvision 60 ft., passive Perception 16
languages: understands all languages but can't speak; communicates via Symbol Speech
cr: 2
traits:
  - name: Physical Restraint
    desc: "The dabus doesn't make melee attacks or opportunity attacks, even in self-defense."
  - name: Symbol Speech
    desc: "A dabus communicates by creating illusory symbols and pictures that float in the air in front of itself and disappear a few seconds later. A creature that can see such a message can decipher it with a successful DC 10 Intelligence (Investigation) check (no action required)."
actions:
  - name: Multiattack
    desc: "The dabus makes two Flying Brick attacks."
  - name: Flying Brick
    desc: "*Ranged Spell Attack:* +5 to hit, range 90 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage."
  - name: Grasping Ground (Recharge 6)
    desc: "The dabus causes a 20-foot-square area of ground it can see within 60 feet of itself to sprout clutching appendages made of stone. Each creature of the dabus's choice in that area must succeed on a DC 13 Dexterity saving throw or take 9 (2d8) bludgeoning damage and have the grappled condition (escape DC 13). While grappled in this way, the creature has the restrained condition. The appendages vanish after 1 minute or if the dabus's concentration ends (as if concentrating on a spell)."
```