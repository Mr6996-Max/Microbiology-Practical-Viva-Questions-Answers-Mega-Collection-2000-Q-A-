# Molecular Biology — Section II: Preparation of Different Tris Buffers
## 50 Viva Questions with Detailed Answers (Masters Level)

---

### BASIC PRINCIPLES

---

**Q1. What is Tris and what is its full chemical name and structure?**

**Tris** stands for **Tris(hydroxymethyl)aminomethane**, also known as **2-amino-2-(hydroxymethyl)-1,3-propanediol**. Its molecular formula is **C₄H₁₁NO₃** and its molecular weight is **121.14 g/mol**. Structurally, it consists of a central carbon atom bearing an amino group (–NH₂) and three hydroxymethyl groups (–CH₂OH). The amino group is the titratable group responsible for its buffering capacity. In its protonated form (Tris·H⁺, also written as Tris-HCl), it is a weak acid with a **pKa of approximately 8.06 at 25°C**. This pKa makes Tris an excellent buffer for biological and molecular biology applications in the physiologically and biochemically relevant pH range of 7.0–9.0. Tris is available as either the free base (unprotonated form) or as Tris-HCl (the hydrochloride salt, protonated form).

---

**Q2. What is the Henderson-Hasselbalch equation and how is it applied to Tris buffer preparation?**

The **Henderson-Hasselbalch equation** describes the relationship between pH, pKa, and the ratio of conjugate base to weak acid in a buffer system:

> **pH = pKa + log ([A⁻] / [HA])**

For Tris buffers:
- **[A⁻]** = concentration of Tris free base (unprotonated, conjugate base)
- **[HA]** = concentration of Tris-HCl (protonated, weak acid)
- **pKa** = 8.06 at 25°C

To prepare a buffer at a desired pH, rearranging gives the required ratio of Tris base to Tris-HCl. For example, at pH 8.0: log([A⁻]/[HA]) = 8.0 − 8.06 = −0.06, so [A⁻]/[HA] ≈ 0.87, meaning slightly more Tris-HCl than free base is needed. In practice, most laboratories prepare Tris buffer by dissolving Tris free base and adjusting pH by adding concentrated HCl, which is simpler and more accurate than calculating exact ratios of the two forms.

---

**Q3. Why is Tris the most widely used buffer in molecular biology?**

Tris is universally preferred in molecular biology for several reasons:
1. **pKa of 8.06** — within the optimal range for DNA stability (pH 7.5–8.5) and most enzyme activities
2. **Biologically compatible** — does not significantly inhibit DNA/RNA polymerases, restriction enzymes, or ligases at standard concentrations
3. **High buffer capacity** — at concentrations of 10–100 mM, it effectively resists pH changes from enzymatic reactions, salt additions, and CO₂ absorption
4. **Chemically inert** — does not react with nucleic acids, proteins, or most laboratory reagents under standard conditions
5. **Highly soluble** in water and stable at room temperature
6. **Inexpensive and widely available** in both free base and HCl salt forms
7. **Traceable pKa data** makes calculations reproducible across laboratories

Common Tris-based buffers include TE buffer (Tris-EDTA), TAE (Tris-Acetate-EDTA), TBE (Tris-Borate-EDTA), and PCR buffer.

---

**Q4. What is the pKa of Tris and why is it important? What is the effective buffering range?**

The pKa of Tris is **8.06 at 25°C**. A buffer is most effective within **±1 pH unit of its pKa**, giving Tris an effective buffering range of approximately **pH 7.0–9.0**. At pH values within this range, small additions of acid or base produce minimal change in pH because the buffer system can absorb H⁺ or OH⁻ by shifting the equilibrium between Tris free base and Tris-H⁺. Outside this range, the buffer capacity falls sharply. The pKa value is critical for calculating the composition of buffer at a desired pH (using Henderson-Hasselbalch) and for understanding how the buffer will perform. Tris should not be used as a buffer below pH 7.0 or above pH 9.0 — alternative buffers such as HEPES, MOPS, or glycine should be selected for those ranges.

---

**Q5. What is the significance of the large temperature dependence of Tris buffer pKa?**

Tris has an unusually large **temperature coefficient of pKa**: approximately **−0.031 pH units per °C** (i.e., the pKa decreases by ~0.031 for every 1°C increase). This means:
- At **4°C**: pKa ≈ 8.85 (buffer is more alkaline)
- At **25°C**: pKa ≈ 8.06 (standard)
- At **37°C**: pKa ≈ 7.71 (buffer is more acidic)

Practical implication: if a Tris buffer is adjusted to pH 8.0 at room temperature (25°C), it will have an actual pH of approximately **7.7 at 37°C** (in an incubator). This is critical for enzymatic reactions performed at 37°C (e.g., restriction digestion, ligation) where the actual buffer pH differs substantially from the measured pH. It also means that a Tris buffer adjusted to pH 7.4 at 37°C will read approximately pH 7.7 when measured at room temperature. Always specify both the **target pH and the temperature of adjustment** when recording buffer preparation.

---

### PROCEDURE

---

**Q6. What are the two approaches to preparing Tris buffer and what are the advantages of each?**

**Approach 1 — Single-salt method (most common):** Dissolve Tris free base in water and adjust pH downward by adding concentrated HCl. This approach allows very precise pH control because HCl is a strong acid and its effect on pH is predictable. No calculation of ratios is needed, and the final pH is adjusted by direct measurement.

**Approach 2 — Two-salt method:** Calculate the required amounts of Tris free base and Tris-HCl (the hydrochloride salt) using the Henderson-Hasselbalch equation, weigh both, dissolve together, and verify pH. This avoids addition of exogenous Cl⁻ ions beyond what is calculated, which can matter for applications sensitive to chloride concentration. However, it requires accurate calculations and is less forgiving of weighing errors.

In most molecular biology laboratories, **Approach 1** (dissolving free base, titrating with HCl) is standard. For applications where chloride must be strictly controlled (e.g., silver staining of gels, certain electrochemical assays), the two-salt method is preferred, or NaOH can be used to adjust pH downward if starting from Tris-HCl.

---

**Q7. Describe the step-by-step preparation of 500 mL of 1 M Tris-HCl, pH 8.0.**

**Materials:** Tris free base (MW 121.14 g/mol), concentrated HCl, calibrated pH meter, volumetric flask (500 mL), magnetic stirrer.

**Steps:**
1. Calculate mass of Tris needed: 1 mol/L × 0.5 L × 121.14 g/mol = **60.57 g**
2. Weigh 60.57 g of Tris free base on an analytical balance into a 600 mL beaker
3. Add approximately **400 mL of distilled/deionized water** and stir until completely dissolved
4. Calibrate the pH meter using standard pH 7.0 and pH 9.0 buffers
5. Insert pH electrode into the solution; begin measuring pH while stirring
6. **Add concentrated HCl dropwise** (use a Pasteur pipette or burette) with continuous stirring until pH reads 8.0
7. Adjust to room temperature if necessary (note: adjust at the temperature the buffer will be used)
8. Transfer to a **500 mL volumetric flask** and make up to exactly 500 mL with distilled water
9. Mix by inversion; verify pH again
10. Label the bottle with: name, concentration, pH, date of preparation, preparer's initials, and expiry date
11. **Autoclave** (121°C, 15 min) or filter-sterilize (0.22 µm) if required; re-check pH after autoclaving

---

**Q8. Why must the pH be adjusted before bringing the solution to final volume?**

This is one of the most important procedural rules in buffer preparation. The pH of a buffer is **concentration-dependent** — as the solution is diluted to its final volume, the H⁺ and OH⁻ concentrations change, altering the ratio of protonated to unprotonated Tris and thus shifting the pH. If you add water to bring to final volume first and then adjust pH, any HCl added to correct the pH introduces Cl⁻ ions and changes the total volume, making the concentration incorrect. The correct order is always:
1. Dissolve solute in ~80% of final volume
2. Adjust pH
3. Bring to final volume
4. Verify pH (minor re-adjustment may be needed if volume change significantly shifts concentration)

This principle applies to all buffer preparations, not just Tris.

---

**Q9. What is TE buffer? Give its composition and explain the role of each component.**

**TE buffer** (Tris-EDTA buffer) is the standard storage buffer for DNA and RNA in molecular biology. Standard composition:

> **10 mM Tris-HCl, pH 8.0 + 1 mM EDTA**

- **Tris-HCl (10 mM, pH 8.0):** Maintains a slightly alkaline pH that keeps DNA in solution and prevents acid-catalyzed depurination, which begins below pH 5. The slightly alkaline pH also partially suppresses DNase activity.
- **EDTA (1 mM):** Ethylenediaminetetraacetic acid is a **chelating agent** that binds divalent cations (Mg²⁺, Ca²⁺, Zn²⁺). Since DNases and RNases require divalent metal ions as cofactors for catalytic activity, EDTA inhibits these nucleases, protecting DNA/RNA from degradation.

TE buffer is not suitable for downstream reactions (PCR, restriction digestion) without dilution, because the EDTA chelates Mg²⁺ required by DNA polymerase and restriction enzymes. Low-TE (0.1 mM EDTA) or EDTA-free Tris buffer is used when EDTA interference is a concern.

---

**Q10. What is TAE buffer? Give its composition and compare it with TBE buffer.**

**TAE (Tris-Acetate-EDTA) buffer** composition (50× stock):
> **2 M Tris base + 1 M glacial acetic acid + 0.05 M EDTA (pH 8.0–8.3)**

Working concentration (1×): 40 mM Tris-acetate, 1 mM EDTA.

**TBE (Tris-Borate-EDTA) buffer** composition (10× stock):
> **0.9 M Tris base + 0.9 M boric acid + 0.02 M EDTA (pH 8.3)**

Working concentration (0.5×): 45 mM Tris-borate, 1 mM EDTA.

| Feature | TAE | TBE |
|---|---|---|
| Ion strength | Lower | Higher |
| DNA resolution | Better for large DNA (>5 kb) | Better for small DNA (<1 kb) |
| Run time | Faster migration | Slower migration |
| DNA recovery | Easy (DNA elutable from gel) | Harder (borate binds agarose) |
| Buffer depletion | Depletes faster during long runs | More stable for long runs |
| Common use | DNA cloning, Southern blot | SSCP, small fragment analysis |

---

**Q11. How do you prepare 1 litre of 50× TAE buffer?**

**Composition for 1 L of 50× TAE:**
- Tris base: 242 g (MW 121.14; target 2 M × 1 L = 2 mol → 242 g)
- Glacial acetic acid: 57.1 mL (density 1.049 g/mL; MW 60.05; target 1 M → 60.05 g → 57.1 mL)
- 0.5 M EDTA stock (pH 8.0): 100 mL (to give 0.05 M in 1 L)

**Procedure:**
1. Add 242 g Tris base to 600 mL distilled water, stir to dissolve
2. Add 57.1 mL glacial acetic acid (in a fume hood — corrosive vapor)
3. Add 100 mL of 0.5 M EDTA (pH 8.0) stock solution
4. Make up to 1 litre with distilled water; mix well
5. The pH should be approximately 8.3 without additional adjustment — the acetic acid titrates the Tris base
6. Verify pH; no adjustment should normally be needed; if pH deviates significantly, check reagent purity
7. Autoclave or filter-sterilize; store at room temperature
8. Dilute 1:50 with distilled water to prepare 1× working solution for gel electrophoresis

---

**Q12. Why is EDTA prepared and added at pH 8.0 when making TE, TAE, or TBE buffers?**

**EDTA (ethylenediaminetetraacetic acid)** is a tetraprotic acid (H₄EDTA) that does not dissolve appreciably at low pH because it is poorly ionized. Its solubility increases dramatically when the carboxylic acid groups are deprotonated. At **pH 8.0**, EDTA is essentially fully dissociated as EDTA⁴⁻, which is also the chelating form that binds divalent metals with high affinity (stability constants: K_f for Mg²⁺ ≈ 4.9×10⁸; for Ca²⁺ ≈ 5×10¹⁰). EDTA dissolves very poorly at pH < 7 — adding NaOH is required to dissolve it. Standard protocol: prepare **0.5 M EDTA stock** by dissolving disodium EDTA in water and adjusting pH to **8.0 with NaOH pellets** (approximately 8 g NaOH per 100 mL of 0.5 M EDTA). Adding un-dissolved or low-pH EDTA to a buffer will not provide effective nuclease inhibition.

---

**Q13. How do you prepare 0.5 M EDTA stock solution (pH 8.0)?**

**For 500 mL of 0.5 M EDTA:**

1. Calculate mass: 0.5 mol/L × 0.5 L × 372.24 g/mol (disodium EDTA·2H₂O) = **93.06 g**
2. Add 93.06 g disodium EDTA·2H₂O to a beaker containing 400 mL distilled water
3. Begin stirring — EDTA will not dissolve at this pH
4. Add **NaOH pellets** (approximately 9–10 g) gradually while stirring and monitoring pH
5. As pH rises above 7, EDTA begins dissolving; continue adding NaOH until pH reaches **8.0** and EDTA is fully dissolved
6. Make up to 500 mL with distilled water
7. Verify pH; autoclave to sterilize; store at room temperature in a sealed bottle

**Key point:** Using Na₂EDTA·2H₂O (disodium salt) rather than the free acid H₄EDTA reduces the amount of NaOH needed and makes dissolution easier since the disodium salt is already partially neutralized.

---

**Q14. What is the role of pH meter calibration before buffer preparation, and what buffers are used to calibrate the pH meter when making Tris buffers at pH 7.4, 8.0, or 9.0?**

A pH meter measures the electromotive force (EMF) across a glass electrode proportional to H⁺ activity; it requires calibration with at least two standard buffer solutions that **bracket the target pH**. The calibration establishes the electrode's slope (~59.16 mV/pH unit at 25°C, by Nernst equation) and offset. For Tris buffers:
- **pH 7.4 buffer:** calibrate with pH 7.0 and pH 9.0 standards (or pH 7.0 and pH 10.0)
- **pH 8.0 buffer:** calibrate with pH 7.0 and pH 9.0 standards ← most common for Tris
- **pH 9.0 buffer:** calibrate with pH 7.0 and pH 10.0 standards

Standard calibration buffers (NIST-traceable) are typically available at pH 4.0, 7.0, and 10.0. The electrode must be rinsed with distilled water between calibration buffers and between sample measurements. After calibration, the electrode slope should be 95–105% of theoretical (between −56 and −62 mV/pH unit). A slope outside this range indicates a damaged or aged electrode requiring replacement.

---

**Q15. Why should Tris buffer NOT be adjusted using a glass electrode without temperature compensation?**

Tris buffer has a very high temperature coefficient of pKa (−0.031 pH/°C), meaning its pH changes substantially with temperature. If the pH meter does not have **Automatic Temperature Compensation (ATC)**, the reading reflects the pH at the reference temperature rather than the actual temperature of the solution, introducing error. Additionally, the Nernst equation that governs electrode response is itself temperature-dependent (slope = 2.303RT/F, where T is absolute temperature), meaning the electrode response changes with temperature. A solution adjusted to pH 8.0 at 4°C in the cold room using a pH meter without ATC could actually be at a different pH when brought to 25°C. Always:
1. Use a pH meter **with ATC**
2. Specify and record the **temperature of pH adjustment**
3. Allow buffer and electrode to **equilibrate** to the adjustment temperature before measuring

---

### CALCULATIONS

---

**Q16. How much Tris free base and concentrated HCl are needed to prepare 200 mL of 50 mM Tris-HCl, pH 7.5?**

**Step 1 — Tris free base (MW 121.14 g/mol):**
Moles needed = 0.05 mol/L × 0.2 L = 0.01 mol
Mass = 0.01 × 121.14 = **1.21 g**

**Step 2 — HCl needed (estimated from Henderson-Hasselbalch):**
At pH 7.5 with pKa 8.06:
log([Tris base]/[Tris-HCl]) = 7.5 − 8.06 = −0.56
[Tris base]/[Tris-HCl] = 10^(−0.56) = 0.275
So: [Tris-HCl] / ([Tris base] + [Tris-HCl]) = 1 / (1 + 0.275) = 0.784
Fraction of total Tris that is protonated = 78.4%
Moles of HCl ≈ 0.01 × 0.784 = **0.00784 mol**
Volume of 12 M HCl = 0.00784 / 12 = **0.65 mL** (approximately 650 µL)

**In practice:** Dissolve 1.21 g Tris free base in ~150 mL water, add HCl dropwise with stirring while monitoring pH with a calibrated pH meter until pH = 7.5, then make up to 200 mL.

---

**Q17. How do you prepare 1 litre of 10× PCR buffer containing 100 mM Tris-HCl (pH 8.3), 500 mM KCl, and 15 mM MgCl₂?**

**Calculations:**
- Tris free base: 1 mol/L × 0.1 mol/L × 1 L × 121.14 g/mol = **12.114 g**
  (pH adjusted to 8.3 with HCl after dissolving)
- KCl (MW 74.55 g/mol): 0.5 mol/L × 1 L × 74.55 = **37.275 g**
- MgCl₂·6H₂O (MW 203.30 g/mol): 0.015 mol/L × 1 L × 203.30 = **3.050 g**

**Procedure:**
1. Dissolve 12.114 g Tris free base in 600 mL water
2. Add 37.275 g KCl and 3.050 g MgCl₂·6H₂O; stir to dissolve
3. Adjust pH to 8.3 at room temperature with concentrated HCl
4. Make up to 1 litre with distilled water; verify pH
5. Filter-sterilize through 0.22 µm membrane (do not autoclave — Mg²⁺ may precipitate)
6. Aliquot and store at −20°C; working solution diluted 1:10 to give 1× PCR buffer

---

**Q18. A stock solution of 1 M Tris-HCl (pH 8.0) is available. How would you prepare 250 mL of 10 mM Tris-HCl (pH 8.0) working solution?**

Using the **dilution equation**: C₁V₁ = C₂V₂

C₁ = 1 M (stock), C₂ = 0.01 M (10 mM), V₂ = 250 mL

V₁ = (C₂ × V₂) / C₁ = (0.01 × 250) / 1 = **2.5 mL**

**Procedure:**
1. Pipette **2.5 mL of 1 M Tris-HCl (pH 8.0)** stock into a 250 mL volumetric flask
2. Add approximately 200 mL distilled water and mix
3. Make up to exactly 250 mL with distilled water; mix by inversion
4. Verify pH — upon dilution, the pH may shift slightly; re-adjust if necessary
5. Filter-sterilize or autoclave as required

Note: Upon significant dilution (100-fold in this case), the buffer capacity decreases proportionally. 10 mM Tris has low buffer capacity and is easily overwhelmed by CO₂ absorption from air — use fresh solution for sensitive applications.

---

**Q19. Calculate the buffer capacity of a 50 mM Tris-HCl buffer at pH 8.0 (pKa = 8.06 at 25°C).**

**Buffer capacity (β)** is defined as the moles of strong acid or base required to change the pH of 1 litre of buffer by 1 unit:

> **β = 2.303 × C × Ka × [H⁺] / (Ka + [H⁺])²**

Where C = total buffer concentration = 0.05 M; Ka = 10^(−8.06) = 8.71 × 10⁻⁹; [H⁺] at pH 8.0 = 10⁻⁸

β = 2.303 × 0.05 × (8.71×10⁻⁹ × 10⁻⁸) / (8.71×10⁻⁹ + 10⁻⁸)²
= 2.303 × 0.05 × (8.71×10⁻¹⁷) / (1.871×10⁻⁸)²
= 2.303 × 0.05 × (8.71×10⁻¹⁷) / (3.50×10⁻¹⁶)
≈ **0.0287 mol/L/pH unit**

This means approximately **28.7 mmol of HCl or NaOH** is needed to change the pH of 1 litre of this buffer by 1 unit. Maximum buffer capacity occurs exactly at pH = pKa (8.06), where β_max = 2.303 × C / 4 = 2.303 × 0.05 / 4 ≈ 0.0288 mol/L/pH unit — confirming our value is near-maximum.

---

**Q20. How do you account for the temperature difference between preparation (25°C) and use (37°C) of a Tris buffer intended for restriction enzyme digestion?**

Since Tris pKa changes by −0.031 pH units per °C, the pH shift from 25°C to 37°C is:
ΔpH = −0.031 × (37 − 25) = −0.031 × 12 = **−0.372 pH units**

So a buffer prepared at pH 8.0 at 25°C will have an actual pH of approximately:
8.0 − 0.372 = **7.63 at 37°C**

To ensure pH 8.0 at 37°C (optimal for many restriction enzymes), prepare the buffer at:
pH_preparation = 8.0 + 0.372 ≈ **pH 8.37 at 25°C**

When measured at room temperature, this will read 8.37, but in the 37°C incubator it will be at the desired 8.0. Alternatively, adjust pH in a water bath at 37°C using a thermostated pH meter. Most commercial restriction enzyme buffers are formulated to have the correct pH at 37°C, accounting for this temperature effect.

---

### TROUBLESHOOTING

---

**Q21. You prepare Tris buffer at pH 8.0 and autoclave it. The pH after autoclaving is 7.6. What happened and how do you prevent this?**

**Autoclaving causes pH drift in Tris buffers** due to two mechanisms:
1. **Absorption of CO₂**: During cooling after autoclaving, some CO₂ dissolves from the air into the buffer, forming carbonic acid and lowering pH
2. **Hydrolysis of components**: At 121°C, minor chemical changes can occur in some buffer additives (not typically in pure Tris, but in complex buffers)
3. **Evaporation imbalance**: Steam condensation can dilute or concentrate the buffer slightly depending on container sealing

**Prevention:**
- Autoclave Tris buffer with the cap **loosely tightened** to allow pressure equalization, then tighten immediately upon removal and cool sealed — this limits CO₂ entry
- Alternatively, **filter-sterilize** (0.22 µm membrane) instead of autoclaving — this is the preferred method for Tris buffers to avoid pH drift
- **Re-check pH** after autoclaving and re-adjust if necessary before use
- Add minimal headspace above the buffer in the storage bottle to minimize CO₂ exposure

---

**Q22. EDTA will not dissolve in water when you are trying to make a 0.5 M EDTA stock. What is the cause and how do you resolve it?**

EDTA (whether the free acid H₄EDTA or the disodium salt Na₂EDTA) is poorly soluble at low pH because the carboxylate groups are protonated and the molecule is uncharged. Solubility increases dramatically above pH 7 as the groups ionize. If the solution pH is below 7, even vigorous stirring will not dissolve EDTA at 0.5 M concentration. 

**Resolution:**
- Add **NaOH pellets** gradually while stirring — each addition raises the pH slightly, progressively ionizing EDTA and dissolving it
- Monitor with pH paper or a pH meter; add NaOH until pH reaches **8.0** and dissolution is complete
- Use **Na₂EDTA·2H₂O** (disodium salt) rather than H₄EDTA — it requires far less NaOH to reach pH 8.0
- Heat the solution gently (40–50°C) to aid dissolution while adding NaOH

If you add all the NaOH at once, you may overshoot pH 8.0 — add NaOH in small increments as dissolution progresses.

---

**Q23. You measure the pH of your Tris buffer at pH 8.0 but after adding it to a PCR reaction, amplification fails. What buffer-related issues could explain this?**

Several buffer-related problems can cause PCR failure despite correct pH:
1. **EDTA contamination** (if TE buffer was used instead of plain Tris): EDTA chelates Mg²⁺ required by Taq polymerase — even 0.1 mM EDTA can inhibit PCR
2. **Salt carry-over**: If the Tris buffer was made with excessive NaCl or KCl (wrong recipe), high ionic strength inhibits Taq by interfering with primer-template hybridization
3. **Contaminating nucleases**: If buffer was not sterilized or was contaminated during preparation, nucleases degrade template
4. **CO₂-induced pH shift**: If the buffer was exposed to air for long periods before use, CO₂ absorption may have lowered pH below the range for Taq activity
5. **Incorrect Mg²⁺ concentration**: Using a PCR buffer without MgCl₂, or with incorrect MgCl₂ amount, is the most common cause — even the correct Tris at wrong Mg²⁺ causes failure
6. **Ethanol or phenol carry-over from DNA extraction** — inhibits Taq regardless of buffer composition

---

**Q24. Your Tris buffer has a white precipitate after storage for 2 weeks at 4°C. What could cause this?**

White precipitates in Tris buffer after cold storage have several possible causes:
1. **Calcium or magnesium phosphate precipitation**: If the water used contained Ca²⁺ or Mg²⁺ and phosphate was present (e.g., if the buffer was not prepared with properly deionized water), these can co-precipitate at low temperature
2. **Microbial growth**: If the buffer was not sterilized, white flocculent precipitate may be bacterial or fungal growth — inspect under microscope to confirm
3. **Buffer component crystallization**: At high Tris concentrations (>1 M), Tris may partially crystallize at 4°C if the solution is near saturation — warming restores dissolution
4. **EDTA sodium salt precipitation at low temperature**: Rare but possible at high EDTA concentrations in the presence of divalent metals

**Resolution:** Inspect the precipitate microscopically. If microbial, discard and prepare fresh using sterile technique. If crystalline (redissolves on warming to 25°C), the concentration may be too high for cold storage. If calcium phosphate, use higher-quality water (Milli-Q or equivalent) in future preparations.

---

**Q25. A student prepares Tris buffer by adjusting pH with NaOH instead of HCl when starting from Tris free base. Is this correct? What is the consequence?**

This is **incorrect**. Tris free base is already in the unprotonated (alkaline) form. Adding **NaOH** (a strong base) to Tris free base solution would further increase the pH, making the solution more alkaline — moving it away from the desired pH range. To prepare a buffer at pH 7.0–9.0 starting from Tris free base, you must add **HCl** (a strong acid), which protonates the Tris amine group (Tris + HCl → Tris-H⁺Cl⁻) and lowers the pH into the buffering range.

**Conversely**, if starting from **Tris-HCl** (the protonated salt), you would need to add **NaOH** to raise the pH into the buffering range. In practice, many molecular biology protocols use Tris-HCl salt as the starting material when preparing lower-pH Tris buffers (e.g., pH 6.8 for SDS-PAGE stacking gel buffer). Using the wrong acid/base is a classic beginner error that results in a solution with no buffering capacity or incorrect pH.

---

**Q26. What happens if you use tap water instead of distilled water to prepare Tris buffers for molecular biology?**

Tap water contains multiple contaminants that interfere with molecular biology applications:
1. **Divalent cations (Ca²⁺, Mg²⁺)**: Can alter effective EDTA concentration (excess cations saturate EDTA, leaving active nucleases) and affect enzyme activity
2. **Chloramines/chlorine**: Used in water treatment, these inhibit PCR polymerases and can oxidize nucleotides
3. **Heavy metals (Fe³⁺, Cu²⁺, Pb²⁺)**: Catalyze reactive oxygen species generation, degrading nucleic acids; also inhibit enzymes
4. **Dissolved organic matter**: Can interfere with spectrophotometric measurements (A₂₆₀ readings for DNA quantitation)
5. **Variable mineral content**: Makes buffer composition unpredictable and non-reproducible
6. **Microbial contamination**: Tap water is not sterile and may contain nuclease-producing bacteria

Molecular biology buffers must be prepared with **Milli-Q water (Type 1, resistivity ≥18.2 MΩ·cm)** or equivalent high-purity water. Using tap water is a fundamental error that invalidates all downstream experiments.

---

**Q27. You prepare a Tris buffer and later realize you used Tris-HCl (hydrochloride salt) instead of Tris free base. What are the consequences and how do you correct this?**

**Consequences:** Tris-HCl (protonated form, acidic) has an inherently lower pH in solution compared to Tris free base. Starting from Tris-HCl and adding HCl to adjust pH would drive the pH down further, not achieving a neutral/alkaline buffer. The solution may not reach the target pH of 7.5–9.0 by HCl addition at all, and adding excess HCl to "over-acidify and come back" is chemically wasteful and imprecise.

**Correction:** If you realized you used Tris-HCl and need pH 8.0, **adjust pH upward with NaOH** rather than downward with HCl. This is actually the correct approach when starting from Tris-HCl — add NaOH until the target pH is achieved. Alternatively, discard and restart with Tris free base. Note that using Tris-HCl + NaOH introduces Na⁺ and additional Cl⁻ into the buffer, which may be relevant for ionic-strength sensitive applications but is generally acceptable for most molecular biology uses.

---

### APPLICATIONS AND INTERPRETATION

---

**Q28. Compare the use of Tris-HCl, HEPES, and MOPS buffers in molecular biology. When would you choose each?**

| Feature | Tris-HCl | HEPES | MOPS |
|---|---|---|---|
| pKa at 25°C | 8.06 | 7.55 | 7.20 |
| Effective range | pH 7.0–9.0 | pH 6.8–8.2 | pH 6.5–7.9 |
| Temperature coefficient | −0.031 pH/°C | −0.014 pH/°C | −0.013 pH/°C |
| Metal chelation | None | None | None |
| Cell toxicity | Low (charged form) | Very low | Low |
| UV absorbance | None at 260/280 nm | Absorbs at 230 nm | Absorbs at 230 nm |
| Cost | Very low | High | Moderate |

**Choose Tris-HCl for:** DNA/RNA work (PCR, gel electrophoresis, storage), enzyme assays at pH 7.5–9.0, general laboratory buffers — low cost, well-characterized.
**Choose HEPES for:** Cell culture, cytotoxicity assays, enzyme kinetics at 37°C (lower temperature coefficient means less pH drift), any application requiring CO₂ stability.
**Choose MOPS for:** RNA gel electrophoresis (MOPS-formaldehyde gels for Northern blot), enzyme assays at pH 6.5–7.5 where Tris would have low capacity.

---

**Q29. What is the role of Tris buffer in SDS-PAGE? Explain the buffer compositions used in Laemmli system.**

The **Laemmli discontinuous SDS-PAGE system** uses Tris at two different pH values to create a stacking/resolving interface:

**Stacking gel buffer:** 0.5 M Tris-HCl, **pH 6.8**
**Resolving gel buffer:** 1.5 M Tris-HCl, **pH 8.8**
**Running buffer (tank buffer):** 25 mM Tris + 192 mM glycine + 0.1% SDS, **pH 8.3**

The **discontinuous pH system** creates a moving boundary: in the stacking gel at pH 6.8, glycine is mostly protonated (near its pKa 9.7, but at pH 6.8 it is nearly uncharged) and migrates slowly, while chloride ions from Tris-HCl migrate fast. SDS-protein complexes are sandwiched between these two ion fronts and stack into a sharp band. In the resolving gel at pH 8.8, glycine is more ionized and speeds up, breaking the stack and separating proteins by size. The specific Tris pH values in each layer are thus not arbitrary — they are precisely chosen to create the stacking/destacking ion boundary.

---

**Q30. Explain the preparation and use of Tris-glycine buffer for Western blot transfer.**

**Transfer buffer (Towbin buffer):**
> 25 mM Tris + 192 mM glycine + 20% methanol (± 0.1% SDS)
> pH approximately 8.3 (no pH adjustment needed)

**Preparation of 1 litre:**
- Tris base: 3.03 g (25 mM × 121.14 g/mol × 1 L)
- Glycine: 14.4 g (192 mM × 75.03 g/mol × 1 L)
- Methanol: 200 mL (20%)
- Make up to 1 litre with distilled water
- Mix well; pH should be ~8.3 without adjustment; check and record

**Role of each component:**
- **Tris-glycine:** Provides ionic conductivity for electrophoretic transfer; the same discontinuous system ensures protein remains SDS-bound and negatively charged
- **Methanol (20%):** Removes SDS from proteins (improves binding to nitrocellulose/PVDF membrane) but reduces transfer efficiency for large proteins; reduced to 10% or eliminated for proteins >100 kDa
- **SDS (optional 0.1%):** Improves transfer of large proteins by maintaining negative charge; reduces protein-membrane binding affinity so used only when transfer of large proteins is challenging

---

**Q31. What is the role of Tris buffer in restriction enzyme digestion? What Tris-based buffer is typically used?**

Most restriction enzyme reactions are performed in **1× CutSmart Buffer** (NEB) or similar proprietary buffers, which typically contain:
> 50 mM Potassium Acetate + 20 mM Tris-acetate + 10 mM Magnesium Acetate + 100 µg/mL BSA, pH 7.9 at 25°C

The Tris component:
- **Maintains pH at 7.9–8.0**: Optimal pH for most Type II restriction enzymes
- **Provides buffering capacity** to prevent pH drift during digestion (which releases H⁺ as phosphodiester bonds are hydrolyzed)

**MgCl₂ (or Mg-acetate)** is essential — Mg²⁺ is a cofactor for the endonuclease catalytic mechanism. EDTA must be completely absent (or < 0.01 mM) since it chelates Mg²⁺ and inhibits restriction enzymes. This is why DNA stored in TE buffer must be either diluted significantly (so EDTA concentration becomes negligible) or precipitated and resuspended in pure Tris buffer before restriction digestion.

---

**Q32. How is Tris buffer used in DNA extraction protocols? What concentration and pH are typically used?**

Tris buffer is used at multiple stages of DNA extraction:
1. **Cell lysis buffer**: 10 mM Tris-HCl (pH 8.0) + 100 mM NaCl + 10 mM EDTA + 0.5% SDS — Tris maintains alkaline pH that facilitates SDS-mediated lysis; EDTA inhibits DNases
2. **Resuspension of DNA pellet**: 10 mM Tris-HCl (pH 8.0) alone or as TE buffer — slightly alkaline pH prevents DNA depurination
3. **Wash buffers in column-based kits**: Typically Tris-based to maintain pH during silica column steps

**pH 8.0 is standard** for all DNA-related Tris buffers because:
- DNA is stable at slightly alkaline pH (depurination is acid-catalyzed)
- Most DNases have slightly reduced activity at pH 8.0
- The pH is optimal for Tris's buffering capacity (close to pKa 8.06)
- Slightly alkaline conditions help maintain DNA in the B-form double helix conformation

---

**Q33. What is the shelf life of Tris buffer and what are proper storage conditions?**

**Shelf life and storage guidelines:**

| Buffer | Storage | Shelf Life |
|---|---|---|
| 1 M Tris-HCl stock (sterile) | Room temperature | 12–18 months |
| TE buffer (sterile) | Room temperature or 4°C | 12 months |
| 50× TAE (non-sterile) | Room temperature | 6–12 months (check for microbial growth) |
| 10× TBE (non-sterile) | Room temperature | 6 months (borate can precipitate on long storage) |
| Working-dilution buffers | 4°C (sterile) | 1–3 months |

Signs of deterioration: pH drift (>0.1 pH units from target), turbidity, precipitate, color change, visible microbial growth. All buffers should be labeled with **preparation date, preparer, concentration, pH, and expiry date**. Opened buffers should be used within a shorter timeframe than unopened stocks.

---

**Q34. A student adds too much HCl while preparing Tris buffer and overshoots the target pH to 7.2 (target was 8.0). How can this be corrected?**

**If the overshoot is minor** (pH 7.8 instead of 8.0): Add dilute NaOH (0.1 M or 1 M) dropwise with stirring, monitoring pH until 8.0 is reached.

**If the overshoot is large** (pH 7.2, target 8.0): Several correction options exist:
1. **Add NaOH solution** (1 M or 0.1 M) dropwise with pH monitoring — this works but adds Na⁺ ions and increases total volume
2. **Add Tris free base solid** — Tris base raises pH directly by consuming H⁺, without adding extra ions; however, this changes the final concentration of Tris unless recalculated
3. **Start fresh** — for critical applications where ionic composition must be precise, discard and prepare a new batch

**Prevention:** Add HCl from a burette or in small measured increments (e.g., 0.5 mL at a time) with stirring and pH measurement between additions, slowing down as the target pH is approached. Use dilute HCl (1 M instead of 12 M) in the final stages for fine control.

---

**Q35. What is the ionic strength of a 50 mM Tris-HCl buffer at pH 8.0 and why does it matter?**

**Ionic strength (I)** is calculated as: **I = ½ Σ cᵢzᵢ²**

In 50 mM Tris-HCl buffer at pH 8.0, the Henderson-Hasselbalch equation shows that approximately 47% of Tris is in the Tris-H⁺ form (from calculation at pH 8.0 vs pKa 8.06). At 50 mM total Tris:
- [Tris-H⁺] ≈ 23.5 mM (z = +1) and [Cl⁻] ≈ 23.5 mM (z = −1)

I = ½ × [23.5×10⁻³ × 1² + 23.5×10⁻³ × 1²] = ½ × 0.047 ≈ **0.0235 mol/L (23.5 mM)**

Ionic strength matters because it affects:
- **Electrostatic interactions** in enzyme-substrate binding
- **DNA conformation** (B-form stability requires some ionic strength for counterion neutralization of phosphate groups)
- **Gel electrophoresis** migration rates (higher ionic strength slows migration and generates more heat)
- **Colligative properties** of the buffer

For PCR, moderate ionic strength (50–100 mM at 1× from a 10× stock) is optimal for primer-template hybridization specificity.

---

### ADVANCED / APPLICATION QUESTIONS

---

**Q36. Compare the preparation of Tris buffer using free base vs. Tris-HCl salt as starting material, in terms of the ions introduced.**

**Starting from Tris free base + HCl:**
Reaction: Tris-NH₂ + HCl → Tris-NH₃⁺ + Cl⁻
Ions introduced: Cl⁻ (from HCl), Tris-H⁺
At pH 8.0 in 50 mM Tris: ~47% Tris-H⁺ and ~53% Tris free base

**Starting from Tris-HCl + NaOH:**
Reaction: Tris-NH₃⁺Cl⁻ + NaOH → Tris-NH₂ + NaCl + H₂O
Ions introduced: Na⁺ and Cl⁻ (from NaOH neutralization, as NaCl is formed as a byproduct)

**Key difference:** Starting from Tris base + HCl introduces **only Cl⁻** as the counterion. Starting from Tris-HCl + NaOH introduces **both Na⁺ and Cl⁻** (as NaCl), increasing ionic strength. For most applications, this is negligible. For applications where Na⁺ must be controlled (e.g., Na⁺/K⁺-sensitive enzymes, electrophysiology studies, ion transport assays), starting from Tris free base with HCl is preferred.

---

**Q37. Explain how you would prepare a Tris buffer at pH 7.4 for use in a mammalian cell lysis experiment, accounting for temperature of use.**

Mammalian cell lysis is typically performed at **4°C** (on ice, to slow proteases and phosphatases). Given Tris ΔpKa/ΔT = −0.031 pH/°C:

At 4°C: pKa = 8.06 − (0.031 × (4 − 25)) = 8.06 + 0.65 = **8.71**

A buffer needed at pH 7.4 at 4°C must be prepared at room temperature (25°C) at:
pH_prep = 7.4 + (0.031 × (25 − 4)) = 7.4 + 0.65 = **pH 8.05 at 25°C**

**Preparation:**
1. Dissolve Tris free base in water at room temperature
2. Adjust pH to **8.05** at 25°C using concentrated HCl
3. Add other components (150 mM NaCl, protease inhibitors, EDTA)
4. Make to volume, verify pH at 25°C = 8.05
5. When used on ice at 4°C, actual pH will be approximately 7.4

This principle is critical for physiological cell biology experiments where protein-protein interactions depend on accurate pH control.

---

**Q38. What quality control tests should be performed on a freshly prepared Tris buffer before releasing it for use?**

A comprehensive **quality control (QC) checklist** for Tris buffer includes:

1. **pH verification**: Measure with a calibrated (two-point calibrated) pH meter; confirm within ±0.05 of target pH
2. **Concentration verification**: For concentrated stocks (0.5–1 M), verify by titration or conductivity measurement if precise concentration is critical
3. **Clarity and appearance**: Buffer should be clear and colorless; turbidity indicates precipitation or contamination
4. **Sterility check** (if autoclaved or filter-sterilized): Inoculate a small sample into thioglycolate broth; incubate 48 hours at 37°C; confirm no growth
5. **EDTA effectiveness test** (for TE buffer): Add exogenous DNase to DNA + TE; confirm DNA is protected on gel
6. **pH stability test**: Measure pH immediately after preparation and after 24 hours storage — drift >0.1 units suggests inadequate buffering capacity or CO₂ contamination
7. **Documentation**: Confirm label information is complete (name, pH, concentration, date, preparer, expiry)

Only after passing QC is the buffer labeled "APPROVED" and entered into the inventory system.

---

**Q39. What is the significance of the buffer in agarose gel electrophoresis and what happens if the buffer is depleted during a run?**

In agarose gel electrophoresis, the running buffer (TAE or TBE) serves multiple functions:
1. **Conductivity**: Carries electrical current from anode to cathode; without ions, no current flows and DNA does not migrate
2. **pH maintenance**: Maintains alkaline pH (8.3) that keeps DNA negatively charged (deprotonates phosphate groups)
3. **DNA stabilization**: Prevents denaturation of double-stranded DNA
4. **Joule heating absorption**: Buffer absorbs heat generated by current flow

**If buffer is depleted** (common in long TAE runs — TAE has lower buffering capacity and depletes faster than TBE):
- pH becomes extreme at one end of the tank (acidic at anode, alkaline at cathode) as H⁺ and OH⁻ accumulate
- DNA bands become distorted, diffuse, and "smile-shaped"
- Ethidium bromide fluorescence is reduced (pH-sensitive)
- At extreme pH, double-stranded DNA can denature (very alkaline) or undergo depurination (very acidic)
- Migration rate changes unpredictably, making size estimation from ladder inaccurate

**Prevention:** Recirculate buffer between electrode chambers during long runs; replace buffer every 2–3 hours for long electrophoresis runs using TAE.

---

**Q40. How is Tris used in the Tris-tricine SDS-PAGE system and how does it differ from the classic Laemmli system?**

The **Tris-Tricine system** (Schägger & von Jagow, 1987) was developed specifically for resolving **small proteins and peptides (1–30 kDa)** that run off a standard Laemmli gel.

**Composition differences:**

| Component | Laemmli (Tris-Glycine) | Tris-Tricine |
|---|---|---|
| Resolving gel buffer | 1.5 M Tris-HCl, pH 8.8 | 1.0 M Tris-HCl, pH 8.45 |
| Stacking gel buffer | 0.5 M Tris-HCl, pH 6.8 | 0.5 M Tris-HCl, pH 6.8 |
| Cathode (upper) tank buffer | Tris-Glycine + SDS | Tris-Tricine + SDS |
| Anode (lower) tank buffer | Same as cathode | Tris-HCl pH 8.9 (no Tricine) |
| Resolving pH | 8.8 | 8.45 |

Tricine (pKa 8.15) replaces glycine as the trailing ion. Tricine is smaller and has a lower pKa than glycine, creating sharper stacking conditions and better resolution of low-molecular-weight peptides. The lower pH (8.45 vs. 8.8) in the resolving gel also slows Tricine's mobility, maintaining better resolution. Tris plays the same role in both systems — providing the buffering environment and the leading/terminating ion in the discontinuous system.

---

**Q41. What is the role of Tris in the lysis buffer for plasmid DNA miniprep (alkaline lysis method)?**

The **alkaline lysis method** (Birnboim & Doly, 1979) uses three sequential solutions, of which Tris is critical in Solution I:

**Solution I (Resuspension buffer):**
> 50 mM Glucose + 25 mM Tris-HCl (pH 8.0) + 10 mM EDTA

Role of each component:
- **Tris-HCl (pH 8.0)**: Maintains alkaline pH to inhibit DNases and stabilize cell membranes; supports bacterial resuspension
- **EDTA**: Chelates Mg²⁺ in the outer membrane, weakening cell wall and inhibiting DNases
- **Glucose**: Maintains osmotic pressure of the bacterial suspension

**Solution II (Lysis):** 0.2 M NaOH + 1% SDS — no Tris (alkaline denaturation environment; Tris would provide unwanted buffering against the NaOH)

**Solution III (Neutralization):** 3 M Potassium Acetate, pH 4.8 — acid precipitates SDS-protein complexes and re-anneals plasmid (covalently closed circular = rapid renaturation); Tris is again absent here as acidic pH is needed

Tris is thus specifically used in Solution I where mild alkalinity and DNase inhibition are needed, and correctly excluded from Solutions II and III where extreme pH is essential for the technique to work.

---

**Q42. What precautions must be taken when preparing Tris buffer for RNA work?**

RNA is extremely susceptible to degradation by **RNases**, which are ubiquitous, thermostable, and highly active. Tris buffer for RNA work requires additional precautions beyond standard DNA buffer preparation:

1. **DEPC treatment**: Add **0.1% DEPC (diethyl pyrocarbonate)** to water, mix, and incubate at 37°C overnight; then autoclave (121°C, 20 min) to inactivate residual DEPC (which itself inhibits enzymes). DEPC chemically modifies and inactivates RNases
2. **DEPC-treated water** must be used for all solutions
3. **Gloves throughout**: Skin is a major RNase source
4. **Dedicated RNase-free glassware/plasticware**: Bake glassware at 180°C for 4+ hours; use disposable RNase-free plastics
5. **Sodium dodecyl sulfate (SDS)** can be added at 0.1–0.5% to buffer used for lysis to denature RNases
6. **Vanadyl ribonucleoside complexes** or **RNasin (RNase inhibitor protein)** may be added to Tris buffer used in RNA extraction

Note: **Tris cannot be DEPC-treated directly** (DEPC reacts with primary amines in Tris, inactivating DEPC and modifying Tris). Always treat the water with DEPC first, autoclave, then dissolve Tris base in this DEPC-treated water.

---

**Q43. Describe the preparation of 10× TBE buffer and explain why it should not be stored as a 10× concentrate for long periods.**

**For 1 litre of 10× TBE:**
- Tris base: 108 g (0.89 M; 0.89 mol × 121.14 g/mol)
- Boric acid: 55 g (0.89 M; 0.89 mol × 61.83 g/mol)
- 0.5 M EDTA (pH 8.0): 40 mL (to give 20 mM final)

**Procedure:** Dissolve Tris base and boric acid in ~900 mL water; add EDTA stock; make up to 1 litre; mix; check pH should be ~8.3 without adjustment.

**Why 10× TBE should not be stored long-term:**
At high concentration, **boric acid forms precipitates** with tris-borate complexes, particularly upon cooling or after prolonged storage. These precipitates form a white crystalline or gummy deposit that does not redissolve easily. The borate also **polymerizes** at high concentrations over time, changing its buffering properties. Best practice is to prepare **5× TBE** as the stock (less prone to precipitation) and use 0.5× working solution, or prepare fresh batches rather than storing large quantities of 10× TBE. If white crystals appear, the stock should be discarded.

---

**Q44. What is the effect of Tris buffer on Bradford and BCA protein assays?**

**Tris interference with protein assays:**
- **Bradford assay (Coomassie G-250):** Tris at concentrations > 100 mM can slightly interfere by interacting with Coomassie dye and altering the blue color shift. At standard molecular biology concentrations (10–50 mM), interference is minimal. High Tris (> 0.5 M) can cause a false positive shift.
- **BCA assay (Bicinchoninic acid):** Tris itself does not significantly interfere with BCA, but **reducing agents** often added to Tris-containing buffers (DTT, β-ME) do — they reduce Cu²⁺ independently of protein, causing false-positive elevation. Tris-buffered saline (TBS) is commonly used as a diluent for BCA standard curves.
- **Lowry assay:** Tris interferes significantly at concentrations >10 mM — phenol reagent turbidity is altered. Not suitable for Tris-containing samples.

Best practice: Always run **protein standard curves in the same buffer** as the sample (matrix matching) to account for any buffer-specific matrix effects on absorbance.

---

**Q45. What is the difference between Tris-HCl and Tris-acetate in terms of buffering properties and when would you choose Tris-acetate?**

**Tris-HCl:** Uses hydrochloric acid to protonate Tris; introduces Cl⁻ as counterion; chloride is metabolically inert and non-reactive in most molecular biology systems.

**Tris-acetate:** Uses acetic acid to protonate Tris; introduces CH₃COO⁻ (acetate) as counterion; acetate is a weaker acid (pKa 4.75) and contributes additional (though minor) buffering capacity at lower pH.

**Tris-acetate is preferred:**
1. In **TAE gel electrophoresis** — acetate migrates faster than chloride, reducing buffer depletion rate during electrophoresis
2. In **restriction enzyme buffers** (e.g., NEB CutSmart — 20 mM Tris-acetate, pH 7.9) — acetate is compatible with restriction enzyme activity and some manufacturers prefer it for buffer stability
3. Where **lower ionic strength** at the same Tris concentration is needed (acetate contributes slightly differently to ionic strength)
4. In **ion chromatography** where chloride would interfere with the column chemistry

In general, for DNA storage (TE buffer) and routine molecular work, Tris-HCl is preferred due to lower cost and simpler pH adjustment behavior.

---

**Q46. How would you verify that a Tris buffer is correctly prepared and at the correct concentration without a pH meter?**

Without a pH meter, several alternative verification methods can be used:

1. **pH paper (indicator strips):** Use narrow-range pH paper (e.g., pH 7.5–9.0 range) for approximate verification. Accuracy ±0.2–0.5 pH units — sufficient for qualitative confirmation but not for precise molecular biology work.
2. **pH indicators:** Add a few drops of a universal indicator or a specific indicator (e.g., thymol blue changes from yellow at pH 8.0 to blue at pH 9.6) — gives colorimetric estimate of pH.
3. **Titration (for concentration):** A known volume of the Tris buffer is titrated with a standardized HCl or NaOH solution to the neutralization point to confirm molar concentration.
4. **UV spectrophotometry:** Tris absorbs very weakly in the UV; not suitable for concentration verification.
5. **Conductivity measurement:** Buffer ionic conductivity correlates with ion concentration; a conductivity meter can be used to estimate concentration, though it requires a calibration curve for Tris-HCl.
6. **Functional test:** Use the buffer in a PCR or restriction digest reaction alongside a positive control prepared with verified buffer — identical results suggest comparable buffer quality.

In professional laboratory practice, a calibrated pH meter is mandatory — alternative methods are only acceptable for educational or emergency situations.

---

**Q47. What is the 'Good's buffer' concept and how do Tris and HEPES compare as molecular biology buffers in light of this concept?**

**Good's buffers** (Norman Good, 1966) are a set of zwitterionic buffering agents designed to overcome limitations of previously used buffers (phosphate, borate, Tris). The criteria Good specified for an ideal biological buffer include:
1. pKa between 6 and 8 (physiological range)
2. High water solubility
3. Minimal membrane permeability
4. Minimal interaction with biological molecules
5. Minimal effect on biochemical processes
6. Chemically stable
7. Minimal light absorption in UV/visible range
8. Easily prepared and inexpensive

**Tris** meets most criteria but falls short on two: its **large temperature coefficient** (−0.031 pH/°C) and **reactivity with some biological molecules** (its amine group can react with aldehydes like glutaraldehyde or glyoxylate) and it inhibits some metal-dependent enzymes by weakly chelating transition metals.

**HEPES** is a Good's buffer that meets all criteria more fully — lower temperature coefficient, zwitterionic (no free amine to react with aldehydes), stable, and no metal interaction. Despite this, **Tris remains dominant in molecular biology** due to its far lower cost, long historical use, and proven compatibility with nucleic acid applications.

---

**Q48. How does the presence of Tris buffer affect restriction enzyme digestion, and what concentration is optimal?**

Restriction enzymes perform optimally within specific buffer systems provided by manufacturers. The role of Tris in restriction digest buffers:

1. **pH maintenance**: Type II restriction enzymes typically require pH 7.5–8.0 for optimal activity; Tris provides this
2. **Concentration**: Typically **10–50 mM Tris** in 1× reaction buffer — higher concentrations are unnecessary and can slightly increase ionic strength above optimal for some enzymes
3. **Tris concentration from TE buffer**: If DNA stored in TE (10 mM Tris + 1 mM EDTA) is added directly to a restriction digest, and if the volume ratio of sample to total reaction is high (>10%), the EDTA from TE can reach inhibitory concentrations. EDTA at 0.1 mM inhibits most restriction enzymes. A general rule: add ≤1/10th reaction volume of DNA in TE, diluting EDTA to ≤0.1 mM

**Optimal protocol:** Use DNA resuspended in low-TE (10 mM Tris + 0.1 mM EDTA) or pure Tris buffer, add manufacturer's 10× enzyme buffer, and keep the reaction volume consistent to maintain all component concentrations within specified ranges.

---

**Q49. How would you prepare serial dilutions of a 1 M Tris-HCl stock to obtain 500 mM, 100 mM, 50 mM, 10 mM, and 1 mM working solutions, and which concentration is used in which common molecular biology application?**

**Serial dilutions from 1 M Tris-HCl stock** (using C₁V₁ = C₂V₂, preparing 100 mL each):

| Target | Volume of 1 M stock | Add water to |
|---|---|---|
| 500 mM | 50 mL | 100 mL |
| 100 mM | 10 mL | 100 mL |
| 50 mM | 5 mL | 100 mL |
| 10 mM | 1 mL | 100 mL |
| 1 mM | 0.1 mL (100 µL) | 100 mL |

**Application guide:**
- **1 M Tris (stock)**: Used to prepare working buffers; not used directly in reactions
- **500 mM**: Gel resolving/stacking buffer components (4× Laemmli buffers)
- **100 mM**: 10× PCR buffer component; enzyme reaction buffers
- **50 mM**: Enzyme assay buffers; DNA ligation buffer
- **10 mM**: TE buffer (standard DNA/RNA storage and dilution); elution from DNA columns
- **1 mM**: DNA storage when EDTA is omitted; sensitive assays where ionic strength must be minimized

---

**Q50. Design a complete protocol for preparing a molecular biology buffer kit (TE, TAE 50×, TBE 10×, 1 M Tris-HCl pH 7.5 and pH 8.0, 0.5 M EDTA pH 8.0) for a new molecular biology laboratory, including quality control and documentation requirements.**

**Complete Buffer Preparation Protocol:**

**Materials required:**
- Tris free base (MW 121.14 g/mol), disodium EDTA·2H₂O (MW 372.24), boric acid (MW 61.83), glacial acetic acid, concentrated HCl (12 M), NaOH pellets
- Analytical balance (0.001 g readability), calibrated pH meter with ATC, magnetic stirrer/hotplate
- DEPC-treated or autoclaved Milli-Q water (18.2 MΩ·cm)
- Volumetric flasks, autoclaved glass bottles with labels, 0.22 µm filter membranes

**Preparation Order (build from stock to working buffers):**

1. **0.5 M EDTA (pH 8.0)** — Prepare first (needed for TE, TAE, TBE): Dissolve 186.12 g Na₂EDTA·2H₂O in 900 mL water; add NaOH pellets slowly until pH 8.0 and EDTA fully dissolves; make to 1 L; autoclave.

2. **1 M Tris-HCl (pH 7.5)**: Dissolve 121.14 g Tris free base in 800 mL water; adjust pH to 7.5 with concentrated HCl; make to 1 L; filter-sterilize (0.22 µm).

3. **1 M Tris-HCl (pH 8.0)**: As above, adjust to pH 8.0; filter-sterilize.

4. **TE buffer**: Mix 10 mL of 1 M Tris (pH 8.0) + 2 mL of 0.5 M EDTA; make to 1 L; filter-sterilize.

5. **50× TAE**: Dissolve 242 g Tris + 57.1 mL glacial acetic acid + 100 mL 0.5 M EDTA; make to 1 L; store at RT.

6. **10× TBE**: Dissolve 108 g Tris + 55 g boric acid + 40 mL 0.5 M EDTA; make to 1 L; store at RT.

**Quality Control:**
- Measure pH of each buffer with calibrated pH meter (two-point calibrated); record measured vs. expected; accept if within ±0.05 pH units
- Visual inspection: clarity, colorless
- Sterility testing: inoculate thioglycolate broth with 0.1 mL; incubate 48 h at 37°C; confirm no growth
- **Functional test**: Run a standard agarose gel of 1 kb DNA ladder in prepared TAE/TBE; confirm expected band pattern and sharp resolution; verify TE protects DNA from DNase digestion

**Documentation:**
- Preparation logbook entry: date, preparer, lot numbers of all chemicals, volumes prepared, measured pH, QC results, expiry date
- Labels on all bottles: buffer name, concentration, pH, date prepared, expiry date, preparer's initials, "QC PASSED" stamp
- Retain one bottle per batch as **reference sample** until expiry
- File QC records in lab's buffer preparation master file with copy retained for 3 years minimum

---

*End of Section II: Preparation of Different Tris Buffers — 50 Questions & Answers*
*Masters Level | Molecular Biology Practical Viva Preparation*
