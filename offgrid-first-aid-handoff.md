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
- **The tips below are from my knowledge of the guidelines.** The cloud could not open the guideline texts. Check each tip against the reading list in 5c when you build. Where a tip is shaky, it says so.
- The app text is Hebrew. These are the English working lines; write the Hebrew at build time, short and plain.

## 4. The wasteland tips

The frame for all five: **you are alone, far from a road, and the phone is dead or has no signal.**

### 4.1 Snake bite

1. **Step back from the snake and sit for a minute.** Panic and running do more harm than that minute costs.
2. **Take off rings, watch and anything tight on that limb now.** Swelling comes fast.
3. **Note the time of the bite.** Doctors will ask.
4. **Leave the bite alone.** No cutting, no sucking, no tourniquet, no ice. None of them help, and several cause damage.
5. **Then walk out.** Nothing in the field treats venom. Only antivenom does, and it is in a hospital. If no one knows where you are, waiting is the worse bet.
6. **Walk smart, not fast.** Steady pace, the shortest way to a road or people, rests in shade, small sips of water. Bitten on the hand: keep the arm still against the body.
7. **Stay findable.** Keep to the marked trail and head toward where people pass.

- **The one judgment call:** if someone knows your route and return hour, staying put near the trail can beat walking on a bitten leg.
- **Pain:** paracetamol only. Not aspirin, not ibuprofen: they raise the bleeding risk. (From memory of the WHO guideline; check.)
- **Good to know:** Israel has no rattlesnakes. The dangerous ones are vipers: the tzefa, and the saw-scaled viper in the desert. Snakes do not chase. Most bites happen when a hand or foot goes where the eyes did not.
- **Shaky:** splint or not. The sources split (section 5a). "Keep it still" is the part they all agree on, so that is the tip.

### 4.2 Heavy bleeding

1. **Press hard, straight on the wound,** with any cloth and your full weight. Do not lift to look.
2. **Blood comes through:** add cloth on top and keep pressing.
3. **Free your hands:** tie a cloth strip tightly over the wad, so the pressure stays while you move.
4. **Arm or leg, and it still pours:** tourniquet. A wide strip of cloth, above the wound, not on a joint. Twist it with a stick until the bleeding stops. Note the time. Do not loosen it.
5. **Something stuck in the wound:** leave it in. Press around it.
6. **Then get out,** the same way as 4.1: steady, shortest way, findable.

- **Before the trip:** a real tourniquet and a pressure bandage weigh nothing. An improvised one works much worse.
- **Shaky:** nothing. This is the best-supported card of the five.

### 4.3 Heat

Heat is the bigger killer of hikers than any snake. Alone, the rule is: **act at the first signs, because later you will not be able to think.**

- **First signs:** headache, dizziness, nausea, cramps, unusual tiredness.

1. **Stop walking. Now, not at the next ridge.**
2. **Shade.** Any: a rock, a wadi wall, a shirt stretched over a bush.
3. **Wet your clothes and head** with some of the water, and fan yourself. Evaporation is what cools.
4. **Drink in small sips.** Add salt or a salty snack if you have one.
5. **Stay until the sun is low.** Walk out in the evening or at dawn, not at noon.

- **With a partner who is confused, stumbling or passes out:** that is heat stroke. Cool first, move second. Strip extra clothes, pour water over the whole body and fan hard. If there is a pool or stream, put the body in with the head out. No drink to someone who is not fully awake. No fever pills: they do nothing here.
- **Before the trip:** about one litre of water per person per hour of walking, start early, and turn back when half the water is gone.
- **Shaky:** the Ministry of Health says no drink at all in heat stroke. The tip above gives drink only to a person who is fully awake.

### 4.4 Severe allergic reaction

- **Signs, minutes after a sting or food:** hard to breathe, throat or face swelling, rash all over, faintness.

1. **Adrenaline injector into the outer thigh, at once.** Through trousers is fine. Do not wait to see if it gets worse.
2. **Lie down with legs raised.** If breathing is hard, sit up instead. Do not stand up fast and do not walk yet.
3. **Not better after several minutes:** use the second injector if you have one.
4. **Bee sting:** scrape the stinger off quickly with a nail or card.
5. **No injector:** lie down, legs up, take an antihistamine if you carry one, and stay still until it eases. A pill is not a replacement, only all there is.
6. **When it has passed, get out anyway.** The reaction can come back hours later.

- **Before the trip:** a known allergy means two injectors, in date, in the bag's top pocket.
- **Shaky:** the exact wait before the second injector. The 2025 international review leaves the interval open.

### 4.5 Dead phone, no signal: being found

Before the trip, which is where this card does its real work:

1. **Tell one person the route and the return hour.** This is the single most valuable line in this file. It turns "nobody knows" into "someone will send help tonight".
2. **Download the map.** Carry a power bank and a whistle.
3. **Leave the phone on low power, and off in long stretches with no signal.** Searching for a network drains it.

In the field:

1. **No bars:** try 112 anyway, then try again from higher, open ground. It may connect through another network. It may also not. Do not burn the battery on it.
2. **A text needs less signal than a call.** Write where you are and what happened, send it to the person who knows your route, and let the phone keep trying.
3. **Stay on the marked trail.** Searchers follow trails first.
4. **Signal in threes:** three whistle blasts, three flashes, three shouts. A bright cloth in the open by day.
5. **Night:** stop. Do not walk cliffs or wadis in the dark. Cold, not thirst, is the night's problem: wind shelter and every layer on.
6. **Injured and cannot walk:** make yourself visible from above and from the trail, and save water.

- **Shaky:** almost everything about 112. No official Israeli page says what works without your carrier or without a SIM, and the European emergency-number body reports failures. So the tip is "try", never "it works".

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
