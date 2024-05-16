```statblock
name: Factol Terrance
size: Medium
type: Humanoid
subtype: Human
alignment: Neutral good
ac: 14 (leather armor)
hp: 84
hit_dice: 13d8 + 26
speed: 30 feet
stats: [12, 16, 14, 15, 14, 10]
saves:
  - DEX: +6
  - WIS: +5
skillsaves:
  - Investigation: +8
  - Perception: +5
  - Stealth: +6
languages: Common plus two more languages
cr: 5
traits:
  - name: Avoidance
    desc: "If Factol Terrance is subjected to an effect that allows it to make a saving throw to take half as much damage, it instead takes no damage if it succeeds on the saving throw, and half as much damage if it fails."
actions:
  - name: Multiattack
    desc: "The null makes two Force Dagger attacks"
  - name: Force Dagger
    desc: "*Melee or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit*: 5 (1d4 + 3) piercing damage plus 13 (3d8) force damage. Hit or Miss: The dagger magically returns to the null's hand immediately after a ranged attack."
bonus_actions:
  - name: Defier's Whim
    desc: "The null takes the Dash, Disengage, or Use an Object action"
reactions:
  - name: Nullify Spell (3/Day)
    desc: "The Factol utters a magical word of cancelation to interrupt a creature it can see that is casting a spell. If the spell is 3rd level or lower, it fails and has no effect. If the spell is 4th level or higher, the null makes an Intelligence check (DC 10 + the spell's level). On a successful check, the spell fails and has no effect."
```