# Molecular Biology — Section IV: Extraction of Chromosomal DNA from Gram Negative Bacteria
## 50 Viva Questions with Detailed Answers (Masters Level)

---

### BASIC PRINCIPLES

---

**Q1. What is chromosomal (genomic) DNA in bacteria and how does it differ from plasmid DNA?**

**Chromosomal DNA** (also called genomic DNA or gDNA) is the primary genetic material of bacteria, typically existing as a single, circular, double-stranded DNA molecule compacted into the **nucleoid region** of the cytoplasm. In *Escherichia coli*, the chromosome is approximately **4.6 Mb** in length, encoding ~4,300 genes. Key differences from plasmid DNA:

| Feature | Chromosomal DNA | Plasmid DNA |
|---|---|---|
| Size | 1–10 Mb (large) | 1–200 kb (small) |
| Copy number | 1–4 per cell | 10–700 per cell |
| Essentiality | Essential for cell viability | Usually dispensable |
| Shape | Single circular chromosome (some linear in Streptomyces) | Small circular (usually) |
| Replication origin | oriC (single) | ori (varies by plasmid) |
| Gene content | Core metabolic, structural, regulatory genes | Accessory genes (antibiotic resistance, virulence, metabolic) |
| Extraction challenge | More complex — requires lysis + removal of RNA/protein | Simpler — alkaline lysis selectively releases plasmid |

In molecular biology, chromosomal DNA is extracted for whole-genome sequencing, Southern blotting, PCR-based diagnostics, MLST (multi-locus sequence typing), and genomic library construction.

---

**Q2. What is the structure of the cell envelope of Gram-negative bacteria and why does it make DNA extraction more challenging than from Gram-positive bacteria?**

Gram-negative bacteria possess a **complex, multilayered cell envelope** consisting of:
1. **Cytoplasmic (inner) membrane**: Phospholipid bilayer enclosing the cytoplasm
2. **Periplasmic space**: Contains peptidoglycan layer (thin, 2–7 nm) and periplasmic proteins
3. **Outer membrane**: Unique to Gram-negatives; contains phospholipids in inner leaflet and **lipopolysaccharide (LPS)** in outer leaflet; studded with **porin proteins** (OmpA, OmpC, OmpF) allowing passive diffusion of small molecules

**Challenges for DNA extraction from Gram-negatives:**
1. **Outer membrane barrier**: The outer membrane is more resistant to simple detergent lysis than the inner membrane — requires SDS at higher concentrations or additional treatment (proteinase K, EDTA pretreatment to destabilize outer membrane by chelating Mg²⁺ that cross-links LPS)
2. **LPS contamination**: LPS co-purifies with DNA and inhibits downstream enzymatic reactions (PCR, restriction digestion) at nanogram quantities
3. **Thinner peptidoglycan**: Paradoxically, the thinner cell wall means cell integrity depends more on the outer membrane — mechanical disruption is less effective than for thick-walled Gram-positives
4. **EDTA requirement**: EDTA chelates Mg²⁺ linking LPS in the outer membrane, partially permeabilizing it before detergent lysis — an additional step not needed for Gram-positives

---

**Q3. What are the three fundamental steps in chromosomal DNA extraction from bacteria, regardless of the method used?**

All chromosomal DNA extraction protocols, regardless of their specific chemistry, share three fundamental steps:

**Step 1 — Cell Lysis (breaking open the bacterial cell):**
The bacterial cell envelope must be disrupted to release intracellular contents. Lysis methods include chemical (SDS, NaOH), enzymatic (lysozyme, proteinase K), mechanical (bead beating, sonication, freeze-thaw), or combinations. For Gram-negatives, a combination of EDTA pretreatment + SDS + proteinase K is most common.

**Step 2 — Protein and RNA Removal:**
The crude lysate contains DNA, RNA, proteins (histones, enzymes, structural proteins), lipids, and cell wall fragments. Proteins are removed by proteinase K digestion and/or phenol-chloroform extraction. RNA is removed by RNase A treatment. LPS and other contaminants are removed during the purification steps.

**Step 3 — DNA Precipitation/Purification and Recovery:**
Purified DNA is recovered from aqueous solution by:
- **Alcohol precipitation** (ethanol or isopropanol + salt) — precipitates DNA as a pellet
- **Silica column binding** (commercial kits) — DNA binds silica in chaotropic salt conditions, contaminants wash through, DNA eluted
- **CTAB precipitation** — used specifically for high-polysaccharide-containing organisms

---

**Q4. What is the role of EDTA in the lysis buffer for Gram-negative bacterial DNA extraction?**

EDTA (ethylenediaminetetraacetic acid) plays multiple critical roles in DNA extraction from Gram-negative bacteria:

1. **Outer membrane destabilization**: The Gram-negative outer membrane is stabilized by **Mg²⁺ ions** that cross-link LPS molecules. EDTA (typically 10–100 mM) chelates these Mg²⁺ ions, disrupting LPS-LPS bridges and destabilizing the outer membrane. This makes cells more susceptible to lysozyme and detergent lysis.

2. **DNase inhibition**: EDTA chelates Mg²⁺ and Ca²⁺ required as cofactors by DNase I and other endonucleases. Without EDTA, released DNA would be immediately degraded by bacterial nucleases liberated during lysis.

3. **RNase inhibition**: Most RNases also require divalent metal cofactors — EDTA provides partial inhibition (though RNA is separately removed with RNase A later).

4. **Cell permeabilization**: EDTA alone (without detergent) partially permeabilizes Gram-negative outer membranes, allowing small molecules (including lysozyme, ~14 kDa) to access the periplasm and peptidoglycan layer.

Typical lysis buffer contains: **50 mM Tris-HCl (pH 8.0) + 50 mM EDTA + 100 mM NaCl**. EDTA concentration may be as high as 50–100 mM specifically for Gram-negative outer membrane disruption.

---

**Q5. What is the role of lysozyme in bacterial DNA extraction and why is it more effective against Gram-positive than Gram-negative bacteria?**

**Lysozyme** (muramidase, EC 3.2.1.17) is an enzyme that cleaves the **β-1,4 glycosidic bond between N-acetylmuramic acid (NAM) and N-acetylglucosamine (NAG)** in the peptidoglycan (murein) layer of bacterial cell walls. This enzymatic hydrolysis weakens the rigid peptidoglycan mesh, causing osmotic lysis or facilitating detergent-mediated lysis.

**Why more effective against Gram-positives:**
- Gram-positive bacteria have a **thick peptidoglycan layer (20–80 nm)** that is directly exposed on the outer surface — lysozyme has immediate, unrestricted access
- Gram-negative bacteria have a **thin peptidoglycan layer (2–7 nm)** protected inside the **outer membrane** — lysozyme (14 kDa) cannot normally penetrate the outer membrane unless it is first destabilized by EDTA or detergent pretreatment

**For Gram-negative lysis:** Cells are first treated with **EDTA** (which loosens the outer membrane) to allow lysozyme to access the peptidoglycan. Lysozyme is then added (0.5–5 mg/mL) and incubated at 37°C. Some protocols use **mutanolysin** (which has broader substrate specificity) or skip lysozyme entirely for Gram-negatives, relying on SDS + proteinase K.

---

### PROCEDURE

---

**Q6. Describe the complete step-by-step CTAB method for extraction of chromosomal DNA from Gram-negative bacteria.**

The **CTAB (cetyltrimethylammonium bromide) method** is a classical approach for extracting high-quality, high-molecular-weight chromosomal DNA, particularly useful for organisms with high polysaccharide content.

**Materials:** CTAB lysis buffer (2% CTAB, 1.4 M NaCl, 20 mM EDTA, 100 mM Tris-HCl pH 8.0), proteinase K (20 mg/mL), chloroform:isoamyl alcohol (24:1), isopropanol, 70% ethanol, TE buffer, RNase A.

**Procedure:**
1. **Grow culture**: Grow bacteria overnight in 5–10 mL LB broth at 37°C with shaking
2. **Harvest cells**: Centrifuge at 6,000–8,000 × g for 5 minutes; discard supernatant; resuspend pellet in 567 µL TE buffer
3. **Lyse**: Add 30 µL of 10% SDS and 3 µL proteinase K (20 mg/mL); mix by inversion; incubate at **55°C for 1–2 hours** with occasional mixing until solution clears
4. **CTAB precipitation**: Add 100 µL of 5 M NaCl and 80 µL of CTAB/NaCl solution; mix thoroughly; incubate at **65°C for 10 minutes**
5. **Chloroform extraction**: Add equal volume of **chloroform:isoamyl alcohol (24:1)**; mix by inversion for 5–10 minutes; centrifuge at 12,000 × g for 5 minutes
6. **Transfer aqueous phase**: Transfer upper aqueous phase to a new tube (avoid the white interface — protein/CTAB complex)
7. **Phenol-chloroform extraction (optional)**: Add equal volume phenol:chloroform:isoamyl alcohol (25:24:1); repeat centrifugation; transfer aqueous phase
8. **DNA precipitation**: Add 0.6 volumes isopropanol (or 2 volumes ethanol + 0.1 volume 3M sodium acetate); mix gently until DNA precipitates as a visible white spool/thread
9. **Wash**: Centrifuge at 12,000 × g for 15 minutes; discard supernatant; wash pellet with 70% ethanol; air-dry
10. **Resuspend**: Dissolve DNA pellet in 50–200 µL TE buffer at 4°C overnight (high-molecular-weight DNA dissolves slowly)
11. **RNase treatment**: Add RNase A (20 µg/mL final); incubate 37°C for 30 minutes; re-extract with chloroform if high RNA purity needed
12. **Store at −20°C or 4°C**

---

**Q7. What is the role of SDS in bacterial cell lysis for DNA extraction?**

**SDS (sodium dodecyl sulfate)** is an anionic detergent that plays multiple roles in bacterial lysis:

1. **Membrane solubilization**: SDS disrupts both the cytoplasmic membrane and outer membrane by inserting its hydrophobic dodecyl tail into the lipid bilayer and solubilizing lipid components — effectively dissolving the membrane
2. **Protein denaturation**: SDS denatures proteins by disrupting hydrophobic interactions and coating proteins with negative charge — inactivates nucleases, proteases, and other enzymes that would degrade DNA
3. **Cell lysis**: The combined membrane disruption and protein denaturation causes cell lysis and release of intracellular contents
4. **DNA-histone-like protein dissociation**: Bacterial DNA is associated with histone-like proteins (HU, H-NS, IHF) — SDS denatures and dissociates these, freeing the DNA
5. **Viscosity**: After SDS lysis, the solution becomes highly viscous due to the long chromosomal DNA molecules — this is used as an indicator of successful lysis

**Typical concentration:** 0.5–2% SDS in lysis buffer. Higher concentrations improve lysis but can make subsequent DNA purification more difficult (excess SDS inhibits enzymes and precipitates with K⁺ in downstream steps). SDS is incompatible with CTAB at low salt concentrations (they form a precipitate together) — hence salt concentration must be adjusted when combining protocols.

---

**Q8. What is the role of proteinase K in DNA extraction and what are the conditions required for its activity?**

**Proteinase K** (a serine protease from *Tritirachium album*, EC 3.4.21.64) is the most commonly used protease in DNA extraction protocols:

**Functions:**
1. **Protein digestion**: Cleaves peptide bonds broadly (particularly at aliphatic, aromatic, and hydrophobic residues), destroying nucleases (DNase, RNase) that would degrade the nucleic acids
2. **Nucleoprotein disruption**: Digests proteins bound to DNA (HU, H-NS in bacteria; histones in eukaryotes), releasing free DNA and improving yield and purity
3. **SDS compatibility**: Uniquely active in the presence of **0.5–1% SDS**, which denatures substrate proteins and makes them more accessible to proteolysis — most proteases are inhibited by SDS, but proteinase K is resistant because SDS unfolds its substrates rather than the enzyme
4. **EDTA compatibility**: Active in EDTA-containing buffers (metal-independent serine protease)

**Optimal conditions:**
- **Temperature**: 50–65°C (activity is 2× higher at 60°C than 37°C; elevated temperature also improves lysis and denaturation of substrate proteins)
- **pH**: 7.5–8.0 (active between pH 6.5–9.5)
- **Concentration**: 100–200 µg/mL (20 mg/mL stock solution added to 1:100 ratio)
- **Incubation time**: 1–12 hours (overnight at 55°C gives complete protein digestion)
- **Inactivation**: Proteinase K is inactivated by heating at 95°C for 10 minutes or by phenol-chloroform extraction before sensitive downstream applications

---

**Q9. Explain the phenol-chloroform-isoamyl alcohol (PCI) extraction step in DNA purification. What does each component do?**

**Phenol-chloroform-isoamyl alcohol (PCI) extraction** (25:24:1 ratio) is a liquid-liquid phase separation technique that separates DNA (aqueous phase) from proteins and lipids (organic phase):

**Role of each component:**

**Phenol (25 parts):**
- Denatures proteins by disrupting hydrogen bonds and hydrophobic interactions
- Denatured proteins partition into the organic (phenol) phase or remain at the interface
- Phenol is partially miscible with water — the aqueous phase retains DNA in solution
- Phenol used must be **Tris-saturated (pH 8.0)** — acidic phenol (pH 4.5) causes DNA to partition into the organic phase instead of the aqueous phase

**Chloroform (24 parts):**
- Denatures proteins (complementary to phenol)
- Removes residual phenol from the aqueous phase (phenol and chloroform are miscible; chloroform extracts phenol from the aqueous phase)
- Chloroform is denser than water, helping phase separation
- Breaks up cell membranes and extracts lipids

**Isoamyl alcohol (1 part):**
- **Reduces foaming** during mixing (without it, vigorous mixing creates stable foam that makes phase separation difficult)
- Stabilizes the interface between aqueous and organic phases
- Improves phase separation clarity

**Procedure:** Mix lysate 1:1 with PCI; vortex or invert gently 5–10 min; centrifuge 12,000 × g for 10 min; three layers form — bottom organic phase (yellow phenol), white protein-lipid interface, top aqueous phase (DNA); carefully transfer aqueous phase avoiding interface.

---

**Q10. Why must phenol be Tris-equilibrated to pH 8.0 before use in DNA extraction?**

The **pH of phenol is critical** because it determines how DNA partitions between aqueous and organic phases:

- **At pH < 7.0 (acidic phenol)**: DNA becomes partially protonated and loses its overall negative charge → DNA partitions preferentially into the **organic phase** — DNA is LOST
- **At pH 8.0 (alkaline/neutral phenol)**: DNA remains deprotonated (negatively charged phosphate backbone) → DNA stays in the **aqueous phase** — DNA is RETAINED

RNA, by contrast, can be extracted using acidic phenol (pH 4.5) because RNA also partitions into the aqueous phase at low pH, while **single-stranded DNA and DNA-RNA hybrids** at low pH move to the organic phase. This principle is exploited in the **TRIzol/TriPure** method for RNA extraction — acidic guanidinium-phenol extracts RNA into the aqueous phase while DNA goes to the organic phase.

**Equilibration procedure:** Phenol is equilibrated by repeated washing with **0.1 M Tris-HCl pH 8.0** until the aqueous phase pH reaches 8.0 (checked with pH paper). Phenol from commercial suppliers for molecular biology is pre-equilibrated. Never use phenol directly from the bottle without verifying pH — unequilibrated phenol often has pH 4–6 and will destroy the DNA extraction.

---

**Q11. Describe how ethanol precipitation of DNA works and what role sodium acetate plays.**

**Ethanol precipitation** is the standard method for concentrating and desalting DNA after purification steps.

**Mechanism:**
1. **Salt addition** (e.g., sodium acetate, 0.1–0.3 M): Na⁺ ions neutralize the negative charges on DNA phosphate groups, reducing electrostatic repulsion between DNA strands and allowing them to associate
2. **Ethanol addition** (2–2.5 volumes of ice-cold absolute ethanol): Ethanol has a much lower dielectric constant than water, reducing the solvent's ability to stabilize charged molecules (like DNA) in solution
3. Combined effect: DNA is electrostatically neutralized (by Na⁺) and the solvent can no longer solubilize it → DNA precipitates as a white pellet or spool
4. **RNA and oligonucleotides** (< 100 bp) precipitate less efficiently than high-molecular-weight DNA under standard conditions — providing some size selectivity
5. Proteins remain in solution at low salt concentrations (they precipitate with DNA at high salt — hence salt concentration must be controlled)

**Role of sodium acetate (3 M, pH 5.2, 0.1 volume):**
- Provides Na⁺ for charge neutralization
- Slightly acidic pH improves DNA precipitation efficiency
- Acetate ion does not interfere with downstream enzymatic reactions
- Alternative salts: LiCl (2.5 M, 1/3 volume — better for RNA; worse for proteins that coprecipitate with SDS), ammonium acetate (avoids coprecipitation of dNTPs and primers — used after PCR)

---

**Q12. What is isopropanol precipitation and when is it preferred over ethanol precipitation?**

**Isopropanol (2-propanol) precipitation** is an alternative alcohol precipitation method:

**Comparison:**

| Feature | Ethanol Precipitation | Isopropanol Precipitation |
|---|---|---|
| Volume required | 2–2.5× sample volume | 0.6–1× sample volume (less volume) |
| Temperature | −20°C or −80°C (30 min–overnight) | Room temperature (5–15 min) |
| Speed | Slower (requires cold incubation) | Faster |
| Small fragment precipitation | Poor (<100 bp coprecipitates poorly) | Better precipitation of smaller fragments |
| Salt coprecipitation | Less salt coprecipitation | More salt coprecipitation |
| Residual isopropanol | Harder to remove (higher boiling point) | Key disadvantage — must wash twice with 70% ethanol |
| Suitability | General purpose | Large volumes, quick protocol |

**When isopropanol is preferred:**
- When working with **large volume samples** (isopropanol volume added is much less)
- When a **rapid protocol** is needed
- When precipitating **total chromosomal DNA** visible as spooled material — isopropanol at room temperature allows the DNA spool to be wound onto a glass rod
- When the DNA fragments are large (chromosomal DNA) — all fragment sizes precipitate equally well

**Key requirement:** Isopropanol must be **completely removed** by washing with 70% ethanol before dissolving the DNA pellet, as residual isopropanol inhibits many downstream enzymes.

---

**Q13. What is the role of RNase A treatment in chromosomal DNA preparation and when is it performed?**

After cell lysis, the crude preparation contains both **DNA and RNA** (predominantly rRNA from ribosomes, which constitutes ~85% of total cellular RNA, and mRNA). RNA removal is necessary because:

1. **Spectrophotometric quantitation error**: RNA absorbs at 260 nm just like DNA, so contaminating RNA causes overestimation of DNA concentration
2. **Gel electrophoresis**: RNA migrates as a smear on agarose gels and can obscure the chromosomal DNA band
3. **PCR inhibition**: High RNA concentrations can compete with DNA template-primer interactions
4. **Restriction digestion**: RNA does not affect most RE reactions, but high RNA levels make it difficult to assess completeness of digestion by gel analysis

**RNase A treatment:**
- Add RNase A to a final concentration of **20–100 µg/mL**
- Incubate at **37°C for 30–60 minutes** (or at room temperature for 2 hours)
- RNase A is a pancreatic ribonuclease that cleaves single-stranded RNA at pyrimidine (C, U) residues
- RNase A is active in a wide range of salt and detergent concentrations
- After RNase A treatment, the preparation is re-extracted with PCI (phenol:chloroform) to remove the RNase protein before precipitation
- Alternatively, RNase A is added after DNA precipitation and resuspension — in this case, re-extraction is still needed for highest purity

---

**Q14. How is chromosomal DNA extracted using a commercial spin column kit, and what are the advantages over the classic CTAB method?**

**Commercial kit principle (e.g., Qiagen DNeasy Blood & Tissue Kit adapted for bacteria):**
1. **Pretreatment**: Bacterial pellet resuspended in buffer; lysozyme (and optionally EDTA) added; incubate 37°C for 30 min (Gram-negatives may need shorter pretreatment)
2. **Lysis**: Add lysis buffer (chaotropic guanidinium thiocyanate or guanidinium HCl + SDS); proteinase K added; incubate 56°C for 30 min
3. **Adjust conditions**: Add ethanol to adjust binding conditions; transfer to silica spin column
4. **Bind**: Centrifuge — DNA binds silica membrane in high chaotropic salt + ethanol conditions; proteins, RNA, small molecules flow through
5. **Wash**: Two wash steps with ethanol-containing wash buffer — remove residual proteins, salts, SDS
6. **Elute**: Add low-salt buffer (10 mM Tris, pH 8.0) or water, incubate 1 min, centrifuge — DNA elutes from silica

**Advantages of commercial kit over CTAB:**

| Feature | CTAB Method | Commercial Kit |
|---|---|---|
| Time | 4–6 hours | 1–2 hours |
| Hazardous reagents | Phenol, chloroform, CTAB | None (or minimal) |
| Throughput | Low | High (96-well format available) |
| DNA size | High-MW (>50 kb) | Fragmented (~50 kb max) |
| Purity (A260/A280) | Variable (1.6–1.9) | Consistent (1.8–2.0) |
| Training required | High | Low |
| Cost | Low (reagents) | Higher (kit cost) |

**Disadvantage of kits:** DNA is sheared during the column binding/elution process — maximum fragment size ~50 kb. For applications requiring very high-molecular-weight DNA (>100 kb) such as pulsed-field gel electrophoresis (PFGE) or optical mapping, CTAB or in-gel lysis methods are required.

---

**Q15. What safety precautions must be taken when performing chromosomal DNA extraction from Gram-negative bacteria?**

**Biosafety considerations:**
1. **Containment level**: Work must be performed at the appropriate biosafety level (BSL-1 for non-pathogenic lab strains like *E. coli* K12; BSL-2 for clinical isolates, *Salmonella*, *Pseudomonas aeruginosa*, *Klebsiella*)
2. **Aerosol prevention**: Vortexing bacterial cultures can create aerosols — work in a biosafety cabinet (BSC) for clinical/pathogenic strains
3. **Inactivation before extraction**: Some protocols require autoclaving (121°C, 15 min) or chemical inactivation of the bacterial culture before proceeding with DNA extraction, particularly for BSL-2 organisms

**Chemical safety:**
1. **Phenol**: Highly corrosive; causes chemical burns on contact; toxic by inhalation and absorption — use in fume hood; wear gloves, eye protection, lab coat; phenol burns treated immediately with polyethylene glycol 400
2. **Chloroform**: Suspected carcinogen; hepatotoxic; volatile — use in fume hood; minimize exposure time; dispose as halogenated solvent waste
3. **CTAB**: Skin and respiratory irritant — gloves and mask required
4. **Ethanol**: Flammable — keep away from heat/flame sources during precipitation steps
5. **Proteinase K**: Protease — can digest skin proteins; wear gloves

**Waste disposal:**
- Phenol/chloroform waste: Halogenated organic waste containers
- Bacterial culture waste: Autoclave before disposal
- CTAB solutions: Non-halogenated waste or biohazard waste

---

### CALCULATIONS

---

**Q16. If you start with a 10 mL overnight culture of *E. coli* with OD₆₀₀ = 1.0, estimate the number of cells harvested and the expected DNA yield.**

**Cell number estimation:**
For *E. coli*, OD₆₀₀ of 1.0 ≈ **8 × 10⁸ cells/mL** (this varies with strain and growth conditions; range: 5×10⁸ – 1×10⁹)

Total cells in 10 mL = 10 mL × 8×10⁸ cells/mL = **8 × 10⁹ cells**

**DNA yield estimation:**
*E. coli* chromosome = ~4.6 Mb = 4.6 × 10⁶ bp
Mass of one *E. coli* chromosome:
= 4.6 × 10⁶ bp × 660 Da/bp = 3.04 × 10⁹ Da
= 3.04 × 10⁹ / (6.022 × 10²³) g = 5.05 × 10⁻¹⁵ g = **5.05 fg/chromosome**

Total DNA from 8 × 10⁹ cells (assuming 1 chromosome/cell for simplicity):
= 8 × 10⁹ × 5.05 × 10⁻¹⁵ g = 4.04 × 10⁻⁵ g = **40.4 µg**

**Practical expected yield (accounting for losses during extraction):**
Typical recovery = 50–80% → Expected yield = **20–32 µg**

In reality, cells may have 2–4 chromosomes during active growth (faster growing cells replicate DNA before dividing), so yield may be slightly higher.

---

**Q17. After DNA extraction, spectrophotometric measurement gives: A₂₆₀ = 0.45, A₂₈₀ = 0.25 in a 1 cm cuvette with 50× dilution of the DNA sample. Calculate DNA concentration and purity ratio. Is this acceptable?**

**DNA concentration:**
Using the relationship: A₂₆₀ of 1.0 = 50 µg/mL double-stranded DNA (in 1 cm path length)

Concentration of diluted sample = 0.45 × 50 µg/mL = 22.5 µg/mL

Concentration of undiluted stock = 22.5 µg/mL × 50 (dilution factor) = **1,125 µg/mL = 1.125 mg/mL**

**Purity ratio (A₂₆₀/A₂₈₀):**
= 0.45 / 0.25 = **1.8**

**Interpretation:**
- Pure dsDNA: A₂₆₀/A₂₈₀ = 1.8–2.0 ✓
- Ratio of 1.8 is at the lower acceptable limit — indicates trace protein contamination (proteins absorb at 280 nm due to Trp, Tyr residues)
- If ratio < 1.7: significant protein contamination → repeat PCI extraction
- If ratio > 2.0: RNA contamination (RNA has higher A₂₆₀/A₂₈₀ ratio) → treat with RNase A

**Additional check:** A₂₆₀/A₂₃₀ ratio should be 2.0–2.2; if < 1.8, contaminants such as phenol, chaotropic salts, or EDTA are present (all absorb at 230 nm).

---

**Q18. How do you calculate the molar concentration of chromosomal DNA for use in a Southern blot experiment requiring 5 µg of DNA at 10 µg/mL?**

**Given:** DNA stock concentration = 1.125 mg/mL (from Q17), target = 5 µg at 10 µg/mL.

**Volume to prepare:** V = mass / concentration = 5 µg / 10 µg/mL = **0.5 mL (500 µL)**

**Volume of stock needed:** Using C₁V₁ = C₂V₂:
V₁ = (10 µg/mL × 0.5 mL) / 1125 µg/mL = **4.4 µL of stock**
Volume of TE to add = 500 − 4.4 = **495.6 µL TE buffer**

**Molar concentration of chromosomal DNA molecules:**
*E. coli* chromosome MW = 4.6 × 10⁶ bp × 660 g/mol/bp = 3.04 × 10⁹ g/mol

At 10 µg/mL = 10 × 10⁻⁶ g/mL:
Molar concentration = (10 × 10⁻⁶ g/mL) / (3.04 × 10⁹ g/mol) = **3.29 × 10⁻¹⁵ mol/mL = 3.29 fmol/mL**

This extremely low molar concentration (femtomolar range) illustrates why chromosomal DNA is always quantified by mass (µg/mL) rather than molarity for most applications.

---

**Q19. A DNA pellet after ethanol precipitation is resuspended in 100 µL TE buffer. A₂₆₀ (undiluted, 2 µL in NanoDrop) = 12.5. What is the total DNA yield and the concentration?**

**NanoDrop** measures absorbance using a 1 mm path length (0.1 cm), but automatically corrects for path length and reports results as if measured in a standard 1 cm cuvette.

**Concentration from NanoDrop:**
For dsDNA: Concentration = A₂₆₀ × 50 µg/mL × (1/path length correction)
NanoDrop reports directly: Concentration = A₂₆₀ × 50 µg/mL = 12.5 × 50 = **625 µg/mL**

(NanoDrop internally applies path length correction — the reading is already in µg/mL equivalent to 1 cm path)

**Total yield:**
Total volume = 100 µL = 0.1 mL
Total DNA = 625 µg/mL × 0.1 mL = **62.5 µg**

**Assessment:** 62.5 µg from a 10 mL culture — this is a good yield, slightly above average (expected 20–40 µg), suggesting either a denser culture or efficient extraction. Verify by gel electrophoresis to confirm DNA integrity and absence of RNA contamination.

---

**Q20. In a chromosomal DNA extraction from *E. coli*, you want to achieve a final concentration of 500 ng/µL in 200 µL. You extracted DNA from 5 mL of culture at OD₆₀₀ = 2.0. Is the yield theoretically sufficient?**

**Step 1 — Calculate target amount:** 500 ng/µL × 200 µL = **100,000 ng = 100 µg**

**Step 2 — Theoretical yield from 5 mL at OD₆₀₀ 2.0:**
OD₆₀₀ = 2.0 → approximately 1.6 × 10⁹ cells/mL
Total cells = 5 mL × 1.6×10⁹ = 8 × 10⁹ cells

At OD 2.0, cells are in late exponential/early stationary phase — approximately 2–3 chromosomes per cell (active replication)
Average chromosomes/cell = 2.5
Total chromosomes = 8×10⁹ × 2.5 = 2×10¹⁰

Mass = 2×10¹⁰ × 5.05×10⁻¹⁵ g = 1.01×10⁻⁴ g = **101 µg theoretical DNA**

**Step 3 — Practical yield (50–70% recovery):**
Expected yield = 101 × 0.6 = **~60 µg**

**Conclusion:** The theoretical yield (~101 µg) meets the target, but practical yield (~60 µg) is below the required 100 µg. To achieve 100 µg reliably, start with **at least 10 mL of culture at OD₆₀₀ = 2.0**, or concentrate the final DNA to higher concentration.

---

### TROUBLESHOOTING

---

**Q21. The extracted chromosomal DNA is highly viscous and difficult to pipette. What does this indicate and how should it be handled?**

**High viscosity** of the DNA solution is a **positive sign** — it indicates successful extraction of **high-molecular-weight chromosomal DNA**. Long DNA molecules (>50 kb) form entangled networks that resist flow, creating gel-like, viscous solutions. The longer the DNA, the higher the viscosity.

**Handling high-MW DNA:**
1. **Wide-bore pipette tips**: Use wide-bore or cut-off tips to prevent shearing — forcing viscous DNA through a narrow tip aperture creates high shear stress that breaks the long DNA molecules into smaller fragments
2. **Gentle resuspension**: Never vortex high-MW DNA — invert gently or use a rotary mixer at low speed; allow to dissolve at 4°C overnight
3. **Dilution**: Dilute 1:5 to 1:10 before quantitation to reduce viscosity for accurate pipetting during spectrophotometry
4. **Incubation**: Warm gently to 37°C briefly (no more than 10 minutes) to reduce viscosity for accurate volume measurements

If viscosity is too high for the intended application (e.g., restriction enzyme digestion requiring accurate volume measurements), the DNA can be **mildly sonicated** (brief, low-power pulses) or passed through a narrow-gauge needle (23–25 G) to shear to a working size of 20–50 kb without completely fragmenting.

---

**Q22. After DNA extraction, agarose gel electrophoresis shows a smear instead of a high-molecular-weight band. What went wrong?**

A **DNA smear** on agarose gel (continuous distribution from high to low MW, rather than a distinct high-MW band) indicates **DNA degradation**. Possible causes and solutions:

1. **DNase contamination in reagents**: DNases (particularly DNase I) degrade DNA during extraction. Prevention: add EDTA to all buffers immediately; use DEPC-treated or autoclaved water; ensure all tubes and tips are nuclease-free
2. **Mechanical shearing**: Vigorous vortexing, pipetting through narrow tips, or excessive sonication shears chromosomal DNA. Prevention: use wide-bore tips, gentle mixing throughout
3. **Insufficient proteinase K treatment**: If bacterial nucleases are not inactivated by proteinase K + SDS, they remain active and degrade DNA. Prevention: ensure complete incubation (55°C, 1–2 hours); use adequate proteinase K concentration (200 µg/mL)
4. **Low pH during phenol extraction**: Acidic phenol (pH < 7) degrades DNA and causes it to partition into the organic phase. Prevention: verify phenol pH 8.0 before use
5. **Freeze-thaw cycles**: Repeated freezing and thawing shears DNA. Prevention: store in single-use aliquots; avoid more than 2 freeze-thaw cycles
6. **Bacterial culture in stationary phase**: Dying cells release DNases into the medium. Prevention: harvest cells in late exponential phase (OD₆₀₀ = 0.6–1.5)

---

**Q23. The A₂₆₀/A₂₈₀ ratio of the extracted DNA is 1.5. What contaminant is likely present and how do you remove it?**

A ratio of **1.5 (below 1.7)** indicates **protein contamination** (proteins absorb strongly at 280 nm due to aromatic amino acid residues: Trp, Tyr, Phe).

**Causes:**
- Incomplete phenol-chloroform extraction (interface disturbed during transfer, allowing protein carry-over)
- Insufficient proteinase K digestion
- Omission of the chloroform-only back-extraction step

**Removal:**
1. **Repeat PCI extraction**: Add equal volume of phenol:chloroform:isoamyl alcohol (25:24:1) to the DNA solution; mix gently by inversion 5 minutes; centrifuge; transfer aqueous phase; repeat with chloroform:isoamyl alcohol (24:1) to remove residual phenol
2. **Re-precipitate with ethanol**: After PCI re-extraction, re-precipitate DNA with 0.1 volume sodium acetate and 2 volumes ethanol; wash pellet with 70% ethanol; resuspend in TE; measure A₂₆₀/A₂₈₀ again
3. **Commercial cleanup column**: Pass through a silica column (e.g., Qiagen MinElute) — proteins do not bind silica under high-salt conditions

**Expected A₂₆₀/A₂₈₀ after cleanup:** 1.8–2.0 (pure dsDNA)

---

**Q24. The A₂₆₀/A₂₈₀ is 2.3 (higher than expected). What contaminant is present and what is the remedy?**

A ratio of **2.3 (above 2.0)** indicates **RNA contamination**. RNA has a higher intrinsic A₂₆₀/A₂₈₀ ratio (~2.1–2.3) than dsDNA (~1.8–2.0) because RNA has a higher proportion of adenine-containing bases with higher absorbance at 260 nm relative to 280 nm.

**Confirmation:** Run the sample on a 1% agarose gel — RNA contamination appears as a diffuse smear or distinct rRNA bands (23S and 16S for bacteria, ~3 kb and ~1.5 kb) at the bottom of the gel, below the chromosomal DNA band.

**Remedy:**
1. Add RNase A to the DNA solution: final concentration 20–50 µg/mL; incubate 37°C for 30–60 minutes
2. After RNase A treatment, perform a **PCI extraction** to remove the RNase protein (which would otherwise affect A₂₈₀)
3. Re-precipitate DNA with ethanol
4. Re-measure A₂₆₀/A₂₈₀ — should now be 1.8–2.0

**Prevention:** Add RNase A routinely to the lysis buffer or immediately after lysis, before DNA purification, to eliminate RNA before it can interfere with spectrophotometric quantitation.

---

**Q25. After extraction from *Pseudomonas aeruginosa*, DNA concentration appears high on NanoDrop but PCR amplification fails. What could explain this discrepancy?**

This scenario — high apparent DNA concentration but failed PCR — is a classic sign of **PCR inhibitor contamination**. Potential inhibitors in *P. aeruginosa* DNA preparations:

1. **LPS (lipopolysaccharide)**: *P. aeruginosa* produces an unusually high amount of LPS, which co-purifies with DNA. LPS inhibits Taq polymerase and disrupts Mg²⁺ availability for PCR. Even 1 ng/µL LPS can inhibit PCR.
2. **Alginate (extracellular polysaccharide)**: *P. aeruginosa* mucoid strains produce alginate that co-purifies with DNA and inhibits polymerases
3. **Phenol residues**: If phenol extraction was incomplete, trace phenol (A₂₃₀ elevation) inhibits Taq polymerase at concentrations > 0.1%
4. **EDTA carry-over**: If EDTA concentration in the final DNA exceeds 0.5 mM, it chelates Mg²⁺ in the PCR reaction, inhibiting Taq
5. **SDS residues**: Even trace SDS inhibits Taq polymerase

**Solutions:**
- Dilute DNA 1:10 to 1:100 in PCR-grade water before adding to PCR (dilutes inhibitors without significantly reducing template)
- Use **BSA (100 µg/mL)** in PCR — BSA absorbs many inhibitors
- Use **PCR-grade Taq** with enhanced inhibitor tolerance
- Re-extract using an LPS-reducing protocol (additional chloroform washes or commercial LPS removal kits)
- Quantify using **fluorometric assay** (e.g., Qubit) rather than NanoDrop — NanoDrop overestimates DNA concentration when LPS or polysaccharides are present (they absorb at 260 nm)

---

### APPLICATIONS AND INTERPRETATION

---

**Q26. How does extraction of chromosomal DNA from Gram-negative bacteria differ between different species such as *E. coli*, *Pseudomonas aeruginosa*, and *Klebsiella pneumoniae*?**

Species-specific differences affect extraction protocols:

***E. coli* (most common laboratory organism):**
- Standard CTAB or kit protocols work well
- Standard lysozyme + SDS lysis efficient
- Moderate LPS contamination — one PCI extraction usually sufficient
- Expected yield: 20–50 µg per 10 mL culture

***Pseudomonas aeruginosa*:**
- More resistant to lysozyme than *E. coli* — requires longer EDTA pretreatment (30 min, 65°C) or higher lysozyme concentration, or bead-beating
- High LPS content — extra chloroform washes or LPS removal columns needed
- Mucoid strains produce alginate — add CTAB at higher concentration (2%) to precipitate polysaccharides; use polysaccharide-precipitation step
- Expected yield: 15–40 µg per 10 mL culture

***Klebsiella pneumoniae*:*
- Produces a thick polysaccharide capsule (K-antigen) — major challenge for DNA extraction
- CTAB precipitation is **essential** for capsulated strains — CTAB forms an insoluble complex with polysaccharides at low salt, allowing removal of capsular polysaccharide from the DNA-containing aqueous phase
- Without CTAB, polysaccharides co-precipitate with DNA and severely inhibit downstream applications
- Adjust CTAB concentration to 2–4% and NaCl to >1.2 M for effective polysaccharide removal

---

**Q27. What is PFGE (pulsed-field gel electrophoresis) and why does it require specially prepared chromosomal DNA?**

**PFGE** is an electrophoresis technique that separates very large DNA molecules (100 kb to 10 Mb) that cannot be resolved on conventional agarose gels by alternating the electric field in different directions at set time intervals (switch times). As the field alternates, large DNA molecules must reorient, and their reorientation time is proportional to their size — this allows separation of megabase-sized chromosomal fragments.

**Why standard extracted DNA cannot be used:**
- Conventional extraction methods (CTAB, column kits) inevitably shear chromosomal DNA during vortexing, pipetting, and column binding — resulting in fragments of 20–100 kb maximum
- PFGE requires **intact chromosomal DNA** or DNA cut only by rare-cutting restriction enzymes (e.g., SpeI, XbaI) into fragments of 200 kb – 2 Mb
- DNA sheared below this size cannot be resolved by PFGE

**In-plug (in-gel) lysis method for PFGE:**
1. Bacteria are harvested and **embedded in molten low-melting-point agarose** (forming "plugs")
2. Cell lysis is performed **within the agarose plug** — all steps (detergent lysis, proteinase K digestion, washing) occur in the gel, without any pipetting of the DNA
3. DNA remains intact (not sheared) within the plug
4. Restriction enzymes are diffused into the plug for digestion
5. Plugs are loaded directly into PFGE gel wells

PFGE remains the gold standard for **molecular epidemiology typing** of bacterial pathogens (Salmonella, E. coli O157:H7, MRSA, Klebsiella) despite being largely supplemented by whole-genome sequencing.

---

**Q28. How is chromosomal DNA used in MLST (Multi-Locus Sequence Typing) for bacterial characterization?**

**MLST** is a genotyping method that characterizes bacterial strains based on the sequences of internal fragments of multiple (typically 7) housekeeping genes. Each unique sequence at each locus is assigned an allele number; the combination of allele numbers across all loci defines the strain's **sequence type (ST)**.

**Workflow using chromosomal DNA:**
1. Extract chromosomal DNA (as per standard protocol)
2. PCR-amplify 7 housekeeping gene fragments (e.g., for *E. coli* MLST: *adk, fumC, gyrB, icd, mdh, purA, recA*) using published MLST primers
3. Purify PCR products
4. Sanger sequence the amplicons (both strands)
5. Compare sequences to the MLST database (pubmlst.org) to assign allele numbers
6. Determine ST from the allelic profile

**Requirements for chromosomal DNA in MLST:**
- **Purity**: A₂₆₀/A₂₈₀ ≥ 1.8 (protein contamination would inhibit PCR)
- **Concentration**: 10–50 ng/µL for PCR (high concentration inhibits PCR)
- **Integrity**: Not critical for MLST (short amplicons 400–500 bp) — even partially degraded chromosomal DNA works, unlike for Southern blot or PFGE

**Clinical importance:** MLST identifies high-risk clones such as *K. pneumoniae* ST258 (hypervirulent, carbapenem-resistant), *E. coli* ST131 (fluoroquinolone-resistant, UPEC), enabling infection control and epidemiological monitoring.

---

**Q29. What is the significance of extracting chromosomal vs. total DNA (chromosomal + plasmid) in bacterial genomics?**

In most routine molecular biology applications, **total genomic DNA** (chromosomal + plasmid, if present) is extracted and used without separating the two:
- PCR-based assays amplify specific sequences regardless of whether they are chromosomal or plasmid-encoded
- Whole-genome sequencing sequences all DNA present
- MLST amplifies chromosomal housekeeping genes

However, **selective extraction** is sometimes desired:
- **Plasmid-only extraction** (alkaline lysis miniprep): Used when only plasmid sequences are needed (cloning, plasmid characterization)
- **Chromosomal-only preparation** (eliminating plasmids): Rarely needed in standard work, but for certain Southern blot experiments or genomic library construction, plasmid contamination could produce background bands — plasmids can be removed by ultracentrifugation in CsCl gradient (plasmids and chromosomal DNA band at different densities due to different supercoiling states) or by preferential plasmid retention on alkaline lysis

**Key difference:** Commercial kit "total DNA" extractions for bacteria yield a mixture of chromosomal and plasmid DNA, but for standard-size plasmids (< 50 kb) and chromosomes (> 1 Mb), the mass contribution of plasmid DNA is usually negligible (<5% of total) unless multiple high-copy plasmids are present.

---

**Q30. How do you verify the quality and integrity of extracted chromosomal DNA by agarose gel electrophoresis?**

**Gel electrophoresis quality assessment:**

**Gel setup:** 0.8% agarose in 1× TAE buffer; ethidium bromide (0.5 µg/mL) or SYBR Safe staining; DNA molecular weight marker (lambda DNA/HindIII digest or 1 kb+ ladder with bands up to 10 kb).

**Sample preparation:** Mix 100–200 ng chromosomal DNA with 6× loading dye; load gently (wide-bore tip).

**Expected result for high-quality chromosomal DNA:**
- **A single, high-molecular-weight band** at or above the 48 kb lambda band (chromosomal DNA is too large to resolve discretely on standard 0.8% agarose — appears as a faint high-MW band at the well or just below)
- **No smearing** below the main band (smearing indicates degradation)
- **No distinct low-MW bands** (which would indicate plasmid contamination or RNA)
- **Faint/no RNA band**: 23S and 16S rRNA bands (2.9 kb and 1.5 kb) should be absent if RNase A treatment was effective

**Interpretation guide:**
- Thick smear from well to bottom → severely degraded; not suitable for most applications
- Faint smear below main band → some degradation; acceptable for PCR, not for PFGE or Southern blot
- Sharp high-MW band, clean gel → high-quality DNA; suitable for all applications

---

**Q31. What is CTAB's specific role in precipitation of polysaccharides during chromosomal DNA extraction from capsulated Gram-negative bacteria?**

**CTAB (cetyltrimethylammonium bromide)** is a cationic (positively charged) detergent that forms insoluble complexes with negatively charged polymers, including:
- Polysaccharides (capsular polysaccharides, exopolysaccharides)
- DNA and RNA
- LPS (to some extent)

**Salt-dependent CTAB behavior:**
- **At low salt (<0.5 M NaCl)**: CTAB forms insoluble complexes with BOTH nucleic acids AND polysaccharides — everything precipitates; this is NOT what we want
- **At high salt (>0.7 M NaCl, typically 1.4 M)**: CTAB complexes with polysaccharides remain insoluble and precipitate, while CTAB-nucleic acid complex remains in solution — selective precipitation of polysaccharides

**Mechanism for capsulated bacteria:**
1. Raise NaCl concentration to 1.4 M in the lysate
2. Add CTAB (2% final concentration) → CTAB binds and precipitates polysaccharides at this high salt
3. Centrifuge → CTAB-polysaccharide complex pellets; DNA-CTAB complex remains in supernatant (at high salt, the DNA-CTAB complex is soluble)
4. Lower the salt by adding water or low-salt buffer to the supernatant
5. When salt drops below 0.5 M, DNA-CTAB complex precipitates → visible white fibrous precipitate
6. Dissolve DNA-CTAB complex in 1.2 M NaCl; extract with PCI; precipitate DNA with ethanol

This differential salt-dependent behavior of CTAB is the reason it is so valuable for organisms that produce abundant polysaccharides.

---

**Q32. Compare the DNA extraction results from Gram-negative bacteria grown in different phases: lag, exponential, and stationary phase. Which is optimal?**

| Growth Phase | OD₆₀₀ | Cell Number | DNA/Cell | DNA Condition | Extraction Outcome |
|---|---|---|---|---|---|
| **Lag** | <0.1 | Very low | 1 chromosome | Intact | Low yield (insufficient cells) |
| **Early exponential** | 0.2–0.5 | Moderate | 2–4 chromosomes (replicating) | Intact, high content | Good yield, excellent quality |
| **Mid exponential** | 0.5–1.5 | High | 2–4 chromosomes | Intact, maximum content | **OPTIMAL**: best yield AND quality |
| **Late exponential** | 1.5–2.5 | Very high | 1–2 chromosomes | Intact | Good yield, good quality |
| **Stationary** | >2.5 | Maximum | 1 chromosome | Beginning degradation (nucleases released) | Acceptable yield, risk of degradation |
| **Death phase** | Declining | Decreasing | <1 chromosome | Degraded (autolysis) | Poor yield, degraded DNA |

**Recommendation:** Harvest bacteria at **mid-exponential phase (OD₆₀₀ = 0.6–1.5)** for optimal chromosomal DNA extraction. At this phase:
- Cells are metabolically active with maximum DNA synthesis (highest chromosomes/cell)
- Cell membranes are intact (no autolysis, minimal nuclease release)
- Cells lyse efficiently with standard protocols
- DNA is intact and undegraded

---

### ADVANCED / APPLICATION QUESTIONS

---

**Q33. What is the CsCl-ethidium bromide density gradient ultracentrifugation method for DNA purification and when is it used?**

**CsCl-EtBr density gradient ultracentrifugation** is the classical method for preparing extremely pure, high-molecular-weight chromosomal DNA, now largely replaced by simpler methods but still used for critical applications:

**Principle:**
1. DNA is mixed with CsCl solution to a density of ~1.55 g/mL and ethidium bromide (200 µg/mL)
2. Centrifugation at **100,000–150,000 × g for 36–48 hours** in an ultracentrifuge creates a CsCl density gradient
3. DNA molecules band at a density corresponding to their buoyant density in CsCl:
   - **Linear chromosomal dsDNA**: bands at ~1.70 g/mL (appears as lower band when EtBr is present — EtBr intercalation lowers density)
   - **Covalently closed circular (supercoiled) plasmid DNA**: bands at slightly higher density (~1.75 g/mL with EtBr — less EtBr intercalation due to torsional constraint — appears as upper band)
   - **RNA**: pellets (too dense)
   - **Proteins**: float (too light)
4. Bands are visualized under UV and collected by needle puncture

**When used:**
- Preparing extremely pure chromosomal DNA for sequencing reference libraries
- Separating plasmid from chromosomal DNA when plasmid DNA must be isolated cleanly from total genomic DNA preparations
- Historical method for preparing high-purity plasmid DNA (now replaced by miniprep/midiprep kits)
- Research requiring endotoxin-free, very high purity DNA for transfection

**Disadvantages:** Requires ultracentrifuge, toxic EtBr, hazardous CsCl, 48 hours, specialized equipment — rarely justified when commercial kits provide adequate purity for most applications.

---

**Q34. How is the CTAB extraction method modified for bacteria with high lipid content, such as mycobacteria?**

While mycobacteria are not Gram-negative, they present unique challenges relevant to lysis chemistry. For **high lipid organisms** (Gram-negative bacteria with unusually high lipid content in their membranes, such as certain *Burkholderia* species or mycolactone-producing bacteria):

**Modifications to standard CTAB protocol:**

1. **Extended lysozyme treatment**: Some fatty acid-rich bacteria require lysozyme treatment for 2–4 hours at 37°C with EDTA (0.5 M) to permeabilize the thick lipid-protein outer membrane
2. **Additional detergent step**: SDS concentration may be increased to 1–2% and proteinase K incubation extended to 55°C overnight
3. **Multiple PCI extractions**: Lipids partition into the organic phase during PCI extraction, but lipid-rich organisms require 3–4 sequential PCI extractions to remove all lipid material
4. **Chloroform back-extraction**: A chloroform-only (no phenol) extraction step after PCI helps remove residual lipids and phenol without risk of DNA loss to organic phase
5. **Alternative lysis (bead-beating)**: For organisms with very high lipid content, mechanical lysis (bead-beating with 0.1 mm glass beads) is more reliable than chemical lysis alone
6. **Hexadecyltrimethylammonium bromide (HTAB)** — a longer-chain CTAB analog — may be used for better precipitation of lipopolysaccharide-protein complexes from lipid-rich organisms

---

**Q35. What is the impact of LPS on downstream molecular biology applications and how is it removed from chromosomal DNA preparations?**

**LPS (lipopolysaccharide/endotoxin)** is a major component of the Gram-negative outer membrane that co-purifies with DNA during extraction. It is a potent inhibitor of many molecular biology reactions:

**Effects of LPS contamination:**
- **PCR inhibition**: LPS at >1 ng/µL inhibits Taq polymerase (binds and denatures the polymerase)
- **Restriction enzyme inhibition**: LPS at high concentrations chelates Mg²⁺ required by restriction enzymes
- **Transformation efficiency**: LPS inhibits bacterial transformation (reduced competence)
- **Transfection toxicity**: LPS activates NF-κB in mammalian cells, causing cell death during DNA transfection experiments
- **Animal experiments**: LPS causes endotoxin shock in animals; DNA preparations for in vivo use must be endotoxin-free (<1 EU/µg DNA)

**LPS removal methods:**
1. **Triton X-114 phase partition**: Mix DNA with 1% Triton X-114; incubate at 37°C; LPS partitions into detergent-rich phase that separates from DNA-containing aqueous phase upon centrifugation — can remove >99% LPS
2. **EndoTrap HD (column chromatography)**: Commercial column that specifically binds LPS via polymyxin B ligand — DNA passes through while LPS is retained
3. **Additional chloroform extractions**: Multiple PCI extractions remove lipid components including LPS
4. **Limulus Amebocyte Lysate (LAL) assay**: Used to **measure** residual LPS — not to remove it; acceptable limit for in vitro applications: <1 EU/µg; for in vivo: <0.1 EU/µg

---

**Q36. How would you extract chromosomal DNA from a biofilm-forming Gram-negative bacterium such as *Pseudomonas aeruginosa* grown as a biofilm?**

Biofilm cells present unique challenges compared to planktonic (free-swimming) cells:

**Challenges:**
1. **Extracellular polymeric substances (EPS)**: Biofilm matrix contains polysaccharides (alginate in *P. aeruginosa*), extracellular DNA (eDNA), and proteins — all co-purify with chromosomal DNA
2. **Altered cell physiology**: Biofilm cells have different membrane composition and metabolic state — standard lysis conditions may not be optimal
3. **Reduced cell accessibility**: Cells within the biofilm matrix are harder to reach with lytic agents

**Modified extraction protocol:**
1. **Harvest biofilm**: Scrape biofilm from surface with sterile cell scraper or loop; resuspend in PBS; vortex vigorously to homogenize
2. **DNase I treatment (to remove eDNA)**: Add DNase I (10 U/mL) to the biofilm suspension; incubate 37°C, 30 minutes — this degrades the eDNA component in the EPS matrix (eDNA is extracellular and not in cells); wash cells to remove degraded eDNA and add EDTA to inactivate DNase before lysis
3. **CTAB extraction**: Use high CTAB (4%) and high NaCl (1.4 M) to precipitate alginate and other polysaccharides
4. **Bead-beating**: Include mechanical disruption to ensure complete lysis (biofilm cells can be harder to lyse than planktonic)
5. **Multiple polysaccharide removal steps**: May need 2 CTAB precipitation steps
6. **Validate with PCR and gel**: Confirm intracellular chromosomal DNA is amplifiable and check purity ratios

---

**Q37. What molecular markers are used to assess the success of chromosomal DNA extraction by PCR?**

After chromosomal DNA extraction, **PCR amplification of housekeeping genes** is used as a functional verification:

**Commonly used markers:**

1. ***16S rRNA gene* (universal bacterial marker):**
   - Amplify with universal primers (e.g., 8F/1492R for ~1.5 kb product, or V3-V4 region ~400 bp)
   - Presence of expected band confirms chromosomal DNA was successfully extracted and is PCR-amplifiable
   - Can also be sequenced for species confirmation

2. ***gyrB* (DNA gyrase B subunit):**
   - More discriminatory than 16S for species identification
   - 1.2 kb product; amplifies from most Gram-negatives with conserved primers

3. ***recA* gene:**
   - DNA repair gene present in all bacteria; used in MLST schemes
   - 400–500 bp product

4. **Species-specific markers:**
   - *E. coli*: *uidA* (β-glucuronidase gene) — specific for *E. coli*
   - *P. aeruginosa*: *ecfX* gene — species-specific
   - *Klebsiella*: *phoE* gene — species-specific

**Negative controls:**
- Water negative control — confirms no contamination in PCR reagents
- Extraction negative control (no cells) — confirms no environmental DNA contamination

A successful amplification of the expected product confirms: (1) cells were lysed, (2) DNA was released, (3) DNA is intact enough for PCR amplification, and (4) inhibitors are at acceptable levels.

---

**Q38. How is chromosomal DNA extraction from Gram-negative bacteria performed for whole-genome sequencing (WGS), and what specific quality requirements must be met?**

**WGS of bacteria** now uses next-generation sequencing (NGS) platforms (Illumina, Nanopore, PacBio). DNA quality requirements vary by platform:

**For Illumina (short-read, ~150–300 bp reads):**
- Concentration: **≥ 50 ng/µL** (minimum 1 µg total preferred)
- Purity: A₂₆₀/A₂₈₀ = 1.8–2.0; A₂₆₀/A₂₃₀ ≥ 2.0
- Fragment size: **Does not matter** — Illumina library prep shears DNA to ~300–500 bp anyway
- Can use commercial kit (DNeasy, MagNA Pure) — size fragmentation is acceptable
- RNA must be removed (RNase treatment mandatory)

**For Nanopore/PacBio (long-read, 10 kb–Mb reads):**
- Concentration: **≥ 400 ng/µL** (need several micrograms)
- Fragment size: **Critical — must be >10 kb, ideally >50 kb** for meaningful long reads
- Must use CTAB or in-gel method — NO vortexing, NO column kits (which shear DNA)
- Wide-bore tips throughout; no bead-beating
- Purity: Same as above

**Validation before library prep:**
- NanoDrop for purity
- Qubit fluorometer for accurate concentration (NanoDrop overestimates in presence of RNA/LPS)
- **Tapestation or Bioanalyzer** for fragment size distribution — essential for long-read sequencing to confirm fragments are >20 kb

---

**Q39. What is the difference between extracting chromosomal DNA for Southern blotting versus PCR? How does the required quality differ?**

| Application | Southern Blot | PCR |
|---|---|---|
| DNA integrity requirement | **High** — DNA must be intact (>20–50 kb) to produce clear restriction fragments | **Lower** — fragments only need to be >amplicon size (0.1–3 kb) |
| Amount required | 10–20 µg (large amounts needed for blotting) | 1–100 ng (very small amount) |
| Purity requirement | High (A₂₆₀/A₂₈₀ 1.8–2.0; no RNA to create background) | Moderate (A₂₆₀/A₂₈₀ >1.7; inhibitor-free) |
| RNA contamination | Must be removed (RNase treatment) — RNA creates background on Southern blot | Must be removed if quantitating; some contamination tolerable if not quantitative |
| Extraction method | CTAB preferred (higher-MW DNA) | Any method including commercial kits |
| Shearing tolerance | Very low — mechanical stress must be minimized throughout | Moderate — partially sheared DNA still has intact target sequences |
| Verification | Gel electrophoresis confirming intact high-MW band + test restriction digest showing expected band pattern | PCR with positive/negative controls |

**Southern blot specifics:**
- Requires DNA to be cut cleanly by restriction enzymes into defined fragments
- If DNA is already fragmented (degraded), the restriction digest produces a smear instead of discrete bands
- Probes must be able to hybridize to genomic fragments of defined expected sizes

---

**Q40. How is the chromosomal DNA extraction approach modified when working with a viable but non-culturable (VBNC) state of a Gram-negative pathogen?**

**VBNC (Viable But Non-Culturable) bacteria** are cells that cannot be grown on standard culture media but remain metabolically active. VBNC state is entered in response to stress (starvation, temperature extremes, disinfectant exposure) by pathogens including *E. coli*, *Vibrio cholerae*, *Campylobacter*, *Salmonella*.

**Challenges for DNA extraction from VBNC cells:**
1. **Cannot culture for cell amplification** — must extract from environmental samples with low cell numbers
2. **VBNC cells have altered membrane composition** — increased fatty acid unsaturation, modified LPS — may be more resistant to standard lysis
3. **Low biomass** — environmental samples may have 10³–10⁶ cells/mL versus 10⁸–10⁹/mL in laboratory culture

**Modified approach:**
1. **Concentrate cells**: Large-volume filtration (500 mL–1 L through 0.2 µm membrane filter) to concentrate cells from environmental samples
2. **Direct lysis on filter**: Perform lysis directly on the filter membrane (bead-beating most effective for environmental samples)
3. **Commercial kits for environmental DNA**: Kits optimized for soil or water samples (e.g., PowerSoil, PowerWater — Mo Bio/Qiagen) include mechanical disruption (bead-beating) and are designed to handle inhibitor-rich matrices
4. **PCR-based detection only**: For VBNC organisms, viability assays (EMA- or PMA-PCR — ethidium or propidium monoazide blocks PCR from dead cell DNA) combined with chromosomal DNA extraction allow detection of VBNC specifically

---

**Q41. What is the role of sodium chloride in the CTAB lysis buffer and how does its concentration affect the extraction?**

**NaCl concentration** in the CTAB extraction method is critical because it determines CTAB's selectivity for polysaccharides vs. nucleic acids:

**At different NaCl concentrations:**
- **<0.5 M NaCl**: CTAB binds and precipitates ALL negatively charged polymers — nucleic acids AND polysaccharides coprecipitate together. This is not useful for DNA isolation.
- **~1.2 M NaCl**: CTAB preferentially precipitates polysaccharides; nucleic acids remain in solution. This is the optimal concentration for **polysaccharide removal** from the lysate.
- **>1.4 M NaCl**: Even more selective — polysaccharides precipitate while nucleic acids and CTAB-nucleic acid complexes remain soluble.
- **After lowering salt to <0.5 M**: CTAB-nucleic acid complex precipitates from the high-salt supernatant.

**NaCl also functions to:**
1. Stabilize cell membranes osmotically before lysis
2. Provide ionic strength needed for protein denaturation in conjunction with SDS
3. Facilitate phase separation during subsequent PCI extraction
4. Stabilize extracted DNA (moderate ionic strength prevents DNA denaturation)

**Standard CTAB buffer composition:** 1.4 M NaCl + 20 mM EDTA + 100 mM Tris-HCl (pH 8.0) + 2% CTAB — the 1.4 M NaCl ensures selective polysaccharide precipitation when CTAB is added at this salt concentration.

---

**Q42. How do you extract chromosomal DNA from a Gram-negative bacterium resistant to standard lysis methods (e.g., carbapenem-resistant *Acinetobacter baumannii*)?**

*Acinetobacter baumannii* and other carbapenem-resistant Gram-negatives often have modified LPS and altered outer membrane compositions that increase resistance to lysis:

**Modified lysis strategies:**

1. **Physical disruption first:**
   - **Bead-beating** (FastPrep instrument, 0.1 mm zirconia beads, 6 m/s for 3 × 30 seconds with 1 min on ice between) — most reliable for difficult-to-lyse Gram-negatives
   - **Freeze-thaw cycling** (5× between liquid nitrogen and 37°C) — breaks cells by ice crystal formation; less damaging to DNA than bead-beating

2. **Enhanced chemical lysis:**
   - Extend EDTA pretreatment to **100 mM EDTA at 65°C for 30 minutes** before lysozyme
   - Increase SDS to 2% (vs. standard 1%)
   - Proteinase K at 200 µg/mL overnight at 55°C

3. **Combined approach (most effective for *A. baumannii*):**
   - Resuspend in TE + 100 mM EDTA
   - Add lysozyme 10 mg/mL + incubate 65°C 30 min
   - Add SDS 2% + proteinase K 200 µg/mL + incubate 55°C overnight
   - Then proceed with CTAB protocol as standard

4. **Commercial kits with bead-beating**: Mo Bio UltraClean Microbial DNA Kit or similar kits incorporating bead-beating step are designed specifically for difficult-to-lyse bacteria

---

**Q43. How does temperature during lysis affect the quality of extracted chromosomal DNA from Gram-negative bacteria?**

Temperature during lysis affects multiple aspects of DNA extraction quality:

**Low temperature (4°C lysis):**
- Pros: Reduces DNase activity; minimizes DNA degradation by thermal hydrolysis; preferred if working with RNase-sensitive applications
- Cons: Lysis efficiency is low — SDS and CTAB solubilize membranes poorly at cold temperatures; proteinase K activity is low (<10% of 55°C activity)
- Outcome: Incomplete lysis, low yield, but preserved DNA integrity

**Optimal temperature (55–65°C lysis):**
- 55–65°C: Optimal for proteinase K (maximum activity); SDS efficiently solubilizes both membranes; CTAB fully dissolved and active; most bacterial DNases are inactivated at these temperatures (DNase I Tm ~55°C in SDS)
- **Standard protocol**: incubate lysate at 55°C for 1–2 hours after adding SDS + proteinase K
- Outcome: Complete lysis, maximum yield, DNA intact (DNases inactivated by SDS + heat)

**High temperature (>70°C):**
- Pros: Kills all bacteria; inactivates all nucleases; necessary for certain resistant organisms
- Cons: Above 70°C, DNA begins to denature (Tm of bacterial DNA ~85–90°C in standard salt) and some non-enzymatic depurination occurs; SDS may crystallize and need to be resolubilized
- Outcome: Good lysis but some DNA quality compromise

**Recommendation:** Lysis at **55–65°C with SDS + proteinase K** for 1–12 hours is optimal for most Gram-negative bacteria — balancing complete lysis, enzyme inactivation, and DNA preservation.

---

**Q44. What is the difference between extracting chromosomal DNA for diagnostic PCR versus for research genomics? How does this affect your choice of protocol?**

| Criteria | Diagnostic PCR | Research Genomics |
|---|---|---|
| Turnaround time | Urgent (2–4 hours) | Flexible (days) |
| Sample number | High throughput (50–200/day) | Low (10–20 samples) |
| Amount of DNA needed | 1–10 ng per PCR reaction | 1–50 µg for sequencing/library prep |
| Purity requirement | Moderate (inhibitor-free) | High (A260/A280, A260/A230) |
| Fragment size | Any (short amplicons) | High-MW for long-read sequencing |
| Automation | Required (robotic extraction) | Manual or semi-automated |
| Regulatory compliance | Clinical standards (ISO 15189, CE-IVD validated kits) | Research standards (GLP) |
| Preferred method | Magnetic bead kits (automated), column kits | CTAB, column kits, in-gel lysis |
| Validation | Clinical validation (sensitivity, specificity, LOD) | Scientific validation (purity, yield, gel integrity) |

**For diagnostic PCR:** Commercial validated kits (e.g., Qiagen EZ1 Advanced, bioMérieux NucliSENS) on automated platforms provide standardized, reproducible results meeting regulatory requirements. Speed and reproducibility outweigh purity for single-target PCR diagnostics.

**For research genomics (WGS, comparative genomics, Southern blot):** Manual CTAB or optimized column methods with careful attention to DNA integrity and purity are preferred. The additional time investment is justified by the higher quality requirements of these applications.

---

**Q45. How is chromosomal DNA from Gram-negative bacteria used in Southern blot hybridization, and what are the steps from extraction to hybridization?**

**Southern blot workflow** using bacterial chromosomal DNA:

**Step 1 — DNA extraction:** CTAB method to obtain high-MW DNA (>50 kb); concentration ≥ 1 µg/µL; A₂₆₀/A₂₈₀ 1.8–2.0; RNase A treated.

**Step 2 — Restriction digestion:** Digest 10–20 µg DNA with appropriate restriction enzyme(s) for 4–16 hours at 37°C in appropriate buffer; check completeness on mini-gel.

**Step 3 — Agarose gel electrophoresis:** Run digested DNA on 0.8–1% agarose TAE gel; include λ/HindIII marker; run at low voltage (30V, overnight) for maximum resolution of large fragments.

**Step 4 — Gel treatment:** 
- Depurination: 0.25 M HCl, 10 min (nicks large DNA for efficient transfer)
- Denaturation: 0.5 M NaOH + 1.5 M NaCl, 30 min (denatures DNA to ssDNA)
- Neutralization: 1 M Tris-HCl pH 7.5 + 1.5 M NaCl, 30 min

**Step 5 — Transfer:** Transfer DNA from gel to **nylon or nitrocellulose membrane** by capillary transfer overnight (upward or downward), vacuum transfer, or electroblotting.

**Step 6 — Fixation:** UV crosslink (auto-crosslink setting, 120 mJ/cm²) or bake (80°C, 2 hours) — covalently binds DNA to membrane.

**Step 7 — Hybridization:** Block membrane; hybridize with labeled probe (radioactive ³²P or digoxigenin-labeled) at 65°C overnight in hybridization buffer.

**Step 8 — Washing and detection:** Wash off non-specific probe; detect signal by autoradiography (⁃²P) or colorimetric/chemiluminescent detection (DIG).

---

**Q46. Describe the in-gel lysis method for preparing chromosomal DNA of high molecular weight for PFGE.**

**In-gel lysis (agarose plug method):** This method preserves DNA integrity by preventing all mechanical and most chemical shearing.

**Complete procedure:**
1. **Culture preparation**: Grow bacteria to mid-log phase (OD₆₀₀ = 0.6–1.0); harvest by centrifugation
2. **Cell suspension**: Resuspend in SE buffer (75 mM NaCl, 25 mM EDTA pH 7.5) at 10⁸–10⁹ cells/mL
3. **Plug preparation**: Mix cell suspension 1:1 with **1.6% low-melting-point agarose** (warmed to 55°C); pipette quickly into plug molds; allow to solidify at 4°C for 15 minutes
4. **Lysis I — Cell wall degradation**: Transfer solidified plugs to 5 mL EC lysis buffer (6 mM Tris-HCl pH 7.5, 1 M NaCl, 100 mM EDTA, 0.5% Brij-58, 0.2% deoxycholate, 0.5% sarkosyl, 1 mg/mL lysozyme); incubate 37°C, 4–16 hours with gentle agitation
5. **Lysis II — Protein digestion**: Transfer plugs to ES buffer (500 mM EDTA pH 9.0, 1% sarkosyl) + proteinase K (1 mg/mL); incubate 50°C, 16–48 hours — DNA is released and proteins fully digested within the plug
6. **Washing**: Wash plugs 4× with TE buffer, 30 minutes each at 4°C — removes EDTA, SDS, protein fragments
7. **Storage**: Store plugs in TE at 4°C — stable for months to years
8. **Restriction digestion**: Transfer plug slice to restriction enzyme buffer; add enzyme; digest at appropriate temperature (typically 37°C, 4–16 hours)
9. **Load and run PFGE**: Load plug slice into PFGE gel well; seal with agarose; run PFGE

---

**Q47. What are the common Gram-negative bacteria from which chromosomal DNA is extracted in a clinical microbiology research laboratory, and what specific modifications are needed for each?**

**Common organisms and modifications:**

***Escherichia coli*:**
- Standard protocol (CTAB or kit) works well
- No special modifications needed for non-mucoid lab strains
- For O157:H7 and other pathogenic strains: BSL-2 containment; use autoclaved or heat-killed cells for extraction

***Klebsiella pneumoniae*:**
- Capsulated strains require CTAB at 2–4% + high NaCl (1.4 M) for polysaccharide removal
- Carbapenem-resistant strains (KPC, NDM, OXA): BSL-2 with special containment

***Pseudomonas aeruginosa*:**
- Mucoid strains: extended CTAB precipitation; consider 3× CTAB washes
- Multiple extra PCI extractions for LPS removal
- Bead-beating may be needed for biofilm cultures

***Salmonella* spp.:**
- BSL-2 containment
- Standard CTAB or kit; no unique modifications for common serovars
- For extraintestinal salmonellosis strains with Vi capsule (*S.* Typhi): CTAB polysaccharide removal step needed

***Haemophilus influenzae*:**
- Fastidious organism — requires X and V factors in growth medium (chocolate agar/broth)
- DNA extraction straightforward once sufficient biomass obtained
- Encapsulated type b strains: CTAB polysaccharide removal

***Neisseria gonorrhoeae/meningitidis*:**
- BSL-2 (*N. meningitidis*) — containment critical
- Autolysis-prone — must process immediately after harvesting
- Standard kit-based extraction works; capsule removal needed for *N. meningitidis*

---

**Q48. How would you troubleshoot a scenario where the chromosomal DNA extraction consistently fails to yield any DNA, despite following the standard protocol?**

**Systematic troubleshooting of zero yield:**

**Step 1 — Verify bacterial growth:**
- Confirm OD₆₀₀ before harvesting — if culture did not grow (OD < 0.2), yield will be zero
- Check culture on agar plate for growth; verify incubation conditions (temperature, oxygen)

**Step 2 — Verify cell harvest:**
- After centrifugation, confirm visible cell pellet; if no pellet, cells did not grow or centrifuge speed was too low
- Increase centrifugation to 8,000 × g

**Step 3 — Verify lysis:**
- After adding SDS and incubating, solution should become **viscous and clear** (DNA-SDS complex makes it viscous; lysis clears turbidity)
- If solution remains turbid and non-viscous after 1–2 hours at 55°C, lysis failed — increase SDS to 2%, proteinase K to 200 µg/mL, or add lysozyme pretreatment

**Step 4 — Verify precipitate formation:**
- After alcohol precipitation, DNA pellet should be visible (may be very small)
- If no pellet: salt was insufficient (add sodium acetate), ethanol was not cold, or DNA concentration was very low
- Increase precipitation efficiency: add glycogen (20 µg) as carrier; incubate at −80°C for 30 min

**Step 5 — Check reagents:**
- Test with a known-good DNA sample — if it also fails, reagent problem
- Replace ethanol, sodium acetate, TE buffer; verify EDTA was added to all lysis buffers

**Step 6 — Verify spectrophotometer:**
- A₂₆₀ reading of 0 may indicate machine malfunction or incorrect blanking; run a positive control (commercial λ DNA)

---

**Q49. What are the ethical and biosafety considerations when extracting chromosomal DNA from clinical Gram-negative bacterial isolates?**

**Biosafety considerations:**

**Risk assessment:**
- All clinical isolates must be assigned a risk group (RG) — most non-sporulating Gram-negatives are RG2; exceptions include *Burkholderia pseudomallei* (RG3), *Y. pestis* (RG3)
- Work must be performed in appropriate containment (BSL-2 for most clinical Gram-negatives)

**Before extraction:**
- Confirm organism identity and antibiotic resistance profile before beginning
- Multi-drug-resistant organisms (MRSA, CR-KPN, CRKP) require enhanced precautions
- All work in a **Class II biosafety cabinet** — never open tubes or vortex outside the BSC
- Personal protective equipment: gloves, lab coat, eye protection

**Inactivation options:**
- Heat-killing at 80°C for 30 minutes before extraction reduces risk but may affect DNA quality
- Chemical inactivation with guanidinium lysis buffer (provided in commercial kits like Qiagen) simultaneously inactivates pathogens and initiates lysis

**Ethical considerations:**
- Clinical isolates from patients are personal health information — handle under data protection regulations (GDPR in EU, HIPAA in US)
- Patient-linked isolates must be anonymized or handled under appropriate consent protocols
- Genomic data from whole-genome sequencing of clinical isolates must be stored securely with access controls
- Approval from institutional biosafety committee (IBC) and ethics committee for research using clinical isolates

**Disposal:**
- All cultures, supernatants, and DNA preparations from clinical BSL-2 organisms must be autoclaved before disposal
- Contaminated plasticware: biohazard bags for autoclave; sharps in sharps containers

---

**Q50. Design a complete, optimized protocol for extracting chromosomal DNA from Gram-negative *Klebsiella pneumoniae* capsulated clinical isolate for whole-genome sequencing by Illumina platform, including all quality control steps and documentation.**

---

**COMPLETE PROTOCOL: Chromosomal DNA Extraction from *K. pneumoniae* for Illumina WGS**

---

**MATERIALS:**
- CTAB lysis buffer: 2% CTAB, 1.4 M NaCl, 20 mM EDTA, 100 mM Tris-HCl pH 8.0
- Lysozyme (100 mg/mL stock in 10 mM Tris-HCl pH 8.0)
- Proteinase K (20 mg/mL stock)
- RNase A (10 mg/mL stock)
- Chloroform:isoamyl alcohol (24:1)
- Phenol:chloroform:isoamyl alcohol (25:24:1), pH 8.0
- Isopropanol (molecular biology grade)
- 70% ethanol (freshly prepared with nuclease-free water)
- 3 M sodium acetate (pH 5.2)
- TE buffer (10 mM Tris-HCl pH 8.0, 1 mM EDTA)
- Nuclease-free water

**BIOSAFETY:**
- *K. pneumoniae* is BSL-2
- All work until complete lysis: Class II BSC
- PPE: double gloves, lab coat, eye protection
- Confirmed culture identity and antibiotic susceptibility pattern on file

**DAY 1 — CULTURE AND HARVEST:**
1. Inoculate 10 mL LB broth from single colony; incubate 37°C, 200 rpm overnight
2. Measure OD₆₀₀ (target: 1.5–2.5); record OD
3. In BSC: Transfer to sterile 15 mL centrifuge tube; centrifuge 6,000 × g, 5 min; discard supernatant into 10% bleach
4. Resuspend pellet in 1 mL TE buffer in BSC

**DAY 1 — LYSIS:**
5. Add 10 µL lysozyme (final 1 mg/mL); add 10 µL RNase A (final 100 µg/mL); incubate 37°C, 30 min
6. Add 100 µL 10% SDS + 10 µL proteinase K (20 mg/mL); mix gently by inversion; incubate 55°C, 2 hours (or overnight); solution should be clear and viscous
7. (Now safe to take out of BSC — SDS inactivates bacteria)

**POLYSACCHARIDE REMOVAL (CTAB-specific for *K. pneumoniae*):**
8. Add 200 µL 5 M NaCl (to raise NaCl to ~1.4 M)
9. Add 150 µL CTAB/NaCl solution (10% CTAB in 0.7 M NaCl); mix thoroughly; incubate 65°C, 10 min
10. Centrifuge 12,000 × g, 5 min; transfer supernatant to new tube (leave white CTAB-polysaccharide pellet behind)

**DNA PURIFICATION:**
11. Add equal volume PCI (25:24:1 phenol:chloroform:isoamyl alcohol, pH 8.0) to supernatant; mix by inversion 10 min; centrifuge 12,000 × g, 10 min
12. Carefully transfer aqueous (upper) phase to new tube
13. Repeat step 11–12 once more
14. Add equal volume chloroform:isoamyl alcohol (24:1); mix by inversion 5 min; centrifuge 12,000 × g, 5 min; transfer aqueous phase

**DNA PRECIPITATION:**
15. Add 0.1 volume 3 M sodium acetate (pH 5.2); add 0.7 volumes isopropanol; mix gently; incubate room temperature 15 min (DNA should spool)
16. Centrifuge 12,000 × g, 15 min; discard supernatant
17. Wash pellet with 500 µL ice-cold 70% ethanol; centrifuge 12,000 × g, 5 min; remove supernatant completely
18. Air-dry pellet 10 min at room temperature (do not over-dry)
19. Resuspend in 100 µL TE buffer; incubate 4°C overnight (high-MW DNA dissolves slowly; use wide-bore tips)

**QC MEASUREMENTS:**
20. **NanoDrop**: Measure A₂₆₀, A₂₈₀, A₂₃₀; calculate A₂₆₀/A₂₈₀ and A₂₆₀/A₂₃₀; concentration
    - Accept: A₂₆₀/A₂₈₀ 1.8–2.0; A₂₆₀/A₂₃₀ ≥ 2.0
21. **Qubit fluorometer**: dsDNA BR or HS assay for accurate fluorometric quantitation
    - Accept: ≥ 50 ng/µL (required for Illumina library prep)
22. **Agarose gel**: Run 200 ng on 0.8% agarose; expect high-MW band ≥ 20 kb, no smear, no RNA bands
23. **PCR validation**: PCR-amplify 16S rRNA gene and *K. pneumoniae*-specific *phoE* gene; confirm bands of expected size
    - *K. pneumoniae* confirmation: *phoE* amplicon at expected size

**DOCUMENTATION:**
- Record: date, operator, culture OD, volumes of all reagents, incubation conditions
- Record all QC results: NanoDrop (both ratios + concentration), Qubit concentration, gel result (photograph gel), PCR result
- Label tubes: organism ID, strain designation, extraction date, concentration, QC status
- Enter into LIMS with sample ID linked to culture records
- Store at −20°C in nuclease-free microtubes; label with cryo-resistant labels

**EXPECTED RESULTS:**
- Yield: 30–80 µg from 10 mL culture
- A₂₆₀/A₂₈₀: 1.8–2.0
- A₂₆₀/A₂₃₀: 2.0–2.2
- Gel: high-MW band, clean background
- PCR: positive for 16S and *phoE*

**PASS CRITERIA FOR WGS SUBMISSION:**
- Qubit ≥ 50 ng/µL ✓
- A₂₆₀/A₂₈₀ ≥ 1.8 ✓
- A₂₆₀/A₂₃₀ ≥ 2.0 ✓
- Gel: no obvious smearing ✓
- PCR: positive ✓

---

*End of Section IV: Extraction of Chromosomal DNA from Gram Negative Bacteria — 50 Questions & Answers*
*Masters Level | Molecular Biology Practical Viva Preparation*
