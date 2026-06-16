# Molecular Biology — Section V: Extraction of Plasmid DNA from Gram Negative Bacteria
## 50 Viva Questions with Detailed Answers (Masters Level)

---

### BASIC PRINCIPLES

---

**Q1. What is a plasmid and what are its essential structural features?**

A **plasmid** is an extrachromosomal, autonomously replicating, circular (usually) double-stranded DNA molecule found in bacteria and some eukaryotes. It exists independently of the chromosomal DNA and replicates using the host cell's replication machinery. Essential structural features include:

1. **Origin of replication (ori)**: The sequence at which replication initiates; determines copy number and host range. ColE1-type ori (in pUC, pBR322) gives high copy number (500–700 copies/cell); p15A ori gives low copy number (~15 copies/cell); RK2/RP4 ori gives broad host range.
2. **Selectable marker**: Usually an antibiotic resistance gene (ampicillin/bla, kanamycin/kan, chloramphenicol/cat) that allows selection of plasmid-containing cells on antibiotic-containing media
3. **Multiple cloning site (MCS)**: A polylinker region with multiple unique restriction enzyme sites for inserting foreign DNA (in cloning vectors)
4. **Promoter/terminator sequences**: For expression of cloned genes (in expression vectors)

Common laboratory plasmids: pUC19 (2.7 kb, high copy, AmpR), pBR322 (4.4 kb, low copy, AmpR+TetR), pET series (expression vectors, T7 promoter), pACYC184 (p15A ori, low copy, CmR+TetR).

---

**Q2. What are the different topological forms of plasmid DNA and how do they behave during extraction and electrophoresis?**

Plasmid DNA exists in three (or four) topological forms with distinct properties:

**Form I — Supercoiled (covalently closed circular, CCC):**
- Both strands intact, negative supercoils from DNA gyrase activity
- Most compact form — migrates fastest on agarose gel
- Highest purity/activity for cloning and transfection
- Buoyant density in CsCl-EtBr: slightly higher than linear (less EtBr intercalation due to torsional constraint)

**Form II — Relaxed circular (open circular, OC, nicked):**
- One strand nicked (single-strand break) — relaxes supercoiling
- Largest apparent size on gel — migrates slowest (large, floppy circle)
- Less efficient for transfection; indicates DNA damage during extraction

**Form III — Linear:**
- Both strands cut (double-strand break)
- Migrates between forms I and II on gel
- Results from restriction enzyme digestion or mechanical breakage

**Form IV — Supercoiled dimer (or higher oligomers):**
- Formed during replication errors
- Migrates slightly slower than monomeric supercoiled form

**On gel:** Form I (supercoiled) > Form III (linear) > Form II (OC) in migration speed, though the exact order depends on agarose percentage and running conditions. Form I can appear to migrate faster than expected because supercoiling compacts the molecule. This is why uncut plasmid on a gel shows multiple bands even from a pure preparation.

---

**Q3. What is the alkaline lysis principle that underlies plasmid DNA extraction from bacteria?**

**Alkaline lysis** (Birnboim & Doly, 1979) is the fundamental principle behind virtually all plasmid miniprep procedures. It exploits the difference in **denaturation and renaturation kinetics** between small circular plasmid DNA and large linear chromosomal DNA:

**Step 1 — Cell resuspension (Solution I):** Cells resuspended in glucose-Tris-EDTA buffer. EDTA chelates Mg²⁺, weakening the outer membrane and inhibiting DNases.

**Step 2 — Alkaline denaturation (Solution II — NaOH + SDS):** At pH 12–12.5 (0.2 M NaOH):
- SDS lyses cell membranes and denatures proteins
- NaOH denatures (unwinds) DNA by disrupting hydrogen bonds between base pairs
- Both chromosomal DNA (large, linear) AND plasmid DNA (small, circular) are denatured to single-stranded form
- Proteins precipitate as SDS-protein complexes

**Step 3 — Neutralization (Solution III — potassium acetate, pH 4.8):** Upon rapid neutralization with acidic potassium acetate:
- **Plasmid DNA**: The two complementary strands of the small circular plasmid rapidly find each other (due to their topological proximity — covalently linked) and re-anneal correctly → soluble, renatured plasmid remains in solution
- **Chromosomal DNA**: The large linear fragments cannot find complementary strands quickly enough and instead form an insoluble tangled aggregate → precipitates
- SDS-protein complexes: K⁺ + SDS forms **potassium dodecyl sulfate**, which is insoluble and precipitates together with chromosomal DNA

The precipitate (chromosomal DNA + protein-SDS + cell debris) is removed by centrifugation, leaving purified plasmid DNA in the supernatant.

---

**Q4. Why does the alkaline lysis method selectively recover plasmid DNA over chromosomal DNA? What is the critical factor?**

The **critical factor** is the **topological difference between covalently closed circular plasmid DNA and linear chromosomal DNA**:

- **Plasmid DNA**: The two strands are covalently linked (joined at both ends of the circular molecule). Even after complete denaturation under alkaline conditions, the two strands cannot fully separate — they remain **topologically interlocked** (like two interlocked rings). Upon neutralization, the complementary sequences of the two strands are held in close proximity by their covalent connectivity, facilitating rapid and correct re-annealing.

- **Chromosomal DNA**: The large chromosomal fragments are linear (or effectively so after shearing during extraction). Upon denaturation, the complementary strands fully separate. During rapid neutralization (rapid mixing step), these long single-stranded molecules cannot find their specific complementary partners and instead form non-specific interstrand hydrogen bonds — creating a **tangled aggregate** that co-precipitates with SDS-protein complex.

**Critical technical requirement:** Neutralization must be **rapid and gentle** (gentle inversion, not vortexing). If vortexed, mechanical shearing of chromosomal DNA into small fragments prevents complete co-precipitation, leading to chromosomal DNA contamination of the plasmid preparation.

---

**Q5. What is the copy number of a plasmid and how does it affect the yield of plasmid DNA extraction?**

**Plasmid copy number** refers to the average number of plasmid molecules per bacterial cell. It is determined primarily by the **origin of replication (ori)** and the replication control mechanism:

| Plasmid/ori Type | Copy Number | Example Plasmids |
|---|---|---|
| High copy (ColE1/pMB1) | 500–700 | pUC19, pUC18, pGEM |
| Medium copy (ColE1 relaxed) | 15–20 | pBR322 |
| Low copy (p15A) | 10–15 | pACYC184, pACYC177 |
| Very low copy (F factor, RK2) | 1–5 | pBAC, pFOS |
| Amplifiable (ColE1 + chloramphenicol) | Up to 3000 | pUC with CmAmp |

**Effect on yield:**
- From 1 mL overnight *E. coli* culture (OD₆₀₀ ~4, ~3.2×10⁹ cells):
  - High copy pUC19: ~3.2×10⁹ × 700 × 2.7 kb × 660 Da/bp ÷ (6.022×10²³) ≈ **~3.4 µg plasmid/mL** (practical yield ~1–3 µg/mL)
  - Low copy pBR322: ~3.2×10⁹ × 20 × 4.4 kb × 660 Da/bp ÷ (6.022×10²³) ≈ **~0.077 µg/mL** (practical yield ~0.05–0.1 µg/mL)

High copy number plasmids are therefore preferred for cloning vectors, while low-copy vectors are used when overexpression of a gene product would be toxic or when copy number must be controlled.

---

### PROCEDURE

---

**Q6. Describe the complete alkaline lysis miniprep procedure (classical method) for extracting plasmid DNA from *E. coli*.**

**Materials:** Solution I (50 mM glucose, 25 mM Tris-HCl pH 8.0, 10 mM EDTA), Solution II (0.2 M NaOH, 1% SDS — freshly prepared), Solution III (3 M potassium acetate, 11.5% glacial acetic acid, pH 4.8), isopropanol, 70% ethanol, TE buffer.

**Procedure:**
1. **Culture**: Inoculate 5 mL LB + appropriate antibiotic; grow overnight at 37°C, 200 rpm
2. **Harvest**: Transfer 1.5 mL to microcentrifuge tube; centrifuge 12,000 × g, 1 min; discard supernatant; repeat to pellet cells from remaining culture if higher yield needed
3. **Resuspend (Solution I)**: Add 100 µL ice-cold Solution I; vortex to fully resuspend pellet (no clumps)
4. **Lyse (Solution II)**: Add 200 µL freshly prepared Solution II; mix by **gentle inversion 5–6 times** (do NOT vortex); solution becomes clear and viscous (SDS lysis); incubate at room temperature ≤5 minutes
5. **Neutralize (Solution III)**: Add 150 µL ice-cold Solution III; mix immediately by **gentle inversion** until white precipitate forms uniformly; incubate on ice 5 minutes
6. **Centrifuge**: 12,000 × g, 10 minutes; transfer supernatant to fresh tube (avoid disturbing white precipitate)
7. **Optional PCI extraction**: Add equal volume of phenol:chloroform:isoamyl alcohol (25:24:1); mix; centrifuge; transfer aqueous phase (removes protein contamination for higher purity)
8. **Precipitate DNA**: Add 0.9 volumes isopropanol to supernatant; mix; centrifuge 12,000 × g, 10 min; discard supernatant
9. **Wash**: Add 500 µL 70% ethanol; centrifuge 12,000 × g, 5 min; remove supernatant completely
10. **Dry**: Air-dry pellet 5–10 min; resuspend in 50 µL TE buffer or nuclease-free water
11. **RNase treatment**: If needed, add RNase A (20 µg/mL final); incubate 37°C 30 min
12. **Store** at −20°C

---

**Q7. What are Solutions I, II, and III in the alkaline lysis protocol? Explain the precise role of each component.**

**Solution I (Resuspension buffer):**
- **50 mM Glucose**: Maintains osmotic pressure around bacteria before lysis — prevents premature lysis and helps maintain cell integrity during resuspension
- **25 mM Tris-HCl (pH 8.0)**: Buffers the solution at slightly alkaline pH; maintains pH stability during EDTA action
- **10 mM EDTA**: Chelates Mg²⁺ — destabilizes the outer membrane (Gram-negatives) and inhibits DNases; begins permeabilization

**Solution II (Lysis buffer — MUST be freshly prepared):**
- **0.2 M NaOH**: Strong base that raises pH to ~12.5 — denatures DNA (disrupts hydrogen bonds) and denatures/precipitates proteins; must be fresh (CO₂ from air neutralizes NaOH over time)
- **1% SDS (sodium dodecyl sulfate)**: Anionic detergent that lyses cell membranes and denatures proteins; the SDS-protein complex will precipitate in Solution III

**Solution III (Neutralization buffer):**
- **3 M Potassium acetate**: K⁺ specifically reacts with SDS (forms insoluble KDS — potassium dodecyl sulfate) causing SDS-protein-chromosomal DNA to precipitate; acetate drops the pH to 4.8 neutralizing NaOH and promoting DNA renaturation
- **Acetic acid (glacial)**: Provides the acidic pH (4.8) for neutralization — carefully balanced so that pH drops to exactly the point where chromosomal DNA precipitates but plasmid reanneals
- pH 4.8 is critical: too high → incomplete precipitation; too low → plasmid DNA may also precipitate or degrade

---

**Q8. Why must Solution II be prepared fresh each time and not stored?**

Solution II contains **0.2 M NaOH**, which is highly reactive with atmospheric CO₂:
> CO₂ + 2NaOH → Na₂CO₃ + H₂O

Over time, absorbed CO₂ converts NaOH to sodium carbonate, **lowering the pH** of Solution II below the critical pH 12–12.5 needed for complete DNA denaturation. If the pH is insufficient:
- Chromosomal DNA may not fully denature → incomplete denaturation → chromosomal DNA contamination in the final plasmid preparation
- Proteins may not fully precipitate in Solution III → lower purity plasmid

**Additionally:** SDS in Solution II can partially hydrolyze over time at alkaline pH, reducing its lytic effectiveness.

**Practical rule:** Prepare Solution II fresh by mixing **equal volumes of 0.4 M NaOH and 2% SDS** immediately before use. Stored solutions degrade within hours of preparation if not sealed tightly. Some protocols add a phenol red indicator — if Solution II has turned yellow (acidic), it has absorbed CO₂ and must be discarded.

---

**Q9. What is the role of glucose in Solution I of the alkaline lysis protocol? Can it be replaced?**

**Glucose (50 mM)** in Solution I serves as an **osmotic stabilizer** — it maintains the osmotic pressure around the bacteria before and during the early stages of lysis, preventing cells from lysing prematurely due to osmotic shock when transferred from the culture medium to the resuspension buffer. If bacteria lyse prematurely (before the controlled alkaline lysis step), chromosomal DNA is released in an uncontrolled manner and cannot be selectively precipitated in Step 3.

**Can it be replaced?** Yes — glucose is not chemically essential for the alkaline lysis mechanism. It can be replaced with:
- **Sucrose (8–10%)**: More effective osmotic stabilizer, used in some protocols
- **No glucose**: In many commercial kit formulations, glucose is omitted and replaced with higher EDTA concentrations or different osmotic agents

In practice, glucose in Solution I makes minimal difference for laboratory strains of *E. coli* when the resuspension is done gently. It becomes more important when working with organisms that have fragile membranes or when large cell pellets (from >5 mL culture) are resuspended, as the osmotic change would otherwise be more abrupt.

---

**Q10. Describe the commercial spin-column miniprep procedure and compare it to the classical alkaline lysis method.**

**Commercial spin-column miniprep (e.g., Qiagen QIAprep Spin Miniprep):**

**Procedure:**
1. Harvest 1.5–5 mL overnight culture; centrifuge; discard supernatant
2. Resuspend in Buffer P1 (50 mM Tris-HCl pH 8.0, 10 mM EDTA, 100 µg/mL RNase A)
3. Lyse with Buffer P2 (200 mM NaOH, 1% SDS); mix by inversion; incubate ≤5 min
4. Neutralize with Buffer N3 (3 M potassium acetate pH 5.5 + chaotropic salt); mix by inversion; centrifuge 10 min
5. Load supernatant onto silica spin column; centrifuge → plasmid DNA binds silica membrane in high chaotropic salt + slightly acidic conditions
6. Wash with Buffer PE (ethanol-containing wash buffer) × 2 — removes salts, proteins, SDS
7. Elute: Add 50 µL Buffer EB (10 mM Tris-HCl pH 8.5) or water; incubate 1 min; centrifuge → plasmid DNA elutes

**Comparison:**

| Feature | Classical Alkaline Lysis | Commercial Spin Column |
|---|---|---|
| Time | 1.5–2 hours | 30–45 minutes |
| Purity (A260/A280) | 1.5–1.8 (variable) | 1.8–2.0 (consistent) |
| RNA removal | Requires separate RNase step | RNase in Buffer P1 (included) |
| Hazardous reagents | PCI optional (phenol, chloroform) | None |
| Yield | ~2–5 µg from 1 mL culture | ~3–5 µg from 1.5–3 mL |
| Throughput | Low (manual) | Medium-high (96-well format available) |
| Cost | Very low | Higher |
| Batch-to-batch reproducibility | Variable | High |

---

**Q11. What is a midiprep and a maxiprep? When are they used and how do they differ from a miniprep?**

**Scale comparison:**

| Parameter | Miniprep | Midiprep | Maxiprep |
|---|---|---|---|
| Culture volume | 1–5 mL | 25–100 mL | 100–500 mL |
| Expected yield | 3–20 µg | 50–200 µg | 500–2500 µg |
| Time | 30–45 min | 1–2 hours | 2–3 hours |
| Typical use | Screening clones, small-scale work | Transfection (small-scale), sequencing | Large-scale cloning, virus production, animal injection |
| Column type | Small silica column | Medium anion-exchange column | Large anion-exchange column |
| Purity | Good | Excellent | Excellent (endotoxin-free option) |

**Midiprep/Maxiprep principle (anion-exchange chromatography):**
Unlike minipreps that use silica columns (hydrophobic/chaotropic interaction), midi/maxiprep kits (e.g., Qiagen HiSpeed Midiprep) use **anion-exchange resin (DEAE-based)**:
- Plasmid DNA (negatively charged phosphate backbone) binds positively charged DEAE resin under low-salt conditions
- Contaminants (RNA, proteins, LPS) wash off with medium salt buffer
- Plasmid DNA elutes with high-salt buffer (1.25 M NaCl)
- DNA is then isopropanol-precipitated and washed

Anion-exchange maxipreps yield **endotoxin-reduced** (but not endotoxin-free) DNA. For **mammalian cell transfection or animal experiments**, endotoxin-free maxiprep kits (Qiagen EndoFree Plasmid Maxi Kit) use an additional detergent extraction step to remove residual endotoxin to <0.1 EU/µg.

---

**Q12. What is the composition of the TE buffer used for final resuspension of plasmid DNA, and why is it preferred over water?**

**TE buffer:** 10 mM Tris-HCl (pH 8.0) + 1 mM EDTA

**Why TE over water:**
1. **pH stability**: Tris-HCl at pH 8.0 maintains a slightly alkaline environment; pure water exposed to air absorbs CO₂ forming carbonic acid (pH drops to ~5.6); acid pH accelerates **depurination** of DNA (hydrolysis of purine-N-glycosidic bonds, particularly at adenine and guanine), causing strand breaks
2. **DNase inhibition**: EDTA at 1 mM chelates Mg²⁺ required by any contaminating DNases, protecting stored plasmid from enzymatic degradation
3. **DNA solubility**: Tris provides a mild ionic environment that maintains DNA in solution and prevents aggregation

**When water is preferred over TE:**
- **Downstream applications sensitive to EDTA**: PCR (EDTA chelates Mg²⁺ needed by Taq), restriction enzyme digestion (Mg²⁺ required), in vitro transcription — plasmid resuspended in water or low-TE (0.1 mM EDTA) avoids EDTA inhibition when used in these reactions
- **Sequencing**: Many sequencing facilities prefer DNA in water or 10 mM Tris (no EDTA) because EDTA can affect the sequencing reaction

For long-term storage (>3 months), TE is superior. For immediate use in enzymatic reactions, water or low-TE is preferred.

---

**Q13. How is the alkaline lysis procedure modified for low-copy-number plasmids?**

Low-copy plasmids (pBR322, pACYC series, BAC vectors — 1–20 copies/cell) yield far less plasmid per extraction than high-copy vectors. Standard miniprep from 1 mL culture may yield only 50–200 ng — insufficient for most applications.

**Modifications to maximize yield from low-copy plasmids:**

1. **Larger culture volume**: Use 10–50 mL overnight culture instead of 1.5 mL; perform a midiprep or maxiprep scale extraction
2. **Chloramphenicol amplification**: For ColE1-based low-copy plasmids — add **chloramphenicol (170 µg/mL)** to exponentially growing culture; incubate 12–16 hours. Chloramphenicol inhibits protein synthesis (translation), blocking chromosome replication (requires new protein synthesis to initiate replication at oriC) while plasmid replication (ColE1 replication requires only RNA synthesis) continues — plasmid copy number increases 3–10× (up to ~1000 copies/cell). Note: This amplification trick does NOT work for p15A-based plasmids (their replication is also protein-dependent).
3. **Optimized lysis**: Increase volumes of Solutions I, II, III proportionally to the larger cell pellet
4. **Multiple elutions**: For column-based methods, elute twice with warm buffer (65°C improves elution efficiency)
5. **Grow at 30°C** (for some low-copy systems): Lower temperature can increase plasmid stability and copy number in some strains

---

**Q14. What is RNase A and why is it included in many plasmid extraction protocols?**

**RNase A (bovine pancreatic ribonuclease A)** is a single-strand-specific RNA endonuclease (EC 3.1.27.5) that cleaves RNA at pyrimidine (C and U) residues, producing 3'-pyrimidine nucleotide residues. It is active across a wide range of pH (4.5–9.5) and salt conditions, and requires no metal cofactors (thus not inhibited by EDTA).

**Why included in plasmid extraction:**
- After alkaline lysis, the cleared lysate contains both plasmid DNA and RNA (predominantly rRNA from ribosomes)
- RNA has A₂₆₀ absorbance — its presence causes **overestimation** of plasmid DNA concentration by spectrophotometry
- RNA appears as a smear at the bottom of agarose gels, obscuring the plasmid bands and making quantitative assessment difficult
- RNA can interfere with some downstream applications (ligation, transfection, quantitative PCR)

**Implementation:**
- **Buffer P1 (commercial kits)**: RNase A (100 µg/mL) included in resuspension buffer — RNA is degraded during the lysis/neutralization steps
- **Classical miniprep**: RNase A added to the cleared lysate (20 µg/mL) after neutralization, before precipitation; incubate 37°C 30 min; then precipitate DNA
- Alternatively, treat resuspended final plasmid pellet with RNase A

After RNase A treatment, the RNA is fragmented to oligoribonucleotides and mononucleotides, which wash away during the ethanol wash step or elute separately from the silica column under the high-salt wash conditions.

---

**Q15. How do you prepare competent *E. coli* cells and why is this relevant to plasmid extraction?**

Competent cells are bacteria capable of taking up exogenous DNA. Their preparation is directly linked to plasmid extraction because plasmid DNA produced by extraction is used for:
1. **Retransformation** after cloning (confirming insert)
2. **Expression** in a different host strain
3. **Library propagation**

**Chemical competent cells (CaCl₂ method):**
1. Inoculate 100 mL LB with 1 mL overnight culture; grow at 37°C to OD₆₀₀ = 0.4–0.5
2. Chill on ice 10 min; centrifuge 4,000 × g, 10 min at 4°C
3. Resuspend in 50 mL ice-cold 0.1 M CaCl₂; incubate on ice 30 min
4. Centrifuge; resuspend in 5 mL ice-cold 0.1 M CaCl₂ + 15% glycerol
5. Aliquot 100 µL; flash-freeze in liquid nitrogen; store at −80°C

**Transformation efficiency test:** Transform 1 ng of plasmid DNA; plate on selective media; count colonies; calculate CFU/µg DNA. High-efficiency chemical competent cells: 10⁷–10⁸ CFU/µg. Electroporation-competent cells: 10⁹–10¹⁰ CFU/µg.

**Relevance to plasmid extraction quality:** Impure plasmid (contaminated with SDS, ethanol, or salts) significantly reduces transformation efficiency. A₂₆₀/A₂₈₀ = 1.8–2.0 and A₂₆₀/A₂₃₀ ≥ 2.0 are required for high-efficiency transformation. LPS contamination reduces transformation efficiency in some strains.

---

### CALCULATIONS

---

**Q16. Calculate how much Solution I, II, and III to use when processing 3 mL of overnight culture instead of the standard 1.5 mL.**

Standard miniprep volumes (for 1.5 mL culture):
- Solution I: 100 µL
- Solution II: 200 µL
- Solution III: 150 µL

**Scale factor** for 3 mL culture = 3.0 mL / 1.5 mL = **2×**

Scaled volumes:
- Solution I: 100 × 2 = **200 µL**
- Solution II: 200 × 2 = **400 µL**
- Solution III: 150 × 2 = **300 µL**

**Note:** The ratio of Solution I : II : III must always be maintained at **2 : 4 : 3** (proportional to 100:200:150). If this ratio is not maintained, lysis or neutralization will be incomplete. For volumes larger than 5 mL equivalent, switch to a midiprep protocol rather than simply scaling up miniprep volumes, as very large volumes of precipitate become difficult to pellet effectively in a microcentrifuge.

---

**Q17. A plasmid miniprep gives A₂₆₀ = 0.38 (undiluted in NanoDrop). Calculate concentration, total yield in 50 µL elution volume, and molar concentration of plasmid molecules (plasmid is pUC19, 2.7 kb).**

**Concentration:**
Using NanoDrop (A₂₆₀ × 50 µg/mL for dsDNA):
Concentration = 0.38 × 50 = **19 µg/mL = 19 ng/µL**

**Total yield:**
Total DNA = 19 ng/µL × 50 µL = **950 ng = ~1 µg**

This is slightly below average for pUC19 from 1.5 mL culture (expected 3–5 µg). Yield may be improved by using more culture volume or optimizing lysis.

**Molar concentration of plasmid molecules:**
MW of pUC19 = 2,700 bp × 660 Da/bp = 1.782 × 10⁶ Da = 1.782 × 10⁶ g/mol

Concentration = 19 µg/mL = 19 × 10⁻⁶ g/mL

Molar concentration = (19 × 10⁻⁶ g/mL) / (1.782 × 10⁶ g/mol)
= 1.066 × 10⁻¹¹ mol/mL
= **10.66 nM**

**Molecules per µL:**
= 10.66 × 10⁻⁹ mol/L × 6.022 × 10²³ molecules/mol × 10⁻³ L/mL × 10⁻³ mL/µL
= **6.42 × 10⁹ molecules/µL**

---

**Q18. How much plasmid DNA do you need for a restriction enzyme digestion to produce bands visible on an agarose gel, and how do you dilute your miniprep stock to achieve this?**

**For restriction digest and gel visualization:**
- Minimum needed per gel lane: **200–500 ng** (with ethidium bromide staining)
- With SYBR Safe or GelRed: **50–200 ng** is sufficient
- Standard digest: **500 ng – 1 µg** in 20 µL reaction volume

**Using the miniprep stock from Q17 (19 ng/µL):**
To digest 500 ng in a 20 µL reaction:

Volume of plasmid stock = 500 ng ÷ 19 ng/µL = **26.3 µL** — this exceeds the reaction volume!

The stock must be **concentrated** (speed-vac or repeat ethanol precipitation to resuspend in smaller volume) OR use a larger reaction volume (50 µL) OR:

Volume in 50 µL reaction = 500 ng ÷ 19 ng/µL = **26.3 µL plasmid**
Add: 5 µL 10× buffer + 1 µL enzyme + 17.7 µL water = 50 µL total ✓

**Or concentrate first:**
If resuspended in 30 µL instead of 50 µL: New concentration = 950 ng / 30 µL = 31.7 ng/µL; Volume needed = 500 ng ÷ 31.7 = 15.8 µL ✓ (feasible in 20 µL reaction)

---

**Q19. Calculate the expected plasmid yield from 50 mL of *E. coli* culture carrying pUC19 (2.7 kb, 500 copies/cell) at OD₆₀₀ = 3.0.**

**Step 1 — Cell number:**
OD₆₀₀ = 3.0 → ~2.4 × 10⁹ cells/mL (approx. 8×10⁸/OD unit × 3)
Total cells in 50 mL = 2.4×10⁹ × 50 = **1.2 × 10¹¹ cells**

**Step 2 — Plasmid molecules:**
Plasmid copies/cell = 500 (high copy pUC19 in stationary phase, overestimate slightly)
Total plasmid molecules = 1.2×10¹¹ × 500 = **6.0 × 10¹³ molecules**

**Step 3 — Mass of plasmid:**
MW of pUC19 = 2,700 bp × 660 Da/bp = 1.782 × 10⁶ g/mol
Mass = (6.0×10¹³ molecules) / (6.022×10²³ molecules/mol) × 1.782×10⁶ g/mol
= 9.95×10⁻¹¹ × 1.782×10⁶ = **1.77×10⁻⁴ g = 177 µg (theoretical)**

**Step 4 — Practical yield (50–60% recovery):**
Expected yield = 177 × 0.55 = **~97 µg** (approximately 100 µg from midiprep)

This is a reasonable midiprep yield — confirms that a midiprep from 50 mL high-copy plasmid culture can yield approximately 50–200 µg, consistent with manufacturer claims.

---

**Q20. A restriction enzyme digest of plasmid DNA produces fragment sizes of 3.2 kb and 1.5 kb when cut with EcoRI. What is the approximate size of the original plasmid and what does this tell you about the cloning?**

**Plasmid size:**
When a plasmid is linearized or cut into fragments by restriction enzymes, the sum of all fragment sizes equals the total plasmid size.

Plasmid size = 3.2 kb + 1.5 kb = **4.7 kb**

**Interpretation:**
- If the vector used was, for example, **pUC19 (2.7 kb)** with a 2.0 kb insert cloned at the EcoRI site, the expected fragments after EcoRI digestion would be: vector = 2.7 kb and insert = 2.0 kb → total = 4.7 kb. However, this gives 2.7 + 2.0, not 3.2 + 1.5.
- The pattern 3.2 + 1.5 could indicate: a 3.2 kb vector with a 1.5 kb insert at a single EcoRI site, OR a 4.7 kb plasmid with internal EcoRI sites
- **If EcoRI cuts once** → one linear fragment of 4.7 kb (confirms plasmid size; single EcoRI site used for cloning)
- **If EcoRI cuts twice** → two fragments (3.2 + 1.5 = 4.7 kb total); could mean a 3.2 kb vector backbone (with RE sites flanking MCS) and 1.5 kb insert
- Single-enzyme double digestion pattern confirms insert has been successfully cloned when compared to the expected size of vector + insert from the cloning design

---

### TROUBLESHOOTING

---

**Q21. After alkaline lysis miniprep, the agarose gel shows no plasmid bands but a diffuse smear. What went wrong?**

A diffuse smear with no discrete plasmid bands indicates one of several problems:

1. **Alkaline denaturation of plasmid (over-lysis):** If Solution II incubation exceeded 5 minutes, or NaOH was too concentrated, the plasmid itself denatured irreversibly — alkali at pH >12.5 for >5 min causes irreversible denaturation of the covalently closed circular DNA, which cannot re-anneal upon neutralization and precipitates or degrades. Check NaOH concentration (must be exactly 0.2 M); limit incubation to ≤5 min.

2. **No plasmid in bacteria:** Culture may have lost the plasmid (plasmid curing) or was grown without antibiotic selection, allowing non-plasmid cells to outgrow. Verify by plating on selective media; grow next culture WITH antibiotic.

3. **DNA degradation by DNase:** DNases from improperly prepared reagents (non-sterile, no EDTA) degrade plasmid during extraction. Ensure all solutions contain EDTA; autoclave or filter-sterilize reagents.

4. **Chromosomal DNA contamination:** If neutralization was incomplete or vortexed, chromosomal DNA fragments contaminate the preparation and appear as a high-MW smear. This doesn't produce a smear at the plasmid size range but rather a smear at the top of the gel.

5. **RNA smear only:** If what appears is a smear at the bottom of the gel (low MW), it is RNA contamination, not degraded plasmid — add RNase A treatment.

---

**Q22. The plasmid preparation appears pure by spectrophotometry (A₂₆₀/A₂₈₀ = 1.85) but restriction enzyme digestion is incomplete or fails. What could be responsible?**

Complete restriction enzyme digestion failure despite spectrophotometrically pure plasmid suggests **enzyme inhibitors** or **suboptimal conditions**:

1. **EDTA inhibition:** If EDTA concentration in the plasmid TE buffer is >1 mM and contributes significantly to the reaction's EDTA total (e.g., plasmid resuspended in high-EDTA buffer), the Mg²⁺ required by restriction enzymes is chelated → enzyme fails. Solution: Resuspend plasmid in low-TE (0.1 mM EDTA) or pure water; or use a larger reaction volume to dilute EDTA below inhibitory level (<0.5 mM).

2. **SDS contamination:** Trace SDS from lysis step (incomplete ethanol wash) inhibits restriction enzymes even at very low concentrations (> 0.01%). Perform additional 70% ethanol washes.

3. **Ethanol residue:** Incompletely dried plasmid pellet retains ethanol → inhibits restriction enzymes and shifts ionic conditions. Allow pellet to air-dry completely (10–15 min) or speed-vac briefly before resuspension.

4. **Salt contamination:** Excess salt from isopropanol/ethanol precipitation (if sodium acetate was too concentrated or carry-over from Solution III) can inhibit restriction enzymes. Perform additional wash with 70% ethanol.

5. **Plasmid methylation:** Bacterial *dam* (GATC) or *dcm* (CCWGG) methylase activity methylates specific sequences → certain restriction enzymes cannot cleave methylated sites. Use dam⁻/dcm⁻ strains or enzymes insensitive to methylation.

---

**Q23. After miniprep, the A₂₆₀/A₂₈₀ ratio is 1.6. What is the likely contaminant and how do you improve purity?**

**A₂₆₀/A₂₈₀ = 1.6** indicates **protein contamination** (proteins absorb at 280 nm due to aromatic amino acid residues). For plasmid minipreps, protein contamination most commonly comes from:
- Incomplete removal of SDS-protein precipitate (disrupted precipitate during supernatant transfer)
- Insufficient washing of the silica column (in kit-based protocols)
- Omission or insufficient phenol-chloroform extraction (in classical protocols)

**Remedies:**
1. **Re-extract with PCI**: Add equal volume phenol:chloroform:isoamyl alcohol (25:24:1) to plasmid solution; mix gently; centrifuge; transfer aqueous phase; re-precipitate with ethanol
2. **Additional column wash**: If using a kit, add an extra PE wash buffer step and allow column to dry completely (centrifuge 2 min at maximum speed without buffer to remove residual ethanol)
3. **Repeat neutralization centrifugation**: If the Problem was incomplete precipitation of protein, re-centrifuge the cleared lysate for longer (15 min instead of 10 min) before loading the column
4. **Better supernatant transfer**: In classical miniprep, use a narrower tip to carefully transfer supernatant without disturbing the white precipitate

After cleanup: Expected A₂₆₀/A₂₈₀ = 1.8–2.0

---

**Q24. After miniprep, gel electrophoresis shows three bands for a supposedly pure plasmid preparation. Explain all possible causes.**

**Three bands for a single plasmid** preparation is actually **normal and expected** if the plasmid preparation contains a mixture of topological forms:

- **Band 1 (fastest migrating, lowest position)**: Supercoiled (Form I, CCC) — the desired form; most compact; migrates fastest
- **Band 2 (middle position)**: Linear (Form III) — from restriction enzyme contamination or double-strand nicking during extraction; migrates at position corresponding to linearized plasmid size
- **Band 3 (slowest migrating, highest position)**: Open circular/relaxed (Form II, OC) — nicked plasmid from DNase or mechanical stress; migrates slowest

**Other explanations for three bands:**
1. **Supercoiled monomer + supercoiled dimer + OC monomer**: Dimer forms during replication errors and migrates slightly slower than monomeric supercoiled form; at high yield, dimers are visible
2. **Two different plasmids**: If the bacterial strain carries two different plasmids (e.g., cloning vector + helper plasmid)
3. **Chromosomal DNA contamination**: A very bright, diffuse high-MW band at the top plus two plasmid bands could be mistaken for three bands

**Assessment:** Run the same plasmid after restriction enzyme linearization — if three bands collapse to one linear band, all three were topological forms of the same plasmid. If bands remain after linearization, multiple plasmids or contamination are present.

---

**Q25. The plasmid miniprep yields very low amounts (<200 ng from 3 mL culture). What are the systematic causes and how would you optimize yield?**

**Causes of low plasmid yield:**

1. **Loss of plasmid (plasmid curing)**: Culture grown without antibiotic selection allows non-plasmid cells to dominate. Always grow with the appropriate antibiotic.

2. **Wrong bacterial strain/plasmid combination**: Some plasmid-strain combinations are incompatible — plasmid copy number may be very low in certain host strains.

3. **Low-copy-number plasmid**: May require larger culture volume or chloramphenicol amplification.

4. **Over-lysis**: Exceeding 5 min lysis with Solution II denatures and irreversibly precipitates some plasmid.

5. **Insufficient cell growth**: If OD₆₀₀ < 2 at harvest, insufficient biomass. Allow culture to grow longer (16–18 hours) or inoculate with more starter culture.

6. **Poor lysis due to incorrect Solution II**: Degraded NaOH (absorbed CO₂) → insufficient pH for full lysis.

7. **Column overloading (kit)**: Loading too much lysate onto a silica column exceeds its binding capacity (~20 µg) → excess DNA flows through; use larger column or split into multiple columns.

8. **Poor elution**: Eluting with cold buffer reduces DNA recovery from silica — use warm elution buffer (65–70°C) and extend incubation to 5 minutes before centrifugation.

9. **Isopropanol carry-over inhibiting resuspension**: If pellet was not washed with 70% ethanol, residual isopropanol prevents DNA from dissolving.

---

### APPLICATIONS AND INTERPRETATION

---

**Q26. How is plasmid DNA used in bacterial transformation and what properties of the plasmid are critical for successful transformation?**

**Bacterial transformation** is the process by which bacteria take up exogenous DNA (plasmid) from the environment. Plasmid properties critical for successful transformation:

1. **Supercoiled form (Form I)**: Supercoiled plasmid transforms 3–10× more efficiently than linearized or relaxed circular forms. Supercoiled DNA is more compact, enters the cell more easily, and is recognized more efficiently by the cellular recombination and replication machinery.

2. **Size**: Smaller plasmids transform more efficiently than larger ones — transformation efficiency decreases approximately 10-fold for every 10 kb increase in plasmid size.

3. **Compatible origin of replication**: The plasmid ori must be compatible with the host strain (e.g., ColE1 ori works in most *E. coli* strains but not in *Bacillus* or yeast).

4. **Selectable marker**: Must carry a marker that can be selected in the recipient strain (correct antibiotic resistance; the strain must not already carry the same resistance chromosomally).

5. **Purity**: Contaminants (SDS, ethanol, phenol) reduce transformation efficiency dramatically. A₂₆₀/A₂₈₀ 1.8–2.0 and A₂₆₀/A₂₃₀ ≥ 2.0 are required; use low-EDTA or water for resuspension before transformation.

6. **Concentration**: For chemical transformation, 10–100 ng/50 µL reaction is optimal; too much DNA reduces efficiency (compete for uptake).

---

**Q27. How do you use restriction enzyme analysis to confirm the identity and integrity of a cloned plasmid?**

**Restriction enzyme analysis (diagnostic digest)** is performed after every cloning step to verify:
1. **Insert presence**: The plasmid is larger than the empty vector by the expected insert size
2. **Insert orientation**: Using asymmetric single-cut enzymes that reveal insert directionality
3. **No rearrangements**: Fragment sizes match theoretical predictions

**Standard verification strategy:**

**Step 1 — Single enzyme cut (linearization):**
Cut with enzyme outside the insert → one linear fragment = vector + insert size
Expected: 2.7 kb (vector) + 1.5 kb (insert) = 4.2 kb linear fragment

**Step 2 — Double digest (vector + insert release):**
Use enzymes that flank the insert (e.g., the same enzymes used for cloning)
Expected: vector band at 2.7 kb + insert band at 1.5 kb

**Step 3 — Orientation check:**
Use one enzyme within the insert (known position) and one in the vector MCS
Expected fragment sizes differ depending on insert orientation (calculate from restriction map)

**Interpretation:** All fragment sizes confirmed by comparison to DNA ladder → cloning is correct. Any unexpected band sizes indicate: partial ligation of vector, multiple inserts, insert rearrangement, or different plasmid pick-up.

**Gold standard confirmation:** After restriction analysis suggests correct clone, always **Sanger sequence** the insert and flanking regions to confirm sequence integrity.

---

**Q28. What is plasmid incompatibility and how does it affect plasmid co-extraction and analysis?**

**Plasmid incompatibility** is the inability of two plasmids with the same or closely related origins of replication to coexist stably in the same cell. Plasmids sharing the same replication control elements compete for the same replication machinery and partition proteins → one plasmid is randomly lost at cell division → only one plasmid is retained.

**Incompatibility groups (Inc groups):**
- ColE1-type plasmids (pUC, pBR322) are in the **IncFII** group — incompatible with each other
- p15A plasmids (pACYC184) are in the **IncX** group — compatible with ColE1 plasmids
- This is why **pUC + pACYC** or **ColE1 + pSC101** can be maintained together but two ColE1-based plasmids cannot

**Relevance to plasmid extraction:**
- When two compatible plasmids are co-maintained (common in two-plasmid expression systems), miniprep extracts BOTH plasmids together
- On gel electrophoresis, two sets of plasmid bands appear (or overlapping bands if sizes are similar)
- Restriction analysis must be designed to cut both plasmids at diagnostic sites to identify each separately
- DNA sequence must be confirmed for both plasmids independently

**Practical implication:** When co-maintaining two plasmids, select with BOTH antibiotics simultaneously; culture grown in only one antibiotic may lose the other plasmid.

---

**Q29. What is the role of plasmid DNA extraction in the study of antibiotic resistance in Gram-negative bacteria?**

Antibiotic resistance in Gram-negative bacteria is predominantly plasmid-mediated, making plasmid extraction central to resistance studies:

**Types of resistance on plasmids:**
- **β-lactamases** (blaTEM, blaSHV, blaCTX-M, blaKPC, blaOXA): Genes conferring β-lactam resistance (ampicillin, cephalosporin, carbapenem) on conjugative resistance plasmids (IncF, IncI, IncL/M types)
- **Aminoglycoside resistance**: *aac*, *aph*, *aad* genes on plasmids
- **Fluoroquinolone resistance**: *qnr* genes on plasmids
- **Colistin resistance**: *mcr-1, mcr-2* on mobile plasmids — global concern for last-resort antibiotic resistance

**Plasmid extraction applications in resistance studies:**
1. **Conjugation experiments**: Extract plasmid from donor; confirm presence before conjugation; confirm transfer to recipient by extracting from transconjugant
2. **Resistance gene identification**: Extract plasmid; sequence by NGS or Sanger; identify resistance genes and their genetic context (integrons, transposons)
3. **Plasmid typing**: PBRT (PCR-based replicon typing) uses primers for 18 incompatibility groups to type resistance plasmids from extracted miniprep DNA
4. **S1-PFGE**: Plasmid DNA extracted or prepared in plugs; linearized with S1 nuclease; sized by PFGE to determine plasmid size and number

---

**Q30. How does plasmid extraction differ between a standard laboratory *E. coli* K-12 strain and a clinical *E. coli* isolate?**

| Feature | *E. coli* K-12 (Lab strain) | Clinical *E. coli* isolate |
|---|---|---|
| Biosafety level | BSL-1 | BSL-2 |
| Number of plasmids | 1 (cloned experimental plasmid) | Multiple (2–10 resistance/virulence plasmids) |
| Plasmid sizes | 2–10 kb (well-defined) | Variable (1 kb–200+ kb); large conjugative plasmids |
| Plasmid copy number | High copy (pUC, pBR322) | Often low copy (conjugative IncF: 1–5 copies/cell) |
| Extraction method | Standard miniprep sufficient | May need midiprep/maxiprep for low-copy plasmids; larger culture |
| Gel pattern | 1–2 clear bands | Multiple bands of varying sizes; complex pattern |
| LPS contamination | Moderate (standard K-12) | Higher in mucoid/capsulated clinical strains |
| Downstream use | Cloning, expression, sequencing | Resistance characterization, typing, conjugation |

**Key practical difference:** Clinical isolates often carry **multiple large conjugative plasmids** (50–300 kb). Large plasmids:
- Do not enter standard silica columns efficiently
- Migrate poorly on standard agarose gels
- Require specialized extraction (PFGE with S1 nuclease, or alkaline lysis of larger volumes followed by size-selective precipitation)
- Cannot be differentiated from chromosomal DNA contamination by gel alone — S1 nuclease digestion (linearizes all circular DNA — plasmid; does not cut linear chromosomal DNA which is already linear) followed by PFGE is needed to visualize large plasmids

---

**Q31. What is the S1 nuclease-PFGE method for plasmid profiling and how does it use extracted plasmid DNA?**

**S1 nuclease-PFGE** is the gold standard for determining the **number and sizes of large plasmids** in Gram-negative bacteria:

**Principle:**
- **S1 nuclease** is a single-strand-specific endonuclease that preferentially cleaves single-stranded DNA/RNA, but also linearizes **supercoiled (CCC) circular DNA** by introducing a single-strand nick that converts it to a relaxed circle, which then is converted to linear form upon further digestion
- S1 cleaves the ssDNA regions exposed in supercoiled DNA
- **Linear chromosomal DNA** is NOT susceptible to S1 (no single-stranded regions)
- After S1 treatment, all circular plasmids are linearized; linear chromosomal DNA remains linear
- PFGE separates all DNA by size

**Method:**
1. Embed bacteria in agarose plugs (as for PFGE, no shearing)
2. Lyse within plugs; wash thoroughly
3. Incubate plugs in S1 nuclease buffer (pH 4.5) at 37°C for 30 minutes → all circular DNA (plasmids) linearized
4. Run PFGE; all bands above chromosomal DNA are linearized plasmids
5. Size each band against lambda ladder standards

**Advantage over conventional miniprep + gel:** Reveals ALL plasmids including very large ones (up to 800 kb) that cannot be extracted by standard alkaline lysis without shearing.

---

**Q32. How is plasmid DNA quantified accurately and what are the sources of error in quantification?**

**Methods for plasmid DNA quantification:**

**1. NanoDrop UV spectrophotometry (A₂₆₀):**
- Principle: dsDNA absorbs UV at 260 nm; A₂₆₀ of 1.0 = 50 µg/mL
- Advantage: Fast, no reagents, small volume (2 µL)
- Errors: Overestimates if RNA present (RNA also absorbs A₂₆₀); overestimates if single-stranded DNA or denatured regions present; phenol absorbs at 230 nm (A₂₃₀), slightly affecting A₂₆₀ reading; inconsistent path length reproducibility between measurements

**2. Qubit fluorometer (fluorometric, dsDNA-specific):**
- Principle: intercalating fluorescent dye (PicoGreen or OliGreen-based) binds specifically to dsDNA; fluorescence proportional to dsDNA concentration
- Advantage: RNA and ssDNA do NOT bind → no overestimation; extremely sensitive (0.2–1000 ng/µL range)
- Most accurate method for downstream applications (transfection, NGS)
- Errors: Some modified bases may bind dye differently; requires calibration standards

**3. Gel electrophoresis (semi-quantitative):**
- Comparison of band intensity to DNA ladder bands of known mass
- Provides size confirmation as well as rough quantification
- Not accurate for absolute concentration

**4. A₂₆₀/A₂₈₀ and A₂₆₀/A₂₃₀ ratios (purity assessment):**
- A₂₆₀/A₂₈₀ = 1.8–2.0 → pure DNA; < 1.7 → protein contamination; > 2.0 → RNA contamination
- A₂₆₀/A₂₃₀ should be 2.0–2.2; < 1.8 suggests phenol, guanidinium salts, or EDTA contamination

---

**Q33. What is the importance of using the correct antibiotic concentration for plasmid maintenance during culture before extraction?**

Antibiotic selection is essential during plasmid culture for two reasons:
1. **Prevents plasmid loss**: Without selection pressure, bacteria that have lost the plasmid grow faster (plasmid maintenance costs metabolic energy) and outcompete plasmid-containing cells — within 20–30 generations (approximately 10–15 hours), plasmid-free cells dominate the culture
2. **Ensures uniform plasmid content**: All surviving cells maintain the plasmid, giving consistent yield per cell

**Standard antibiotic working concentrations for common resistance markers:**

| Antibiotic | Marker Gene | Working Concentration |
|---|---|---|
| Ampicillin | *bla* (β-lactamase) | 50–100 µg/mL |
| Kanamycin | *kan* (neomycin phosphotransferase) | 50 µg/mL |
| Chloramphenicol | *cat* (chloramphenicol acetyltransferase) | 25–34 µg/mL |
| Tetracycline | *tet* (tetracycline efflux) | 12.5–15 µg/mL |
| Spectinomycin | *aadA* | 100 µg/mL |
| Gentamicin | *aac* | 10–15 µg/mL |

**Critical note for ampicillin:** β-lactamase hydrolyzes ampicillin in the medium — in a dense overnight culture, ampicillin is completely degraded within 6–8 hours. Satellite colonies (small colonies around larger colonies on plates) indicate ampicillin breakdown and plasmid-free cells growing. For critical experiments requiring confirmed plasmid retention, use **carbenicillin** (a β-lactamase-resistant penicillin, 50 µg/mL) instead — more stable in medium.

---

**Q34. How do you confirm successful insert ligation in a plasmid by blue-white colony screening?**

**Blue-white screening** is a visual selection method for detecting successful insert cloning into vectors with a disrupted *lacZα* gene (e.g., pUC19, pGEM, pBluescript):

**Molecular basis:**
- pUC19 carries the *lacZα* gene encoding the α-fragment of β-galactosidase
- The MCS is located within *lacZα* — multiple cloning site is in-frame with the coding sequence
- Unmodified pUC19 in an appropriate *lacZ* deletion host (*E. coli* JM109, DH5α) allows complementation of *lacZα* and *lacZΔM15* fragments → active β-galactosidase is produced
- Active β-galactosidase cleaves **X-gal (5-bromo-4-chloro-3-indolyl-β-D-galactoside)** → releases 5-bromo-4-chloro-indigo (blue dye) → **blue colonies** (vector only, no insert)
- When an insert disrupts the MCS reading frame, *lacZα* is non-functional → no β-galactosidase → X-gal not cleaved → **white colonies** (likely has insert)

**Screening protocol:**
1. Transform ligation products into *lacZ* deletion host
2. Plate on LB agar + antibiotic + **IPTG** (100 µM, induces *lac* promoter) + **X-gal** (40 µg/mL, spread on plate)
3. Incubate 37°C overnight; allow colour to develop at 4°C 2–4 hours
4. Pick white colonies (putative inserts); grow overnight; perform miniprep; verify by restriction digest and sequencing

**False positives (white but no insert):** Short deletions in *lacZα*, frameshifts from partial digestion, IPTG/X-gal concentration issues. Always verify white colonies by restriction digest.

---

**Q35. What is the difference between a plasmid miniprep for cloning verification and one prepared for mammalian cell transfection?**

| Parameter | Cloning Verification | Mammalian Cell Transfection |
|---|---|---|
| Scale | Miniprep (1–5 µg) | Maxiprep, often endotoxin-free (50–500 µg) |
| Purity requirement | Moderate (A₂₆₀/A₂₈₀ ≥ 1.7 for sequencing) | Very high (A₂₆₀/A₂₈₀ 1.8–2.0; A₂₆₀/A₂₃₀ ≥ 2.0) |
| Endotoxin | Not critical | Critical — LPS activates TLR4/MD2 → NF-κB → cell death; must be <0.1 EU/µg |
| DNA form | Any (supercoiled preferred but not required) | Supercoiled strongly preferred (higher transfection efficiency) |
| Buffer | TE or water | Water or physiological saline (TE-EDTA can affect cells) |
| Sterility | Not required | Sterile — filter through 0.22 µm after preparation |
| Validation | Restriction digest + gel | Restriction digest + gel + endotoxin test (LAL assay) + transfection efficiency test on control cells |

**Endotoxin removal for transfection-grade plasmid:**
- Use EndoFree Plasmid Maxi Kit (Qiagen) — uses QBT buffer containing a detergent that disrupts LPS micelles → LPS binds anion-exchange column instead of flowing through
- Alternative: Triton X-114 phase partition or EndoTrap column
- Verify: Limulus Amebocyte Lysate (LAL) assay — acceptable limit ≤0.1 EU/µg DNA for in vivo injection; ≤1 EU/µg for cell culture transfection

---

### ADVANCED / APPLICATION QUESTIONS

---

**Q36. Compare the silica membrane column and anion-exchange column principles used in commercial plasmid extraction kits.**

**Silica membrane columns (miniprep scale):**
- **Principle**: In **high chaotropic salt + ethanol** conditions, DNA binds to silica (SiO₂) by: (1) disruption of DNA hydration shell by chaotropes (guanidinium HCl/thiocyanate), (2) dehydration by ethanol exposing DNA to silica surface, (3) electrostatic interaction between slightly positive silica surface (at low pH) and DNA phosphates
- **Wash**: Ethanol-containing wash buffer removes proteins, salts, and SDS while DNA remains bound
- **Elution**: Low-salt buffer (Tris pH 8.5) or water at slightly elevated temperature disrupts silica-DNA interaction; DNA elutes
- **Capacity**: ~20 µg maximum per column
- **DNA form**: Supercoiled form is eluted (not denatured)
- **Limitation**: Shears DNA to ~20–50 kb maximum (due to column passage); not suitable for large plasmids (>50 kb)

**Anion-exchange columns (midi/maxiprep scale):**
- **Principle**: DEAE (diethylaminoethyl) resin is positively charged at physiological pH; DNA (negatively charged phosphate backbone) binds by electrostatic interaction; binding strength proportional to DNA charge density
- **Selectivity**: At medium salt (0.7–0.8 M NaCl), RNA and proteins do not bind; supercoiled DNA binds more tightly than nicked/linear forms; LPS partially retained
- **Elution**: High salt (1.25–1.6 M NaCl) elutes DNA; then desalted by isopropanol precipitation
- **Capacity**: 100 µg – 2+ mg per column depending on size
- **DNA form**: Supercoiled plasmid preferentially retained over nicked/linear forms
- **Advantage**: Endotoxin reduction (some LPS binds and is separated); higher yield; better for large plasmids

---

**Q37. What is conjugation and how is plasmid extraction used to study conjugative transfer of resistance plasmids?**

**Conjugation** is a form of horizontal gene transfer in which a donor bacterium transfers plasmid DNA to a recipient cell through direct cell-to-cell contact via a **sex pilus** and **mating bridge**. Self-transmissible (conjugative) plasmids encode all the genes needed for their own transfer (tra genes — encoding pilus assembly, mating pair stabilization, relaxase, coupling proteins). Mobilizable plasmids can be transferred by a co-resident conjugative plasmid in trans.

**Plasmid extraction in conjugation studies:**

**Pre-conjugation:** Extract plasmid from donor strain; run on gel; confirm identity and size of conjugative plasmid; PCR for resistance genes.

**Post-conjugation:** Select transconjugants on medium selecting for recipient markers + plasmid-encoded resistance (dual selection eliminates donor). Extract plasmid from confirmed transconjugants; run on gel → confirm plasmid of same size was transferred.

**Transfer frequency calculation:**
Transfer frequency = (Number of transconjugants) / (Number of donor cells)

A typical conjugative frequency for IncF plasmids: 10⁻³ – 10⁻⁵ transconjugants per donor.

**Plasmid characterization post-transfer:** Restriction map, PCR for tra genes, replicon typing, sequence comparison with donor plasmid — confirms intact transfer and identifies any rearrangements during transfer.

---

**Q38. How is plasmid DNA used as a vector for gene expression in Gram-negative bacteria, and what plasmid features are required for expression?**

For **protein expression** in bacteria (e.g., *E. coli*), plasmid vectors must contain specific elements beyond basic replication and selection:

**Essential expression vector features:**

1. **Strong promoter**: Determines transcription rate of the cloned gene
   - **T7 promoter** (in pET vectors): Requires T7 RNA polymerase (supplied from chromosomal T7 RNAP gene in BL21(DE3) host); strongest prokaryotic promoter; extremely high expression
   - **tac promoter** (tac = trp + lac hybrid): IPTG-inducible; uses host RNAP; strong but less than T7
   - **araBAD (pBAD)**: Arabinose-inducible; tightly regulated; good for toxic proteins
   - **T5 promoter**: IPTG-inducible; moderate expression

2. **Ribosome binding site (RBS/Shine-Dalgarno)**: Positioned 5–10 nt upstream of ATG start codon; required for efficient translation initiation

3. **ATG start codon in correct frame with MCS**: Allows in-frame fusion of insert

4. **Transcription terminator**: Prevents read-through transcription that wastes resources

5. **Optional tags**: His₆-tag (for Ni-NTA purification), GST-tag (for glutathione affinity), SUMO, MBP (for enhanced solubility)

6. **Inducible system**: Critical for proteins that inhibit bacterial growth — express at low level during growth; induce for production

**Plasmid preparation for expression:** Maxiprep-scale preparation of expression vector; transform into expression host (BL21(DE3) for T7 system); mini-culture test of expression before large-scale production.

---

**Q39. What is the difference in plasmid extraction when the host is a recombination-proficient (*recA⁺*) vs. recombination-deficient (*recA⁻*) strain?**

**RecA** is a key bacterial recombinase responsible for homologous recombination. Its presence in the extraction host has several consequences:

***recA⁺* strains (wild-type *E. coli* K-12, BL21):**
- RecA can catalyze recombination between **direct repeats** in the plasmid sequence — leading to deletions of sequences flanked by repeats (common in plasmids with long direct repeats or expression cassettes)
- Plasmid DNA extracted from *recA⁺* strains may show multiple bands or smears on gel due to recombination-derived deletion products
- Problematic for plasmids with: inverted repeats, multiple cloning sites of the same sequence, long direct repeats, repetitive elements (viral sequences, repeated promoters)

***recA⁻* strains (DH5α, DH10B, Top10, XL1-Blue):**
- Lack functional RecA → no intramolecular or intermolecular recombination
- Plasmid stability greatly improved — inserts and repetitive sequences maintained intact
- **Standard choice for cloning** applications
- DH5α: *recA1, endA1* — RecA-deficient and lacks EndA1 endonuclease (EndA1 degrades plasmid DNA during alkaline lysis if present)

**EndA1 significance:** EndA1 is a periplasmic DNase present in most standard *E. coli* strains. When the outer membrane is disrupted during extraction, EndA1 is released and can degrade plasmid DNA. *endA1* mutant strains (DH5α, DH10B) are strongly preferred for miniprep because EndA1 absence significantly improves plasmid yield and quality. When using EndA1-proficient strains, rapid extraction and careful technique are essential.

---

**Q40. How would you extract and verify a 50 kb cosmid or fosmid vector used in genomic library construction?**

**Cosmids** (40–50 kb inserts) and **fosmids** (35–45 kb inserts in F-plasmid-based vectors) are large-insert cloning vectors used for genomic library construction.

**Extraction challenges:**
- Large size (50–55 kb total) → behaves more like chromosomal DNA than a typical plasmid
- Low copy number (1–5 copies/cell for fosmids based on F-factor ori) → very low yield per cell
- Cannot be extracted efficiently by standard miniprep (silica columns shear DNA >50 kb)

**Modified extraction protocol:**
1. Grow 50–100 mL culture (larger volume to compensate for low copy)
2. For fosmids: Do NOT use chloramphenicol amplification (F-factor-based replication is protein-dependent — amplification does not work)
3. Harvest cells; perform gentle alkaline lysis with Solutions I, II, III (scale up proportionally)
4. Use **anion-exchange midiprep column** (not silica column) for size-tolerant purification
5. Elute with high-salt buffer; precipitate with isopropanol gently (no vortexing); resuspend in TE

**Verification:**
1. Restriction digest (EcoRI or HindIII) → compare fragment pattern to expected restriction map of the insert
2. Agarose gel: Large linear bands after digestion; uncut cosmid runs as a diffuse high-MW smear
3. PCR: Amplify insert ends using T7/SP6 primers flanking the cloning site to confirm insert presence
4. For fosmid libraries: end-sequence both ends of the insert using Sanger sequencing to identify the genomic coordinates of the insert

---

**Q41. What is a plasmid rescue experiment and how does it use plasmid extraction from Gram-negative bacteria?**

**Plasmid rescue** is a technique used to recover a chromosomally-integrated sequence by extracting it on a plasmid vector:

**Principle:**
- A plasmid vector (carrying an ori and antibiotic resistance) is integrated into the bacterial chromosome (e.g., by transposon insertion or recombination with a suicide vector)
- The integrated plasmid is flanked by chromosomal DNA of interest (e.g., the site of transposon insertion)
- To identify the chromosomal sequence flanking the insertion, the rescue is performed:

**Rescue protocol:**
1. Extract total DNA (chromosomal + integrated plasmid) from the bacteria
2. Digest with a restriction enzyme that cuts outside the integrated plasmid in the flanking chromosomal sequence (enzyme must not cut within the plasmid ori or resistance gene)
3. Self-ligate the digestion products (creates circular molecules of plasmid + flanking chromosomal sequence)
4. Transform *E. coli* competent cells; select on antibiotic corresponding to the plasmid rescue marker
5. Pick colonies; perform miniprep; sequence the rescued plasmid → the chromosomal sequences flanking the integrated plasmid are recovered

**Applications:**
- **Transposon insertion site identification**: Identify which gene was disrupted by transposon insertion
- **Promoter trapping**: Recover promoter sequences driving a reporter gene integrated randomly in the chromosome
- **Mapping integration sites** of suicide vectors in allelic exchange experiments

---

**Q42. How does the choice of *E. coli* host strain affect plasmid extraction quality and yield?**

Different *E. coli* strains have specific genetic features that affect plasmid extraction:

| Strain | Key Genotype | Effect on Extraction |
|---|---|---|
| **DH5α** | *recA1, endA1, hsdR17* | Gold standard for cloning — no recombination, no EndA1 degradation, no restriction; high quality, high yield |
| **DH10B / Top10** | *recA1, endA1, mcrA, mcrBC, dam⁻, dcm⁻* | No methylation (dam⁻, dcm⁻) — useful for restriction enzymes sensitive to Dam/Dcm methylation; same quality as DH5α |
| **JM109** | *recA1, endA1, lacIq* | Similar to DH5α; suitable for blue-white screening |
| **BL21(DE3)** | *recB, recC, lon, ompT, endA1⁺* (some backgrounds) | Expression strain — NOT ideal for cloning (some are EndA1-proficient); use only for expression, not for stable propagation |
| **HB101** | *recA, hsdR, supE* | Older strain; adequate but DH5α preferred |
| **SURE strain** | *recB, recJ, sbcC, sbcD, uvrC, umuC, endA1, (λcI857Δ)* | For palindromes, repetitive elements, unstable inserts — prevents rearrangement |
| **Stbl3 / Stbl4** | *recA* | For lentiviral vectors and direct repeats — prevents recombination of LTR sequences |

**Key takeaway:** Always use a *recA⁻ endA1⁻* strain (DH5α, DH10B) for plasmid propagation. Use methylation-deficient strains when cloning into methylation-sensitive restriction sites. Use specialty strains (SURE, Stbl) for inherently unstable inserts.

---

**Q43. What is the importance of the A₂₆₀/A₂₃₀ ratio in plasmid DNA quality assessment and what contaminants does it detect?**

The **A₂₆₀/A₂₃₀ ratio** measures the absorbance ratio of the DNA peak (260 nm) to the short-wavelength UV region (230 nm). Acceptable range for pure plasmid DNA: **2.0–2.2**.

**Contaminants absorbing at 230 nm:**

1. **Guanidinium salts** (guanidinium thiocyanate, guanidinium HCl): Used as chaotropic agents in commercial kit lysis buffers; if not washed completely, they absorb at 230 nm and reduce the ratio to <1.5
2. **Phenol**: Absorbs at 230 nm (also at 270 nm — phenol has a shoulder absorbance); residual phenol from PCI extraction → ratio <1.5; phenol also inhibits downstream enzymes
3. **EDTA**: Absorbs very weakly at ~230 nm; significant only at high concentrations (>50 mM)
4. **Ethanol**: Absorbs at ~200 nm; residual ethanol in incompletely dried pellets gives reduced A₂₃₀ ratio
5. **Carbohydrates (polysaccharides)**: Absorb in the 230 nm region; relevant for extractions from encapsulated organisms

**Effect of low A₂₆₀/A₂₃₀ ratio on downstream applications:**
- PCR inhibition (guanidinium salts, phenol inhibit Taq polymerase)
- Restriction enzyme inhibition
- Sequencing failure (polymerases inhibited)
- Transfection failure (phenol is cytotoxic)

**Remedy:** Additional wash steps with ethanol wash buffer; additional column elution and re-binding; re-purification using a clean-up column.

---

**Q44. How is plasmid DNA extracted from bacteria expressing toxic genes, and what special considerations apply?**

When cloning and expressing **potentially toxic genes**, the extraction strategy must address:

1. **Tight promoter control**: Use tightly repressed promoters (T7/lac with lacI overexpression in BL21(DE3)/pLysS; arabinose-inducible pBAD) — prevent any leaky expression during culture

2. **Low copy number vector**: Use pACYC-based (p15A ori, 10–15 copies) or pSC101 (4–5 copies) instead of high copy pUC — fewer copies = less total toxic protein from leaky expression

3. **Grow at 30°C instead of 37°C**: Lower temperature reduces overall transcription/translation rates and may reduce leaky expression of toxic gene

4. **Use *lacI*-overexpressing strains**: Strain BL21-AI or BL21(DE3)/pLysS over-expresses the Lac repressor → tighter repression of T7 promoter; pLysS produces T7 lysozyme which inhibits T7 RNAP, providing additional regulation

5. **Short culture time**: Harvest cells at mid-log phase (OD₆₀₀ = 0.6–0.8) before the culture reaches saturation; longer growth allows more cumulative leaky expression → cell death and plasmid loss

6. **Verify plasmid integrity more frequently**: Miniprep after every passage through bacteria; confirm correct insert by restriction digest; toxic gene plasmids are prone to deletions that eliminate toxicity but also gene function

7. **Special extraction consideration**: If cells are partially lysed from toxic protein expression, they may lyse prematurely in Solution II → chromosomal DNA contamination; handle cells gently and process immediately after harvesting

---

**Q45. What are integrating vectors and how does plasmid extraction demonstrate their integration into the bacterial chromosome?**

**Integrating vectors** (also called suicide vectors or integration vectors) are plasmids that carry:
- A cloned sequence homologous to a chromosomal target (for recombination-mediated integration)
- A selectable marker
- An origin of replication functional only in a non-*E. coli* host (conditional ori — cannot replicate in the target host organism)

After introduction into the target bacteria, the vector cannot replicate autonomously (no functional ori) — survival requires **chromosomal integration** by homologous recombination between the cloned insert and the chromosome.

**Confirming integration by plasmid extraction:**
1. After transformation and antibiotic selection, perform miniprep from putative integrant colonies
2. **Expected result if integration occurred:** NO plasmid is recovered (vector is integrated into chromosome; it no longer exists as an extrachromosomal element and cannot be extracted as a discrete plasmid)
3. **If plasmid is recovered:** Integration has NOT occurred; vector is still replicating (suggests the ori is functional in this strain, or a second copy of the ori was introduced)

**Confirmation of chromosomal integration:**
- PCR using one primer within the integrated vector and one in the flanking chromosomal sequence → band only if vector is integrated at the correct location
- Southern blot using the vector sequence as probe → single band of correct size (vector + flanking sequence) confirms integration
- Loss of integrant upon removal of antibiotic selection (if integration is via single crossover/Campbell-type) — confirmed by replica plating

---

**Q46. Describe the preparation and use of plasmid DNA for electroporation into Gram-negative bacteria.**

**Electroporation** uses brief high-voltage electrical pulses to transiently permeabilize bacterial membranes, allowing plasmid DNA to enter cells. It achieves 10–100× higher transformation efficiency than chemical methods.

**Plasmid DNA requirements for electroporation:**
1. **Purity**: Must be extremely pure — A₂₆₀/A₂₈₀ 1.8–2.0; A₂₆₀/A₂₃₀ ≥ 2.0; contaminants (salts, SDS, EDTA) cause electrical arcing during electroporation (characteristic loud "pop" and sample loss)
2. **Low ionic strength**: Salt content must be minimal — even 10 mM NaCl can cause arcing at standard voltages; resuspend DNA in water or 10% glycerol rather than TE buffer (NaCl in TE is fine for chemical transformation but not electroporation)
3. **Concentration**: 1 ng – 1 µg per 50 µL cell suspension; too much DNA reduces efficiency
4. **Volume**: Add 1–5 µL DNA to 50 µL electrocompetent cells

**Preparation for electroporation:**
- Perform standard miniprep; elute in water (not TE or salt buffer)
- If DNA is in TE or salt buffer: ethanol-precipitate, wash with 70% ethanol, resuspend in water to remove salts
- Alternatively: Qiagen PCR purification column to exchange buffer from TE to water

**Electroporation conditions for *E. coli*:** 2500 V, 25 µF, 200 Ω; time constant should be 4–5 ms (if < 3 ms → arcing occurred, most cells killed)

---

**Q47. How does plasmid copy number regulation work, and how does understanding copy number control affect extraction strategy?**

**ColE1-type copy number control (pUC, pBR322):**
- Replication initiated by RNAII transcript (preprimer); processed by RNaseH; RNAII primes replication at ori
- **RNAI** (counter-transcript RNA; transcribed in opposite direction) inhibits RNAII by complementary base pairing → prevents replication initiation
- **Rop protein** (from pBR322) facilitates RNAI-RNAII interaction → increases inhibition → lower copy number
- **pUC19** lacks Rop protein gene (deleted) + mutated RNAI binding site → RNAI inhibition reduced → higher copy number (500–700 vs 15–20 for pBR322)
- **Temperature sensitivity**: ColE1 copy number increases at 37°C vs 30°C because RNAI:RNAII interaction is temperature-dependent (weaker at higher temperature)

**Implications for extraction strategy:**
1. **Temperature of culture**: Growing pUC-type plasmids at **37°C** maximizes copy number and yield vs. 30°C
2. **Chloramphenicol amplification**: Adding chloramphenicol to mid-log cultures of ColE1-ori plasmids inhibits protein synthesis → RNAI level falls (RNAI is unstable RNA) → RNAII no longer inhibited → uncontrolled plasmid replication continues → copy number rises from 500 to ~3000 → 3–6× yield increase
3. **Growth to high density**: For maxipreps, growing to OD₆₀₀ 4–6 (overnight) with optimal aeration maximizes total cell number and hence plasmid yield

---

**Q48. What is the difference between extracting plasmid DNA from *E. coli* versus from other Gram-negative bacteria such as *Pseudomonas*, *Klebsiella*, or *Acinetobacter*?**

The alkaline lysis principle applies broadly but with species-specific modifications:

***Pseudomonas aeruginosa*:**
- Produces alginate (polysaccharide) → add 1 mg/mL RNase A to Solution I AND add 4 U/µL α-amylase to pre-digest polysaccharides before alkaline lysis
- More resistant outer membrane → pretreat with EDTA (50 mM, 65°C, 15 min) before alkaline lysis
- Endogenous proteases more active → process immediately; keep on ice
- Yield typically 50% lower than *E. coli* from equivalent culture volume

***Klebsiella pneumoniae*:*
- Thick polysaccharide capsule → CTAB addition to cleared lysate (after Solution III centrifugation) at 1.4 M NaCl precipitates polysaccharides before column loading
- Higher LPS content → extra wash with wash buffer; consider endotoxin removal step

***Acinetobacter baumannii*:*
- Very thick outer membrane → increase SDS in Solution II to 1.5%; extend lysis to 10 min (monitor — must not exceed 12 min)
- Multiple native plasmids in clinical strains — gel will show multiple bands; individual plasmids must be characterized separately

***General adaptation principle:*** Any Gram-negative that produces extracellular polysaccharide, has an unusually resistant outer membrane, or carries active nucleases will require EDTA pretreatment, extended lysis, and additional cleanup steps beyond the standard E. coli miniprep protocol.

---

**Q49. What are the key differences in plasmid DNA extraction when the plasmid is being prepared for gene therapy applications versus standard laboratory use?**

**Gene therapy plasmid DNA requirements (much stricter than laboratory standards):**

| Parameter | Laboratory Standard | Gene Therapy Standard |
|---|---|---|
| Scale | Miniprep/Midiprep | Pharmaceutical-scale GMP production (grams) |
| Regulatory framework | None | GMP (Good Manufacturing Practice), FDA/EMA IND |
| Purity (A₂₆₀/A₂₈₀) | 1.8–2.0 | 1.8–2.0 (same) |
| Supercoiled form | >50% acceptable | >90% supercoiled required |
| Endotoxin | <1 EU/µg (research) | <1 EU/mL (final formulation) — essentially endotoxin-free |
| Host cell proteins | Not specified | <1 µg/mg DNA |
| Host cell DNA | Not specified | <1 ng chromosomal DNA per µg plasmid |
| RNA | Not specified | <1% of total nucleic acid |
| Residual solvents | Not tested | HPLC quantification of residual ethanol, isopropanol |
| Sterility | Not required | Sterility testing (European Pharmacopoeia) |
| Container closure | Any tube | Validated cryovials, certified sterile |
| Certificate of Analysis | Not required | Required — detailed analytical testing results |

**Additional purification steps for gene therapy plasmid:**
- Cesium chloride gradient or anion exchange HPLC for supercoil enrichment
- Multiple TFF (tangential flow filtration) steps for buffer exchange and concentration
- Multiple endotoxin removal steps and LAL testing of each batch

---

**Q50. Design a complete, optimized protocol for plasmid miniprep from *E. coli* DH5α carrying pUC19 for use in restriction enzyme verification and Sanger sequencing, with full QC documentation.**

---

**COMPLETE PROTOCOL: Plasmid Miniprep from *E. coli* DH5α/pUC19 for Restriction Verification and Sequencing**

---

**REAGENTS:**

*Solution I (Resuspension buffer) — store at 4°C:*
- 50 mM glucose, 25 mM Tris-HCl (pH 8.0), 10 mM EDTA + RNase A (100 µg/mL, added fresh before use)

*Solution II (Lysis buffer) — freshly prepared:*
- Mix equal volumes 0.4 M NaOH + 2% SDS immediately before use

*Solution III (Neutralization buffer) — store at 4°C:*
- 3 M potassium acetate + 11.5% glacial acetic acid; pH 4.8

*Other:* Isopropanol (RT), 70% ethanol (ice-cold), TE buffer pH 8.0, nuclease-free water

---

**CULTURE:**
1. Inoculate 5 mL LB + ampicillin (100 µg/mL) from a single white colony (blue-white screened)
2. Incubate 37°C, 200 rpm, 14–16 hours (overnight)
3. Verify culture turbidity (OD₆₀₀ should be 4–6 for dense overnight)

**HARVEST:**
4. Transfer 1.5 mL to 1.5 mL microcentrifuge tube; centrifuge 12,000 × g, 1 min; remove supernatant completely; repeat with additional 1.5 mL (total: 3 mL cells in one tube)

**RESUSPENSION:**
5. Add 200 µL Solution I + RNase A (100 µg/mL); vortex vigorously until no cell clumps remain; incubate 5 min at RT

**LYSIS:**
6. Add 400 µL freshly prepared Solution II; mix by **gentle inversion 6–8 times only — DO NOT VORTEX**; solution becomes clear and viscous; incubate exactly **4 minutes** at RT

**NEUTRALIZATION:**
7. Add 300 µL ice-cold Solution III; mix by gentle inversion immediately until white precipitate forms throughout; incubate on ice **5 minutes**

**CLARIFICATION:**
8. Centrifuge 12,000 × g, 10 minutes at 4°C; carefully transfer supernatant to fresh tube (avoid white precipitate); repeat centrifugation if precipitate in supernatant

**DNA PRECIPITATION:**
9. Add 0.7 volumes isopropanol (~560 µL); mix by inversion; centrifuge 12,000 × g, 10 minutes; discard supernatant

**WASH:**
10. Add 500 µL ice-cold 70% ethanol; centrifuge 12,000 × g, 5 minutes; remove supernatant completely; repeat once
11. Air-dry pellet at RT for 10 minutes (pellet turns from white/opaque to clear when dry)

**RESUSPENSION:**
12. Add 50 µL nuclease-free water (for sequencing) or TE buffer (for storage); incubate at 37°C, 5 minutes to aid dissolution; pipette gently to resuspend

---

**QUALITY CONTROL:**

**QC1 — NanoDrop measurement:**
- Load 2 µL (undiluted); blank with water or TE
- Record: A₂₆₀, A₂₈₀, A₂₃₀, concentration (ng/µL)
- Accept: A₂₆₀/A₂₈₀ 1.75–2.0; A₂₆₀/A₂₃₀ ≥ 1.8; concentration ≥ 30 ng/µL
- Fail action: A₂₆₀/A₂₈₀ < 1.7 → PCI re-extraction; A₂₆₀/A₂₃₀ < 1.5 → additional ethanol wash column cleanup; Concentration < 30 ng/µL → re-miniprep with 5 mL culture

**QC2 — Agarose gel electrophoresis:**
- Run 200 ng (calculate volume from NanoDrop result) on 1% agarose gel alongside 1 kb ladder
- Load: 200 ng plasmid in 10 µL total (with 6× loading dye)
- Expected: 2–3 bands (supercoiled Form I fastest; nicked Form II slowest; possibly linear Form III middle)
- Accept: Clear bands with Form I dominant (brightest/most intense); no smear; no RNA band at bottom
- Fail action: Smear → DNase contamination; repeat with fresh EDTA-containing buffers; All RNA, no plasmid → no plasmid in strain, plate on ampicillin plates to confirm

**QC3 — Restriction enzyme verification:**
- Set up 20 µL digest: 500 ng plasmid + 1 µL EcoRI + 2 µL CutSmart 10× buffer; incubate 37°C, 1 hour
- Expected: pUC19 digested with EcoRI → one linear band at 2.7 kb (pUC19 has a single EcoRI site)
- If insert present: two bands = vector + insert (record sizes; confirm match expected design)
- Run digest on 1% agarose alongside uncut plasmid and 1 kb ladder
- Accept: Band sizes within ±5% of expected

**QC4 — Sequencing preparation:**
- If insert verification required: Set up Sanger sequencing reaction with M13 forward or M13 reverse primer (flank pUC19 MCS)
- Submit: 5–10 µL at 30–100 ng/µL in water; 10 µM primer

---

**DOCUMENTATION:**
- Miniprep log entry: date, operator, strain, plasmid name, culture volume, OD₆₀₀, NanoDrop results (concentration + ratios), gel image (photograph), RE digest image, QC pass/fail determination
- Label tube: strain/plasmid ID, concentration, date, A₂₆₀/A₂₈₀, QC pass
- Store: −20°C (long-term); 4°C (working stock for ≤1 month)
- Retain gel photographs as part of experimental record for minimum 5 years

---

*End of Section V: Extraction of Plasmid DNA from Gram Negative Bacteria — 50 Questions & Answers*
*Masters Level | Molecular Biology Practical Viva Preparation*
