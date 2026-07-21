# CLAUDE.md — HS Biology 1 (Florida 2000310)

This file provides build context for every Claude Code session working on this course. **Read it at the start of every session before touching any other file.** It governs course identity, structure, source material, assessments, skills to load, build conventions, and hard rules.

---

## Course identity

- **Course name:** Biology 1
- **Florida course code:** 2000310 (Florida NGSSS-aligned; Biology 1 EOC)
- **Level:** High school (grades 9–10)
- **Delivery:** Fully asynchronous, Canvas LMS (the same curriculum is also used unchanged by live/synchronous sections)
- **School:** Optima Academy Online — classical liberal arts, virtue-centered, spatial-computing emphasis
- **Duration:** 36 weeks total — 34 instructional weeks + a Week-15 Midterm + a Week-36 Final
- **Course spine:** One long argument, microscopic → macroscopic. Atoms and molecules → cells → energy → genetics → evolution → diversity → plants → the human body → ecosystems. The connections between units are the architecture of biology, not digressions.

---

## Semester and module map (authoritative — from `02_Design/Biology_Course_Map.docx`)

The Course Map is the authoritative pacing and standards source. The `01_Analysis/units.md` Reference Guide is authoritative for **content depth, historical threads, and CER prompts**, but where the two disagree on unit order or grouping, **the Course Map wins**. (Note: the Reference Guide treats Biotechnology/PCR as a standalone unit and orders Plants before Genetics; the Course Map folds biotechnology into Modules 5 and 9 and uses the order below. Follow the Course Map.)

### Semester 1 (Weeks 1–15)
| Module | Title | Weeks | Dur. | Florida standards (tracked, never student-facing) | CER focus |
|---|---|---|---|---|---|
| 1 | Nature of Science | 1–2 | 2 wk | SC.912.N.1.1–1.7, N.2.1, N.3.1, N.3.4, N.3.5 | Evaluate a flawed experimental design — identify claim, evidence quality, reasoning error |
| 2 | Chemistry of Life | 3–4 | 2 wk | SC.912.L.18.1, L.18.12, P.8.1, P.8.2, P.8.7 | Explain how water's bent geometry produces life-enabling properties |
| 3 | Cell Structure, Function, and Transport | 5–7 | 3 wk | SC.912.L.14.1–14.4, L.14.6 | Predict/justify red-blood-cell behavior in hypo-, hyper-, isotonic solutions |
| 4 | Cell Energy | 8–10 | 3 wk | SC.912.L.18.7, L.18.8, L.18.9 | Analyze leaf-disk assay data — effect of light intensity on photosynthesis rate |
| 5 | DNA, Cell Division, and Genetics | 11–14 | 4 wk | SC.912.L.16.1–16.5, L.16.8–16.10, L.16.14, L.16.16–16.17 | Trace a mutation: base substitution → amino-acid change → protein shape → disease phenotype |
| — | **Midterm Review & Exam** | **15** | 1 wk | Units 1–5 cumulative | EOC-format: 50 MC + 2 CER short-response (Units 1–5) |

### Semester 2 (Weeks 16–36)
| Module | Title | Weeks | Dur. | Florida standards (tracked, never student-facing) | CER focus |
|---|---|---|---|---|---|
| 6 | Evolution and Natural Selection | 16–18 | 3 wk | SC.912.L.15.1–15.3, L.15.13–15.15 | Evaluate three independent lines of evidence for evolution; argue for common descent |
| 7 | Classification and Diversity of Life | 19–22 | 4 wk | SC.912.L.15.4–15.6, L.15.8, L.14.7 | Justify the three-domain system using molecular sequence data vs. morphology |
| 8 | Plant Biology | 23–25 | 3 wk | SC.912.L.14.7, L.18.10, L.18.11 | Analyze potometer transpiration data — how environment affects water loss |
| 9 | Human Body Systems | 26–29 | 4 wk | SC.912.L.14.26, L.14.36, L.14.52, L.16.10 | Trace a drug's mechanism: synapse → physiological effect → basis of addiction |
| 10 | Ecology and Environmental Science | 30–35 | 6 wk | SC.912.L.17.1–17.2, L.17.4–17.5, L.17.8–17.9, L.17.11, L.17.16–17.17, L.17.19–17.20, E.7.1, E.7.3 | Evaluate evidence for anthropogenic climate change from three independent sources |
| — | **Final Review & Exam** | **36** | 1 wk | All units cumulative | EOC-format: 70 MC + 3 CER short-response (molecular, genetic, ecological) |

**Per-module essential questions, key figures, historical threads, assignment ideas, EOC notes, and CER seeds are all in `01_Analysis/units.md`. Always read the relevant entry before building a module.**

---

## Source files in this folder

| File | Role |
|------|------|
| `01_Analysis/Biology-2e_-_WEB.pdf` | **Primary textbook (OpenStax Biology 2e).** Creative Commons licensed — copy, adapt, and modify freely. Read the relevant chapter(s) per lesson and adapt into Optima voice on Canvas-internal Reading pages. |
| `01_Analysis/Biology 1 (2000310).pdf` | Florida NGSSS standards for this course. Reference for objectives and coverage; **never displayed to students.** |
| `01_Analysis/units.md` | **Unit Reference Guide** — per-unit core idea, key figures, human/historical thread, backward/forward connections, assignment ideas, EOC readiness notes, CER seeds, reflective seeds, and the cross-unit connection map. Read the relevant unit before building. |
| `01_Analysis/cer_guide.md` | **CER Framework Guide** — what CER is, the three components, four scaffolding levels, historical-CER variation, the 3-point scoring rubric, and all 10 unit CER prompts. Governs every writing assignment. |
| `01_Analysis/eoc_review.md` | **Florida Biology EOC Review Guide** — domain weights, per-unit key concepts, common misconceptions, and EOC-style practice items. Use to align reading-quiz and exam questions to EOC format. |
| `01_Analysis/Biology Sem 1 OD.imscc`, `Biology Sem 2 - OD.imscc` | Prior Canvas course exports. Unzip and mine for reusable structure/content if helpful; not authoritative over the design docs. |
| `02_Design/Biology_Course_Map.docx` | **Authoritative 36-week pacing guide** — modules, weeks, essential questions, standards, CER focus, midterm/final specs. |
| `02_Design/Biology_Course_Syllabus.docx` | Syllabus — course philosophy, grading weights, CER framework, vetted online resource list (PhET, HHMI BioInteractive, CK-12, Khan, Visible Body, learn.genetics, etc.). |

---

## Grading weights (from the syllabus — informs assignment design)

| Category | Weight | Maps to |
|---|---|---|
| CER writing assignments | 30% | The per-module CER essay + in-lesson CER practice |
| Unit assessments | 25% | Paired lesson assignments, reading quizzes, midterm/final |
| Laboratory work & scientific notebooks | 20% | Lab / virtual-lab assignments and VR build activities |
| Discussion & participation | 15% | Structured discussion-board assignments (async) |
| Midterm & Final exams | 10% | Week-15 and Week-36 EOC-format exams |

These are weighting targets, not a rule that every week must hit every category. Design the weekly mix so the year lands roughly on these proportions.

---

## Normal-week structure (every week except Weeks 15 and 36)

Each normal week contains the following, **every week, no exceptions:**

### 4 reading pages (Canvas Pages) — one per lesson
- OpenStax *Biology 2e* content for the lesson, **adapted into Optima voice** — not copied verbatim, not citing OpenStax.
- One reading page per lesson, named to its lesson.
- This is the anchor text the lesson and assignment point back to.

### 4 lesson pages (Canvas Pages) — one per reading
Each lesson is asynchronous and fully self-contained — there is no live instruction. Every lesson page includes:
1. **Core content** — shaped by the module's `units.md` entry and the adapted reading. Inline-styled HTML fragment (see hard rules).
2. **Learning objectives** — 2–4, specific, in "I will be able to…" form. Aligned to the module's standards (not shown as codes).
3. **Anchor reading pointer** — directs students to that lesson's Reading page.
4. **History-of-science callout (where appropriate)** — embedded "helpful info" (blue/teal) callout, ~150–250 words, drawn from the module's key figures / historical thread in `units.md`. Include where there's a genuine hook, not as box-checking.
5. **Contemporary-research callout (where appropriate)** — gold "highlight" callout, ~100–200 words, hedged tone ("recent research suggests…", "scientists are currently exploring…").
6. **AI-literacy callout (where appropriate)** — see the **AI-literacy integration** section. Either a history/logistics-of-AI box *or* an opportunities-and-pitfalls box, using the **AI-awareness callout style**.
7. **Web-interactive element (where appropriate)** — an embedded or linked interactive (PhET, HHMI BioInteractive, Concord Consortium, learn.genetics, Khan, Visible Body, or a custom widget). Custom interactives are built and hosted per `canvas-interactive-widgets` (GitHub Pages → iframe). Raw `<script>` never runs in a Canvas page — never inline it.
8. **VR session pointers** — a brief "Your VR This Week" section pointing to the week's two VR activities (see VR program).
9. **Activities** — 2–4 sequenced classical-pedagogy activities (narration, diagram, labeling, written response) per `optima-classical-pedagogy`.

### 4 paired assignments (Canvas Assignments) — one per lesson
- Canvas-native, paired directly to the lesson's objectives.
- Follow `optima-canvas-assignments` (tier system, 500:1 ratio — prefer auto-gradable or minimal-review).
- Where the `units.md` unit lists a lab or virtual lab, the assignment may be that lab / its virtual equivalent (counts toward the 20% lab category).
- File deliverables (lab reports, notebooks) are produced per `optima-m365-skills` (Word/Excel via OneDrive).

### 1 weekly reading quiz (Canvas Quiz)
- Covers all four lessons' assigned readings.
- **8–10 questions/week** (exact count set in `plan.md` by module depth).
- Every question must stand alone as a quiz-bank item (clear, unambiguous, answerable without the other questions) and be **EOC-format** (use `eoc_review.md` style and target the unit's common misconceptions).
- **The bank accumulates all year.** Semester-1 weeks (1–14) feed the **Week-15 Midterm**; the **Week-36 Final** draws cumulatively from the full-year bank (all units), weighted proportionally to module size. Do not write any reading-quiz question that couldn't appear on an exam unmodified.

### 2 VR assignments (Canvas Assignments) — see VR program
- **VR-A (Build/Model)** and **VR-B (Explore/Observe)** — two distinct ENGAGE solo activities, each a low-friction Canvas submission (snapshot/IFX or short recording).

---

## Per-module deliverables (in addition to weekly content)

### Module CER writing assignment (1 per module, 10 total)
- This **is** the module's conceptual writing assignment — do not invent a second essay on top of it.
- Assigned at module start, due at module end. Built on the module's CER driving question (seeded in `cer_guide.md` and `units.md`).
- Requires genuine conceptual understanding (mechanism, "why"), not recall. Analytical Claim–Evidence–Reasoning response, ~400–700 words.
- Teacher-reviewed (not auto-graded). Score with the 3-point CER rubric in `cer_guide.md` (Claim / Evidence / Reasoning / Integration).
- Match scaffolding to where the module sits in the year (Levels 1–4 in `cer_guide.md` — guided early, contested/open later). Where a "historical CER" fits (write the argument a scientist could have made with only the evidence of their time), use it.
- Produced as a Word deliverable per `optima-m365-skills`.

---

## VR program

Two layers, governed by `optima-vr-curriculum` (ENGAGE platform; the async VR curriculum is used unchanged by live classes).

### Layer 1 — Weekly solo activities (2 per week, graded, low-friction)
- **VR-A (Build/Model):** students construct or manipulate a 3D model of the week's concept (e.g., build a water molecule and show polarity; assemble a phospholipid bilayer; trace a DNA double helix; model a trophic pyramid).
- **VR-B (Explore/Observe):** students enter a Location/scene to explore and observe (e.g., tour an animal vs. plant cell; walk a Florida ecosystem; examine a hominid fossil sequence; observe transpiration apparatus), then capture evidence.
- Each submits a VR snapshot (IFX) or a short spatial recording to a Canvas assignment. Keep friction low per the VR skill.
- Specific per-week VR activities are designed in `plan.md` (Phase 1), mapped to lesson content. Build/explore examples above are illustrative, not final.

### Layer 2 — Quarterly VR unit project (4 total, graded, gallery-walk-ready)
- One larger synthesizing VR project per quarter. Quarter→week boundaries are set in `plan.md` (the 36-week map does not divide into clean 8-week quarters; propose four ~9-week quarters in Phase 1).
- Each project asks students to combine the quarter's concepts into a single spatial artifact (e.g., a buildable cell, an evolution-evidence gallery, an ecosystem energy-flow walk) suitable for a teacher-assembled gallery walk.
- Graded on a project rubric drafted in `plan.md` (completeness, recognizable accuracy — high-school level, not perfection — and evidence of iterative building).

---

## Midterm & Final weeks (Weeks 15 and 36)

No regular lessons/assignments these weeks. Each contains exactly three items:

1. **Review lesson** (Canvas Page) — synthesis, not new content. A "grand tour" tracing the microscopic→macroscopic spine and the cross-unit connections (`units.md` cross-unit map). Lighter than a normal lesson.
2. **Review activity** (Canvas Assignment) — concept map, comparison chart, or synthesis task. Auto-gradable or minimal-review preferred.
3. **Exam** (Canvas Quiz):
   - **Week 15 Midterm:** 50 MC + 2 CER, drawn from the Units 1–5 reading-quiz bank.
   - **Week 36 Final:** 70 MC + 3 CER, cumulative across all units, drawn from the full-year bank, proportional to module size, spanning molecular, genetic, and ecological domains.
   - Specify bank-draw logic and counts in the quiz spec file.

---

## AI-literacy integration

A distinctive feature of this course. Two kinds of AI callouts, embedded in lessons where genuinely relevant (not as box-checking), both using the **AI-awareness callout style** from `optima-lesson-format`:

1. **History & logistics of AI** — short narratives on what AI is and how it works: what a model is, training data and compute, the arc from the perceptron and early neural nets to deep learning and large language models, and how a tool like AlphaFold actually predicts protein structure. Plainly explanatory.
2. **Opportunities & pitfalls of using AI** — honest, practical guidance: where AI genuinely helps a biology student (organizing notes, generating practice questions, checking reasoning, visualizing structures) and where it fails or harms learning (hallucinated facts and fabricated citations, training-data bias, over-reliance that hollows out understanding, and academic integrity). Frame AI as a tool to interrogate, not an authority to trust.

**Biology-relevant AI hooks by area** (use where they fit naturally):
- **AlphaFold & protein-structure prediction** — Modules 2, 5, 9 (macromolecules, gene→protein, body systems).
- **AI in genomics / CRISPR target prediction & DNA sequence analysis** — Module 5.
- **ML in phylogenetics and building trees of life** — Modules 6–7.
- **AI image classification for microscopy and cell typing** — Module 3.
- **AI in drug discovery and disease modeling** — Module 9.
- **AI in biodiversity monitoring, species ID, and ecological modeling** — Module 10.
- **Nature-of-science lens on AI** — Module 1 (how do we evaluate an AI claim the way we evaluate any scientific claim?).

Tone: same hedged, inquiry-minded voice as the contemporary-research callouts. **Never fabricate** AI capabilities, history, or specific results — if unsure of a detail, write in broader strokes.

---

## History-of-science integration

This is a classical-education school: science is taught as a human story of careful observation, brilliant inference, stubborn error, and eventual revision — not a list of settled facts. Weave history-of-science moments into lessons as **embedded callouts**, never separate pages. Candidate figures/threads (full detail in `units.md`):

- **Nature of Science:** Bacon, Popper, Kuhn; Semmelweis, Wegener, Marshall & Warren (vindicated dissenters).
- **Chemistry of Life:** Wöhler synthesizing urea (1828, the death of vitalism); Franklin / Watson & Crick (DNA structure, and the ethics of credit).
- **Cell:** Hooke, Leeuwenhoek (the draper who saw bacteria), Schleiden & Schwann, Virchow, Ignaz Semmelweis (handwashing/chlorinated lime, confirmed by reduced maternal deaths from puerperal fever).
- **Cell Energy:** van Helmont's willow, Priestley, Lavoisier ("life is slow combustion"), Krebs.
- **DNA/Genetics:** Mendel (ignored 35 years), Flemming, Morgan.
- **Evolution:** Darwin & Wallace, Mayr, Woese (three domains), Miller–Urey, Pasteur (spontaneous generation).
- **Classification:** Linnaeus, Woese; morphology vs. molecular sequence.
- **Plant Biology:** Malpighi, Hales, Darwin's *Power of Movement in Plants*, Frits Went (auxin).
- **Human Body:** Harvey (circulation, vs. 1,400 years of Galen), Jenner, Pasteur & Koch (germ theory), Claude Bernard, Cannon (homeostasis), Banting & Best (insulin).
- **Ecology:** Humboldt, Elton, Leopold (land ethic).

Do not fabricate dates, quotes, or results. If unsure, write in broader strokes.

---

## Contemporary-research integration

Each module should also touch current science — hedged, embedded as callouts, never presented as settled. Candidates: mRNA-vaccine platforms and protein design (Chem of Life / Body Systems); organoids and lab-grown tissues (Cell / Body Systems); CRISPR base/prime editing and gene therapy (Genetics / Biotech); ancient-DNA and molecular phylogenetics (Evolution / Classification); the plant microbiome and drought-resilient crops (Plant Biology); microbiome and human health (Body Systems); eDNA biodiversity surveys and Florida-specific conservation (Ecology). Use "recent research suggests…" / "scientists are currently exploring…".

---

## Skills to load for every session

Name these in your opening prompt to ensure they load:

- **`optima-mission-vision`** — virtue-centered, Portrait of a Graduate alignment (the foundational layer).
- **`optima-classical-pedagogy`** — narration, copywork, imitation, Socratic elements, classical form.
- **`optima-biology`** — the biology subject layer (**use in place of `optima-science`** — never load both for the same lesson). Florida NGSSS / Biology 1 EOC awareness, CER framework, iconic biology experiments, the microscopic→macroscopic arc, lab/VR-lab structure.
- **`optima-stem`** — inquiry-based instructional character (curiosity, investigation, iteration, reasoning from evidence).
- **`optima-lesson-format`** — Canvas-ready inline-styled HTML, Optima visual identity, callout styles (helpful / risky / AI-awareness), accordions, tooltips, LaTeX.
- **`optima-canvas-assignments`** — Canvas-native assignment/quiz/rubric design; four-tier system; 500:1 ratio; module wrappers; GitHub-vs-Canvas deployment split.
- **`optima-vr-curriculum`** — ENGAGE solo activities, quarterly unit projects, snapshot/IFX submissions, gallery walks.
- **`optima-m365-skills`** — CER essays, lab reports, and notebooks as Word/Excel deliverables via the Canvas + OneDrive LTI.
- **`canvas-interactive-widgets`** — for any custom web-interactive element (build + host on GitHub Pages, embed via iframe).

---

## Virtue threads (proposals — confirm in Phase 1)

| Module | Suggested virtue thread |
|---|---|
| 1 — Nature of Science | **Honesty** — following evidence and changing your mind when it points elsewhere |
| 2 — Chemistry of Life | **Wonder** — the same atoms as the stars, arranged into life |
| 3 — Cell | **Perseverance** — Leeuwenhoek the draper, Semmelweis rejected then vindicated |
| 4 — Cell Energy | **Service** — photosynthesis captures the energy that feeds all life |
| 5 — DNA, Cell Division, Genetics | **Responsibility** — faithful copying; what we inherit and pass on |
| 6 — Evolution | **Courage** — Darwin following evidence into 20 years of controversy |
| 7 — Classification | **Courtesy** — the ordered naming of the household of life |
| 8 — Plant Biology | **Wonder** — Darwin's patient watching; sensing and responding without nerves |
| 9 — Human Body Systems | **Self-government** — homeostasis, the body's quiet discipline |
| 10 — Ecology | **Responsibility** — stewardship; Carson's land ethic; the common good |

Treat as locked.

---

## Build conventions (file naming)

```
HSBiology1/
├── CLAUDE.md                         ← this file (course root)
├── 01_Analysis/                      ← source material (read-only inputs)
├── 02_Design/                        ← course map + syllabus (read-only inputs)
└── 03_Build/                         ← all build output
    ├── plan.md                       ← Phase 1 output: full scope-and-sequence
    ├── module-01-nature-of-science/
    │   ├── week-01/
    │   │   ├── reading-1.html        ← OpenStax Biology 2e adapted into Optima voice
    │   │   ├── reading-2.html
    │   │   ├── reading-3.html
    │   │   ├── reading-4.html
    │   │   ├── lesson-1.html          ← points back to its paired reading
    │   │   ├── lesson-2.html
    │   │   ├── lesson-3.html
    │   │   ├── lesson-4.html
    │   │   ├── assignment-1.html
    │   │   ├── assignment-2.html
    │   │   ├── assignment-3.html
    │   │   ├── assignment-4.html
    │   │   ├── reading-quiz.md         ← questions in markdown; implement in Canvas
    │   │   ├── vr-a-build.html         ← weekly VR build/model activity
    │   │   └── vr-b-explore.html       ← weekly VR explore/observe activity
    │   ├── week-02/ ...
    │   └── writing-assignment-cer.html ← module CER (assigned start, due end)
    ├── module-02-chemistry-of-life/ ...
    ├── ... (modules 03–10)
    ├── quarterly-vr-projects/
    │   ├── q1-vr-project.html
    │   ├── q2-vr-project.html
    │   ├── q3-vr-project.html
    │   └── q4-vr-project.html
    ├── semester-1-midterm/             ← Week 15
    │   ├── review-lesson.html
    │   ├── review-activity.html
    │   └── midterm-quiz-spec.md         ← bank-draw logic + counts (50 MC + 2 CER, Units 1–5)
    └── semester-2-final/               ← Week 36
        ├── review-lesson.html
        ├── review-activity.html
        └── final-quiz-spec.md           ← bank-draw logic + counts (70 MC + 3 CER, cumulative)
```

Reading-quiz questions go in `reading-quiz.md` as markdown (question + choices + flagged correct answer). They are implemented in Canvas manually or via the Canvas API — **do not generate Canvas XML.**

---

## Phase 1 output spec (`plan.md`)

Do not build any lesson/reading/assignment HTML until `plan.md` is complete and approved. `plan.md` must contain:

1. **Confirmation of the 36-week map** and the four VR-project quarter boundaries (propose ~9-week quarters).
2. **Week-by-week topic outline** — for every week: the 4 lesson topics, each lesson's reading assignment (which OpenStax *Biology 2e* chapter/section is being adapted), and which callouts are planned (history / contemporary-research / AI / web-interactive).
3. **VR map** — the 2 weekly solo activities (VR-A build, VR-B explore) for every week, plus the 4 quarterly VR projects.
4. **Module CER prompts** — all 10, finalized from `cer_guide.md`/`units.md` seeds, with the scaffolding level chosen per module.
5. **VR project rubrics** — one per quarter (can share a base rubric with project-specific columns).
6. **Virtue-thread confirmations** — the approved virtue per module.
7. **Reading-quiz question counts** — per week, plus the midterm and final bank-draw logic.
8. **Cross-unit connection notes** — the "one long argument" spine (use the `units.md` cross-unit map) that feeds the midterm and final review lessons.

---

## Hard rules (inherited from the Optima design system)

- **No `<html>`, `<head>`, `<body>`, or external `<style>` tags.** Every page is an HTML fragment for Canvas's editor. All styling is inline.
- **No Florida NGSSS standards codes on student-facing pages.** They are tracked in the standards doc and this file — never displayed to students.
- **No OpenStax references on student-facing pages.** Readings are *adapted* from OpenStax *Biology 2e* into Optima voice on Canvas-internal Reading pages. Lesson/reading/assignment/quiz pages do not name, link, or cite OpenStax page/section numbers. A single course-level disclosure (Welcome or Module-1 intro page) notes that readings are adapted from OpenStax; after that, OpenStax is not named again. A student needs only Canvas and ENGAGE VR to take this course.
- **No fabricated content.** This is science — accuracy matters. If you don't have the source for a specific historical detail, research finding, AI fact, or biological fact, say so and ask rather than inventing dates, quotes, mechanisms, or results.
- **The Optima owl logo** is an `<img>` from the GitHub CDN, never a 🦉 emoji.
- **Form follows function.** Every relevant lesson answers both "what is it?" (structure) and "what does it do / why?" (function). Structural description without mechanism is incomplete.
- **CER is the writing backbone.** Every module writing assignment is a CER; in-lesson written responses should practice claim → evidence → reasoning.
- **Cross-unit connections are features, not digressions.** The course is one argument from atoms to ecosystems — when a unit depends on an earlier one (chloroplasts ⟵ endosymbiosis; food webs ⟵ photosynthesis; variation ⟵ meiosis), say so explicitly.
- **Web-interactive elements never use raw `<script>` in Canvas** — Canvas strips/ignores it. Custom interactives are hosted on GitHub Pages and embedded via iframe per `canvas-interactive-widgets`; otherwise link out to vetted tools (PhET, HHMI BioInteractive, etc.).
- **EOC alignment.** Reading-quiz and exam items follow EOC format and target the documented common misconceptions in `eoc_review.md`.
```
