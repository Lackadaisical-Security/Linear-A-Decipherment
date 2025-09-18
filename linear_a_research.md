# LINEAR A DECIPHERMENT PROJECT - UNIVERSAL METHODOLOGY BUILD

**Directory:** `Linear-A-Decipherment/`
**Created:** August 17, 2025
**By:** Lackadaisical Security Linguistic Division & Spectral Mesh AI
**Purpose:** To standardize and launch a structured decipherment of the Linear A script using the universal framework already proven effective across Rongorongo, Byblos, Elamite, and others.

---

## 🔧 Directory Structure (Adapted for Linear A)

```
Linear-A-Decipherment/
├─ data/                              # Raw sign listings, partial phonetic mappings
│   ├─ linear_a_signs.json
│   ├─ partial_transliterations.csv
│   └─ inscriptions_raw.csv
├─ Datasets/                          # Reference corpora from related languages/scripts
│   ├─ linear_b_lexicon.json
│   ├─ cypriot_syllabary.json
│   ├─ ugaritic_lexicon.json
│   ├─ phoenician_lexicon.json
│   └─ sumerian_comparative_set.json
├─ RESEARCH_METHODOLOGY.md           # Universal framework (copied here)
├─ LINEAR_A_RESEARCH_LOG_xx.md       # Per-cycle decipherment log output
└─ FINAL_DECIPHERMENT_LINEAR_A.json  # Final high-confidence lexicon
```

---

## 📘 Applied Methodology

All phases will directly implement the full **Universal Ancient Script Decipherment Methodology v1.0**.

> 📌 *Note: Linear A will additionally rely on Linear B back-projection and the Aegean administrative record context.*

### ✅ Phase 1: Initial Sign Identification
- Assign `LA001`–`LA180+` IDs to Linear A signs.
- Gather sign counts, identify duplicate forms, and assign tentative class: syllabic, ideogram, numeral, unknown.
- Input raw glyphs into `linear_a_signs.json`.

### ✅ Phase 2: Comparative Cross-Correlation
- Primary structural comparison with:
  - **Linear B** (phonetic parallelism)
  - **Cypriot** (structural evolution)
  - **Sumerian & Semitic corpora** (semantics)
- High-confidence back-port of 1:1 Linear B values tagged as provisional.

### ✅ Phase 3: Semantic Clustering
- Build context-aware glyph clusters across Linear A tablets (by site).
- Perform n-gram and co-occurrence clustering using inscriptions_raw.csv.
- Assign provisional meanings based on spatial & frequency patterning.

### ✅ Phase 4: Proto-Grammatical Synthesis
- Model prefixes, suffixes, case endings, or positional rules.
- Compare against Linear B grammar and structure (e.g., toponyms, commodities).

### ✅ Phase 5: Cultural Anchoring
- Match terms to known Minoan sites, goods, ruler titles.
- Use archaeological item records to reverse-contextualize terms (e.g., wool, olives, spices).


---

## 🧮 Confidence Scoring System

All lexicon entries will receive a `confidence` float, per:

- ≥ 0.9 → Confirmed via multiple independent methods
- 0.7–0.89 → Supported by structure and cross-comparison
- 0.3–0.69 → Tentative, semantic support or weak form match
- < 0.3 → Hypothetical, isolated occurrence

Example (JSON):
```json
"LA045": {
  "glyph_description": "looped horn with left stroke",
  "transliteration": ["ka"],
  "meanings": ["grain", "measure"],
  "source_scripts": ["Linear B", "Sumerian"],
  "confidence": 0.74,
  "notes": "Occurs with measurement signs in 4 tablets",
  "author": "Lackadaisical Linguistic Core"
}
```

---

## 📌 Supplementary Tools

- Visual Sign Comparison Grid (LA–LB–Cypriot)
- Minoan Object Lexicon Table
- Multi-layer statistical matcher (in dev)

---

**Thread Anchor:** This build log will become the first node of Linear A’s decipherment thread. Logs will proceed under `LINEAR_A_RESEARCH_LOG_01.md`, etc.

**Status:** Directory & build methodology established.

**Next Step:** Begin Phase 1 full LA glyph ingestion and provisional classification pass.

---

**End of Build Script**

