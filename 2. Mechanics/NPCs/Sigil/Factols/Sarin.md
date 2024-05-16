```statblock
name: Factol Sarin
size: Medium
type: Humanoid
subtype: Human
alignment: Lawful Neutral
ac: 20 (plate armor, shield)
hp: 110
hit_dice: 17d8 + 34
speed: 30 ft.
stats: [19, 10, 14, 12, 16, 16]
saves:
  - STR: +7
  - WIS: +6
skillsaves:
  - Perception: +6
condition_immunities: charmed, frightened
senses: passive Perception 16
languages: Common plus one more language
cr: 8
traits:
  - name: Aura of Command
    desc: "Allies within 30 feet of the captain are immune to the charmed and frightened conditions. This aura is suppressed while the captain has the incapacitated condition."
actions:
  - name: Multiattack
    desc: "The captain makes three Harmonium Blade attacks. The captain can also use Dictate if available"
  - name: Harmonium Blade
    desc: "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 10 (3d6) lightning damage."
  - name: Dictate (Recharge 5-6)
    desc: "The captain verbally commands up to three creatures it can see within 60 feet of itself. This magical command must be to undertake an action or to refrain from taking actions (for example, Throw down your weapons). A target must succeed on a DC 14 Wisdom saving throw or have the charmed condition for 1 minute, during which time it follows the captain's command. The effect ends early if the target takes damage or if it successfully completes the command. A target automatically succeeds on its saving throw if the command is directly harmful to itself, such as commanding it to walk into fire."
```