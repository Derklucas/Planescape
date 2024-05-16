```statblock
name: Factol Hashkar
size: Medium
Type: Humanoid
subtype: Dwarf
alignment: Lawful Neutral
ac: 12 (15 with mage armor)
hp: 137
hit_dice: 25d8 + 25
speed: 30 ft.
stats: [8, 15, 12, 19, 16, 14]
saves:
  - CON: +5
  - WIS: +7
skillsaves:
  - Insight: +7
  - Perception: +7
senses: passive Perception 17
languages: Common plus three more languages
cr: 9
actions:
  - name: Multiattack
    desc: "The law bender makes three Arcane Burst attacks and uses Power of Authority or Spellcasting."
  - name: Arcane Burst
    desc: "*Melee or Ranged Spell Attack:* +8 to hit, reach 5 ft. or range 90 ft., one target. *Hit:* 17 (2d12 + 4) force damage."
  - name: Power of Authority
    desc: "The law bender targets a creature it can see within 60 feet of itself. The target must succeed on a DC 16 Intelligence saving throw or take 10 (3d6) psychic damage and have the incapacitated condition for 1 minute. At the end of each of the target's turns, it can repeat the saving throw, ending the incapacitated condition on itself on a success. A target that succeeds on the saving throw becomes immune to this law bender's Power of Authority for 24 hours."
  - name: Spellcasting
    desc: "The law bender casts one of the following spells, requiring no material components and using Intelligence as the spellcasting ability: At will: dispel magic, fly, mage armor, mage hand, prestidigitation"
bonus_actions:
  - name: Spatial Loophole
    desc: "The law bender teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see."
reactions:
  - name: Probability Loophole (3/Day)
    desc: "When the law bender or a creature it can see makes an attack roll, a saving throw, or an ability check, the law bender can cause the roll to be made with advantage or disadvantage."
```