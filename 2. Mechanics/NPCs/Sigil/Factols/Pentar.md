```statblock
name: Factol Pentar
size: Medium
Type: Humanoid
subtype: Human
alignment: Chaotic Neutral
ac: 18 (plate armor)
hp: 202
hit_dice: 27d8 + 81
speed: 30 ft.
stats: [20, 12, 16, 15, 14, 18]
saves:
  - STR: +9
  - CON: +7
skillsaves:
  - Perception: +6
damage_immunities: necrotic
senses: passive Perception 16
languages: Common plus three more languages
cr: 12
traits:
  - name: Aura of Doom
    desc: "Any creature that starts its turn within 10 feet of the doom lord must make a DC 16 Constitution saving throw, taking 18 (4d8) necrotic damage on a failed save, or half as much damage on a successful one. If the doom lord doesn't have the incapacitated condition, it can suppress or resume this aura at the start of its turn (no action required)."
  - name: Siege Monster
    desc: "The doom lord deals double damage to objects and structures."
actions:
  - name: Multiattack
    desc: "The doom lord makes two Entropic Greatsword or Entropic Javelin attacks"
  - name: Entropic Greatsword
    desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit*: 12 (2d6 + 5) slashing damage plus 10 (3d6) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash."
  - name: Entropic Javelin
    desc: "*Melee or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 8 (1d6 + 5) piercing damage plus 14 (4d6) necrotic damage. A creature killed by this attack has its body and everything it is wearing or carrying, except for magic items, reduced to ash."
```