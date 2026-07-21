# Week 36 Final — Quiz Specification (Bank-Draw Logic + Counts)

**Biology 1 (Florida 2000310) · Semester 2 Final · Modules 1–10 cumulative (full year)**
**Format: 70 multiple-choice (EOC-format) + 3 CER short-response · EOC-aligned**

This file specifies **how the final is assembled from the existing full-year reading-quiz bank** — it is not itself a set of new questions. Build the exam in Canvas as a native Quiz. Do **not** generate Canvas XML. Every MC item already exists, vetted and answer-keyed, in the 34 weekly `reading-quiz.md` files; the final *draws* from them. The 3 CER items are teacher-scored short responses, specified in full at the end.

The final follows the same method as the Week-15 Midterm, extended to the whole year: a stratified draw from the accumulated bank, weighted by module size, balanced against the EOC domain weights, with high-value misconception anchors guaranteed a seat.

---

## 1. The full-year bank it draws from

Every reading-quiz item was written to stand alone as a reusable bank item and to be EOC-format, so any of them can appear on the final unmodified (CLAUDE.md hard rule). The full-year bank is the union of all Module 1–10 weekly quizzes:

| Module | Title | Weeks | Items/wk | Module pool | Source files |
|---|---|---|---|---|---|
| 1 | Nature of Science | 1–2 | 8 | **16** | `module-01-nature-of-science/week-0{1,2}/reading-quiz.md` |
| 2 | Chemistry of Life | 3–4 | 8 | **16** | `module-02-chemistry-of-life/week-0{3,4}/reading-quiz.md` |
| 3 | Cell Structure, Function & Transport | 5–7 | 9 | **27** | `module-03-cell-structure-function-transport/week-0{5,6,7}/reading-quiz.md` |
| 4 | Cell Energy | 8–10 | 9 | **27** | `module-04-cell-energy/week-{08,09,10}/reading-quiz.md` |
| 5 | DNA, Cell Division & Genetics | 11–14 | 10 | **40** | `module-05-dna-cell-division-genetics/week-{11,12,13,14}/reading-quiz.md` |
| 6 | Evolution and Natural Selection | 16–18 | 9 | **27** | `module-06-evolution-and-natural-selection/week-{16,17,18}/reading-quiz.md` |
| 7 | Classification and Diversity of Life | 19–22 | 10 | **40** | `module-07-classification-and-diversity-of-life/week-{19,20,21,22}/reading-quiz.md` |
| 8 | Plant Biology | 23–25 | 9 | **27** | `module-08-plant-biology/week-{23,24,25}/reading-quiz.md` |
| 9 | Human Body Systems | 26–29 | 10 | **40** | `module-09-human-body-systems/week-{26,27,28,29}/reading-quiz.md` |
| 10 | Ecology and Environmental Science | 30–35 | 9 | **54** | `module-10-ecology-and-environmental-science/week-{30,31,32,33,34,35}/reading-quiz.md` |
| | | **34 wk** | | **314 total** | |

The final pulls **70** of these 314 for the MC section.

---

## 2. MC draw — counts by module (proportional to module size, balanced to EOC domain weights)

70 MC allocated across all ten modules per `plan.md` §7. The split is size-proportional and then nudged to match the EOC domain weights (Molecular/Cellular 35–40%, Classification/Evolution 20–25%, Ecosystems/Ecology 20–25%, Human Anatomy/Physiology 15–20%).

| Module | Weeks | **MC drawn** | EOC domain |
|---|---|---|---|
| 1 — Nature of Science | 2 | **3** | Nature of Science (woven through all) |
| 2 — Chemistry of Life | 2 | **5** | Molecular/Cellular |
| 3 — Cell Structure & Transport | 3 | **6** | Molecular/Cellular |
| 4 — Cell Energy | 3 | **6** | Molecular/Cellular |
| 5 — DNA, Division & Genetics | 4 | **8** | Molecular/Cellular |
| 6 — Evolution | 3 | **8** | Classification/Evolution |
| 7 — Classification & Diversity | 4 | **7** | Classification/Evolution |
| 8 — Plant Biology | 3 | **5** | Organismal (plants) |
| 9 — Human Body Systems | 4 | **10** | Human Anatomy/Physiology |
| 10 — Ecology | 6 | **12** | Ecosystems/Ecology |
| **Total** | **34** | **70** | — |

**Resulting domain shares:** Molecular/Cellular (M2–M5) = 25/70 ≈ **36%** · Classification/Evolution (M6–M7) = 15/70 ≈ **21%** · Ecology (M10) = 12/70 ≈ **17%** · Human Anatomy (M9) = 10/70 ≈ **14%** · plants (M8) ≈ 7% and Nature of Science (M1) ≈ 4% make up the balance (NOS is also woven through every domain item). These match the `plan.md` §7 targets and sit inside the EOC bands, with molecular/cellular carrying the largest share as the EOC does.

> **Optional rebalance (per `plan.md` §7 open decision):** to push ecology toward the top of its EOC band (~20%), move 2 items from M9→M10 (M9: 8, M10: 14). Keep the total at 70. The build below uses the size-proportional split; apply the rebalance only if instructed.

### 2a. Sub-allocation by week (keeps coverage even within a module)

Draw each module's allotment spread across its weeks so no single week dominates:

| Module | Per-week draw | Sums to |
|---|---|---|
| 1 | Wk 1: 2 · Wk 2: 1 | 3 |
| 2 | Wk 3: 3 · Wk 4: 2 | 5 |
| 3 | Wk 5: 2 · Wk 6: 2 · Wk 7: 2 | 6 |
| 4 | Wk 8: 2 · Wk 9: 2 · Wk 10: 2 | 6 |
| 5 | Wk 11: 2 · Wk 12: 2 · Wk 13: 2 · Wk 14: 2 | 8 |
| 6 | Wk 16: 3 · Wk 17: 3 · Wk 18: 2 | 8 |
| 7 | Wk 19: 2 · Wk 20: 2 · Wk 21: 2 · Wk 22: 1 | 7 |
| 8 | Wk 23: 2 · Wk 24: 2 · Wk 25: 1 | 5 |
| 9 | Wk 26: 2 · Wk 27: 3 · Wk 28: 3 · Wk 29: 2 | 10 |
| 10 | Wk 30: 2 · Wk 31: 2 · Wk 32: 2 · Wk 33: 2 · Wk 34: 2 · Wk 35: 2 | 12 |

---

## 3. Required-coverage rule (the draw is *stratified*, not blind-random)

The per-week counts above set the quotas. Within each week, selection is random **except** that the following high-value, EOC-targeted **misconception anchors must be guaranteed a seat** (each is a documented misconception from `eoc_review.md`). Fill the remaining seats randomly from that week's pool. This ensures the exam tests the misconceptions the course was built to correct, not an accidental easy subset.

**Must-include anchors (one item each, drawn from the named module):**

- **M1** — theory vs. law (a theory is *not* "a guess that grew up"); identifying the controlled variable / control group in a described experiment.
- **M2** — water's specific heat / hydrogen bonding explains cohesion, ice, solvent behavior; a protein's *function follows its folded shape* (denaturation).
- **M3** — osmosis is the movement of *water* (direction by solute concentration); RBC in hypo-/hyper-/isotonic solution; active transport requires energy (Na⁺/K⁺ pump).
- **M4** — photosynthesis and respiration are *not* simple reverses; the Calvin cycle does not require *direct* light; O₂ is the *final electron acceptor*; energy flows, matter cycles.
- **M5** — transcription vs. translation (where each occurs); meiosis produces genetically unique cells; "dominant" ≠ "more common"; a single base substitution → amino-acid change → protein → phenotype (sickle cell).
- **M6** — *fitness* means reproductive success, not "strongest"; natural selection acts on *existing* variation (it does not create traits on demand); acquired traits are not inherited; antibiotic resistance as evolution in real time.
- **M7** — the three domains rest on *molecular* data, not body shape; a cladogram groups by *shared derived characters*; classification reflects evolutionary history (common descent).
- **M8** — water rises in xylem by *cohesion-tension* driven by transpiration (not "pumped up" by the roots); stomata/guard cells control water loss; plants sense and respond (tropisms) without nerves.
- **M9** — homeostasis works by *negative* feedback; the neuron uses the Na⁺/K⁺ pump (callback to M3); a vaccine does not cause the disease; antibody specificity is a shape→function case.
- **M10** — energy *flows* (one way) while matter *cycles*; the 10% rule limits trophic levels; carbon links photosynthesis/respiration to the atmosphere; evidence for anthropogenic climate change comes from *independent* lines.

> If a future re-build adds more items to a week's pool, keep the per-week quotas in §2a and re-run the stratified draw; the anchors above stay mandatory. Because the final is cumulative, an item already used on the Week-15 Midterm **may** reappear here (the midterm and final are separate administrations); if you prefer no overlap, exclude the 50 midterm items from the M1–M5 sub-pools before drawing.

---

## 4. Assembly rules (Canvas)

1. **No duplication within the exam.** Each of the 70 MC is a distinct bank item; none repeats within the final.
2. **Preserve the vetted item verbatim.** Use each item's stem, four options, flagged correct answer, and (optionally) its explanation as Canvas answer feedback. Distractors are already misconception-based — do not edit.
3. **Shuffle.** Shuffle question order and answer-option order at delivery (Canvas Quiz settings). Because every item stands alone, shuffling is safe.
4. **One point per MC** = 70 points for the MC section.
5. **Group by Canvas Question Banks.** Recommended: maintain ten Canvas Question Banks (one per module) populated from the weekly `reading-quiz.md` items, then use a Quiz with ten question groups set to pull the §2 counts. Pin the §3 anchor items as fixed questions (outside the random groups) so they always appear, and reduce that group's random pull by the number pinned. (This extends the five-bank setup already built for the midterm to all ten modules.)
6. **EOC format throughout** — single-best-answer MC, plain stems, no "all of the above," targeting the documented misconceptions.

---

## 5. CER short-response section (3 items, teacher-scored)

Three analytical short-response CER items, one from each of the year's three great domains (`plan.md` §7, `cer_guide.md`). These are **shorter than the ~400–700-word module essays** — each is a focused ~150–250-word claim-evidence-reasoning paragraph written during the exam. They are **teacher-reviewed, not auto-graded.**

The three sample the full spine: **molecular** (energy & matter), **genetic/evolutionary** (information → variation → common descent), and **ecological** (the living planet).

### CER 1 — Molecular (Modules 4 + 10 anchor; the carbon-atom trace)

> Follow a single **carbon atom** as it enters a plant, becomes part of a sugar, and is later released again. Start with a CO₂ molecule in the air. Trace the atom through **photosynthesis** (into glucose) and then through **cellular respiration** (back to CO₂), naming where each stage happens and what happens to the carbon. Write a claim, cite the steps as evidence, and explain the *mechanism* — including why "energy flows one way but matter cycles" is true for this atom.

*Targets the Module 4 CER focus (photosynthesis/respiration as complementary, not reverse, processes) and the Module 10 carbon-cycle connection. Rewards the M4↔M10 bridge from the review lesson.*

### CER 2 — Genetic / Evolutionary (Modules 5 + 6 anchor; mutation → variation → common descent)

> Explain how a change in **DNA** can, over many generations, become evidence that two species share a **common ancestor**. Begin with a single mutation in one organism. Write a claim, then use as evidence the chain: mutation → heritable variation (via meiosis/reproduction) → natural selection acting on that variation → accumulated differences → the molecular and anatomical similarities we later read as common descent. Explain the *mechanism* at each step — especially why variation must be *heritable* to matter, and why shared DNA sequences are strong evidence of shared ancestry.

*Targets the Module 5→Module 6 bridge (heritable variation is the raw material of selection) and the Module 6 CER focus (independent lines of evidence for common descent). Rewards the M5→M6 bridge from the review lesson.*

### CER 3 — Ecological *(primary form: climate evidence; alternate form: energy flow)*

**Form A (primary) — Evidence for climate change (Module 10 anchor):**

> Scientists argue that recent climate change is driven by human activity. Identify **three independent lines of evidence** that support this claim (for example: the instrumental temperature record, rising atmospheric CO₂ with its isotopic "fingerprint," and shifts in species' ranges or timing). Write a claim, present the three lines as evidence, and explain the *reasoning* — why *independent* lines converging on the same conclusion make the argument strong, the same way independent lines made the case for evolution.

*Targets the Module 10 CER focus (evaluate anthropogenic climate change from three independent sources) and reuses the Module 6 reasoning about convergent independent evidence.*

**Form B (alternate) — Energy flow & the 10% rule (Module 10 anchor):**

> A food chain runs: grass → grasshopper → mouse → hawk. Explain why there are far fewer hawks than blades of grass. Write a claim, use the 10% rule and the idea of trophic levels as evidence, and explain the *mechanism* — where the "lost" 90% of the energy goes at each step, and why this means "energy flows but matter cycles." Connect it back to where the energy first entered the chain (plant photosynthesis).

*Targets the Module 10 energy-flow focus and the M8→M10 and M4→M10 bridges. Use Form B if Form A overlaps too heavily with recent work, or alternate forms across sections.*

### CER scoring — 6 points each (18 points total)

Each CER is scored on the same three components as the year's CER framework, compressed for a timed short-response and weighting reasoning (the mechanism) most heavily — identical to the midterm rubric:

| Component | 0 | 1 | 2 | 3 | Max |
|---|---|---|---|---|---|
| **Claim** | No/incorrect claim | A clear, correct, specific claim that answers the prompt | — | — | **1** |
| **Evidence** | None/irrelevant | Some correct evidence, with gaps | Accurate, specific evidence naming the relevant steps/facts | — | **2** |
| **Reasoning (mechanism)** | None | States *what* happens but not *why* | Explains the mechanism with one or more gaps | Explains *why* each step forces the next; mechanism complete | **3** |
| | | | | **Per CER** | **6** |

**CER section = 3 × 6 = 18 points.**

---

## 6. Scoring summary

| Section | Items | Points | Scored |
|---|---|---|---|
| Multiple choice | 70 | 70 (1 each) | Auto-graded (Canvas) |
| CER short-response | 3 | 18 (6 each) | Teacher-reviewed |
| **Final total** | **73 prompts** | **88 raw** | scale to 100% |

> Weighting note: the final counts toward the **Midterm & Final** grading category (10%), per the syllabus. The MC section is auto-graded, so the only teacher-review load is the 3 CER short-responses (≈2 minutes each), consistent with the course's 500:1 design target.

---

## 7. Sources & alignment (builder reference — never student-facing)

- **Bank source:** the 34 full-year `reading-quiz.md` files listed in §1 (314 vetted EOC items).
- **Draw counts:** `plan.md` §7 (final bank-draw table and EOC domain-weight targets).
- **Misconception anchors:** `01_Analysis/eoc_review.md` (per-unit common misconceptions).
- **CER prompts & rubric:** `plan.md` §7 (three final CER domains) and `01_Analysis/cer_guide.md` (3-component CER framework).
- **Cross-unit reasoning:** `plan.md` §8 spine bridges — the CER prompts deliberately reward the M4↔M10, M5→M6, and M8/M4→M10 connections traced in the Week-36 review lesson.
- **Hard rules honored:** no NGSSS codes and no OpenStax references appear on the student-facing exam; every MC could appear on the EOC unmodified.
