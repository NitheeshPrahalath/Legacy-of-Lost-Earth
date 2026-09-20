# LEGACY OF THE LOST EARTH — Master Reference

> **Purpose:** A single-file handoff so a fresh session (any AI or the author) can continue writing the novel with full context and no re-discovery.
> **Updated through:** Chapter 23 (end). Story date: October 15, 2120, dawn.

---

## 1. HOW TO USE THIS FILE

1. Read this whole file once. It is the canonical summary of everything written so far.
2. For scene-level text, open the chapter `.md` files under `chapters/` (always trust the `.md`, not the `.docx` — canon edits land in `.md`).
3. For deep world lore scrolls, open the files listed in §2 (esp. the MasterLore extraction).
4. Follow the continuity rules in §9. Do NOT re-litigate resolved fixes. Do NOT touch known-ignored inconsistencies (§9.3).
5. To continue the story: start at §7 (Current Story State) and use §10 (Open Plot Threads) as the menu. Suggested Chapter 24 seeds are in §11.

---

## 2. REPO FILE MAP

### Chapters (canon story text, markdown)
| File | Content |
|---|---|
| `chapters/prelude.md` | The catastrophe prologue (2100–2120) |
| `chapters/chapter_1.md` … `chapter_21.md` | Chapters 1–21 |
| `chapters/Chapter_22.md` | Chapter 22 — NOTE the capital "C" in the filename |
| `chapters/chapter_18_5.md` | Chapter 18.5 — "World Data — IRIS Archive Playback" (SDD dossier) |
| `chapters/chapter_23.md` | Chapter 23 — Kyoto Shelter Complex & first big siege |
| `chapters/chapter_N.docx` | Word copies of each chapter (IMPORT/EXPORT duplicates; not canonical source) |

### World docs (lore / setting)
| File | Content |
|---|---|
| `LostEarth_MasterLore.docx` | THE full world bible (see extraction below for a readable version) |
| `/tmp/masterlore_readable.txt` | Text extraction of the MasterLore (102 lines, pre-wrapped) — best lore reading shortcut |
| `Continue prompt.md` | The author's 17-section Continuation Bible template/tasklist |
| `To-be-added-later` | 12-line list of promised plot details not yet written into chapters |
| `world_in_2120.md` | 2120 world-state notes |
| `Regions_and_Prefectures_of_Japan.svg` | Geography reference (Nara/Osaka/Kyoto/Hyōgo) |

### Per-topic lore files
| File | Content |
|---|---|
| `Military/Military.md`, `Military/description.md` | SDD structure, equipment, doctrine |
| `Military/Soverign Nations that survive.md` | Post-catastrophe nation tiers + survivor populations |
| `Military/Military_Bases.xls`, `Military/SDD_badge.txt` | Base registry, badge reference |
| `Vehicles/description.md` | Narrative look of all 17 vehicles (7 ground + 10 aero-cruisers) |
| `Vehicles/Aero-Cruisers.md`, `Vehicles/Aero-Strider.md` | Aero-cruiser specs / strider |
| `Weapons.txt`, `Medicals.txt` | Weapons & medical tech lists |
| `Schools and colleges.txt`, `Caste Hierachy.txt` | Pre-war education & caste system |
| `Mount Myoken.txt` | Mount Myōken setting notes |
| `123.png`, `Vehicles/*.png`, `Military/*.png` | Concept art |

---

## 3. STORY OVERVIEW

**Title:** Legacy of the Lost Earth
**Setting:** Earth, year 2120 — a devastated world one month past the "Beast" catastrophe.
**Genre:** Post-apocalyptic progression fantasy / sci-fi (Beast Energy power system).

In 2100 mankind achieved spatial travel. Twenty years later, humanity awakened vast, ancient creatures dwelling in the remaining wilderness of the planet. The creatures unleashed mutagenic energy, transforming animals into Beasts. Nuclear weapons proved useless. 27 Ancient Beasts (Beast 1–27) now claim dominion over enormous regions; the energy they emit is called **Beast Energy** (a.k.a. Viraya).

The protagonists are a small band of Japanese survivors fighting their way from Osaka toward regional safety, led in practice by **Kael Ardyn** — a 21-year-old who mysteriously survived mutation with his mind intact and gained superhuman growth. Kael carries **IRIS**, an AI companion wired into his body. A **Giant Tree** — apparently far more than a Beast — has taken an interest in Kael and feeds him its fruit, thrusting him into a purpose he does not yet understand.

**Arc context:** 
- Ch 1–8: Kael alone in Osaka (survival, IRIS, finding Cherry).
- Ch 8–15: Meeting the Nakamura group; Yodo River crossing; the cherries-crows incident; camp at the Abandoned Library.
- Ch 16–20: The Giant Tree (Library attack → wood chamber → fruit → transcendent vision), IRIS status report, and a month of training/travel toward Kyoto.
- Ch 21–23: Arrival at a base-town at the foot of Mount Myōken; the dome Shelter; the Four-Waves Siege; the Kyoto Black Citadel relief fleet arrives and tells Kael to stand down.

**Destination in view:** Kyoto Black Citadel (claimed ~98 km away as of Ch 18 coordinates / map reference).

---

## 4. WORLDBUILDING & SYSTEMS

### 4.1 The catastrophe
- 2100: birth of spatial travel. 2120: the Beast awakening — survivors call the event a disaster on the scale of the old world's extinction scenarios.
- Remaining habitable/savage land ≈ 20% of the Earth's surface; the ancient creatures rose from that wilderness.
- Early estimates: ~85% of humanity died immediately (≈8.9B of ~10.46B); global survivor population ≈1.57B (see `Soverign Nations that survive.md` for nation-by-nation breakdown; largest survivors: India 210M, China 170M; Japan, an A-tier nation, ≈16M).

### 4.2 Beast Energy / Viraya / Elarion (MasterLore)
- Beast Energy is the power source of the age; units of it are called **Viraya**. Human civilization runs on Elarion-tier conduits of it.
- ~4.4 trillion units existed pre-war; by 2120 only ~1.18 trillion remain (dwindling stockpile — a plot weight).
- Ancient Beasts: **Beast 1–27**. Each carries a ★ rating (power density); elites reach the 50–60★ range. Named examples:
  - **Beast15-ish / Infernal Phoenix** — Nachi Waterfall, Kii Peninsula. (Its territory & the ≥100 km² "destroyed" radius vs Ch 18's epicenter line is the knowingly-ignored inconsistency — §9.3.)
  - **Beast25 — Divine Pegasus** — the Alps region, 58★.
  - **Beast26 — Celestial Kraken** — ocean/coastal, 59.5★.
  - **Beast27 — Eclipsing Behemoth** — Antarctica, 60★ (currently the highest known).
- Beast grading: D → C → B → A → S tiers; common "C-tier remnant" energy sits on every street in the ruins.
- Awakening grades for humans: **White → (color ladder) → Rainbow**. Kael's growth implies an awakening underway.
- Weapons are graded **1–10** (heavier = higher tier); the group routinely uses grade-1 tools (spears, crossbows, air rifles).

### 4.3 The Sovereign Nations (food & control)
- Pre-war and post-war, power is consolidated in a federation of **Sovereign Nations**.
- **Food is the axis of control:** natural agriculture provably cannot feed the population; the Sovereigns centralized all food production & distribution.
  - Private farming prohibited; fruit trees removed from cities; livestock state-controlled; seeds, soil, crops regulated.
  - Generations have forgotten the taste of natural food ("food control = civilization control").
- A pre-war **caste hierarchy** existed (see `Caste Hierachy.txt`) and shapes the world order.

### 4.4 SDD — the military (from Ch 18.5 "IRIS Archive Playback")
- **SDD** = the planetary military/security force of the Sovereign Nations.
- **Five branches:**
  1. Territorial Pacification Vanguard (TPV) — frontline combat
  2. Hydro-Resource Armada — water/coastal
  3. Atmospheric Supremacy Command — air
  4. Orbital Strike & Logistics Division — space strike / supply
  5. Verdant Guard — wilderness/biome control
- **Officer ranks (ascending):** Sub-Prime → **Captain-Prime** → Major-Tactical → **Commander-Regent** → Colonel-Logis → (higher ranks exist, unrevealed).
  - Commander-Regent ≈ battalion-level command, earned not given.
- **Structure:** 47 Joint Bases consolidated into **8 Regional Commands**. Kyoto is the hub of its own Regional Command ("Kyoto Black Citadel").
- On-screen ranks: **Ariga** = Captain-Prime (shelter commander); the relief-force officer who calls him out is a **Sub-Prime**; **Aoi Tanaka** is a retired SDD officer who once ran an old family library; his son **Aoi Nakamura** currently serves as a **Commander-Regent** at **Izumo Coastal Base, shimane**. (Note: the original chapter 9 line reads "my son,Aoi Nakamura" — missing space, left untouched as per the author's revert.)

### 4.5 Vehicles (from `Vehicles/description.md`)
Visual hierarchy = social hierarchy in 2120 Earth.
- **Ground (Bikes/Cars):** V-TEK "Drifter" Mk.II (industrial worker's hover-bike), TORRENT-8 (heavy hauler), OMNOVA "Sylph" 900 (sleek corporate pod), AURELIA "Zenith" V-TOL (luxury), AEGIS "Interceptor" Mk-IV (law-enforcement), KESTREL-V APEX (military predator), VEKTOR "Screaming Mantis" RS-9 (exotic purple-lit racer).
- **Aero-Cruisers:** V-TEK "Hab-Crawler" (boxy micro-van), TORRENT "Nomad" (sporty cruiser), ATLAS "Behemoth" Cargo-Lifter, OMNI-TRANSIT "Leviathan" (public-transit cruiser — repurposed as war transports in Ch 23), OMNOVA "Regalia" (executive luxury, black + gold lines), AGRI-SEC "Ceres" (agricultural), AEGIS "Bastion" (police pursuit), VEKTOR "Wraith" GTR (illegal midnight-races look), AURELIA "Pantheon" (airborne palace), TPV "Juggernaut" Strike-Cruiser (armored assault fortress, twin-plasma cannons).
- Featured in Ch 23 siege relief: 20 Leviathans (boarding-action paint) + 5 Juggernauts.

### 4.6 Medical & weapons tech
- Medical: sterilization bay, **nanofiller**, **Regeneration Gel**, **Antiseptic Foam**, compact field medical kits (compress patch used on Kael's shoulder, Ch 12).
- Personal arms: wind-up crossbows, air rifles, **pulse guns** (Maya fires one at the tree branch, Ch 16).

---

## 5. TIMELINE

| Date (2120) | Event |
|---|---|
| 2100 | Birth of spatial travel |
| 2120 (pre-Sept) | Beast awakening; mutations; nukes fail; 27 Ancient Beasts claim regions; ~85% die |
| ~Aug (≈Sept 9 − 37 days) | **Kael awakes post-mutation** with mind intact (Time Post-Awakening anchor) |
| Sept 9 | Ch 1 (Osaka ruins, crimson sky); Ch 2 (17:30 — mutated dog, 90 cm at shoulder); Ch 3 (food hunt, meat-edibility debate) |
| Sept 10 04:00 | Ch 4 — Kadoma, Osaka; journey from Nara Prefecture to Osaka had taken ~a month |
| Sept 10 | Ch 5 (Cherry found under collapsed building); Ch 6 (IRIS: satellites, sterilization bay) |
| Sept 11 06:00 | Ch 7 — Cherry grows 2→4 month size overnight; Kael healing faster from residual energy |
| Sept 11 09:30 | Ch 8 — Automated Retail Store; Hirota Ren + Nakamura's group |
| Sept 11 | Ch 9 (introductions — Tanaka, Nakamura father/son); Ch 10 (roasted raccoon feast, seven leaf-plates) |
| Sept 11 13:00 | Ch 11 — Yodo River Bridge approach; two 1.2–1.3 m mutated red foxes |
| Sept 11 14:30 | Ch 12 — Yodo crossing; Kael shoulder wound (3 cm lacerations); Tanaka gravely injured, carried |
| Sept 11 (dusk→night) | Ch 13 (Kael rescues Emily on the cables; the crows "Seven… eight"); Ch 14 (Cherry kills the crows, three clean slashes each) |
| Sept 11 22:00 | Ch 15 — Abandoned Library; group regards Cherry as a friendly mutant |
| Sept 15 08:20 | Ch 16 — Library attacked by a colossal branch; Emily seized; Cherry's claws fail; Maya pulse-gun |
| Sept 15 09:00 | Ch 17 — underground wood chamber; fruit scent stirs parents' memories; the tree speaks ("Eat the fruit. Completely. Even the core."); IRIS vows to stay with Kael |
| Sept 15 | Ch 18 — "Wake up" vision: celestial body, colossal tree at world's core, ancient soil/forests/streams; ~98 km to Kyoto Black Citadel |
| Sept 15 10:30 | Ch 19 — IRIS status report (stats, 37 days post-awakening) |
| Sept 15 – Oct 15 | Ch 20 — montage of travel/training; IRIS's lecture on food centralization |
| Oct 15 12:30 | Ch 21 — foothills of Mount Myōken; town ~4 km away on horizon; abandoned hover-bike etc. |
| Oct 15 14:30 | Ch 22 — base town; mutated crow/insect activity concentrates; massive circular **dome shelter**; 15 SDD soldiers in heavy combat suits holding a half-closed, malfunctioning entrance |
| Oct 15 15:40 | Ch 23 — inside the Kyoto Shelter Complex; the Four-Waves Siege; dawn relief fleet from the Black Citadel |

---

## 6. CHAPTER-BY-CHAPTER SUMMARY

- **Prelude:** 2100 spatial travel; 2120 humans wake ancient creatures in the last 20% of land; mutations spread; nuclear weapons fail; 27 Ancient Creatures; mankind names the energy **Beast Energy**.
- **Ch 1** — Osaka, Sept 9. Crimson skies, ruined city, derailed Margil trains piled with dead. Kael (21), one month into the collapse, hunts and survives with IRIS.
- **Ch 2** — 17:30. A mutated dog stands 90 cm at the shoulder. IRIS analyzes it; they reposition rather than fight a losing battle.
- **Ch 3** — No food found. Kael asks the moral/medical question: is mutated meat edible? IRIS is hesitant.
- **Ch 4** — Kadoma, Osaka, 04:00. Researching mutated meat; backstory: Kael walked from Nara Prefecture over ~a month.
- **Ch 5** — A small white-brown cat (initially judged unmutated) is found trapped beneath broken buildings. Cherry joins Kael.
- **Ch 6** — IRIS explains its reach: satellite signals dead, but it can still read parts of the world; Kael's base tech (sterilization bay, nanofiller, Regeneration Gel, Antiseptic Foam).
- **Ch 7** — Overnight Cherry jumps from 2-month to 4-month kitten size. Kael's wounds close faster; his strength climbs from the residual energy of the mutated dog.
- **Ch 8** — Automated Retail Store, 09:30. **Hirota Ren**: father died shielding him & his mother; his mother pushed him away to force his escape. Kael meets **Aoi Nakamura**'s survivor group.
- **Ch 9** — Introduction scene. **Aoi Tanaka** introduces himself (retired SDD, "old family library"); Tanaka presents the group captain as "my son, **Aoi Nakamura**." Kael's speech: he can show strength, but the choice to stay or go is theirs. Discussion of the Kyoto Black Citadel.
- **Ch 10** — Roasted raccoon meat; dinner is served on **seven leaf-plates** (Cherry first, Tanaka first among humans). Group bonds.
- **Ch 11** — Yodo River Bridge approach, 13:00. Two mutated red foxes (~1.2–1.3 m at the shoulder) drink from the river. Bridge corpse-littered.
- **Ch 12** — Yodo River Bridge, 14:30. The crossing is violent; Kael takes 3 cm lacerations to the left shoulder. **Nakamura cradles Tanaka** — his father — pale and blood at the mouth. Maya treats Kael with a compact medical kit (compress patch).
- **Ch 13** — Emily is saved by Kael while both are on the cables; the crows come — a chaotic count ("Seven… eight of them").
- **Ch 14** — Cherry shreds the crows; her paws are red; each corpse bears **three clean slashes**.
- **Ch 15** — Abandoned Library, 22:00. The group debates Cherry: a **friendly mutant**; could the SDD tame such creatures? Kael stands his ground.
- **Ch 16** — Abandoned Library, Sept 15 08:20. A **gigantic tree branch** smashes through the windows and coils around Emily. Cherry attacks: claws **clang** — no scratch. Maya opens fire with a pulse gun.
- **Ch 17** — Underground wood chamber, 09:00. The scent of fruit unlocks Kael's buried memories of his parents. The **Giant Tree speaks** (a third voice beyond Kael and IRIS): it brought Kael here for a purpose. Command: **"Eat the fruit. Completely. Even the core."** IRIS declares she will stay beside Kael no matter what.
- **Ch 18** — "Wake up." Kael enters a vision of deep space: a celestial body with a **colossal tree at the world's core**, ancient soil, forests, running streams. He wakes changed. Map reference: **98 km to the Kyoto Black Citadel**.
- **Ch 18.5** — "World Data — IRIS Archive Playback": the SDD dossier (five branches, rank ladder, 47 bases → 8 Regional Commands). Pure exposition chapter.
- **Ch 19** — Mount Myōken, Hyōgo, 10:30. IRIS status report (see §8 character entry — stats ~3× baseline).
- **Ch 20** — Sept 15 – Oct 15 montage. IRIS narrates history: agriculture failed; Sovereign Nations centralized food; private farming illegal; fruit trees removed; livestock state-owned; regulation of crops; **generations of forgetting**. (Month of training/travel toward Kyoto inside the time skip.)
- **Ch 21** — Foothills of Mount Myōken, Oct 15 12:30. A town appears ~4 km off through the haze; an elevated roadway, an abandoned hover-bike and other debris mark the edge of civilization.
- **Ch 22** — Base town at the mountain's foot (header names it "Mountain Foothills, Kyoto"). The party follows **concentrated mutant-animal activity** to a **massive circular dome shelter** with a partially collapsed, malfunctioning entrance. **15 SDD soldiers in heavy combat suits** hold a defensive ring around it.
- **Ch 23** — **Kyoto Shelter Complex, 15:40.** (Full reading → §7.) Kael & Cherry are admitted with Ariga leading; 14 soldiers hold the entrance. Three 52-meter floors: (1) hundreds of packed, dying civilians (mutation illness — air/water borne, not Beasts), (2) exhausted survivors, empty nutrient pods, a dead man in the aisle, (3) sealed SDD deck — dead biometric lock, corrupted breakers, one dying comms line. IRIS proposes **spoofing a shelter status report to Kyoto** on her own connection, in the shelter's identity, using the shelter's encryption keys — she needs Kael's explicit approval ("This is not an authorized use of my systems"). Kael says *"Do it."* The transmission leaves. At dusk the animals hit: 4 waves in 7 hours (crows by the hundred, then boars & dogs; a midnight third wave; a pre-dawn fourth with a **blade-antlered mutated sika deer** that nearly breaks the line — Kael takes a rake across the shoulder, kills it with an under-the-chin spear thrust). At dawn: **20 repurposed Omni-Transit "Leviathan" cruisers + 5 TPV "Juggernaut" Strike-Cruisers** land — a relief force from the Kyoto Black Citadel (94 combat troops + 40 SDD general personnel). A Sub-Prime addresses **"Captain-Prime Ariga"**: *"Kyoto received your shelter's status report."* Ariga and Kael exchange a knowing silence — nobody acknowledges the transmission was never a shelter report. Civilians to be evacuated to the Citadel; shelter to be recommissioned. To Kael: **"Stand down, civilian. Your work here is done."**

---

## 7. CURRENT STORY STATE (END OF CH 23)

- **Place:** the clearing outside the Kyoto Shelter Complex, base town at Mount Myōken's foot, just before dawn, October 15/16 2120.
- **Immediate scene:** the battle is over. A relief fleet (5 Juggernauts + 20 Leviathans) from the **Kyoto Black Citadel** is disembarking: medics, supply crates, and nearly a hundred soldiers in exoskeleton combat suits. A Sub-Prime is directing the operation. Civilians (~3,000 surviving shelter inhabitants) are being evacuated to the Citadel.
- **Kael's state:** minor fresh wound (antler rake to the shoulder), exhausted after fighting without rotating off (re-shafted his spear twice, arms raw); Cherry blood-matted but alive.
- **IRIS:** just executed an **unauthorized transmission** — a forged shelter status report in Kyoto's channel, built from the shelter's captured encryption keys, sent over her own connection. Only Kael (and by implication Ariga's guess) knows. This is a live liability.
- **The party:** Ariga & the 14 SDD other ranks, the survivor group (Tanaka's son Nakamura, Maya, Emily, Hirota Ren, others), ~3,000 civilians, and the relief force. Tanaka's condition (gravely wounded at the Yodo, Ch 12) is unresolved on-page.
- **Open question on the page:** Kael has been ordered to stand down. What happens to him, his group, and his unacknowledged secret under the eyes of a regional military power?

---

## 8. CHARACTER BIBLE

**Kael Ardyn** — protagonist, male, **21**. Deep inside the ruins of Osaka at the open of Ch 1; walked from Nara over ~a month before that. Survived mutation with his consciousness intact; grows by consuming Beast energy. **Ch 19 IRIS report:** Time Post-Awakening 37 days; Strength 8.54 (baseline 2.78), Speed 8.04 (2.48), Life Force 8.93 (2.97), Stamina 8.92 (2.96), Constitution 7.32 (2.42), Reaction 0.20 s (0.22 s) — roughly triple across the board. Cracks stone with "barely a fraction" of his strength. Fights with a spear. Youthful pride + growing responsibility; mourns nothing on camera but carries buried memories of his parents (stirred by the tree's fruit). Canon school per story text: **Osaka Metaverse College** (MasterLore says Tokyo — see §9.3).

**IRIS** — AI companion implanted within Kael's body; speaks directly in his mind ("Her voice"). Functions: analytics, satellite/comms interception, status reports, mapping, and network infiltration (she spoofed the shelter's radio identity). Ethics guardrails: she asks Kael's explicit permission for **unauthorized** system use. Character: quiet, precise, fiercely loyal ("I will stay by your side"). Unresolved core mystery: she is **not a normal device** — the lore says she needs **Viraya added to her main unit** to gain true sentiment; her true origin/purpose is a major thread.

**Cherry** — small **white-brown cat** found trapped beneath a collapsed building (Ch 5), initially judged unmutated. Overnight grew from a ~2-month to ~4-month kit size (Ch 7) and is far stronger/faster than any cat: in the Ch 23 siege she fought as "a white storm at the flank," blood matting her coat. Claws leave **three clean slashes**; they failed utterly against the Giant Tree's branch (clang). Eats first at every meal; treated by the group as a **friendly mutant** companion. Kael's first and closest friend.

**Aoi Tanaka** — elderly, **retired SDD officer**, father of the group captain; the "old family library" holder (a knowledge asset against the world's mass forgetting). First human to eat at the feast. **Gravely wounded** at the Yodo crossing (Ch 12) and carried by his son — long-term survival unconfirmed on-page. 18.5 associates the Commander-Regent rank with his generation of SDD command.

**Aoi Nakamura** — captain of the survivor group, former SDD (like his father); Tanaka's son. Pragmatic leader; holds/carries his father; wary but accepts Kael's strength and Cherry.

**Maya** — the party's medic; treats Kael's shoulder with a compact kit (compress patch, Ch 12); fights with a **pulse gun** (fired at the tree branch, Ch 16).

**Emily** — young survivor of the group; rescued mid-cable by Kael from the crows (Ch 13); seized/coiled by the Giant Tree's branch at the Library (Ch 16) — trauma unresolved on-page.

**Hirota Ren** — reunited at the Automated Retail Store (Ch 8). Father died shielding him and his mother; mother pushed him away to force his escape. Joined the group; bears quiet survivor guilt.

**Ariga** — SDD **Captain-Prime**, commanding the 15-man detail at the shelter. Pliable enough to let Kael & Cherry inside; knows something is off about the "received" status report. His silence with Kael at the fleet's arrival is a bond and a warning.

**The Giant Tree** — a colossal, sentient tree entity; speaks with a voice beyond Kael's and IRIS's (the "third voice"). Stated it brought Kael for a **purpose**; fed him its fruit (**"Eat the fruit. Completely. Even the core."**); showed him the vision of the world-tree at the core of the cosmos. Physically overwhelming (Cherry's claws cannot scratch it; branches reach through walls). Relationship to the 27 Ancient Beasts **unknown** — possibly greater. Its earlier failed promise to save Kael on schedule is flagged in `To-be-added-later` to be explained when Kael meets *her* in true form.

**Recurring institutions:** the **Sovereign Nations** (global federation), the **SDD** (military), the **Kyoto Black Citadel** (Regional Command stronghold / destination), the **27 Ancient Beasts** (world-scale antagonists).

---

## 9. CONTINUITY RULES, RESOLVED FIXES, AND KNOWN EXCEPTIONS

### 9.1 Resolved fixes (already applied to the `.md` files — DO NOT re-edit)
1. **Crow count = 8.** Ch 14 "all eight" is canonical. Ch 15 "seven" → "eight". Ch 13's "Seven… eight of them" is deliberately kept as in-scene chaotic counting.
2. **Distance to Kyoto Black Citadel = 98 km.** Ch 18 canonical; Ch 20 "ninety-seven" → "ninety-eight".
3. **Kael is 21.** Ch 1 "Twenty years old" → "Twenty-one years old".
4. **Ch 2 header 15 → 17:30.**
5. **Ch 20 header** now reads "September 15 – October 15, 2120" (month-long montage).
6. ~~Father/son naming fix~~ — **REVERTED on request**: the Ch 9 line intentionally stays as "my son,Aoi Nakamura" (missing space kept). Nakamura is the son and a Commander-Regent at Izumo Coastal Base, shimane; Tanaka is the retired father.
7. **Ch 15 status block** "1.9s" → "1.9"; stray "s" removed.

### 9.2 Working rules for new chapters
- Single-occurrence numbers/names are canon by default. On conflict between a lore doc and chapter text, **chapter text wins**.
- `.md` chapter files are the canonical drafts; keep `.docx` exports in sync when time permits.
- New hard numbers (distances, stats, counts, dates) — keep a mental ledger; a fresh session must not contradict Ch 19's stat report or the Ch 23 fleet numbers (5 Juggernauts / 20 Leviathans / 94+40 troops / ~3,000 civilians).

### 9.3 Known intentionally-ignored inconsistencies (DO NOT "fix")
1. **Infernal Phoenix (Nachi Waterfall) territory / the ≥100 km² destroyed area vs Ch 18's epicenter line** — the author chose to leave this unreconciled. Note only, never edit.
2. **MasterLore "Tokyo Metaverse College" vs Ch 1 "Osaka Metaverse College"** — Osaka (story text) is canon. Note only, never edit.

---

## 10. OPEN PLOT THREADS (pending payoff)

1. **The Giant Tree's purpose & the promise.** `To-be-added-later`: the Giant Tree failed to save Kael on the promised schedule — to be explained in a later chapter when Kael meets her **in true form**. "Eat the fruit. Completely. Even the core." — what did that fully awaken?
2. **IRIS's true nature.** Not a normal device; needs **Viraya added to her main unit** for true sentiment. Origin, builders, and agenda unknown (and the Ch 23 spoof proves she can operate well beyond spec).
3. **The spoofed transmission.** Kyoto believes the shelter report was legit. Discovery = institutional conflict; Ariga's quiet complicity is a lever.
4. **Kael vs the Citadel.** Ordered to "stand down" — but Kael's path points *into* the power structure (Beast Energy, awakening, the tree, Tanaka's library knowledge about the old world).
5. **Tanaka's family library / the forgetting.** An asset against the Sovereign Nations' food-and-history control.
6. **Kael's parents.** Buried memories surfaced by the fruit; who were they, what happened?
7. **The 27 Ancient Beasts & dwindling Viraya.** 4.4T → 1.18T units; someone must act before power runs out. Beast 27 (Eclipsing Behemoth, 60★) looms as a world-end.
8. **Destroyed SDD bases** (`To-be-added-later`): JB-25 Osaka (Sakai Logistics Fortress), JB-28 Nara (Tenri Security Base), JB-29 Wakayama (Gobo Coastal Base), JB-30 Mie (Matsusaka Naval Base) — the trail of destruction adjacent to Kael's route.
9. **Emily's aftermath** of the Library seizure; **Tanaka's survival** post-Yodo.
10. **Kael's awakening grade** climbing toward the Rainbow tier — what does the apex cost?

---

## 11. SUGGESTED NEXT CHAPTER

**Chapter 24 seeds (choose one or weave):**
- The exodus: ~3,000 civilians + the party under SDD escort to the **Kyoto Black Citadel**; first real look at a Regional Command hub and post-war society (caste + food-control visible on the ground).
- The Sub-Prime tries to separate Kael from his group / confiscate Cherry (a "specimen"?) — pushing the party toward choice.
- The spoof's consequences: IRIS quietly notes traffic starting to move toward the shelter's identity; a quiet question from Ariga.
- Cut to the mountain: the Giant Tree stirring again, watching Kael enter the Citadel.

Keep the structural habits from the existing chapters (see §12).

---

## 12. WRITING CONVENTIONS (as observed)

- **Format:** Markdown chapter files `chapters/chapter_N.md`; chapter headers state **location + date + time** (e.g., "Kyoto Shelter Complex, Mountain Foothills — October 15, 2120 — 15:40"); scene breaks use `---`.
- **Style:** third-person limited, past tense, cinematic short prose; dialogue on its own line with minimal tags; IRIS speaks in italics-free plain text in Kael's mind; sensory emphasis (smells, sky color, sound).
- **Systemic beats:** IRIS **status reports** are printed as fixed-field blocks (NIGHTLY/status blocks with Name / Age / Time Post-Awakening / Location / Date / raw stat table). New power gains should read as numbers plus visceral description.
- **Pacing:** chapters are short (often 1,000–2,000 words); a chapter usually advances exactly one scene or one reveal; only 18.5 is pure exposition and it is labeled "World Data."
- **World-check:** new tech must come from §4 (or be introduced with an SDD/Sovereign rationale); new named characters should join the §8 roster.