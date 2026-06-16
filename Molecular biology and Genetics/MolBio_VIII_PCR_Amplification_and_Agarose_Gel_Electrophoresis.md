# Molecular Biology – VIII. Amplification of Plasmid DNA from Bacteria by Conventional PCR Method and Post PCR Analysis by Agarose Gel Electrophoresis
## 50 Master's-Level Viva Questions with Detailed Answers

---

### SECTION A: BASIC PRINCIPLES & BACKGROUND (Q1–Q10)

---

**Q1. What is PCR? Explain the basic principle underlying the polymerase chain reaction.**

PCR (Polymerase Chain Reaction) is an in vitro enzymatic technique used to amplify a specific segment of DNA exponentially, producing millions of copies of a defined target sequence from even trace amounts of template DNA. It was invented by Kary Mullis in 1983 (Nobel Prize in Chemistry, 1993). The principle is based on the natural process of DNA replication, adapted for in vitro conditions using a thermostable DNA polymerase.

The reaction exploits three fundamental molecular biology phenomena: (1) DNA denaturation — hydrogen bonds between the two complementary strands are broken at high temperature (~94–98°C), separating the double helix into single strands; (2) primer annealing — short synthetic oligonucleotide primers (18–25 bp) complementary to sequences flanking the target region hybridize to the single-stranded template at a reduced temperature (50–65°C); and (3) primer extension — a thermostable DNA polymerase (most commonly *Taq* polymerase from *Thermus aquaticus*) extends the annealed primers in the 5'→3' direction using dNTPs, synthesizing new complementary DNA strands. Each cycle doubles the number of target DNA molecules, resulting in exponential amplification: after n cycles, the theoretical yield is 2ⁿ copies of the target sequence (minus the initial template copies which are negligible). After 30 cycles, a single DNA molecule yields ~10⁹ copies.

---

**Q2. Why is plasmid DNA used as a template in this experiment rather than genomic DNA? What are the advantages?**

Plasmid DNA is preferred as a PCR template in this experiment for several reasons:

1. **Defined target:** Plasmids carry known insert sequences (cloned genes, antibiotic resistance genes, reporter genes), making it straightforward to design primers to a well-characterized target. Genomic DNA contains billions of base pairs of complex sequence where off-target priming is more likely.

2. **Higher copy number:** Bacterial cells typically contain 10–500 copies of a high-copy-number plasmid (e.g., pUC19 at ~500 copies/cell) compared to a single copy of most chromosomal genes, providing a richer template source.

3. **Absence of repetitive sequences:** Plasmid DNA lacks the repetitive elements (transposons, satellite DNA) abundant in bacterial chromosomal DNA that can cause non-specific amplification.

4. **Purity and size:** Extracted plasmid DNA (especially after mini-prep) is relatively pure, small (2–10 kb typical), and free of contaminating chromosomal DNA fragments that could cause spurious amplification.

5. **Reproducibility:** Since plasmid sequence is fully known (from cloning records or sequencing), primer design is precise and results are highly reproducible.

6. **Diagnostic utility:** PCR from plasmid templates is used to verify successful cloning, confirm insert orientation, and screen recombinant colonies — all central to molecular biology workflows.

---

**Q3. What are the essential components of a PCR reaction mixture? State the role of each component.**

A standard PCR reaction mixture (typically 25–50 µL total volume) contains:

1. **Template DNA (1–100 ng):** Provides the target sequence to be amplified; for plasmid DNA, 1–10 ng is usually sufficient. Excess template can inhibit PCR by competing for primers and polymerase.

2. **Forward and Reverse Primers (0.1–0.5 µM each):** Synthetic oligonucleotides (18–25 bp) complementary to sequences flanking the target on opposite strands; define the boundaries and specificity of amplification. Too high a primer concentration promotes mispriming.

3. **Thermostable DNA Polymerase (1–2.5 U per reaction):** *Taq* polymerase (or high-fidelity variants: Phusion, Q5, Pfu) synthesizes new DNA strands by extending primers in the 5'→3' direction. *Taq* lacks 3'→5' proofreading exonuclease activity (error rate ~10⁻⁴/bp/cycle); high-fidelity polymerases have lower error rates (~10⁻⁶/bp/cycle).

4. **dNTPs (200 µM each of dATP, dCTP, dGTP, dTTP):** Deoxynucleoside triphosphates serve as building blocks for new DNA synthesis. Imbalanced dNTP concentrations increase *Taq* error rate.

5. **MgCl₂ (1.5–2.5 mM):** Magnesium ions are an essential cofactor for *Taq* polymerase activity; Mg²⁺ binds to dNTPs (forming Mg-dNTP complexes), stabilizes the primer-template duplex, and is required for the polymerase active site. Optimal Mg²⁺ concentration must be empirically determined — too low reduces yield; too high increases non-specific amplification.

6. **PCR Buffer (1×):** Provides optimal pH (typically Tris-HCl, pH 8.3–9.0 at room temperature; ~pH 7.2 at 72°C) and ionic strength (KCl, 50 mM) for polymerase activity and primer annealing.

7. **Molecular biology-grade water (nuclease-free):** Makes up the reaction volume; must be free of DNases, RNases, and PCR inhibitors.

---

**Q4. Describe the three steps of a single PCR cycle. What temperatures and durations are typically used?**

Each PCR cycle consists of three precisely controlled temperature steps:

**Step 1 — Denaturation (94–98°C, 15–60 seconds):**
The reaction is heated to 94–98°C, disrupting the hydrogen bonds and hydrophobic stacking interactions between the two complementary strands of the double-stranded DNA template. This produces two single-stranded DNA templates accessible to primer annealing. The high temperature also dissociates any secondary structures (hairpin loops) in the template. For GC-rich templates, higher denaturation temperatures (96–98°C) or longer times may be required. The initial denaturation step at the start of the PCR program is typically extended (2–5 min, "hot start") to ensure complete template denaturation and activate hot-start polymerases.

**Step 2 — Annealing (50–65°C, 15–60 seconds):**
The temperature is lowered to allow the primers to hybridize (anneal) to their complementary sequences on the single-stranded template DNA. The annealing temperature (Tₐ) is typically set 3–5°C below the melting temperature (Tm) of the primers. Tm is estimated by: Tm = 4(G+C) + 2(A+T)°C (Wallace rule, for short oligonucleotides) or by nearest-neighbor thermodynamic calculations. Too low an annealing temperature causes non-specific binding; too high causes failure of primer-template hybridization (no amplification).

**Step 3 — Extension/Elongation (72°C, 30 seconds to several minutes):**
The temperature is raised to 72°C — the optimal activity temperature of *Taq* polymerase (~1,000 bp/min extension rate). The polymerase extends from the 3'-OH of each annealed primer, incorporating dNTPs complementary to the template strand in the 5'→3' direction, synthesizing a new complementary DNA strand. Extension time is calculated based on target length: typically 1 min per 1 kb of expected product for *Taq* (30 sec/kb for high-fidelity polymerases). A final extension step (5–10 min at 72°C) after the last cycle ensures all partially extended products are completed.

---

**Q5. What is Taq polymerase? Why is it used in PCR? What are its limitations and what alternatives exist?**

*Taq* DNA polymerase is a thermostable DNA polymerase isolated from the thermophilic bacterium *Thermus aquaticus*, which inhabits hot springs (optimal growth temperature 70–75°C). It was first characterized by Chien et al. (1976) and became the enzyme of choice for PCR after its commercialization by Cetus Corporation.

**Properties:**
- Optimal activity temperature: 72–75°C
- Half-life: >40 min at 95°C (thermostable — survives repeated denaturation cycles)
- Extension rate: ~1,000 bp/min at 72°C
- Molecular weight: 94 kDa
- Has 5'→3' polymerase activity and 5'→3' exonuclease activity (nick translation, Taqman probe cleavage)
- **Lacks 3'→5' exonuclease (proofreading) activity**

**Limitations:**
1. **No proofreading:** Error rate ~10⁻⁴ to 10⁻⁵ errors/bp/cycle — unsuitable for cloning applications requiring high fidelity.
2. **Adds 3' A-overhang:** *Taq* has terminal transferase activity, adding a non-templated adenine to the 3' end of PCR products — useful for TA cloning but problematic for blunt-end cloning.
3. **Processivity:** Relatively low; may drop off template during long amplifications.
4. **Maximum amplicon size:** Typically limited to ~3–5 kb.

**Alternatives:**
- **Pfu polymerase** (*Pyrococcus furiosus*): Has 3'→5' proofreading; error rate ~10⁻⁶; blunt-end products; used for cloning.
- **Phusion/Q5 polymerase** (NEB): Fusion of *Pfu*-like polymerase with processivity-enhancing domain; very high fidelity + speed; industry gold standard for cloning.
- **Vent polymerase** (*Thermococcus litoralis*): Proofreading; blunt ends.
- **KOD polymerase:** Extremely high fidelity and extension rate; used for long-range PCR.
- **LA Taq (Long-range Taq):** Mixture of *Taq* + proofreading polymerase for amplifying targets up to 20 kb.

---

**Q6. What is the Tm of a primer and how do you calculate it? Why is Tm important in PCR primer design?**

The melting temperature (Tm) of a primer is the temperature at which 50% of the primer molecules are hybridized (annealed) to their complementary template strand and 50% are dissociated (single-stranded). It reflects the thermodynamic stability of the primer-template duplex and is a critical parameter in PCR primer design.

**Calculation methods:**

1. **Wallace Rule** (for primers 14–20 bp, rough estimate):
   **Tm = 4(G + C) + 2(A + T) °C**
   Where G, C, A, T = number of each nucleotide in the primer.
   Example: Primer ATGCGCATGCGCATGC (16 bp, 10 G/C, 6 A/T):
   Tm = 4(10) + 2(6) = 40 + 12 = **52°C**

2. **Nearest-Neighbor (NN) Method** (more accurate, accounts for stacking interactions):
   Uses thermodynamic parameters (ΔH° and ΔS° for each dinucleotide pair):
   Tm = ΔH° / (ΔS° + R × ln[primer]/4) − 273.15
   This method is used by online tools (Primer3, OligoCalc, NEB Tm Calculator).

**Importance in PCR:**
- Annealing temperature (Tₐ) is set 3–5°C below Tm to ensure efficient primer-template hybridization.
- Both primers in a pair should have closely matched Tm values (within 2–4°C) to ensure simultaneous efficient annealing; mismatched Tm leads to one primer annealing poorly.
- Too low Tₐ (<Tm − 10°C): Non-specific annealing → spurious bands.
- Too high Tₐ (>Tm): No annealing → no product.
- GC content (ideally 40–60%) and GC-clamps at 3' end (1–2 G or C at the 3' terminus) improve primer stability and extension efficiency.

---

**Q7. What are the key criteria for good PCR primer design? List at least eight parameters.**

Optimal PCR primer design follows these criteria:

1. **Length:** 18–25 nucleotides — short enough for rapid annealing; long enough for specificity.

2. **GC content:** 40–60% — ensures adequate Tm without excessive stability that slows annealing kinetics.

3. **Tm:** 55–65°C for most standard PCR; primers in a pair should have Tm within ±2°C of each other.

4. **3' end stability:** 1–2 G or C residues at the 3' end ("GC clamp") improve primer anchoring and extension efficiency; avoid 3' end complementarity between primers (prevents primer-dimer extension).

5. **Avoid self-complementarity:** No internal palindromes or hairpin structures (ΔG of secondary structure < −2 kcal/mol); hairpins compete with template annealing.

6. **Avoid primer-dimer formation:** No complementarity at 3' ends between forward and reverse primers; primer-dimers produce spurious bands and consume primers/polymerase (ΔG of primer-dimer < −5 kcal/mol is problematic).

7. **Avoid repetitive sequences:** Runs of identical nucleotides (>4 in a row, especially poly-G) cause slippage and non-specific annealing.

8. **Specificity (BLAST check):** Both primers must be specific to the target sequence; BLAST (Basic Local Alignment Search Tool) against the relevant genome/plasmid database ensures no off-target priming sites with high homology.

9. **Amplicon size:** Typically 100–3,000 bp for standard PCR; product size should be appropriate for downstream application (sequencing: 500–800 bp optimal; cloning: as required).

10. **Avoid sequence near restriction sites used for cloning** (unless restriction sites are deliberately incorporated into primer tails for directional cloning).

11. **Tools:** Primer3 (http://primer3.ut.ee), Primer-BLAST (NCBI), OligoCalc, IDT OligoAnalyzer are commonly used for primer design and validation.

---

**Q8. What is the difference between specific and non-specific amplification in PCR? What causes non-specific bands?**

**Specific amplification** produces a single, discrete band of the expected size on agarose gel, corresponding exclusively to the intended target sequence. **Non-specific amplification** produces additional bands of unexpected sizes (or a smear) in addition to (or instead of) the expected band, arising from primer binding to unintended template sequences.

**Causes of non-specific amplification:**

1. **Low annealing temperature:** Tₐ below the primer Tm allows primers to anneal to partially complementary sequences elsewhere in the template, producing off-target products.

2. **Excess MgCl₂:** High Mg²⁺ stabilizes mismatched primer-template duplexes, enabling extension from suboptimal primer binding sites.

3. **High primer concentration:** Excess primers increase probability of bimolecular collision with non-specific sites.

4. **Poor primer design:** Primers with significant homology to sequences other than the intended target (particularly if the 3' end matches), or primers with low complexity/repetitive sequences.

5. **Excess template:** High template concentration increases the probability of off-target priming.

6. **Insufficient initial denaturation:** Incomplete denaturation of complex templates (GC-rich, secondary structures) leaves partially double-stranded regions that misdirect polymerase.

7. **Contamination:** Carry-over contamination from previous PCR products (amplicon contamination) can produce bands corresponding to earlier experiments.

8. **Non-specific extension of primer-dimers:** Primer-dimers (formed by annealing of primer 3' ends to each other) can be extended by polymerase, producing a characteristic low-molecular-weight band (<100 bp) on gel.

---

**Q9. What is a PCR thermocycler? Describe its working principle and key components.**

A PCR thermocycler (thermal cycler) is a laboratory instrument that precisely controls the temperature of samples through repeated cycles of heating and cooling required for PCR. Key components and working principle:

**Key components:**
1. **Thermal block (heat block/sample block):** Typically made of silver, aluminum, or gold-plated aluminum for excellent thermal conductivity; holds PCR tubes, strips, or 96/384-well plates. Temperature uniformity across all wells is critical (±0.2°C specification for high-quality instruments).

2. **Peltier heating/cooling elements:** Thermoelectric devices (Peltier modules) beneath the thermal block use the Peltier effect to rapidly heat or cool the block by applying an electric current — current direction determines heating or cooling. Modern thermocyclers achieve ramp rates of 3–6°C/sec.

3. **Temperature sensor (thermocouple/thermistor):** Measures actual block temperature; feedback to microprocessor ensures accurate temperature control.

4. **Heated lid:** Maintained at 105–110°C — prevents condensation of the reaction mixture on the tube cap (which would concentrate the reaction and alter component concentrations); eliminates need for mineral oil overlay in older protocols.

5. **Microprocessor and software:** Controls and programs the temperature profile (number of cycles, temperature and duration of each step, ramp rates, hold temperatures); modern instruments have gradient function (allows testing of a range of annealing temperatures simultaneously across the block in a single run).

6. **Display/interface:** Touchscreen or PC software for protocol programming.

**Gradient function:** Allows different annealing temperatures across columns of the block (e.g., 50–65°C gradient) — invaluable for optimizing Tₐ without running multiple separate PCR reactions.

---

**Q10. Why is PCR performed from plasmid DNA particularly useful in molecular biology? What downstream applications follow PCR amplification?**

PCR from plasmid DNA is a foundational technique in molecular biology with numerous downstream applications:

1. **Colony PCR / Recombinant screening:** After bacterial transformation, colonies are screened by PCR (using insert-specific or vector-specific primers) to identify recombinant clones containing the desired insert, without the need for plasmid extraction from every colony — a major time-saving step.

2. **Sequencing:** PCR products from plasmid templates are cleaned up and submitted for Sanger sequencing to confirm the identity, sequence integrity, and orientation of cloned inserts.

3. **Subcloning:** PCR amplifies an insert from one plasmid for directional cloning into another vector (primers contain restriction site tails); facilitates construction of expression vectors.

4. **Mutagenesis:** Site-directed mutagenesis uses plasmid template + mutagenic primers to introduce specific point mutations, insertions, or deletions into cloned genes (overlap extension PCR, QuikChange method).

5. **Restriction analysis preparation:** PCR product or plasmid DNA amplified by PCR can be digested with restriction enzymes for mapping or cloning.

6. **Diagnostic confirmation:** Confirms presence of a specific gene (antibiotic resistance gene, virulence gene, reporter gene) in a plasmid after transformation.

7. **Quantitative PCR (qPCR):** Plasmid DNA serves as a standard curve template for absolute quantification of target sequences.

8. **Probe preparation:** Labeled PCR products (using labeled dNTPs or primers) serve as hybridization probes for Southern blotting or FISH.

---

### SECTION B: PROCEDURE & METHODOLOGY (Q11–Q25)

---

**Q11. Describe the complete step-by-step procedure for PCR amplification of plasmid DNA in the laboratory.**

**Materials:** Plasmid DNA template, forward and reverse primers (10 µM stock), 10× PCR buffer, 25 mM MgCl₂, 10 mM dNTP mix, *Taq* DNA polymerase (5 U/µL), nuclease-free water, PCR tubes (0.2 mL), thermocycler, ice.

**Procedure:**

**1. Template preparation:**
Extract plasmid DNA by alkaline lysis miniprep (or use commercial kit); quantify by nanodrop (target: 10–50 ng/µL); dilute to 1–10 ng/µL in nuclease-free water.

**2. Primer preparation:**
Reconstitute lyophilized primers to 100 µM stock with nuclease-free water (TE buffer for long-term storage). Prepare 10 µM working stocks.

**3. Reaction setup (on ice to prevent non-specific extension):**
Prepare a master mix for multiple reactions (reduces pipetting error):

| Component | 1× reaction (25 µL) | Final concentration |
|---|---|---|
| Nuclease-free water | 16.75 µL | — |
| 10× PCR buffer | 2.5 µL | 1× |
| 25 mM MgCl₂ | 1.5 µL | 1.5 mM |
| 10 mM dNTP mix | 0.5 µL | 200 µM each |
| Forward primer (10 µM) | 0.5 µL | 0.2 µM |
| Reverse primer (10 µM) | 0.5 µL | 0.2 µM |
| *Taq* polymerase (5 U/µL) | 0.25 µL | 1.25 U |
| Template DNA (10 ng/µL) | 2.5 µL | 25 ng |
| **Total** | **25 µL** | |

Mix gently by pipetting; do not vortex (shear DNA and denature polymerase).

**4. Controls:**
- **Positive control:** Known template with validated primers — confirms reagents and thermocycler are functioning.
- **Negative control (No Template Control, NTC):** All components except template (replace with water) — detects contamination.
- **Primer control:** Template only without primers — rules out non-specific template amplification.

**5. Thermocycler programming (standard protocol):**

| Step | Temperature | Time | Cycles |
|---|---|---|---|
| Initial denaturation | 94–95°C | 3–5 min | 1 |
| Denaturation | 94°C | 30 sec | × 30–35 |
| Annealing | Tm − 5°C | 30 sec | × 30–35 |
| Extension | 72°C | 1 min/kb | × 30–35 |
| Final extension | 72°C | 5–10 min | 1 |
| Hold | 4°C | ∞ | — |

**6. Post-PCR:**
Store PCR products at 4°C (short-term) or −20°C (long-term). Analyze by agarose gel electrophoresis.

---

**Q12. What is the purpose of the initial denaturation step (hot start) at the beginning of PCR? How does "hot start PCR" work?**

**Initial denaturation (2–5 min at 94–95°C):**
The extended initial denaturation at the start of the PCR program serves multiple purposes:
1. **Complete template denaturation:** Ensures all double-stranded plasmid template DNA is fully denatured into single strands before cycling begins; particularly important for supercoiled plasmid DNA, which requires more energy to denature than linear DNA.
2. **Activation of hot-start polymerases:** Many commercial PCR kits use chemically modified or antibody-blocked hot-start polymerases that are inactive at room temperature; the initial high-temperature step activates the polymerase, preventing non-specific extension during room-temperature reaction setup.
3. **Destruction of secondary structures:** GC-rich regions and hairpin loops in template and primers are denatured.

**Hot start PCR:**
Hot start PCR refers to strategies that prevent *Taq* polymerase activity at temperatures below the annealing temperature (during reaction setup at room temperature), which causes non-specific priming and primer-dimer formation. Methods include:
- **Antibody-mediated hot start:** Anti-*Taq* antibodies inhibit polymerase at <70°C; denatured and inactivated at 95°C during initial denaturation, releasing active polymerase.
- **Chemical modification:** *Taq* polymerase modified with blocking chemical groups that are hydrolyzed at 95°C (e.g., Platinum *Taq*, AmpliTaq Gold).
- **Wax bead separation:** Reaction components separated by a wax bead that melts at ~70°C, mixing components only at high temperature.
- **Manual hot start:** Polymerase or MgCl₂ added to the tube only after the block reaches 80°C — impractical for large experiments.

---

**Q13. What is the role of MgCl₂ in PCR? How do you optimize MgCl₂ concentration?**

**Role of MgCl₂:**
Magnesium ions (Mg²⁺) are the essential metal cofactor for *Taq* DNA polymerase activity and play multiple roles:
1. **Polymerase cofactor:** Mg²⁺ coordinates with the phosphate groups of incoming dNTPs in the polymerase active site, forming the catalytically active Mg²⁺-dNTP complex required for phosphodiester bond formation.
2. **Primer-template stabilization:** Mg²⁺ neutralizes the negative charges of the phosphate backbone in the primer-template duplex, stabilizing hybridization.
3. **DNA polymerase structure:** Mg²⁺ maintains the structural integrity of the polymerase active site.

**Effects of Mg²⁺ concentration:**
- **Too low (<1 mM free Mg²⁺):** Polymerase is inactive or severely inhibited; no or very low yield.
- **Optimal (1.5–2.5 mM free Mg²⁺):** Efficient, specific amplification.
- **Too high (>4 mM free Mg²⁺):** Stabilizes mismatched primer-template duplexes → non-specific amplification; reduces polymerase fidelity; promotes primer-dimer formation.

**Note:** Free Mg²⁺ is the active form. Each dNTP molecule chelates ~1 Mg²⁺; therefore, with 200 µM each dNTP (800 µM total), ~0.8 mM Mg²⁺ is chelated. A 1.5 mM MgCl₂ reaction effectively has ~0.7 mM free Mg²⁺ before chelation.

**Optimization:** Run a Mg²⁺ titration series (0.5, 1.0, 1.5, 2.0, 2.5, 3.0, 4.0 mM MgCl₂) in otherwise identical PCR reactions; run on agarose gel; select concentration giving the brightest specific band with minimal non-specific bands.

---

**Q14. How many cycles are typically used in PCR? What happens if too few or too many cycles are used?**

**Standard cycle number:** 25–35 cycles are used for most standard PCR applications.

**Theoretical yield:** After n cycles, 2ⁿ copies are produced (assuming 100% efficiency):
- 25 cycles: ~3.4 × 10⁷ copies
- 30 cycles: ~1.1 × 10⁹ copies
- 35 cycles: ~3.4 × 10¹⁰ copies

**Too few cycles (<20):**
- Insufficient amplification → faint or absent band on gel.
- May be acceptable for high-copy-number template or detection by Southern blot rather than ethidium bromide staining.

**Too many cycles (>40):**
1. **Reagent exhaustion:** dNTPs, primers, and/or polymerase become limiting; reaction plateaus.
2. **Plateau effect:** At late cycles, amplified products begin to re-anneal to each other rather than primers, reducing efficiency.
3. **Increased error accumulation:** Each cycle introduces *Taq* errors; more cycles → more errors in the final population.
4. **Non-specific amplification:** Rare mispriming events at early cycles are amplified exponentially in later cycles, producing additional non-specific bands not visible at lower cycle numbers.
5. **Chimeric products:** PCR artifacts (recombinants between similar sequences) become more prevalent.
6. **Smearing:** Complete depletion of limiting reagents causes non-templated synthesis and smearing on gel.

**For plasmid templates** (high copy): 25–30 cycles are usually sufficient; more cycles are needed for low-abundance templates (genomic DNA, environmental samples).

---

**Q15. What is the difference between end-point PCR (conventional PCR) and real-time PCR (qPCR)? When is each used?**

| Feature | Conventional (End-Point) PCR | Real-Time PCR (qPCR) |
|---|---|---|
| Detection | After PCR completion (gel electrophoresis) | During PCR (fluorescence monitored each cycle) |
| Quantitation | Semi-quantitative (band intensity) | Highly quantitative (absolute or relative) |
| Dynamic range | Narrow (~10-fold) | Wide (~7–9 orders of magnitude) |
| Sensitivity | Lower (ng level template needed) | Very high (single molecule detection possible) |
| Specificity confirmation | Gel band size + sequencing | Melt curve analysis + probe specificity |
| Time | 2–4 h (PCR) + 1–2 h (gel) | 1–2 h (all-in-one) |
| Contamination risk | Higher (post-PCR handling) | Lower (closed-tube system) |
| Cost | Lower instrument cost | Higher instrument cost |
| Output | Band presence/size | Ct (cycle threshold) value → quantity |
| Common use | Cloning, screening, diagnostic confirmation | Gene expression, pathogen quantification, GMO testing, viral load |

**When to use each:**
- **Conventional PCR:** Colony screening, insert verification, diagnostic confirmation (presence/absence), amplicon preparation for cloning/sequencing — where quantitation is not required.
- **qPCR:** Gene expression analysis (RT-qPCR), copy number variation, microbial quantification in environmental/clinical samples, viral load monitoring (HIV, SARS-CoV-2), food safety testing.

---

**Q16. Describe the complete procedure for agarose gel electrophoresis of PCR products.**

**Materials:** Agarose powder, 1× TAE or TBE buffer, ethidium bromide (EtBr, 0.5 µg/mL) or SYBR Safe, 6× DNA loading dye, DNA ladder (100 bp or 1 kb), electrophoresis tank, power supply, UV transilluminator/gel documentation system.

**Procedure:**

**1. Gel preparation:**
- Weigh agarose (1–2% w/v depending on expected product size; 1% for 500–5,000 bp; 2% for 100–500 bp).
- Dissolve in 1× TAE buffer (40 mM Tris-acetate, 1 mM EDTA, pH 8.0) by heating in microwave (swirl frequently to prevent boiling over); allow to cool to ~55°C.
- Add EtBr (0.5 µg/mL final) or SYBR Safe (1×); mix gently.
- Pour into gel casting tray with combs in place; allow to solidify at room temperature for 20–30 min.

**2. Sample preparation:**
- Mix 5–10 µL PCR product with 1–2 µL 6× loading dye (contains glycerol [density], bromphenol blue [tracking dye], xylene cyanol [second tracking dye], EDTA [stops enzymatic activity]).
- Load DNA ladder (5–10 µL of 100 bp or 1 kb ladder) in first lane for size reference.

**3. Electrophoresis:**
- Place solidified gel (with comb removed) in tank filled with 1× TAE buffer (buffer level ~2–3 mm above gel surface).
- Load samples into wells.
- Connect power supply: cathode (negative, black) at the loading well end; DNA migrates toward anode (positive, red) due to negative charge of phosphate backbone.
- Run at 80–120 V (5–8 V/cm gel length) for 30–60 min until bromphenol blue dye front migrates 3/4 of the gel length.

**4. Visualization:**
- View under UV transilluminator (302 nm short-wave UV for EtBr; 365 nm long-wave for SYBR Safe).
- Photograph using gel documentation system (GelDoc, ChemiDoc).
- Compare band sizes to DNA ladder for size verification.
- Expected result: Single band at the expected amplicon size; no bands in NTC lane.

---

**Q17. What is the principle of agarose gel electrophoresis? Why does DNA migrate toward the positive electrode?**

**Principle:** Agarose gel electrophoresis separates DNA molecules based on size (and to a lesser extent, conformation) by their differential migration through a porous agarose matrix under the influence of an applied electric field.

**Why DNA migrates toward the positive electrode (anode):**
DNA molecules are polyanions — each nucleotide carries a negatively charged phosphate group (pKa ~1.0; fully ionized at physiological pH and electrophoresis buffer pH ~8.0). Under an applied electric field, negatively charged DNA molecules migrate toward the positively charged electrode (anode, red terminal). The net charge per unit mass of DNA is approximately constant regardless of size (each nucleotide has one phosphate), meaning the charge-to-mass ratio is similar for all DNA sizes. Therefore, in free solution, all DNA molecules would migrate at the same rate.

**Role of the agarose matrix:**
Agarose forms a molecular sieve — a network of crosslinked polysaccharide fibers with pore sizes dependent on agarose concentration. Smaller DNA molecules migrate through the pores more easily and move faster; larger molecules are retarded more and move slower. The result is size-based separation: smaller DNA migrates further from the well (higher apparent mobility) than larger DNA in a given time. The relationship between migration distance and DNA size is approximately logarithmic: log(size in bp) is linear with migration distance. This is why DNA ladders with known size fragments allow interpolation of unknown band sizes.

**DNA conformation effects:**
- Supercoiled (covalently closed circular, CCC) plasmid migrates fastest (most compact).
- Linear DNA migrates at intermediate rate (standard for size estimation).
- Relaxed circular (open circular/nicked, OC) plasmid migrates slowest.
This is why plasmid preparations show multiple bands; uncut plasmid should not be used as a size standard.

---

**Q18. What is ethidium bromide (EtBr)? How does it work to visualize DNA? What are its safety concerns and alternatives?**

**Ethidium bromide (EtBr):**
EtBr (3,8-diamino-5-ethyl-6-phenylphenanthridinium bromide) is a planar aromatic molecule that intercalates between the stacked base pairs of double-stranded DNA (and to a lesser extent, single-stranded DNA and RNA). Upon intercalation, EtBr undergoes a dramatic increase in fluorescence quantum yield (~20–30× enhancement) when excited at 302 nm (UV), emitting orange-red fluorescence at 590 nm. The enhancement occurs because the hydrophobic environment between DNA bases shields EtBr from water-mediated quenching of its fluorescence.

**Sensitivity:** EtBr detects as little as 1–10 ng DNA per band.

**Working concentration:** 0.5 µg/mL in gel and/or running buffer.

**Safety concerns:**
1. **Mutagen:** EtBr is a potent frameshift mutagen — intercalation into DNA during replication causes insertion or deletion of nucleotides. Positive in Ames test (*Salmonella* mutagenicity assay).
2. **Potential carcinogen:** Classified as a possible human carcinogen (not confirmed human carcinogen, but treated as such in laboratory safety protocols).
3. **Disposal:** EtBr-containing waste (gels, buffer) must be decontaminated before disposal; methods include: activated charcoal filtration, oxidative destruction (bleach + NaOH), or collection for specialist hazardous waste disposal.
4. **UV hazard:** Use of UV transilluminator requires UV-protective face shield and eye protection.

**Safer alternatives:**
1. **SYBR Safe (Invitrogen):** Cyanine dye that binds DNA; non-mutagenic in Ames test; comparable sensitivity; excitation at 302 nm or blue light (470 nm — Safe Imager); can be viewed without UV (blue light box).
2. **GelRed/GelGreen (Biotium):** Membrane-impermeant (cannot enter live cells); marketed as safer; similar sensitivity to EtBr; fluorescence similar to EtBr.
3. **SYBR Gold:** Highly sensitive (detects <100 pg); useful for very small amounts of DNA; expensive.
4. **Crystal violet:** Non-fluorescent; visible light detection; lower sensitivity; truly safe.

---

**Q19. What is a DNA ladder? How do you choose the appropriate ladder for PCR product analysis?**

A DNA ladder (molecular weight marker, DNA size marker) is a mixture of DNA fragments of known sizes (in base pairs), used as a reference standard to estimate the sizes of unknown DNA fragments on an agarose gel. When electrophoresed alongside unknown samples, the migration distances of the ladder bands create a calibration curve (log bp vs. distance) for size interpolation.

**Types of DNA ladders:**

1. **100 bp DNA ladder:** Contains bands at 100, 200, 300, 400, 500, 600, 700, 800, 900, 1000, 1500, 2000 bp. Ideal for PCR products in the range 100–2,000 bp — the most common range for standard PCR.

2. **1 kb DNA ladder (1 kb Plus):** Contains bands at 0.1, 0.2, 0.3, 0.4, 0.5, 0.65, 0.85, 1.0, 1.65, 2.0, 3.0, 4.0, 5.0, 6.0, 8.0, 10.0 kb. Ideal for larger PCR products and plasmid digests.

3. **Low molecular weight ladder (25–700 bp):** For very small PCR products (multiplex PCR, RAPD); useful for detecting small amplicons.

4. **High molecular weight ladder (>5 kb):** For large PCR products (long-range PCR, genomic Southern blots).

**Choosing the appropriate ladder:**
- Expected PCR product size determines ladder choice: use a ladder whose size range spans and brackets the expected amplicon.
- For most plasmid-based PCR (amplifying inserts of 200–3,000 bp): **100 bp ladder** is most informative.
- Many ladders have an enhanced reference band (typically 500 bp or 1,000 bp is thicker/brighter by having more of that size fragment in the mixture) — useful for rapid visual reference.
- Ladder volume: 5–10 µL of pre-mixed (ladder + loading dye) or 5 µL ladder + 1 µL 6× loading dye.

---

**Q20. What is the composition of TAE and TBE buffers? What are their differences and when is each used?**

| Feature | TAE (Tris-Acetate-EDTA) | TBE (Tris-Borate-EDTA) |
|---|---|---|
| Composition (1×) | 40 mM Tris, 20 mM acetic acid, 1 mM EDTA, pH 8.0 | 89 mM Tris, 89 mM boric acid, 2 mM EDTA, pH 8.3 |
| Buffering capacity | Lower (buffer exhausts faster at high V) | Higher (more stable for long runs) |
| DNA resolution | Better for large DNA (>2 kb) | Better for small DNA (<1 kb) |
| DNA recovery | Better (no borate interference with downstream applications) | Borate inhibits many enzymes (restriction, ligation); not ideal for DNA recovery |
| Migration speed | Slightly faster (DNA migrates faster in lower ionic strength) | Slightly slower |
| Re-use | Not recommended (buffer depletes rapidly) | Can be recirculated (higher buffering capacity) |
| Supercoiled plasmid separation | Better in TBE | |
| Common use | Standard PCR analysis, cloning (DNA recovery from gel) | High-resolution separation, pulse-field gel, Southern blot |

**Preparation of 50× TAE stock:**
Dissolve 242 g Tris base in ~700 mL distilled water; add 57.1 mL glacial acetic acid + 100 mL 0.5 M EDTA (pH 8.0); adjust to 1 L. Dilute 1:50 for 1× working buffer.

**Preparation of 10× TBE stock:**
Dissolve 108 g Tris base + 55 g boric acid in ~800 mL distilled water; add 40 mL 0.5 M EDTA (pH 8.0); adjust to 1 L. Dilute 1:10 for 1× working buffer.

---

**Q21. What is loading dye and what is its role in agarose gel electrophoresis?**

Loading dye (also called sample buffer or tracking dye) is a solution added to DNA samples before loading onto an agarose gel. A standard 6× loading dye contains:

1. **Glycerol (30–40% v/v):** Increases sample density, causing it to sink into the well and remain in the well during loading rather than diffusing into the buffer. Without glycerol, samples would float out of the well.

2. **Bromphenol blue (0.25% w/v):** A negatively charged tracking dye that migrates through the gel ahead of DNA, providing a visual reference for electrophoresis progress. In 1% agarose (TAE), bromphenol blue co-migrates with ~300 bp DNA fragments.

3. **Xylene cyanol FF (0.25% w/v):** A second, slower tracking dye; in 1% agarose, it co-migrates with ~4,000 bp DNA fragments. Its position relative to bromphenol blue provides information about the gel's progress without UV visualization.

4. **EDTA (10 mM, pH 8.0):** Chelates Mg²⁺, inactivating DNases and *Taq* polymerase — prevents enzymatic degradation of DNA samples during loading and electrophoresis.

5. **SDS (optional, 0.1%):** Denatures proteins in samples; not always included.

**Working concentration:** 6× stock is added at 1:6 ratio to the sample (e.g., 1 µL 6× dye + 5 µL sample).

---

**Q22. How do you determine the agarose gel percentage to use for a given PCR product? Provide a practical guide.**

The resolution of agarose gel electrophoresis is directly related to the gel concentration — higher agarose percentage produces smaller pore sizes, better resolving smaller DNA fragments.

**Practical guide for agarose gel percentage selection:**

| DNA size range | Agarose % | Resolving range |
|---|---|---|
| 5,000 – 50,000 bp | 0.3 – 0.5% | Large fragments (Southern blot, lambda digest) |
| 1,000 – 20,000 bp | 0.6 – 0.8% | Large PCR products, plasmid digests |
| 500 – 10,000 bp | 1.0% | Standard PCR products (most common) |
| 200 – 3,000 bp | 1.2 – 1.5% | Medium PCR products, insert screening |
| 100 – 1,000 bp | 2.0% | Small PCR products, multiplex PCR |
| 20 – 500 bp | 3.0 – 4.0% | Very small fragments (microRNA, siRNA, RAPD) |
| <100 bp | Polyacrylamide gel (PAGE) | Very small fragments requiring high resolution |

**For this experiment (PCR from plasmid DNA):**
- Expected amplicon size determines choice.
- Most insert verification PCR products (200–2,000 bp): **1–1.5% agarose** is appropriate.
- Use 1% for products >1 kb; 1.5–2% for products <500 bp.

**Agarose dissolution tip:** Higher percentage gels are more viscous and harder to pour; add agarose slowly to boiling buffer; avoid air bubbles by pouring slowly at ~55–60°C.

---

**Q23. What controls are essential in a PCR experiment? Justify the need for each control.**

**1. Positive control:**
- Contains: All PCR components + validated template DNA with known primer binding sites.
- Purpose: Confirms that PCR reagents (polymerase, dNTPs, buffer, primers) are functional and the thermocycler is working correctly. If the positive control fails, the experiment is invalid regardless of other results.
- Typical positive control: Plasmid with confirmed insert + same primers used in experimental reactions.

**2. Negative control (No Template Control, NTC):**
- Contains: All PCR components + nuclease-free water in place of template DNA.
- Purpose: Detects contamination of any reagent with exogenous DNA (carry-over amplicon contamination, environmental DNA). Any band in the NTC lane indicates contamination → all results from that batch are compromised.
- This is the most critical control in molecular diagnostic and research settings.

**3. No Primer Control:**
- Contains: All PCR components + template, but no primers.
- Purpose: Detects non-specific amplification from the template without primer-directed synthesis (rare, but can occur with highly structured DNA). Also confirms that bands are primer-dependent.

**4. No Polymerase Control:**
- Contains: All components except *Taq* polymerase.
- Purpose: Confirms that bands are due to enzymatic DNA synthesis, not carry-over of template DNA visible on gel.

**5. Internal control:**
- A second primer set amplifying a housekeeping gene or vector backbone simultaneously in the same reaction.
- Purpose: Confirms that template DNA was successfully added to the reaction and PCR conditions were functional — particularly useful when experimental template may be limiting or inhibited.

---

**Q24. What is the expected appearance of the agarose gel after PCR of plasmid DNA? How would you interpret different banding patterns?**

**Expected result (successful PCR):**
- **Single, sharp, discrete band** at the expected amplicon size (in bp) in the experimental lanes.
- **No band in NTC lane** (absence confirms no contamination).
- **Band at expected size in positive control lane.**
- Band intensity proportional to the amount of PCR product loaded.

**Interpretation of different banding patterns:**

| Observation | Interpretation | Action |
|---|---|---|
| Single band at expected size | Successful, specific amplification | Proceed to downstream analysis |
| No band in any lane | PCR failure — reagent failure, thermocycler malfunction, inhibitors | Repeat with fresh reagents; check thermocycler |
| No band in experimental but positive control works | Template issue: degraded, inhibited, wrong template, too little | Re-extract template; quantify DNA |
| Band in NTC lane | Contamination of reagents or workspace | Identify source; repeat with fresh reagents in clean area |
| Multiple bands | Non-specific amplification | Optimize Tₐ, MgCl₂; redesign primers |
| Smear | Degraded template; over-cycling; contamination | Check template quality; reduce cycles; check primers |
| Band at wrong size | Wrong template; mispriming; primer-dimer | Confirm template identity; redesign primers |
| Faint band at expected size | Low template; insufficient cycles; inhibitors | Increase template; increase cycles; dilute template |
| Very bright, thick band | Over-loading or very high yield | Dilute sample before loading |
| Double band at expected size | Heteroduplex formation; two isoforms | Denaturation and reannealing; sequence products |

---

**Q25. What are the post-PCR steps following agarose gel analysis? When and why is gel extraction performed?**

**Post-PCR workflow:**

1. **Gel documentation:** Photograph the gel under UV illumination (gel documentation system); record band sizes by comparison with DNA ladder; note band intensity for yield estimation.

2. **PCR product purification (cleanup):**
   - If amplicon is a single, correct-size band: purify using PCR cleanup column (QIAquick PCR Purification Kit or equivalent) to remove primers, primer-dimers, dNTPs, polymerase, buffer salts, and EtBr.
   - Elute in nuclease-free water or 10 mM Tris-HCl (pH 8.0).
   - Quantify purified product by NanoDrop (expect 10–100 ng/µL from a 25–50 µL PCR).

3. **Gel extraction (gel purification):**
   - Required when: (a) multiple bands are present and only one is correct — must physically separate the band; (b) primer-dimers or non-specific amplicons are present that would interfere with downstream applications; (c) direct PCR cleanup would carry over undesired products.
   - Protocol: Excise the correct band from gel under UV (minimize UV exposure to prevent thymine dimer formation); dissolve gel slice in chaotropic salt buffer (guanidinium thiocyanate); bind DNA to silica column; wash; elute. Recovery: 40–70% (lower than PCR cleanup due to agarose dissolution losses).
   - Note: Long UV exposure during gel excision introduces thymine dimers into the PCR product, which may cause sequencing errors or inhibit downstream enzymatic steps. Use 365 nm (long-wave) UV or blue-light transilluminator for gel excision when possible.

4. **Sanger sequencing:** Send purified PCR product + sequencing primer to sequencing service for verification of amplicon identity.

5. **Restriction digestion:** Digest purified amplicon with appropriate restriction enzymes for subcloning into an expression or cloning vector.

6. **Storage:** Store purified PCR product at −20°C; avoid repeated freeze-thaw cycles.

---

### SECTION C: CALCULATIONS & DATA INTERPRETATION (Q26–Q35)

---

**Q26. Calculate the annealing temperature for a primer pair with the following sequences: Forward: 5'-ATGCGATCGATCGATCGA-3', Reverse: 5'-CGATCGATCGCATGCATG-3'. Use the Wallace rule.**

**Forward primer:** 5'-ATGCGATCGATCGATCGA-3' (18 bp)
- Count: A=4, T=3, G=6, C=5
- Tm(F) = 4(G+C) + 2(A+T) = 4(6+5) + 2(4+3) = 4(11) + 2(7) = 44 + 14 = **58°C**

**Reverse primer:** 5'-CGATCGATCGCATGCATG-3' (18 bp)
- Count: C=4, G=4, A=3, T=3, plus: C=2, G=2 → recount:
- C-G-A-T-C-G-A-T-C-G-C-A-T-G-C-A-T-G
- A=4, T=4, G=5, C=5
- Tm(R) = 4(5+5) + 2(4+4) = 4(10) + 2(8) = 40 + 16 = **56°C**

**Average Tm:** (58 + 56)/2 = 57°C

**Recommended annealing temperature:**
Tₐ = Average Tm − 5°C = 57 − 5 = **52°C**

Note: The Tm difference between primers is 2°C (within acceptable ±2–3°C range). For more precise primer design, use nearest-neighbor calculations via an online tool. The 2°C difference means the lower-Tm primer (reverse, 56°C) sets the upper limit for Tₐ; using 52°C ensures both primers anneal efficiently.

---

**Q27. A PCR reaction of 25 µL total volume requires 200 µM final concentration of each dNTP. You have a 10 mM dNTP stock mix (equimolar mix of all four dNTPs). How much dNTP mix (µL) do you add per reaction?**

**Using C₁V₁ = C₂V₂:**

- C₁ = 10 mM = 10,000 µM (stock concentration)
- C₂ = 200 µM (desired final concentration)
- V₂ = 25 µL (total reaction volume)
- V₁ = ?

V₁ = (C₂ × V₂) / C₁ = (200 µM × 25 µL) / 10,000 µM = 5,000 / 10,000 = **0.5 µL**

**Verification:** 0.5 µL of 10 mM dNTP mix in 25 µL total volume = 0.5/25 × 10,000 µM = 200 µM ✓

Note: The 10 mM dNTP mix typically means each dNTP is at 10 mM (not 10 mM total divided by 4), so the final concentration of each dNTP (dATP, dCTP, dGTP, dTTP) is 200 µM. Always confirm with the manufacturer's specification.

---

**Q28. You expect a PCR product of 1,200 bp. At 80 V in a 1% agarose gel (15 cm long), the 1,200 bp band of the 1 kb ladder migrated 7.2 cm from the well. Your experimental band migrated 7.0 cm. What is the approximate size of your PCR product?**

**Method: Log-linear interpolation using ladder bands**

Using two flanking ladder bands for interpolation:
- Assume 1,000 bp band migrated 7.8 cm
- Assume 1,500 bp band migrated 6.4 cm
- Experimental band: 7.0 cm

**Log interpolation:**
log(1000) = 3.000 at 7.8 cm
log(1500) = 3.176 at 6.4 cm

Slope = (3.176 − 3.000) / (6.4 − 7.8) = 0.176 / (−1.4) = −0.1257 log(bp)/cm

log(unknown) = 3.000 + (−0.1257) × (7.0 − 7.8)
= 3.000 + (−0.1257) × (−0.8)
= 3.000 + 0.1006
= 3.1006

Unknown size = 10^3.1006 = **1,260 bp** (approximately)

**Conclusion:** The experimental band (~1,260 bp) is close to the expected 1,200 bp product — within the typical ±5–10% accuracy of agarose gel size estimation. This slight overestimation is within normal variation; confirm exact size by Sanger sequencing.

---

**Q29. You prepare a master mix for 10 PCR reactions (+ 1 extra for pipetting error). Calculate the volume of each component required.**

**Standard 25 µL reaction × 11 reactions:**

| Component | Per Reaction | × 11 reactions |
|---|---|---|
| Nuclease-free water | 16.75 µL | 184.25 µL |
| 10× PCR buffer | 2.5 µL | 27.5 µL |
| 25 mM MgCl₂ | 1.5 µL | 16.5 µL |
| 10 mM dNTP mix | 0.5 µL | 5.5 µL |
| Forward primer (10 µM) | 0.5 µL | 5.5 µL |
| Reverse primer (10 µM) | 0.5 µL | 5.5 µL |
| *Taq* polymerase (5 U/µL) | 0.25 µL | 2.75 µL |
| **Master mix subtotal** | **22.5 µL** | **247.5 µL** |
| Template DNA (added separately per tube) | 2.5 µL | — |

**Procedure:** Prepare master mix (all components except template) in a single tube; vortex gently; aliquot 22.5 µL into each of the 10 labeled PCR tubes; add 2.5 µL of template DNA (or water for NTC) to each tube individually; cap, spin briefly, transfer to thermocycler.

**Why +1 reaction:** Pipetting dead volume and operator error mean a master mix for exactly 10 reactions will not yield enough for 10 complete reactions; always prepare 10–15% excess.

---

**Q30. After 30 PCR cycles starting from 2 molecules of template DNA, what is the theoretical number of PCR product copies? What percentage of these are the "short" (correct-size) products vs. "long" products from the original template strands?**

**Theoretical total copies after 30 cycles:**
Total copies = Initial template × 2ⁿ = 2 × 2³⁰ = 2 × 1,073,741,824 = **2,147,483,648 ≈ 2.1 × 10⁹**

**Short (correct-size) products vs. long products:**
In the first two cycles, the original template strands produce "long" products (extending beyond the primer binding site to the end of the template, not bounded at both ends). From cycle 3 onwards, short products (bounded by both primers) are produced and accumulate exponentially.

- After n cycles: Number of short (correct-length) products = 2ⁿ − 2n − 2 (from n templates; simplified formula for 2 starting templates)
- After 30 cycles: Short products ≈ 2³⁰ − 2(30) − 2 = 1,073,741,824 − 62 = ~1.07 × 10⁹ per original template × 2 = ~2.15 × 10⁹

**Long products:** 2n × 2 (initial templates) = 2 × 30 × 2 = 120 molecules (negligible)

**Conclusion:** After 30 cycles, >99.999% of all PCR products are the correctly sized, short, double-stranded amplicons bounded at both ends by the primer sequences. The original template-derived long products are negligible — this is why PCR produces a discrete, defined-size amplicon even from complex template DNA.

---

**Q31. You ran a PCR on plasmid DNA and obtained two bands: one at the expected size (800 bp) and one unexpected band at ~200 bp. How would you troubleshoot and resolve this?**

**Interpretation:** The 800 bp band is likely the specific product; the 200 bp band is a non-specific amplification product — possibly a primer-dimer artifact, mispriming, or a short secondary structure in the template.

**Troubleshooting approach:**

**Step 1: Confirm primer-dimer or non-specific band:**
- Check NTC lane: if the 200 bp band is also present in NTC → primer-dimer (no template needed); if absent in NTC → non-specific amplification from template.

**Step 2: If primer-dimer:**
- Reduce primer concentration (try 0.1 µM instead of 0.2 µM).
- Use hot-start PCR protocol.
- Redesign primers to avoid 3' end complementarity.

**Step 3: If non-specific amplification from template:**
- Increase annealing temperature in 1–2°C increments (gradient PCR).
- Reduce MgCl₂ by 0.5 mM increments.
- Reduce cycle number by 3–5.
- Add PCR enhancers: DMSO (5% v/v) for GC-rich regions or betaine (1 M) to reduce secondary structure.
- Check primer specificity by BLAST.

**Step 4: If both bands persist after optimization:**
- Gel-extract only the 800 bp band for downstream use.
- Redesign primers with higher specificity (longer primers, higher GC content, different location).

**Step 5: Sequence both bands** — occasionally an unexpected band can represent an alternative splice form, contaminating plasmid, or genuine biological variant.

---

**Q32. Calculate the mass of agarose needed to prepare 200 mL of 1.5% agarose gel in 1× TAE buffer.**

**Formula:** % w/v = (mass of solute in g / volume of solution in mL) × 100

**Rearranging for mass:**
Mass (g) = (% × Volume) / 100
= (1.5 × 200) / 100
= 300 / 100
= **3.0 g of agarose**

**Procedure:**
1. Weigh 3.0 g agarose powder into a 500 mL Erlenmeyer flask.
2. Add 200 mL of 1× TAE buffer.
3. Heat in microwave (2–3 min, swirling every 30 sec) until agarose is completely dissolved and solution is clear.
4. Cool to ~55–60°C (can hold in hand without discomfort).
5. Add 0.5 µg/mL EtBr (20 µL of 0.5 mg/mL stock) or SYBR Safe (4 µL of 10,000×); swirl gently.
6. Pour into casting tray; insert combs; allow to solidify for 25–30 min.

**Note:** Higher agarose % solutions (>2%) may need longer microwave heating; be careful of superheating (solution may erupt from flask); swirl carefully.

---

**Q33. The expected PCR product from a plasmid is 1,500 bp. The extension time is set at 72°C. If Taq polymerase extension rate is 1,000 bp/min, what is the minimum extension time required? What if Phusion polymerase (2,000 bp/min) is used instead?**

**Minimum extension time with Taq polymerase:**
Extension rate = 1,000 bp/min
Target size = 1,500 bp

Time = Size / Rate = 1,500 bp / 1,000 bp/min = **1.5 minutes (90 seconds)**

**Recommended extension time with Taq:** 1.5 × 1.2 (safety factor) = **1.8 min ≈ 2 min** (adding 20–30% buffer ensures complete extension even if some molecules are slightly slower).

**Minimum extension time with Phusion polymerase:**
Extension rate = 2,000 bp/min (Phusion high-fidelity, NEB specification: ~1 kb/30 sec = 2,000 bp/min)

Time = 1,500 bp / 2,000 bp/min = **0.75 minutes = 45 seconds**

**Recommended with Phusion:** 45 sec is standard; typically rounded to 45–60 seconds.

**Practical note:** Under-estimating extension time (too short) is a common cause of failed PCR or truncated products; over-estimating (too long) wastes time but rarely causes problems. For multiplex PCR amplifying products of different sizes, set extension time for the largest product.

---

**Q34. A PCR product is visualized on agarose gel. The expected product is 600 bp. The band appears at the correct position but is very faint. List potential causes and calculate how much more template DNA you would need to add if using 1 ng initially and wanting to increase yield 10-fold.**

**Causes of faint band:**
1. Insufficient template DNA (below optimal range).
2. Primer concentration too low.
3. Insufficient PCR cycles.
4. Suboptimal annealing temperature (too high — primers not binding efficiently).
5. MgCl₂ too low — polymerase activity suboptimal.
6. dNTP depletion (unlikely if concentrations are correct).
7. Polymerase activity degraded (old stock, improper storage).
8. PCR inhibitors in template preparation (co-purified proteins, EDTA, phenol).
9. Insufficient extension time (products partially extended).

**Template DNA calculation:**
Current template = 1 ng per reaction
Desired yield ≈ 10× increase

PCR is not always linearly proportional to template amount (once primers are not limiting, yield plateaus); however, within the range of 0.1–10 ng for plasmid template:

New template amount = 1 ng × 10 = **10 ng per reaction**

In practice, increasing template 10-fold often does not increase product 10-fold beyond a certain point; it is better to also:
- Increase cycle number by 3–5 cycles.
- Optimize MgCl₂ and Tₐ.
- Increase polymerase to 2 U.
- Try a touchdown PCR protocol (see Q36).

---

**Q35. Calculate the number of PCR cycles needed to amplify a single target DNA molecule to approximately 1 µg of a 500 bp PCR product.**

**Given:**
- Starting template: 1 molecule (1 copy)
- Target amount: 1 µg = 1,000 ng
- Amplicon size: 500 bp

**Step 1: Mass of one copy of 500 bp dsDNA:**
Average molecular weight of 1 bp dsDNA ≈ 660 Da
Mass of 500 bp dsDNA = 500 × 660 = 330,000 Da = 330,000 g/mol

Number of molecules in 1 µg:
= (1 × 10⁻⁶ g) / (330,000 g/mol) × 6.022 × 10²³ molecules/mol
= (1 × 10⁻⁶ / 3.3 × 10⁵) × 6.022 × 10²³
= 3.03 × 10⁻¹² mol × 6.022 × 10²³
= **1.83 × 10¹² molecules**

**Step 2: Number of cycles:**
2ⁿ = 1.83 × 10¹²
n × log(2) = log(1.83 × 10¹²)
n × 0.301 = 12.262
n = 12.262 / 0.301 = **40.7 cycles ≈ 41 cycles**

This assumes 100% efficiency (theoretical). In practice, PCR efficiency is 85–95% per cycle; actual cycle number needed is slightly higher. At 35 cycles, ~3.4 × 10¹⁰ molecules are produced from 1 template — approximately 18 ng of 500 bp product; to reach 1 µg, 40–42 cycles are needed. This illustrates why more than 40 cycles is rarely used (reagent exhaustion + artifact accumulation) and why adequate starting template is important.

---

### SECTION D: TROUBLESHOOTING & PROBLEM SOLVING (Q36–Q43)

---

**Q36. What is touchdown PCR? When is it used and what are its advantages?**

Touchdown PCR (TD-PCR) is a PCR strategy in which the annealing temperature is gradually decreased from above the primer Tm to below the Tm over the first several cycles, rather than using a fixed annealing temperature throughout.

**Typical touchdown protocol:**
- Start at Tₐ = Tm + 10°C (e.g., 70°C) for the first 2 cycles.
- Decrease Tₐ by 1–2°C every 2 cycles ("touchdown") over 15–20 cycles until the final Tₐ (usually Tm − 5°C, e.g., 55°C) is reached.
- Continue at the final Tₐ for the remaining 15–20 cycles.

**Principle:** At high initial annealing temperatures, only perfectly matched (or near-perfectly matched) primer-template pairs anneal — this preferentially amplifies the specific product in the early, exponential cycles. By the time the temperature drops to allow non-specific annealing, the specific product is already present in great excess and outcompetes non-specific priming at later cycles.

**Advantages:**
1. Significantly reduces non-specific bands without requiring extensive optimization.
2. Useful for primers with low specificity or when working with complex templates (genomic DNA, environmental samples).
3. Can rescue PCRs that produce non-specific bands at all tested fixed annealing temperatures.
4. Increases sensitivity — useful for low-abundance targets.

**When to use:** When standard PCR produces non-specific bands; when primer Tm is uncertain; when amplifying from complex templates; when designing primers for degenerate sequences.

---

**Q37. You find that your PCR produces no product. After checking the thermocycler and reagents, you find all seem correct. What systematic approach would you take to diagnose the problem?**

**Systematic diagnostic approach (process of elimination):**

**Step 1: Verify thermocycler function**
- Check that the thermocycler program matches intended parameters.
- Use a calibration thermometer block or check service logs.

**Step 2: Verify template DNA**
- Run 200 ng template DNA on agarose gel: should show intact DNA band; if degraded (smear), re-extract.
- Check NanoDrop: A260/A280 ratio should be ~1.8 (DNA purity); A260/A230 should be >1.8 (if low, inhibitors present — phenol, EDTA, guanidinium).
- Try a 10-fold dilution of template (inhibitors may be present at high concentration).
- Use a positive control with known-good template.

**Step 3: Verify primers**
- Confirm primers were reconstituted correctly (check concentration by NanoDrop or OD₂₆₀).
- Verify primer sequences match the plasmid map (BLAST check).
- Check for primer degradation (DNase contamination during preparation).
- Run primers on high-concentration PAGE or capillary electrophoresis to check integrity.

**Step 4: Verify dNTPs**
- Replace dNTPs with fresh stock; degraded dNTPs are a common silent failure.

**Step 5: Verify MgCl₂ and buffer**
- Run MgCl₂ titration (1.0, 1.5, 2.0, 2.5, 3.0 mM).

**Step 6: Verify polymerase**
- Check storage conditions (−20°C, never freeze-thaw >10×).
- Use fresh aliquot from master stock.
- Test polymerase with a simple positive control (lambda DNA + universal primers).

**Step 7: Check for PCR inhibitors**
- BSA (0.1 mg/mL) addition can overcome many inhibitors.
- Try PCR with diluted template (1:10, 1:100).

**Step 8: Review primer design**
- Recheck with Primer-BLAST; verify that primers are not in repeat regions or forming hairpins.

---

**Q38. Your PCR gel shows a smear instead of a discrete band. What does this indicate and how would you troubleshoot?**

**A smear on PCR gel indicates:**
1. **Template degradation:** If the template DNA itself is degraded (DNase contamination, freeze-thaw damage, or acidic/alkaline pH during storage), the smear represents random-sized fragments.
2. **Primer mispriming at multiple non-specific sites:** Especially at very low annealing temperature → amplification of many different sizes simultaneously.
3. **Over-amplification:** Too many cycles or too much template → product accumulates to saturation; at this plateau, *Taq* produces non-templated synthesis (blunt-end ligation of blunt PCR products, slippage synthesis) → high-molecular-weight smear.
4. **DNA polymerase slippage:** On repetitive sequences, polymerase can slip, producing a ladder/smear of products of incrementally different sizes.
5. **Degraded PCR products:** EtBr or UV exposure causing DNA photodamage → smearing on gel.

**Troubleshooting:**
1. **Check template quality:** Run template alone on gel; if smear → re-extract DNA; if intact band → template is fine.
2. **Increase annealing temperature:** Raise Tₐ by 2–5°C increments; use touchdown PCR.
3. **Reduce cycle number:** Try 25 cycles instead of 35.
4. **Reduce template concentration:** Dilute 1:10 or 1:100.
5. **Optimize MgCl₂:** Reduce to 1.0 mM.
6. **Use hot-start polymerase:** Prevents non-specific extension during setup.
7. **Redesign primers:** Avoid repetitive or low-complexity sequences.

---

**Q39. After running the agarose gel, you notice the DNA bands are curved (smiling effect). What causes this and how do you prevent it?**

**Smiling effect (curved bands):**
DNA bands curve upward at the edges and are straight in the center (smiley face pattern) — or less commonly, curve downward at edges (frowning). This is primarily caused by **uneven temperature distribution across the gel** during electrophoresis.

**Causes:**
1. **Joule heating:** High voltage generates heat in the electrophoresis buffer; the gel center is warmer than the edges (water-cooled edges via contact with the tank walls). Warmer DNA (center) migrates faster than cooler DNA (edges), causing the characteristic smile.
2. **Uneven gel casting:** Air bubbles or uneven agarose concentration can cause localized differences in pore size and thus migration speed.
3. **Uneven current distribution:** Poorly fitting gel tray, damaged electrodes, or non-uniform buffer conductivity.
4. **Buffer depletion/heating:** Running at high voltage for extended time heats the buffer, creating a temperature gradient.

**Prevention:**
1. **Reduce voltage:** Run at 80–100 V instead of >120 V; lower voltage generates less heat (Joule heat ∝ V²).
2. **Chill the running buffer:** Place electrophoresis tank on ice or use a cold room.
3. **Ensure buffer recirculation:** Pumping buffer from one end to the other equalizes ionic concentration and temperature.
4. **Pre-run equilibration:** Allow the gel to equilibrate in buffer for 5–10 min before loading.
5. **Avoid overfilling tank:** Buffer depth should just cover the gel (~2–3 mm above gel surface).

---

**Q40. What is carry-over contamination in PCR? How do you prevent and detect it?**

**Carry-over contamination (amplicon contamination):**
PCR amplicons from previous experiments are the most common and insidious source of false-positive results in PCR. A single PCR reaction produces 10⁹–10¹² copies of the target sequence; even if a minute fraction of these aerosols contaminate subsequent reaction setups, they serve as template and produce positive results even without the intended template. This is particularly problematic in molecular diagnostic and clinical settings.

**Sources:**
- Opening PCR tubes after amplification (aerosols released).
- Pipettes used both pre- and post-PCR.
- Surfaces, gloves, and equipment contaminated with amplicons.
- Non-filtered pipette tips allowing contamination of pipette body.

**Prevention:**
1. **Physical separation:** Maintain strict separation of pre-PCR (template/setup) and post-PCR (product analysis) areas; ideally, separate rooms with dedicated equipment, lab coats, and air flow from pre-PCR to post-PCR area (not reverse).
2. **Positive-pressure PCR hoods (UV-irradiated):** Set up reactions in UV-decontaminated laminar flow cabinet; UV light between uses reduces DNA contamination.
3. **Aerosol-resistant (filtered) tips:** Filter tips prevent amplicon aerosols from contaminating pipette barrels; critical in post-PCR areas.
4. **dUTP + UNG (Uracil-DNA Glycosylase) system:** Replace dTTP with dUTP in all PCR reactions; amplicons contain dU instead of dT. Before each new PCR, treat with UNG at 37°C — UNG cleaves dU-containing amplicons (from previous PCRs), destroying them; DNA extracted from samples contains only natural dT and is not degraded. Heat-inactivate UNG (95°C, 5 min) before PCR cycling.
5. **Negative controls (NTC) in every run:** Detects contamination.
6. **Disposable gloves:** Change frequently; never touch face, hair, or contaminated surfaces.

---

**Q41. You notice that your agarose gel bands are diffuse and poorly defined. What are the possible causes and remedies?**

**Diffuse, poorly defined bands indicate:**

1. **Overloaded wells:** Too much DNA per lane compresses into a thick, diffuse band; solution: dilute sample 1:5 or 1:10 before loading; ensure not loading >200–500 ng DNA per lane in a standard well.

2. **Low voltage / too-slow migration:** At very low voltage (<50 V), diffusion of DNA molecules competes with electrophoretic migration, causing bands to diffuse radially; solution: increase voltage to 80–120 V.

3. **Old or degraded agarose:** Agarose that has been melted and re-solidified multiple times forms a weaker gel with larger, irregular pores; solution: use freshly prepared gel.

4. **Air bubbles in gel:** Bubbles create channels where DNA migrates unpredictably; solution: remove bubbles before gel solidifies by gently blowing them to edges with a pipette tip.

5. **Incomplete gel solidification:** Pouring samples into a gel that has not fully set; solution: allow minimum 30 min solidification at room temperature.

6. **DNA degradation:** Partially degraded DNA produces a diffuse smear rather than discrete bands; solution: check template/product integrity; avoid DNase contamination.

7. **EtBr concentration issues:** Too much EtBr (>1 µg/mL) intercalates extensively and can alter migration; solution: use 0.5 µg/mL.

8. **Buffer pH issues:** Buffer that has become acidic (old buffer, frequent reuse) affects DNA charge and migration; solution: use fresh 1× TAE.

---

**Q42. What are PCR inhibitors? Give examples of inhibitors relevant to molecular biology labs and how they affect PCR.**

PCR inhibitors are substances that reduce or abolish PCR amplification efficiency by interfering with template denaturation, primer annealing, or polymerase activity.

**Common PCR inhibitors in molecular biology:**

1. **EDTA:** Chelates Mg²⁺ (essential *Taq* cofactor) → complete inhibition; carried over from TE buffer used for DNA storage. Solution: dilute template or use Tris-only elution buffer.

2. **Phenol/chloroform residues:** From phenol-chloroform DNA extraction; inhibit *Taq* polymerase; cause falsely low OD₂₈₀ readings (A260/A280 < 1.8). Solution: ethanol precipitation to remove; commercial column-based cleanup.

3. **Ethanol:** Residual from ethanol precipitation or spin-column washing; inhibits *Taq*; dries DNA samples on filter membranes. Solution: ensure complete drying of pellet/column before elution.

4. **SDS:** From lysis buffers in DNA extraction; inhibits *Taq* at >0.01% w/v; also causes primer aggregation. Solution: dilute template; column cleanup.

5. **Heparin:** Used in blood collection (anti-coagulant); potent *Taq* inhibitor at ng/mL concentrations; relevant when PCR is performed on blood-derived DNA. Solution: alternative anti-coagulants (EDTA), heparin lyase treatment, or column-based DNA cleanup.

6. **Humic acids:** From soil/environmental samples; co-purify with DNA; inhibit *Taq* at low concentrations. Solution: dilute template; BSA addition; specialized soil DNA extraction kits.

7. **High salt (KCl, NaCl >75 mM in reaction):** Inhibits *Taq* at high ionic strength. Solution: dilute template.

8. **Melanin:** From dark-pigmented tissues or melanin-containing samples; inhibits *Taq*. Solution: BSA (bovine serum albumin, 0.1–1 mg/mL in reaction) — BSA binds melanin and many other inhibitors, protecting *Taq*.

**Detection of inhibitors:** Spike with known-positive template in the presence of extracted DNA — if positive control fails, inhibitors are present. Dilution series of template often overcomes inhibitors.

---

**Q43. How would you verify the identity of your PCR product beyond its size on an agarose gel?**

Size alone on an agarose gel is insufficient to confirm PCR product identity — a band at the expected size could arise from non-specific amplification, contamination, or primer-dimers extending to the expected size by coincidence. Verification methods:

1. **Sanger sequencing (gold standard):**
   - Purify PCR product; send for Sanger sequencing with one or both primers.
   - Compare sequence to expected plasmid insert sequence by BLAST alignment.
   - Confirms identity, orientation, and sequence integrity (no mutations).

2. **Restriction enzyme digestion:**
   - Digest purified PCR product with restriction enzymes that cut within the expected amplicon at defined positions.
   - Run digestion products on agarose gel; compare band sizes to theoretical digest map.
   - Two bands of correct sizes confirms identity.

3. **Southern blot hybridization:**
   - Transfer gel-separated PCR products to nitrocellulose/nylon membrane; hybridize with labeled probe complementary to internal sequence; positive signal confirms identity.
   - Used when multiple bands are present.

4. **Melting curve analysis (only for qPCR):**
   - A specific PCR product melts at a characteristic Tm; non-specific products and primer-dimers melt at different temperatures.

5. **Nested PCR:**
   - Use internal (nested) primers to re-amplify the PCR product; if internal primers produce the expected smaller product, confirms specificity of the outer primers' product.

6. **Direct comparison to reference standard:**
   - Run alongside a restriction-digested plasmid producing a fragment of the same expected size — co-migration suggests, but does not confirm, identity.

---

### SECTION E: APPLICATIONS, INTERPRETATION & ADVANCED QUESTIONS (Q44–Q50)

---

**Q44. What is colony PCR? How does it differ from standard plasmid PCR and what is its practical utility in molecular cloning?**

Colony PCR is a rapid screening method that uses intact bacterial colonies (rather than extracted plasmid DNA) directly as the PCR template to identify recombinant clones containing the desired insert without the need to extract plasmid DNA from each colony.

**Procedure:**
1. Pick individual colonies (from transformation plates) with a sterile toothpick or pipette tip.
2. Transfer a small amount of cells into a labeled PCR tube containing the reaction mix (the rest of the cells are streaked onto a gridded master plate for archiving — critical, as colony PCR destroys the colony in the tube).
3. Include an initial lysis step at the beginning of the thermocycler program (95°C, 5–10 min) to lyse bacterial cells and release plasmid DNA.
4. Cycle using insert-specific primers (or one insert primer + one vector primer for orientation confirmation).
5. Analyze on agarose gel: colonies with insert show band at expected size; empty vector colonies show either no band (insert primers) or a smaller band (vector backbone only).

**Differences from plasmid PCR:**
- No DNA extraction step — faster, higher throughput (can screen 24–96 colonies simultaneously).
- Less template control (cell density varies between colonies).
- More potential inhibitors (cell wall components, proteins).
- Requires cell lysis step; may require optimization.
- Slightly lower sensitivity/specificity than purified plasmid template.

**Practical utility:**
- Screen hundreds of transformation colonies to identify recombinants in hours rather than days.
- Determine insert orientation when directional cloning is expected.
- Quickly distinguish single-insert from multi-insert clones.
- Identify colonies with correct insert size before sequencing (avoiding expensive unnecessary sequencing).

---

**Q45. What is degenerate primer PCR? When is it used and what modifications to the standard PCR protocol are required?**

Degenerate primers are pools of oligonucleotides with variable nucleotide positions (mixed-base degeneracy) designed to amplify related but not identical sequences from a group of organisms or gene family members where the exact sequence is not known but the amino acid sequence (or conserved nucleotide motif) is known.

**Design rationale:** When designing primers based on a known protein sequence (reverse translation), each amino acid may be encoded by multiple codons (codon degeneracy); to capture all possible DNA sequences encoding that protein region, the primer is synthesized as a mixture of all possible codon combinations at degenerate positions. IUPAC ambiguity codes are used: R (A or G), Y (C or T), W (A or T), S (G or C), N (A, C, G, or T), etc.

**Example:** The amino acid sequence Met-Trp-His-Tyr:
- Met (M): ATG (1 codon) → no degeneracy
- Trp (W): TGG (1 codon) → no degeneracy
- His (H): CAT or CAC (2 codons) → R at 3rd position
- Tyr (Y): TAT or TAC (2 codons) → Y at 3rd position

Primer: 5'-ATG TGG CAR TAY-3' (total degeneracy = 2 × 2 = 4-fold degenerate primer pool)

**Applications:**
- Cloning novel genes from organisms whose genome is not sequenced.
- Amplifying conserved regions of gene families (e.g., kinases, cytochrome P450s).
- Environmental metagenomics (16S rRNA, functional gene amplification from mixed microbial communities).
- Virus detection when sequence variation is expected.

**Protocol modifications:**
- Lower annealing temperatures (to accommodate imperfect matches in the primer pool).
- Touchdown PCR is particularly useful.
- More cycles (35–40) may be needed.
- Higher primer concentration (to ensure representation of all degenerate sequences).
- Use of MgCl₂ at lower end of optimization range (to avoid excessive non-specific bands from the large primer pool).

---

**Q46. What is multiplex PCR? Design an experiment to simultaneously detect two different antibiotic resistance genes from a plasmid.**

**Multiplex PCR** is a PCR variant in which two or more primer pairs (targeting different sequences) are included in the same reaction, amplifying multiple target sequences simultaneously. Each primer pair produces an amplicon of a different size (for discrimination on gel).

**Experimental design: Simultaneous detection of ampicillin resistance (blaᵀᴱᴹ gene, 286 bp) and kanamycin resistance (nptII gene, 534 bp) from plasmid DNA:**

**Primer sets:**
1. **blaᵀᴱᴹ primers:**
   - Forward: 5'-ATGAGTATTCAACATTTCCGTGTCG-3'
   - Reverse: 5'-CCAATGCTTAATCAGTGAGGCACC-3'
   - Expected product: 286 bp

2. **nptII primers:**
   - Forward: 5'-GAGGCTATTCGGCTATGACTG-3'
   - Reverse: 5'-ATCGGGAGCGGCGATACCGTA-3'
   - Expected product: 534 bp

**Reaction setup (50 µL):**
- Template plasmid DNA: 10 ng
- Both primer sets at 0.2 µM each (4 primers total)
- 2 mM MgCl₂ (slightly higher than standard — often needed for multiplex)
- 0.5 U *Taq* per primer pair (1 U total for 2 targets, or 2 U for better yield)
- Standard buffer and dNTPs

**Thermocycler:** Use a compromise annealing temperature between the Tm values of both primer sets (or use touchdown PCR if Tm values differ significantly).

**Expected gel result:**
- Lane with plasmid containing both genes: Two bands — 286 bp and 534 bp.
- Lane with plasmid containing only blaᵀᴱᴹ: One band at 286 bp.
- Lane with plasmid containing only nptII: One band at 534 bp.
- NTC: No bands.
- Use 100 bp DNA ladder for size confirmation.

---

**Q47. Explain the mechanism and applications of site-directed mutagenesis (SDM) using PCR. How does it differ from random mutagenesis?**

**Site-directed mutagenesis (SDM)** is a PCR-based technique used to introduce specific, predetermined nucleotide changes (point mutations, insertions, or deletions) at exact positions in a plasmid DNA sequence, thereby altering the encoded protein in a controlled manner.

**Overlap Extension PCR method:**
1. **Reaction 1:** Forward primer (wild-type) + Mutagenic reverse primer (containing the desired mutation in the middle of the primer) → Product A (contains mutation at 3' end).
2. **Reaction 2:** Mutagenic forward primer (same mutation, complementary sequence to mutagenic reverse) + wild-type Reverse primer → Product B (contains mutation at 5' end).
3. **Fusion PCR:** Products A and B are denatured and reannealed (they overlap in the mutated region), then extended by polymerase using outer primers only → full-length product containing the desired mutation.
4. Ligate into vector or use restriction-free cloning (Gibson Assembly) to replace wild-type sequence.

**QuikChange method (Agilent):**
- Single reaction: Two complementary mutagenic primers (each containing the mutation) + high-fidelity polymerase extend around the entire plasmid.
- DpnI digestion of methylated parental plasmid (from dam+ *E. coli*) selectively degrades template.
- Nicked mutant plasmid is transformed into *E. coli* for nick repair and propagation.

**Applications of SDM:**
- Structure-function studies of proteins (e.g., mutating catalytic residues of enzymes).
- Drug target validation (introduce resistance mutations to confirm drug binding site).
- Codon optimization (replace rare codons with preferred codons for expression).
- Correction of sequencing errors in cloned genes.
- Engineering binding sites, promoters, or regulatory elements.
- Introduction/removal of restriction sites for cloning.

**Difference from random mutagenesis:**
- SDM: Precise, predetermined changes at specific positions; requires knowledge of sequence; used for mechanistic studies.
- Random mutagenesis (error-prone PCR, chemical mutagenesis): Introduces mutations at random throughout the sequence; used in directed evolution (selecting for improved enzyme variants from a library of random mutants).

---

**Q48. What is the significance of the 5' overhang in PCR primers used for cloning? How are restriction sites incorporated into primers?**

When PCR is used to generate fragments for restriction enzyme-based directional cloning, restriction enzyme recognition sequences are incorporated into the 5' ends of PCR primers as **5' overhangs** (also called 5' tails or 5' extensions). These overhangs are not complementary to the template during PCR but are copied and incorporated into both strands of the amplicon after the first few cycles.

**Structure of a restriction site-containing primer:**
5'-[Extra bases]-[Restriction site]-[Template-specific sequence]-3'
- **Extra bases (3–6 bp):** Required for efficient restriction enzyme binding and cutting near the end of the PCR product; most restriction enzymes require at least 2–6 bp of "flank" outside the recognition sequence. Without these, restriction enzyme cleavage efficiency drops dramatically.
- **Restriction site (6 bp for 6-cutter):** e.g., EcoRI (GAATTC) or HindIII (AAGCTT); must not be present internally in the PCR product.
- **Template-specific sequence (18–25 bp):** Determines annealing specificity.

**Example:**
Forward primer with EcoRI site:
5'-**CGCGAATTC**ATGCGATCGATCGATCGA-3'
(CGCG = extra bases; GAATTC = EcoRI site; rest = template-specific)

Reverse primer with HindIII site:
5'-**CCCAAGCTT**CGATCGATCGCATGCATG-3'
(CCC = extra bases; AAGCTT = HindIII site; rest = template-specific reverse complement)

**Cloning procedure:**
1. PCR amplify insert with restriction-tailed primers → PCR product contains EcoRI and HindIII sites at respective ends.
2. Digest PCR product + vector with EcoRI + HindIII.
3. Gel-purify digested insert and vector.
4. Ligate insert into vector with T4 DNA ligase.
5. Transform, plate, pick colonies, perform colony PCR to identify recombinants.
6. Sequence-verify selected clones.

**Directional cloning advantage:** Using two different restriction enzymes ensures insert is cloned in the correct orientation (asymmetric ends); single-enzyme cloning allows insert to integrate in both orientations.

---

**Q49. What is the significance of the A260/A280 and A260/A230 ratios measured by NanoDrop? How would you interpret a ratio of 1.5 and what action would you take before PCR?**

**NanoDrop spectrophotometric ratios:**

**A260/A280 ratio (DNA purity indicator):**
- A₂₆₀: Absorbance at 260 nm — absorbed by nucleic acids (aromatic rings of purines and pyrimidines); used to calculate DNA concentration (Beer-Lambert: A₂₆₀ = 0.02 µg/µL × ε × path; for dsDNA, 1 OD₂₆₀ = 50 µg/mL).
- A₂₈₀: Absorbance at 280 nm — absorbed by aromatic amino acids (tyrosine, tryptophan, phenylalanine) in proteins; also phenol absorbs at 270–280 nm.
- **Pure dsDNA: A260/A280 = 1.8** (acceptable range 1.7–2.0).
- A260/A280 < 1.8: Protein contamination or residual phenol (protein/phenol absorbs at 280 nm, reducing the ratio).
- A260/A280 > 2.0: RNA contamination (RNA absorbs more at 260 nm relative to 280 nm); also single-stranded DNA has a slightly higher ratio.

**A260/A230 ratio (organic solvent/chaotropic salt contamination):**
- A₂₃₀: Absorbed by organic compounds — guanidinium thiocyanate (from silica column extraction), EDTA, carbohydrates, phenol.
- **Pure DNA: A260/A230 = 2.0–2.2.**
- A260/A230 < 1.8: Residual guanidinium salts, EDTA, phenol, ethanol, or other contaminants — inhibitors of PCR.

**Interpreting A260/A280 = 1.5:**
- This indicates significant protein contamination (or phenol residue) in the DNA preparation.
- **Action before PCR:**
  1. Do not use this template directly — protein contaminants will inhibit *Taq* polymerase.
  2. Re-purify: Repeat phenol:chloroform:isoamyl alcohol (25:24:1) extraction → chloroform extraction → ethanol precipitation; or use PCR cleanup column.
  3. Alternatively: Dilute template 10-fold (may dilute inhibitors below inhibitory threshold while still providing sufficient template).
  4. Re-quantify after cleanup; confirm A260/A280 ≥ 1.8 before proceeding.
  5. Verify PCR-grade quality with a test PCR using positive control primers.

---

**Q50. Discuss the latest advances in PCR technology. How have digital PCR, isothermal amplification, and CRISPR-based diagnostics changed molecular diagnostics?**

**1. Digital PCR (dPCR):**
Digital PCR partitions the PCR reaction into thousands to millions of individual nanoliter or picoliter volume reactions (droplets in droplet digital PCR [ddPCR] or chambers in chip-based dPCR). Each partition either contains a target molecule (positive, fluorescence) or does not (negative, no fluorescence). After PCR, the fraction of positive partitions is counted and, using Poisson statistics, the absolute number of target molecules is calculated without a standard curve.

- **ddPCR (Bio-Rad QX200):** Uses microfluidics to generate 20,000 droplets per sample in water-in-oil emulsion; each droplet undergoes independent PCR.
- **Advantages over qPCR:** Absolute quantification (copies/µL without standards); higher precision and sensitivity; superior performance with inhibitors; detects rare mutations (1 in 10,000 wild-type copies) — crucial for liquid biopsy (circulating tumor DNA), rare variant detection, copy number variation.
- **Applications:** Rare mutation detection (oncology), GMO quantification, viral load in HIV/HCV, residual disease monitoring in leukemia.

**2. Isothermal Amplification:**
Unlike PCR, isothermal methods amplify DNA/RNA at a constant temperature (no thermocycler needed), making them suitable for point-of-care (POC) and field diagnostics:
- **LAMP (Loop-Mediated Isothermal Amplification):** 6 primers recognize 8 distinct sequences on target; amplification at 60–65°C for 30–60 min; produces large amounts of DNA detectable by turbidity, colorimetry (HNB dye), or lateral flow strip.
- **NASBA (Nucleic Acid Sequence-Based Amplification):** RNA amplification at 41°C; used for RNA targets (HIV, dengue).
- **RPA (Recombinase Polymerase Amplification):** Room temperature amplification using recombinases; results in 10–20 min; compatible with lateral flow detection.
- **Applications:** SARS-CoV-2 field diagnostics, malaria, TB, food pathogen testing.

**3. CRISPR-based diagnostics (SHERLOCK, DETECTR):**
CRISPR-Cas systems (particularly Cas12 and Cas13) have collateral cleavage activity — upon binding the target nucleic acid, Cas12/Cas13 indiscriminately cleaves reporter molecules (fluorescent ssDNA/RNA probes), generating a detectable signal.
- **SHERLOCK (Specific High-sensitivity Enzymatic Reporter unLOCKing):** Combines isothermal amplification (RPA or LAMP) + Cas13a for RNA detection; attomolar sensitivity.
- **DETECTR (DNA Endonuclease-Targeted CRISPR Trans Reporter):** Combines LAMP + Cas12a for DNA detection; used for SARS-CoV-2, HPV.
- **CRISPR-Dx advantages:** High sensitivity (~100 copies/mL), single-nucleotide specificity, no thermocycler required, compatible with lateral flow strips for visual readout, multiplexable.
- These platforms represent the next generation of molecular diagnostics — combining PCR-level sensitivity with point-of-care simplicity.

---

*End of Molecular Biology – VIII. Amplification of Plasmid DNA from Bacteria by Conventional PCR Method and Post PCR Analysis by Agarose Gel Electrophoresis*
*Total: 50 Questions with Detailed Answers*
*Coverage: Basic Principles (Q1–10) | Procedure & Methodology (Q11–25) | Calculations & Data Interpretation (Q26–35) | Troubleshooting (Q36–43) | Applications & Advanced (Q44–50)*
