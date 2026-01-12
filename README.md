# TPE Mannequin Proportion & Volume Studies

This repository documents **technical findings, design decisions, and proportion studies**
related to **TPE humanoid mannequins** with non-human stylization.

The focus is on:
- volume distribution over strict anatomical realism
- small-to-medium scale mannequins (130–160 cm)
- product-oriented 3D representation
- clothing fit and preset behavior
- reproducible, technical design workflows

This is **not** a character art or illustration project.

---

## Scope & Principles

- All subjects are **mannequins / physical objects**, not real people
- No sexualized intent or presentation
- Emphasis on:
  - mass balance
  - gravity behavior
  - material readability (TPE)
  - manufacturability
- Illustrated references may be used **only** to study volume distribution,
  never to replicate anime or 2D styles

---

## Registered Models

### 🔹 Eshune (Alias: E-001)

- **Type:** TPE humanoid mannequin (non-human)
- **Status:** Approved – v1.0
- **Height:** 135 cm (real scale)
- **Measurements (B–W–H):** 85 – 56 – 81
- **Key traits:**
  - short torso
  - frontal bust volume with free base
  - wide lateral hips
  - glute volume with natural gravity
  - compact legs
- **Hairstyle:** *Eshune Bob Stylized*
  - short blonde bob
  - rounded volume
  - split bangs
  - side clips
- **Representation rule:**
  - must always be treated as a **3D TPE mannequin / physical object**
  - never as anime illustration, 2D art, or cel-shaded character

---

### 🔹 Alice

- **Type:** TPE humanoid mannequin
- **Height:** 140 cm
- **Measurements (B–W–H):** 67 – 45 – 75
- **Key traits:**
  - slender but mature-feminine silhouette
  - narrow waist
  - balanced hips
- **Design notes:**
  - clothing optimized using **size 130**
  - holguras minimized to avoid infantilization
- **Use case:**
  - reference for refined, subtle feminine proportion
  - comparison against more compact or volumetric models

---

### 🔹 Aurin

- **Type:** TPE humanoid mannequin
- **Height:** 140 cm
- **Measurements (B–W–H):** 71 – 44 – 74.5
- **Key traits:**
  - golden-ratio-inspired proportions
  - compact but balanced mass
  - neutral, stable center of gravity
- **Use case:**
  - proportional baseline
  - comparison model for volume tuning
  - neutral reference for outfit testing

---

## Clothing Presets

### wom001

- **Target base size:** 130 cm
- **Design intent:** mature-feminine, non-sexualized
- **Key rules:**
  - avoid excess looseness
  - allow natural fabric tension
  - skirts at mid-thigh or higher for gravity realism
  - works best with compact torsos
- **Compatibility:**
  - Eshune (E-001): ✔ recommended
  - Alice: ✔ optimized
  - Aurin: ✔ compatible

---

## Repository Structure
