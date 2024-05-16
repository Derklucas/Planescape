```statblock
name: Factol Rhys
size: Medium
type: Humanoid
subtype: Tiefling
alignment: Neutral
ac: 18 (Unarmored Defense)
hp: 97
hit_dice: 15d8 + 30
speed: 50 ft.
stats: [10, 19, 14, 10, 18, 12]
saves:
  - WIS: +7
  - Cha: +4
skillsaves:
  - Acrobatics: +7
  - Perception: +7
  - Performance: +4
senses: passive Perception 17
languages: Common plus one more language
cr: 8
traits:
  - name: Instinctive Reflexes
    desc: "The conduit has advantage on initiative rolls, and it can't have disadvantage on attack rolls."
  - name: Unarmored Defense
    desc: "While the conduit is wearing no armor and wielding no shield, its AC includes its Wisdom modifier."
actions:
  - name: Multiattack
    desc: "The conduit makes three Unarmed Strike attacks"
  - name: Unarmed Strike
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage. If the target is a creature, the conduit can choose one of the following additional effects (up to once per turn each):"
  - name: Incapacitate
    desc: "The target must succeed on a DC 15 Constitution saving throw or have the incapacitated condition until the end of the conduit's next turn."
  - name: Push
    desc: "The target is pushed up to 10 feet horizontally away from the conduit."
reactions:
  - name: Deflect Attack
    desc: "In response to being hit by an attack roll, the conduit partially deflects the blow. The damage the conduit takes from the attack is reduced by 1d10."
  - name: Don't Be There
    desc: "When the conduit must make a saving throw, it can move up to half its speed without provoking opportunity attacks. If its new position moves it out of range or otherwise makes it impossible to be targeted by the effect, the conduit avoids the effect entirely."
```