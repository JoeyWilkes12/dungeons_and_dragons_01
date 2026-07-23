# Sritooh Triithe — Level 10 to 11 Build Checklist (Revised 01)

## Purpose and current assumptions

This is a working level-up plan, not a declaration that any unconfirmed choice has been made. It compares `Checklist Monk Build.md` with Sritooh's captured Roll20 level-10 sheet and assumes the campaign is using the 2024 Monk, Warrior of the Elements, and Dragonborn rules shown on that sheet.

Sritooh is already a Dexterity/Wisdom Monk with 50-foot Speed, AC 16, Wisdom-based DC 15, Acid resistance, Mage Slayer, Magic Initiate (Wizard), Resilient, and no recorded magic items. The level-10 values are a mid-fight snapshot: 53/73 HP, 7/10 Focus, and checked resource pips are **not** the values to carry forward automatically.

## Bottom line: what this level actually gives you

Level 11 is not a feat, ASI, spell-selection, or automatic-equipment level. Do not rebuild the character around a new spell or assume new gear is owed. The upgrade is a mobility-and-scaling level:

| Change | Level 10 sheet | Level 11 target | Why it matters |
|---|---:|---:|---|
| Monk level / Hit Dice | 10 / 10d8 | 11 / 11d8 | Add one Hit Die and choose/roll level-up HP by the table's method. |
| Martial Arts die | 1d8 | 1d10 | Updates several Monk rolls. |
| Focus maximum | 10 | 11 | Current Focus remains encounter state; set the maximum to 11. |
| Stride of the Elements | — | New subclass feature | While Elemental Attunement is active, Fly and Swim Speeds equal Speed: currently **50 feet**. |
| Dragonborn Breath Weapon | incorrectly displayed as 1d10 | **3d10 Acid**, DC 14 | Character level 11 also increases this species feature. |
| Proficiency / AC / Speed / save DC | +4 / 16 / 50 ft / 15 | unchanged | No ability-score change occurs at this level. |

## Recommended build identity

Keep Sritooh as a mobile unarmed controller rather than trying to turn this level into a caster or weapon upgrade. Elemental Attunement costs 1 Focus **at the start of your turn**, does not use your Action or Bonus Action, lasts 10 minutes, and ends if you become Incapacitated. At level 11 it now also enables 50-foot flight and swimming. That leaves the Bonus Action free for Flurry of Blows, Patient Defense, or Step of the Wind.

The practical loop is: activate Attunement for a meaningful encounter; use the 15-foot Unarmed Strike reach (normal 5 ft + 10 ft); select a useful elemental damage type; use the push/pull when positioning matters; and use flight for angle, access, and safety—not simply for maximum altitude. Sritooh does **not** have the Grappler feat on the captured sheet, so do not base this level-up on the Grappler-specific advantage/grapple combo unless that feat is obtained later.

## Priority 1 — settle before editing the sheet

- [ ] **Confirm how HP is awarded.** Add either `1d8 + 2` HP or the table's fixed value. If fixed HP is used, the expected maximum is **80** (73 + 5 + CON 2); do not overwrite current HP until the DM says when the level-up takes effect.
- [ ] **Confirm the Resilient selection.** The feat exists, but its chosen ability and added saving-throw proficiency are absent from the visible Roll20 sheet. Constitution is a plausible inference because it is 14 and lacks proficiency, but it is not confirmed. This is the most important pre-existing build question because it changes a saving throw and may explain an ability-score increase.
- [ ] **Confirm the campaign uses the 2024 entries consistently.** The sheet already uses 2024 Monk terminology and features, but Roll20 can mix legacy compendium content. This determines whether a conflicting legacy card should be corrected or intentionally retained as a house rule.

## Priority 2 — make these Roll20 corrections and level-11 updates

### Core sheet

- [ ] Set class level to 11 and Hit Dice to 11d8.
- [ ] Set maximum Focus Points to 11; retain or reset current Focus only as the actual encounter/rest state requires.
- [ ] Add **Stride of the Elements**: while Elemental Attunement is active, Fly Speed 50 ft and Swim Speed 50 ft.
- [ ] Keep AC 16, Speed 50 ft, Proficiency +4, Monk/Spell DC 15, and spell attack +7 unless the Resilient check changes an ability score.
- [ ] Keep Draconic Flight as a separate 1/Long Rest source of 50-foot flight. It is a fallback when Attunement is inactive, not a replacement for Stride.

### Actions, damage, and resources

- [ ] Change Unarmed Strike and Bonus Unarmed Strike to `1d10 + 3`.
- [ ] Change each Flurry of Blows strike to `1d10 + 3`; Heightened Focus still makes three strikes for 1 Focus.
- [ ] Change Elemental Burst to `3d10` of the chosen eligible type; it still costs 2 Focus and uses a Magic action.
- [ ] Change Focused Patient Defense temporary HP to `2d10`.
- [ ] Change Uncanny Metabolism healing to `11 + 1d10`; its use limit remains 1/Long Rest.
- [ ] Change Deflect Attacks reduction to `1d10 + 14` (Martial Arts die + DEX 3 + Monk level 11).
- [ ] Change Redirect Attack damage to `2d10 + 3` if it is entered as a separate attack.
- [ ] Change Slow Fall to reduce falling damage by 55.
- [ ] Correct both Breath Weapon action rows from the displayed 1d10 to **3d10 Acid**, DC 14, with 4 uses per Long Rest. This resolves the known level-10 error (it should already have been 2d10) and applies the character-level-11 increase.
- [ ] Verify Elemental Attunement has 10 additional feet of reach on Unarmed Strikes and a visible STR 15 push/pull reminder.
- [ ] Keep the Elementalism, Fire Bolt, Thunderclap, Thunderwave, and See Invisibility entries. No Monk spell is learned at this level; relabel See Invisibility to **Vecna's Link** if Roll20 allows it, since the current Magic Initiate source label is misleading.

### Markers and practical controls

- [ ] Add an **Attuned** marker plus a 10-minute duration note.
- [ ] Add a separate **Stride flight** marker/altitude label; do not merge it with the once-per-Long-Rest Draconic Flight tracker.
- [ ] Make quick rolls for Elemental Attunement, elemental Unarmed Strike, Flurry (three strikes), Elemental Burst, Focused Patient Defense, Breath Weapon, and Slow Fall.
- [ ] Make the resource bars visible only if the group normally sees them; otherwise keep Focus and one-use pips on the character sheet.

## Remaining Roll20 questions

These are not all questions for the DM. The first four are sheet checks that should be answered directly while editing.

| Priority | Question | Owner | Resolution / next action |
|---|---|---|---|
| P0 | Which ability did Resilient increase and make proficient? | Player + DM if needed | Select the actual ability and make the saving-throw marker/bonus agree with it. |
| P0 | How is level-up HP determined, and when does it take effect? | DM | Then set maximum and current HP. |
| P0 | Are both Breath Weapon rows configured as 3d10 Acid at level 11? | Player | Correct both; the current 1d10 display is wrong even for the level-10 snapshot. |
| P1 | Is the stale Martial Arts prose (1d6) a card-display issue? | Player | Treat the level-11 mechanical die as d10 and update all dependent rolls. |
| P1 | Can See Invisibility be relabeled from Magic Initiate to Vecna's Link? | Player | The source is a display issue; keep its 1/Long Rest usage. |
| P1 | How will altitude and vertical map position be shown? | DM | Agree on a label, token marker, or map annotation before airborne combat. |
| P1 | Does this campaign use a house rule for the 2024 flying/falling rule? | DM | By the listed 2024 rule, falling occurs while flying if Sritooh is Incapacitated or Prone, or Fly Speed becomes 0, unless able to hover. If Draconic Flight is separately active, its Fly Speed remains after Attunement ends. |
| P2 | Does the table allow the 15-foot elemental Unarmed Strike reach to be used for the Unarmed Strike option that grapples? | DM | The sheet currently labels grapple/shove simply “Melee”; establish the table handling before planning ranged grapples. |
| P2 | How are vertical push/pull, carried grappled creatures, and falling damage adjudicated on the grid? | DM | Ask only if Sritooh intends to use aerial control; record the answer in the macro notes. |
| P3 | Is there level-up or campaign loot to choose? | DM | No equipment is automatically required. If loot is available, prioritize unarmed-strike support, AC/saves, then mobility; do not add an item without an award or DM approval. |

## Questions that are already answered

- **Do I choose new Monk spells?** No. Elementalism is already known; level 11 grants Stride of the Elements, not spellcasting progression.
- **Do I get an ASI or new feat?** No. The next Monk ASI/feat decision is level 12.
- **Does Stride replace Draconic Flight?** No. Both grant a 50-foot Fly Speed under different conditions; track their duration and usage independently.
- **Does Elemental Attunement consume a Bonus Action?** No. It is activated at the start of the turn for 1 Focus, so the Bonus Action remains available.
- **Do I need to ask whether flight ends on Incapacitation?** The 2024 flying rule answers this: without Hover, an Incapacitated flying creature falls. The useful DM question is how the table displays and resolves it on Roll20, particularly when more than one fly-speed source is active.

## Session-ready combat checklist

- [ ] At the start of a meaningful fight, decide whether 1 Focus for Attunement is worth 10 minutes of reach, elemental control, flight, and swimming.
- [ ] Mark Attunement and, when airborne, record altitude before moving the token.
- [ ] Favor Unarmed Strikes over the current weapons when using Attunement; they are the attacks that receive the reach and elemental benefits.
- [ ] Use Elemental Burst when it can affect several enemies or solves a range/access problem; otherwise the Action is often more valuable for attacks.
- [ ] Reserve Focus for a consequential Stunning Strike, defensive Patient Defense, or escape/repositioning instead of spending it automatically.
- [ ] Do not finish high in the air without considering Incapacitated, Prone, or Speed-0 risks; Sritooh's Slow Fall reduces 55 falling damage but does not prevent the landing.

## Source notes

The numerical baseline and unresolved sheet discrepancies above come from `Sritooh Triithe - Level 10 Character Sheet.md` and its companion claims dataset. The level-11 interpretation is consistent with the 2024 [Warrior of the Elements overview](https://www.dndbeyond.com/posts/1763-warrior-of-the-elements-monk-bend-the-elements-to), which identifies Stride's Fly and Swim Speeds as equal to Speed while Attunement is active; the [Roll20 Dragonborn Breath Weapon entry](https://roll20.net/compendium/dnd5e/Other%20Options%20and%20Features%3ADragonborn%20Breath%20Weapon/) confirms 3d10 at character level 11; and the [Roll20 rules definitions](https://roll20.net/compendium/dnd5e/Rules%20Definitions) cover flying, falling, and special-speed changes.
