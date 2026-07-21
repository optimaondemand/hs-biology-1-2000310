# Week 15 Midterm — Quiz Specification (Bank-Draw Logic + Counts)

**Biology 1 (Florida 2000310) · Semester 1 Midterm · Modules 1–5 cumulative**
**Format: 50 multiple-choice (EOC-format) + 2 CER short-response · EOC-aligned**

This file specifies **how the midterm is assembled from the existing Semester-1 reading-quiz bank** — it is not itself a set of new questions. Build the exam in Canvas as a native Quiz. Do **not** generate Canvas XML. Every MC item already exists, vetted and answer-keyed, in the weekly `reading-quiz.md` files; the midterm *draws* from them. The 2 CER items are teacher-scored short responses, specified in full at the end.

---

## 1. The Semester-1 bank it draws from

Every reading-quiz item was written to stand alone as a reusable bank item and to be EOC-format, so any of them can appear on the midterm unmodified (CLAUDE.md hard rule). The Semester-1 bank is the union of all Module 1–5 weekly quizzes:

| Module | Title | Weeks | Items/wk | Module pool | Source files |
|---|---|---|---|---|---|
| 1 | Nature of Science | 1–2 | 8 | **16** | `module-01-nature-of-science/week-0{1,2}/reading-quiz.md` |
| 2 | Chemistry of Life | 3–4 | 8 | **16** | `module-02-chemistry-of-life/week-0{3,4}/reading-quiz.md` |
| 3 | Cell Structure, Function & Transport | 5–7 | 9 | **27** | `module-03-cell-structure-function-transport/week-0{5,6,7}/reading-quiz.md` |
| 4 | Cell Energy | 8–10 | 9 | **27** | `module-04-cell-energy/week-{08,09,10}/reading-quiz.md` |
| 5 | DNA, Cell Division & Genetics | 11–14 | 10 | **40** | `module-05-dna-cell-division-genetics/week-{11,12,13,14}/reading-quiz.md` |
| | | **14 wk** | | **126 total** | |

The midterm pulls **50** of these 126 for the MC section.

---

## 2. MC draw — counts by module (proportional to Semester-1 weeks)

50 MC allocated proportionally to each module's instructional weeks (14 weeks total), matching `plan.md` §7.

| Module | Weeks | Share of 14 wk | **MC drawn** |
|---|---|---|---|
| 1 — Nature of Science | 2 | 14% | **7** |
| 2 — Chemistry of Life | 2 | 14% | **7** |
| 3 — Cell Structure & Transport | 3 | 21% | **11** |
| 4 — Cell Energy | 3 | 21% | **11** |
| 5 — DNA, Division & Genetics | 4 | 29% | **14** |
| **Total** | **14** | **100%** | **50** |

### 2a. Sub-allocation by week (keeps coverage even within a module)

Draw the module's allotment spread across its weeks so no single week dominates:

| Module | Per-week draw | Sums to |
|---|---|---|
| 1 | Wk 1: 4 · Wk 2: 3 | 7 |
| 2 | Wk 3: 4 · Wk 4: 3 | 7 |
| 3 | Wk 5: 4 · Wk 6: 3 · Wk 7: 4 | 11 |
| 4 | Wk 8: 4 · Wk 9: 3 · Wk 10: 4 | 11 |
| 5 | Wk 11: 3 · Wk 12: 4 · Wk 13: 4 · Wk 14: 3 | 14 |

---

## 3. Required-coverage rule (the draw is *stratified*, not blind-random)

The per-week counts above set the quotas. Within each week, selection is random **except** that the following high-value, EOC-targeted **misconception anchors must be guaranteed a seat** (each is a documented misconception from `eoc_review.md`). Fill the remaining seats randomly from that week's pool. This ensures the exam tests the misconceptions the course was built to correct, not an accidental easy subset.

**Must-include anchors (one item each, drawn from the named module):**

- **M1** — theory vs. law (a theory is *not* "a guess that grew up"); a single failed prediction vs. an established theory; identifying the controlled variable / control group in a described experiment.
- **M2** — water's specific heat moderates temperature; hydrogen bonding explains cohesion/ice/solvent behavior; a protein's *function follows its folded shape* (denaturation).
- **M3** — osmosis is the movement of *water* (direction by solute concentration); RBC in hypo-/hyper-/isotonic solution; the cell membrane is a phospholipid bilayer (fluid mosaic); active transport requires energy (Na⁺/K⁺ pump).
- **M4** — photosynthesis and respiration are *not* simple reverses of each other; the Calvin cycle does not require *direct* light; ATP is the energy currency; O₂ is the *final electron acceptor* in respiration (energy flows, matter cycles).
- **M5** — transcription vs. translation (where each occurs); gel electrophoresis separates DNA *by size*, smaller travels farther; meiosis produces genetically unique cells (mitosis vs. meiosis); "dominant" ≠ "more common"; a single base substitution → amino-acid change → protein → phenotype (sickle cell).

> If a future re-build adds more items to a week's pool, keep the per-week quotas in §2a and re-run the stratified draw; the anchors above stay mandatory.

---

## 4. Assembly rules (Canvas)

1. **No duplication.** Each of the 50 MC is a distinct bank item; none repeats within the exam.
2. **Preserve the vetted item verbatim.** Use each item's stem, four options, flagged correct answer, and (optionally) its explanation as Canvas answer feedback. Distractors are already misconception-based — do not edit.
3. **Shuffle.** Shuffle question order and answer-option order at delivery (Canvas Quiz settings). Because every item stands alone, shuffling is safe.
4. **One point per MC** = 50 points for the MC section.
5. **Group by Canvas Question Banks.** Recommended: create five Canvas Question Banks (one per module) populated from the weekly `reading-quiz.md` items, then use a Quiz with five question groups set to pull the §2 counts. Pin the §3 anchor items as fixed questions (outside the random groups) so they always appear, and reduce that group's random pull by the number pinned.
6. **EOC format throughout** — single-best-answer MC, plain stems, no "all of the above," targeting the documented misconceptions.

---

## 5. CER short-response section (2 items, teacher-scored)

Two analytical short-response CER items, drawn from the Semester-1 CER focuses (`plan.md` §7, `cer_guide.md`). These are **shorter than the ~400–700-word module essays** — each is a focused ~150–250-word claim-evidence-reasoning paragraph written during the exam. They are **teacher-reviewed, not auto-graded.**

- **CER 1 is molecular/cellular**; **CER 2 is genetic.** Together they sample the two halves of the Semester-1 spine (chemistry→cell, and information→heredity).

### CER 1 — Molecular / Cellular *(primary form: osmosis; alternate form: water)*

**Form A (primary) — Osmosis & tonicity (Module 3 anchor):**

> A hospital must give a patient fluids through an IV line directly into the bloodstream. Explain what would happen to the patient's red blood cells if the IV fluid were **pure water** instead of an isotonic (0.9% saline) solution. Write a claim, support it with evidence about osmosis and tonicity, and explain the *mechanism* — why water moves the way it does and what that does to the cell.

*Targets the Module 3 CER focus (predict/justify RBC behavior in hypo-/hyper-/isotonic solutions) and the "osmosis moves water" misconception.*

**Form B (alternate) — Properties of water (Module 2 anchor):**

> Water makes life on Earth possible. Choose **one** property of water (high specific heat, cohesion/surface tension, ice floating, or its power as a solvent), make a claim about why it matters for living things, give evidence, and explain the *mechanism* by which water's bent, polar molecular shape and hydrogen bonding produce that property.

*Targets the Module 2 CER focus (how water's bent geometry produces life-enabling properties). Use Form B if Form A's content overlaps too heavily with a recent assessment, or alternate forms across sections.*

### CER 2 — Genetic (Module 5 anchor; the mutation→phenotype trace)

> In sickle-cell disease, the beta-globin gene differs from the usual version at a **single DNA base**, changing the mRNA codon **GAG → GUG** and the amino acid **glutamic acid → valine**. Trace how that one change leads to the disease. Write a claim, cite the steps of the chain as evidence (base → codon → amino acid → protein shape → cell shape → phenotype), and explain the *mechanism* at each step — including why changing one amino acid changes the protein's shape and behavior.

*Targets the Module 5 CER focus (trace a base substitution to a disease phenotype) and the shape→function principle from Module 2.*

### CER scoring — 6 points each (12 points total)

Each CER is scored on the same three components as the year's CER framework, compressed for a timed short-response and weighting reasoning (the mechanism) most heavily:

| Component | 0 | 1 | 2 | 3 | Max |
|---|---|---|---|---|---|
| **Claim** | No/incorrect claim | A clear, correct, specific claim that answers the prompt | — | — | **1** |
| **Evidence** | None/irrelevant | Some correct evidence, with gaps | Accurate, specific evidence naming the relevant steps/facts | — | **2** |
| **Reasoning (mechanism)** | None | States *what* happens but not *why* | Explains the mechanism with one or more gaps | Explains *why* each step forces the next; mechanism complete | **3** |
| | | | | **Per CER** | **6** |

**CER section = 2 × 6 = 12 points.**

---

## 6. Scoring summary

| Section | Items | Points | Scored |
|---|---|---|---|
| Multiple choice | 50 | 50 (1 each) | Auto-graded (Canvas) |
| CER short-response | 2 | 12 (6 each) | Teacher-reviewed |
| **Midterm total** | **52 prompts** | **62 raw** | scale to 100% |

> Weighting note: the midterm counts toward the **Midterm & Final** grading category (10%), per the syllabus. The MC section is auto-graded so the only teacher-review load is the 2 CER short-responses (≈2 minutes each), consistent with the course's 500:1 design target.

---

## 7. Sources & alignment (builder reference — never student-facing)

- **Bank source:** the 13 Semester-1 `reading-quiz.md` files listed in §1 (126 vetted EOC items).
- **Draw counts:** `plan.md` §7 (midterm bank-draw table).
- **Misconception anchors:** `01_Analysis/eoc_review.md` (per-unit common misconceptions).
- **CER prompts & rubric:** `01_Analysis/cer_guide.md` (3-component CER framework) and the Module 2/3/5 CER focuses in the Course Map.
- **Hard rules honored:** no NGSSS codes and no OpenStax references appear on the student-facing exam; every MC could appear on the EOC unmodified.
