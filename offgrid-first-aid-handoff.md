# Health Codex: handoff for home (17 Nov 2026)

Written in a cloud session from the phone. Nothing in `infi22/Health-Codex` was changed from here: no branch, no commit, no push.

Use: open the PC session "Guide-color work in progress" (or a new one in `C:\DEV\Health-Codex`) and paste the section you need.

---

## 1. Where the PC stands

Read from this morning's session transcript, not from the disk. Confirm with `git status` first.

- `main` on the PC: 13 changed files, 2 new topic files, 2 new research folders. **Nothing committed.**
- `guide-color`: commit `02491fb`, not pushed. It lacks today's work and needs a merge from `main` later.
- GitHub `main` is still the 15 Nov save (`5cf774a`). Published app is still version 30.

Built today and reported green (codex clean, smoke 52 screens, symptoms 146/146, flow 15/15, climb 64/64, Guide 90/90):

| Work | Serial | Size | Sources |
|---|---|---|---|
| Eating disorders, "הפרעות אכילה" | D46 | 9 steps, 7 signs | S526 to S546 |
| Sting capsule widened: jellyfish, spider | D25.7, D25.8 | 2 steps | part of S547 to S565 |
| Poison, "הרעלה" | D47 | 8 steps | part of S547 to S565 |

## 2. Do in this order at home

1. `git status` in `C:\DEV\Health-Codex`. Check the 13 files are still there.
2. **Commit to `main`** as two commits: eating disorders, then stings and poison. Push only on your yes.
3. **Rule on the snake step.** The app quotes MDA: "יש לקבע את הגפה הפגועה". The Ministry of Health and the Rambam poison centre are reported to say not to immobilise. Recommendation: show both lines until a doctor rules.
4. `tusk save`: `LATER.md` and `deck/deck-data.js` still say 45 paths. It is 47.
5. Merge `main` into `guide-color`.
6. Veto or approve the D46 drafts: the four Guide notes, the intro, the scene line "לא אשמים, ולא לבד."
7. Only then build the wasteland tips (sections 3 and 4) into the app.

## 3. Wasteland rules (the owner's decision, 17.11.2026)

Decided by the owner on 17.11.2026. No further approval needed. Add it to `CLAUDE.md` next to the first-aid rule:

> **Wasteland rules (the owner's decision, 17.11.2026).** When a person is alone, far from help, with no reception or a dead phone, "call 101" is not an answer. For that situation the app gives the tips themselves: what to do with your own hands, in order. Israeli official lines are not required here, because they all assume a phone. The source is wilderness medicine guidelines (WHO for viper bites, Wilderness Medical Society, AHA / Red Cross, ILCOR). The 9.11 "never treatment" rule and the 11.11 "Ministry or MDA quotes only" rule stay in force everywhere else in the app.

What the decision does not settle, because it is a fact and not a rule:

- **A dead phone means a dead app.** These tips must be read before the trip. Build them as a "לפני שיוצאים לשטח" screen that also prints or saves well, not as an emergency screen.
- **The tips below are from memory of the guidelines, not from their text.** The cloud could not open a single guideline. Each tip is marked [G] or [J]; see the key at the top of section 4. Nothing ships before it is checked against the reading list in 5c.
- The app text is Hebrew. These are the English working lines; write the Hebrew at build time, short and plain.

## 4. The wasteland tips

The frame for all five: **you are alone, far from a road, and the phone is dead or has no signal.**

**How to read the marks. Nothing here was checked against a source text from the cloud session.**

- **[G]** I remember this as standard in the major first-aid guidelines (WHO, AHA / Red Cross, CDC, Wilderness Medical Society, allergy societies). Memory, not a quote. Confirm against the reading list in 5c before it ships.
- **[J]** My own judgment. No guideline line behind it that I know of. Ship it only if a doctor or paramedic agrees, or drop it.

Second pass, 17.11.2026: lines I could not stand behind were removed. They are listed in 4.6 so nobody adds them back by accident.

### 4.1 Snake bite

1. **[G]** Move away from the snake. Sit down and calm yourself. Keep the bitten limb as still as you can.
2. **[G]** Take off rings, watch and anything tight on that limb, before the swelling starts.
3. **[G]** Note the time of the bite.
4. **[G]** Do not cut the bite, suck it, tie a tourniquet or put ice on it. No alcohol.
5. **[G]** Do not try to catch or kill the snake. Remember how it looked.
6. **[G]** The only treatment is antivenom, in a hospital. First aid must not delay getting there.
7. **[J]** Alone, and nobody knows where you are: walk out, at a steady pace, by the shortest way to a road or people. The guidelines say "avoid exertion" and "do not delay care"; for a lone person those two collide, and no guideline I know rules on it.
8. **[J]** If someone knows your route and return hour, staying put near the trail may be the better choice.

- **[G]** Pain: paracetamol, not aspirin or ibuprofen. From memory of the WHO South-East Asia guideline; this one needs checking first.
- **Open, do not write a tip yet:** splint or not (sources split, 5a). Limb height (heart level or below; sources split). Drinking: MDA says no food or drink, which nobody has squared with a walk of hours in a desert.

### 4.2 Heavy bleeding

1. **[G]** Press hard, straight on the wound, with any cloth. Do not lift to look.
2. **[G]** Blood comes through: add cloth on top and keep pressing.
3. **[G]** An object stuck in the wound stays in. Press around it.
4. **[G]** Arm or leg, life-threatening, and pressure does not stop it: tourniquet above the wound, tightened until the bleeding stops. Note the time. Do not loosen it.
5. **[G]** A manufactured tourniquet works much better than an improvised one. Carry one.
6. **[J]** Alone, tie a cloth strip tightly over the wad so the pressure stays while you move.
7. **[J]** No manufactured tourniquet: a wide strip of cloth twisted tight with a stick, not on a joint. This is the usual improvised method, but its failure rate is high.

### 4.3 Heat

- **[G]** Early signs: headache, dizziness, nausea, cramps, heavy tiredness.

1. **[G]** Stop the effort. Get into shade. Loosen or take off extra clothes.
2. **[G]** Awake and able to swallow: drink.
3. **[G]** Cool the body: wet the skin and clothes and fan.
4. **[G]** Confusion, stumbling, strange behaviour or passing out, in a hot person, is heat stroke. Cool first, move second. The best method is putting the body in cold water; otherwise pour water over the whole body and fan.
5. **[G]** Nothing by mouth to a person who is not fully awake. Fever pills do not help.
6. **[J]** Alone, act at the first signs, because later you will not think clearly.
7. **[J]** Wait in shade for the cool hours before walking on.

- **Open:** in a desert the water for wetting clothes is the same water you drink. No source I know says how to split it. Israel's Ministry of Health appears to say no drink at all in heat stroke (5a).

### 4.4 Severe allergic reaction

- **[G]** Signs, within minutes of a sting or food: hard to breathe, swelling of throat or face, rash all over, faintness.

1. **[G]** Adrenaline injector into the outer thigh, at once. Through clothes is fine.
2. **[G]** Lie down with legs raised. If breathing is hard, sit up. Do not stand up or walk.
3. **[G]** No improvement after several minutes: a second injector, if there is one. The exact wait differs between guidelines.
4. **[G]** A bee stinger: get it out fast.
5. **[G]** An antihistamine does not treat this. It is not a replacement for the injector.
6. **[G]** Get to a hospital even if it passes. The reaction can return hours later.
7. **[J]** No injector: lie down with legs raised and stay still. There is no field treatment I can honestly offer beyond that.

### 4.5 Dead phone, no signal: being found

This card has the least evidence behind it. Almost all of it is ordinary outdoor practice, not medical guidance.

1. **[G]** Before the trip: tell one person the route and the return hour. Rescue bodies everywhere say this; the Israeli wording was not found.
2. **[J]** Before the trip: downloaded map, power bank, whistle.
3. **[J]** No bars: try 112 anyway, and again from higher, open ground. It may connect through another network. It may not.
4. **[J]** Stay on the marked trail.
5. **[G]** Three whistle blasts, three flashes or three shouts is a recognised distress signal.
6. **[J]** At night, stop. Do not walk cliffs or wadis in the dark.

### 4.6 Removed in the second pass, and why

- "Heat is the bigger killer of hikers than any snake": no figure, no source.
- "Snakes do not chase" and "most bites happen when a hand or foot goes where the eyes did not": no source.
- "Small sips of water" while walking out after a snake bite: contradicts MDA's "no food or drink", and I had no source.
- "Keep the arm still against the body": my own detail.
- "Add salt or a salty snack": not sure enough of the guideline wording.
- "About one litre per hour" and "turn back when half the water is gone": the first is an unverified search lead, the second a hiking rule of thumb.
- "A text needs less signal than a call" and "searchers follow trails first": common claims, no source.
- "Turn the phone off in stretches with no signal": my own.
- "Shaky: nothing" on the bleeding card: an overclaim. Nothing in this file is verified.

## 5. Research findings

### 5a. Israeli official sources: leads only, nothing verified

**The cloud session could not open a single official Israeli page.** Its network blocked `mdais.org`, `gov.il`, `me.health.gov.il`, `rambam.org.il`, `parks.org.il`, `police.gov.il` and the health funds; `kolzchut.org.il` returned 403. Everything below is what a search engine showed of the page, so it is ⚠️ "snippet only": no quote is confirmed word for word, and no page date was read. On the PC, open each URL and copy the text and the date.

**Snake bite**

| Source | URL | What the search showed |
|---|---|---|
| MDA, "כיצד לטפל בהכשת נחש" | https://www.mdais.org/101/snake-bite?page=133 | Do: "יש לחייג מייד 101", "יש להרחיק את הנפגע ולהעביר אותו למקום בטוח", "יש לדאוג למנוחה מוחלטת של הנפגע ולהרגעתו", "יש להסיר בגדים ותכשיטים מהגפה הפגועה", "יש לקבע את הגפה". Don't: cut, suck, tourniquet, food or drink, chase the snake |
| Ministry of Health, parents' site | https://me.health.gov.il/parenting/raising-children/safe-environment/risks-to-children/bites-and-stings-first-aid/ | Lay the person down "כך שהאיבר המוכש יהיה מתחת לגובה הלב ולא יזוז". Never: suck, "לקבע את האיבר המוכש", cool, tourniquet |
| Rambam poison centre | https://www.rambam.org.il/departmentsandclinics/laboratories-division/clinical-pharmacology-and-toxicology/national-center-for-the-treatment-of-poisoning/snakes_important_information/ | "אין לחבוש, לקבע, לקרר או לנסות להוציא את הארס." |
| Rambam magazine (old) | https://www.rambam.org.il/magazine/health-promotion/?itemid=%7BD18C584D-EC24-4B9E-BA4C-ED602EE49FE4%7D | "אם אפשר – קבעו את גופו כדי להפחית למינימום כל תזוזה". Also said to suggest bringing the snake |

**The splint conflict looks real, and narrower than it sounds.** MDA lists "לקבע" as a do and the tourniquet as a separate don't. The Ministry and the poison centre list "לקבע" as a don't, also separate from the tourniquet. All three agree the limb should not move, and on no tourniquet, no cutting, no sucking. So the dispute is only whether to actively splint, or just keep still.

**No signal**

- MDA app, https://www.mdais.org/app and https://www.mdais.org/app/termsofuseapp : one press sends location "גם ללא רשת נתונים זמינה", by SMS. That still needs cellular signal.
- MDA, https://www.mdais.org/101/emergency : SMS and WhatsApp 052-7000-101 is described as for the hearing-impaired only.
- Police rescue units, https://www.police.gov.il/join/rescue : describes the units. No numbers or hiker instructions surfaced.
- 112 without a SIM or on another carrier: **no official Israeli page found.** Only a wiki says so.

**Other cards**

- **Heat stroke**, Ministry of Health, https://me.health.gov.il/older-adult/specialist-advice/managing-extreme-weather/heat-protection/ : shade, cool with wet towels, ER at once, **do not give drink**. Heat exhaustion: rest, loosen clothes, sip water.
- **Allergy**, Ministry of Health, https://me.health.gov.il/parenting/raising-children/safe-environment/risks-to-children/anaphylactic-shock/ : adrenaline injection at once, then ER. MDA adult booklet page 14, https://www.mdais.org/Files/Book/Adult_first_aid/files/basic-html/page14.html : use the auto-injector for a known bee allergy.
- **Bleeding and tourniquet: nothing found.** Look under https://www.mdais.org/101 on the PC.
- **Water**, Parks Authority, https://www.parks.org.il/new/beticut/ and https://www.parks.org.il/new/clalim6 : about 3 litres a person in the north, 5 in the south, or at least 1 litre per hour of walking. Figures differ between pages.

**Other conflicts between official pages**

- Scorpion sting: the Ministry forbids cooling; the old Rambam magazine page recommends it.
- Snake: the old Rambam magazine page says bring the snake; the poison centre and MDA say don't chase it.
- Water per person: several Parks Authority figures.

**No official Israeli line found**

- Walk out or stay, for a lone snake-bite victim with no reception.
- 112, emergency SMS for the public, satellite SOS.
- How to call the rescue units.
- Bleeding, tourniquet, fracture, sprain.
- Allergy with no auto-injector.

**What this changed in the tips (section 4)**

- Card 2: the Ministry's line puts the limb **below heart level** and still. "Take off jewellery" is confirmed as a lead from two sources.
- Card 4: the Ministry says **no drink** in heat stroke. My draft said "drink only if fully awake". The Ministry's line is the stricter one; use it, and keep sipping water for heat exhaustion only.
- Card 1: almost nothing official exists. Most of this card would be international or "one line is mine".

### 5b. International guidelines

**Also leads only.** The cloud network blocked every guideline site (who.int, cdc.gov, nhs.uk, ahajournals.org and the rest), so no guideline text was opened. Everything here is ⚠️ "snippet only". Lines marked "recall" are a helper's memory and weaker still.

**Snake bite**

| Source | Year | URL or DOI | What the search showed |
|---|---|---|---|
| AHA / American Red Cross first aid guidelines | 2024 | https://www.ahajournals.org/doi/10.1161/CIR.0000000000001281 | "Rest and immobilize the bitten extremity, remove constricting objects and avoid exertion if it doesn't delay medical care." Pressure bandaging is said to be listed as potentially harmful |
| Wilderness Medical Society, pit viper guideline | 2015 | doi 10.1016/j.wem.2015.05.007 | "Immobilization of the affected area by splinting (without compression) may benefit the patient." Limb at heart level. Against pressure bandage and tourniquet. Scope: North American pit vipers only |
| WHO, snakebite treatment page | not seen | https://www.who.int/teams/control-of-neglected-tropical-diseases/snakebite-envenoming/treatment | Get to a health facility without delay; avoid traditional first aid |
| NHS 111 Wales | not seen | https://111.wales.nhs.uk/bites,snake | Don't catch the snake, suck, cut or tie tightly. Do: paracetamol, remove jewellery, remember the snake's look |
| CDC / NIOSH | not seen | https://www.cdc.gov/niosh/outdoor-workers/about/venomous-snakes.html | "Take a photograph from a safe distance to identify the snake if possible" |

- **The source that matters most was not reached:** WHO South-East Asia, "Guidelines for the management of snakebites", 2nd edition 2016 (iris.who.int). Recall only: pressure bandaging is discouraged for viper bites, and aspirin and ibuprofen-type painkillers are to be avoided because of bleeding.
- **Ice, electric shock, suction devices, alcohol, caffeine:** not confirmed in any snippet. My "don't" list in card 2 has no source for these yet.

**Walk out or stay**

- WMS 2015: "Field first aid should not delay transport of the patient to an appropriate facility that has antivenom."
- A WMS-linked article: call rescue at once "unless a safe and practical self-evacuation can be confidently carried out without compromising the patient's condition."
- No guideline line on a lone victim was found. "Walk out slowly rather than wait" in card 2 stays an inference, not a quote.

**Other cards**

- **Bleeding**, AHA 2024 summary, https://professional.heart.org/en/science-news/2024-aha-and-american-red-cross-guidelines-for-first-aid/top-things-to-know : "apply direct pressure followed by application of a tourniquet or wound packing, if the location of the wound is amenable."
- **Heat stroke**, WMS heat illness guideline, 2024, doi 10.1177/10806032241227924 : whole-body cold-water immersion is reported as the preferred treatment. Fluid advice not retrieved.
- **Allergy**, ILCOR first aid 2025, https://www.ilcor.org/uploads/FA-2025-Supplementary-Table-S1.pdf : suggests a second auto-injector dose when the first does not relieve symptoms; weak recommendation, very low certainty. **The interval between doses is listed as an open question**, so "about 5 minutes" in card 5 is unsupported.
- **Fracture, sprain, scorpion:** nothing at guideline level.

**No signal: my draft was too confident**

- EENA (the European emergency number body), letter of 28 Nov 2025, https://eena.org/wp-content/uploads/2026/01/2025_11_28_Letter-to-Vice-President-Henna-Virkkunen-concerning-emergency-call-failures.pdf : after 2G and 3G shutdowns, some roaming phones can no longer reach emergency services even while connected.
- So "112 works on any network" is contested by the body that promotes 112. Card 1 must say "try", not "it works".
- Emergency SMS and calling without a SIM: not confirmed anywhere.

**Where the guidelines disagree**

- Limb height: WMS says heart level; Israel's Ministry of Health says below the heart.
- Splint: the US guidelines say rest and immobilise, without pressure. That sits with MDA, against the Ministry and the poison centre.
- Pressure bandage: recommended in Australia for its own snakes; advised against for vipers.
- Washing the bite: "don't wash" is Australian only.

### 5c. What is needed to finish the research

Do it on the PC, where the web is open. Open in this order:

1. The three Israeli snake pages in 5a, with their dates. This settles the splint question's exact wording.
2. `https://www.mdais.org/101` for bleeding, heat and allergy pages.
3. WHO South-East Asia snakebite guidelines 2016.
4. AHA / Red Cross 2024 first aid guidelines: snakebite, bleeding, heat stroke, anaphylaxis tables with their grades.
5. WMS heat illness 2024.
6. ILCOR 2025 and ERC 2025 first aid.

### 5d. How well each card is backed

| Card | Israeli official line | International | Verdict |
|---|---|---|---|
| 1. No signal | almost none | contested | weakest card; mostly "one line is mine" |
| 2. Snake bite | yes, three sources, in conflict on the splint | yes | writable once the pages are opened |
| 3. Bleeding | none found yet | yes | depends on finding MDA's page |
| 4. Heat stroke | yes, Ministry | yes | writable; watch the "no drink" line |
| 5. Allergy | yes, Ministry and MDA | yes, weak grade on the second dose | writable, minus the timing |

## 6. Notes for the build

- **Serials.** The PC is at D47 and S565. The off-grid topic would be D48 and its sources start at S566. Assign only on the PC, after the commit.
- **One writer.** The app is one file. Build the cards on the PC, not in a cloud session, while the PC holds app changes.
- **Review.** These cards carry more risk than any path so far. They should be first in line for the doctor or paramedic review, next to the `now` and `today` signs.
- **Log "one line is mine".** Any line without a source gets marked, as in the poison path.

---

## 7. New capsule: drugs and overdose (asked 17.11.2026)

Plan and first draft only. Nothing is in the app or the codex. Same marks as section 4: **[G]** = I remember it as standard guidance, unchecked; **[J]** = my judgment. The cloud session could not open any source, so there is not one verified line here.

### 7.1 Decisions to make before building

- **No "limits" as numbers.** You asked for limits. I recommend against any dose figure, and wrote none. Reasons: there is no safe amount to state for a street drug of unknown strength; tolerance differs between people and drops after a break; and a number in a health app reads as permission. This is the same rule the eating-disorders path took ("no numbers that can become a target"). What the capsule gives instead is 7.4: what makes a dose dangerous.
- **Wasteland rules do not apply.** An overdose at home or at a party has a phone. So the 11.11 rule holds: first-aid lines only as word-for-word Ministry of Health or MDA quotes. The lines in 7.5 are what to look for in those sources, not app text.
- **Two capsules (the owner's decision, 17.11.2026).** Capsule A is the overdose, an event in the row "משהו קרה?". Capsule B is getting off drugs, a long path through the system. Each links to the other: A's last step opens B, and B's signs point back to A.
- **Overlap with D47 "הרעלה".** D47 already covers medicines swallowed at home and the poison centre. The new capsule should link to it and not repeat it.
- **Overdose on purpose.** Some overdoses are suicide attempts. The capsule needs one calm line pointing to the mental-health path and ער״ן, written with the same care as D08. This line should go to the professional review first.
- **Fear of the police.** Families and friends delay calling 101 because they fear arrest. Whether MDA reports drug use to the police is the most useful single fact this capsule can hold. I do not know the answer. Find the official line or leave it out.

### 7.2 Capsule A, the overdose: proposed steps

| # | Step | Status |
|---|---|---|
| 1 | Call 101 now: the signs that mean "now" (7.3) | needs MDA / Ministry quote |
| 2 | Until the team arrives: what to do, what not to do (7.5) | needs MDA / Ministry quote |
| 3 | What to tell the team: what was taken, how much, when, with what. Keep the package or what is left | [G]; D47 has a matching "keep the package" step |
| 4 | The poison centre at Rambam, 04-7771900, 24 hours, open to the public | already sourced in the codex as S264 |
| 5 | In the ER, and what happens after | to research |
| 6 | The day after: opens capsule B | [J] |

### 7.3 Effects and overdose signs, by family

All **[G]**, from memory. No doses. Check each row against the Ministry of Health or a toxicology reference before use.

| Family | Examples | Usual effects | Signs of overdose |
|---|---|---|---|
| Opioids | heroin, fentanyl, oxycodone, morphine, methadone, tramadol | pain relief, calm, sleepiness, small pupils | cannot be woken, slow or stopped breathing, snoring or gurgling, blue lips |
| Sedatives | benzodiazepines (clonazepam, diazepam, alprazolam), sleeping pills | calm, sleepiness, loose muscles | deep sleep, slurred speech, slow breathing; much more dangerous with alcohol or opioids |
| Alcohol | | loss of inhibition, poor balance | cannot be woken, vomiting while not awake, slow breathing, cold skin |
| Stimulants | cocaine, amphetamines, methamphetamine, MDMA | energy, fast heart, little sleep or appetite | chest pain, very hot body, seizure, extreme agitation or paranoia |
| Cannabis | hashish, marijuana, edibles | relaxation, changed sense of time, hunger | panic, fast heart, vomiting; rarely life-threatening for an adult, more serious for a small child who ate it |
| Synthetic cannabinoids | sold as "נייס גאי" and similar | unpredictable | seizure, psychosis, collapse; far more dangerous than cannabis |
| Dissociatives | ketamine, nitrous oxide | detachment, numbness | not responding, vomiting while not awake, injury from falls |
| GHB / GBL | | euphoria, sleepiness | sudden deep unconsciousness, slow breathing; the gap between a dose and an overdose is small |
| Paracetamol | common painkillers and cold medicines | pain and fever relief | **few or no signs in the first day**, then liver failure. A person who took too much and feels fine still needs the ER |

### 7.4 What makes a dose dangerous (in place of limits)

All **[G]**.

- **Mixing.** Opioids, sedatives and alcohol each slow breathing; together far more.
- **A break.** After days or weeks without the drug (detox, prison, hospital), the old dose can kill.
- **Unknown content.** A street pill or powder may hold something stronger than what it was sold as.
- **Using alone.** Nobody is there to call.
- **A new source or a new route.**
- **Illness, old age, a child's small body.**

### 7.5 First aid to look for in MDA and Ministry sources

All **[G]**. Not app text until a word-for-word official quote is found.

- Call 101. Say what was taken if known.
- Not responding but breathing: on the side, in the recovery position. Stay and watch the breathing.
- Not breathing: resuscitation, as the 101 dispatcher instructs.
- Do not make the person vomit.
- Do not leave them to "sleep it off". No cold shower, no coffee.
- Stimulant overdose with a very hot body: cool the body.
- Seizure: clear the space around, put nothing in the mouth.
- Naloxone reverses an opioid overdose. **Whether the public can get it in Israel, and how, I do not know.** Research it.

### 7.6 Capsule B, getting off drugs: proposed steps

The step order is my proposal, **[J]**. It follows the shape of the existing long paths (first door, assessment, treatment, rights, family). Every fact inside a step is still to be researched; I wrote none from memory, because names, phone numbers and rights in this area change, and a wrong number here costs more than a missing one.

| # | Step | What to research |
|---|---|---|
| 1 | The first door: who to turn to | The family doctor, the fund, the Ministry of Health's addiction units, the welfare office. Which one opens the rest |
| 2 | Assessment: what kind of treatment fits | Who decides, how long it takes, what it costs |
| 3 | Detox | Wards and other public options, waiting times, whether a referral or Form 17 is needed |
| 4 | Substitution treatment | Methadone and buprenorphine: where, and how to get in |
| 5 | Long treatment and rehabilitation | Day centres, therapeutic communities, who pays |
| 6 | Under 18 | Where a parent starts, and what the child must agree to |
| 7 | Rights and money | Bituach Leumi, sick leave, confidentiality at work and in the army |
| 8 | The family | Help lines and support for relatives. ער״ן is 1201; every other number must be read off its official page |
| 9 | A relapse | What to do, and the link back to capsule A: after a break, the old dose can kill (7.4) |

- **Start the research at Kol Zchut**, on its addiction and "גמילה" pages, then the Ministry of Health and the Ministry of Welfare.
- **Signs for capsule B** are the slow ones (level `gp` or `week`): use that is growing, withdrawal, trouble at work or school. They need drafting and review like any other signs.
- **Area on the home screen:** most likely "מצב רוח, שינה ולחץ", and "ילדים" for step 6. Your call.

### 7.7 For the build

- **Serials:** assign on the PC after the commit. Three new topics need a D number after D47: the wasteland tips, capsule A and capsule B.
- **Signs:** the "cannot be woken" and "slow breathing" signs are level `now`. Check which already exist in `SIGNS` before adding.
- **Tone:** calm, no judgment of the person who used. The joke rule applies: none here.
- **Review:** this capsule and the wasteland tips go to the doctor or paramedic before any other content.
