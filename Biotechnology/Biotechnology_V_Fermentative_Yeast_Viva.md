# Biotechnology — Section V
## Isolation, Characterization and Screening of Fermentative Yeast from Different Samples

> **Masters Level Viva Questions & Detailed Answers**
> 50 Questions | Arranged: Basic Principles → Procedure → Calculations → Troubleshooting → Applications/Interpretation

---

### PART A: Basic Principles & Background (Q1–Q12)

---

**Q1. What are yeasts and how are they taxonomically classified?**

Yeasts are unicellular fungi that predominantly reproduce asexually by budding (multilateral or polar) or fission, though many can also reproduce sexually. They are not a formal taxonomic group but a functional/morphological category spanning two fungal phyla: Ascomycota (e.g., *Saccharomyces*, *Pichia*, *Kluyveromyces*, *Candida*, *Yarrowia*) and Basidiomycota (e.g., *Cryptococcus*, *Rhodotorula*, *Trichosporon*). Ascomycetous yeasts reproduce sexually by forming ascospores within asci; basidiomycetous yeasts form basidiospores or teliospores. Most industrially important fermentative yeasts belong to the family Saccharomycetaceae within the Ascomycota. *Saccharomyces cerevisiae* is the model and workhorse fermentative yeast — its genome was the first eukaryotic genome fully sequenced (1996). Yeast classification has been substantially revised by molecular phylogenetics (ITS, D1/D2 domain of 26S rRNA gene sequencing); the authoritative reference is "The Yeasts: A Taxonomic Study" (Kurtzman, Fell, and Boekhout). Key distinguishing features for classification include: cell morphology, budding pattern, ascospore shape, fermentation of specific sugars, assimilation of carbon and nitrogen compounds, and molecular markers.

---

**Q2. What is alcoholic fermentation and what is the biochemical pathway involved?**

Alcoholic fermentation is the anaerobic or micro-aerobic conversion of sugars (glucose, fructose, sucrose, maltose) to ethanol and carbon dioxide by yeast, catalyzed by the enzymes of the Embden-Meyerhof-Parnas (EMP) glycolytic pathway followed by pyruvate decarboxylase (PDC) and alcohol dehydrogenase (ADH). The overall pathway: (1) *Glycolysis* — glucose → 2 pyruvate + 2 ATP + 2 NADH (net); the investment of 2 ATP and recovery of 4 ATP gives a net gain of 2 ATP per glucose. (2) *Pyruvate decarboxylation* — pyruvate + H⁺ → acetaldehyde + CO₂, catalyzed by pyruvate decarboxylase (PDC; requires TPP — thiamine pyrophosphate as cofactor). (3) *Ethanol formation* — acetaldehyde + NADH + H⁺ → ethanol + NAD⁺, catalyzed by alcohol dehydrogenase (ADH; zinc metalloenzyme). The regeneration of NAD⁺ by ADH is essential for continued glycolysis (NADH must be reoxidized). Overall equation: **C₆H₁₂O₆ → 2 C₂H₅OH + 2 CO₂ (ΔG° = −235 kJ/mol)**. The theoretical yield is 0.511 g ethanol per g glucose (Gay-Lussac equation). CO₂ production (0.489 g CO₂ per g glucose consumed) causes visible bubbling in fermentation vessels and is used as a fermentation activity indicator.

---

**Q3. What is the Crabtree effect and how does it relate to yeast fermentation?**

The Crabtree effect (also called short-term Crabtree effect or aerobic fermentation) describes the phenomenon in certain yeasts — most notably *Saccharomyces cerevisiae* — where ethanol production occurs even under fully aerobic conditions when glucose concentration exceeds a threshold (approximately 0.1–0.2 g/L in continuous culture; approximately 5 g/L in batch culture). Above this threshold, the respiratory capacity of *S. cerevisiae* is saturated; excess pyruvate is redirected to ethanol production via PDC and ADH rather than being fully oxidized via the TCA cycle and oxidative phosphorylation. The molecular basis involves: overflow metabolism at the pyruvate node; limited mitochondrial capacity (number and respiratory enzyme content); and regulation of pyruvate decarboxylase (PDC1, PDC5, PDC6 in *S. cerevisiae*) which has a sigmoidal kinetic response to pyruvate — at high glycolytic flux, pyruvate concentration rises sharply, strongly activating PDC. The Crabtree effect is industrially exploited: in ethanol production, high glucose concentrations favor ethanol over biomass; in baker's yeast production, glucose is fed at sub-Crabtree concentrations to maximize biomass and minimize ethanol by-product. Yeasts that do not exhibit the Crabtree effect (Crabtree-negative; e.g., *Kluyveromyces marxianus*, *Pichia kudriavzevii*) fully respire sugars aerobically regardless of glucose concentration.

---

**Q4. What is the Pasteur effect and how does it influence yeast metabolism?**

The Pasteur effect describes the inhibition of fermentation (anaerobic glycolysis and ethanol production) by the presence of oxygen in certain microorganisms. When *S. cerevisiae* is shifted from anaerobic to aerobic conditions, oxygen consumption increases, CO₂ production decreases, and ethanol production is suppressed as pyruvate is preferentially oxidized via the TCA cycle and oxidative phosphorylation (which generates ~32 ATP per glucose vs. only 2 ATP per glucose by fermentation). The mechanistic basis: (1) Oxygen allows reoxidation of NADH via the mitochondrial electron transport chain (ETC), removing the need to use acetaldehyde as NADH acceptor (fermentation). (2) The higher ATP yield of respiration enables allosteric feedback inhibition of phosphofructokinase (PFK) by ATP, slowing glycolytic flux. (3) ADP/AMP ratio changes modulate energy metabolism. However, in *S. cerevisiae* (a Crabtree-positive yeast), the Pasteur effect is incomplete above threshold glucose concentrations — ethanol production continues even under aerobic conditions due to the Crabtree effect overriding respiratory capacity. The Pasteur effect is more complete in Crabtree-negative yeasts (full respiratory metabolism when oxygen is present). In ethanol production, deliberately maintaining slightly anaerobic/micro-aerobic conditions exploits both the Pasteur effect (avoiding over-respiration that consumes ethanol) and the Crabtree effect.

---

**Q5. What are the key properties of an ideal fermentative yeast for industrial ethanol production?**

An ideal industrial fermentative yeast should possess: (1) *High ethanol yield* — close to theoretical maximum (0.511 g ethanol/g glucose); minimum carbon diversion to biomass, glycerol, acetic acid, and other by-products. (2) *High ethanol tolerance* — ability to grow and ferment at ethanol concentrations >10–15% (v/v); industrial fermentations target 12–18% ethanol to maximize reactor productivity and reduce distillation costs. (3) *High temperature tolerance* — fermentation at 35–42°C reduces cooling costs; thermotolerant yeasts (e.g., *Kluyveromyces marxianus*, heat-adapted *S. cerevisiae*) are valuable. (4) *Osmotolerance* — tolerance to high initial sugar concentrations (250–300 g/L in "very high gravity" — VHG fermentation) which create high osmotic stress (water activity reduction). (5) *Broad substrate utilization* — ability to ferment not just glucose and fructose but also maltose (for brewery/grain fermentations), sucrose (cane/beet sugar industry), and ideally pentoses (xylose, arabinose from lignocellulosic biomass, though native *S. cerevisiae* cannot ferment pentoses). (6) *Flocculation* — self-aggregating (flocculent) strains settle rapidly after fermentation, simplifying yeast recovery and broth clarification. (7) *Genetic stability* — resistance to mutation and plasmid loss during long fermentations. (8) *GRAS status* — for food/beverage applications.

---

**Q6. What sample sources are used for isolating fermentative yeasts and what is the rationale?**

Fermentative yeasts can be isolated from a wide variety of sugar-rich, naturally fermenting environments: (1) *Fruits and fruit surfaces* — the waxy epicuticular wax layer of ripe fruits (grapes, plums, figs, berries) harbors resident yeast populations; grape berries are the most classic source of *S. cerevisiae* and wine yeasts; damaged or overripe fruits have higher yeast loads. (2) *Sugarcane juice and jaggery* — the non-sterilized crush of sugarcane carries yeasts from the stalk surface and processing equipment; jaggery (unrefined cane sugar) contains residual fermentative yeasts from traditional preparation. (3) *Fermented foods and beverages* — toddy (fermented palm sap), beer/wine in active fermentation, bread dough, kefir, koumiss, sake, palm wine — all are rich sources of specialized fermentative yeasts. (4) *Soil and rhizosphere* — yeasts are present in soil, particularly beneath fruit trees; rhizosphere soil of sugarcane, grape, and fruit orchards is enriched with fermentative species. (5) *Flower nectars and tree saps* — natural sugar-rich substrates attracting insect-transmitted yeasts. (6) *Industrial environments* — bakeries, wineries, breweries, distilleries; equipment surfaces, drain sediments. The rationale: environments with naturally high sugar concentrations and anaerobic/micro-aerobic niches select for organisms capable of tolerating osmotic stress, low pH, and elevated ethanol — characteristics of superior industrial fermentation yeasts.

---

**Q7. What is the Durham tube method and what does it test in yeast characterization?**

The Durham tube method is a simple, classical test for gas production (CO₂) from sugar fermentation in yeast physiology characterization. A small inverted glass tube (Durham tube, approximately 6×30 mm) is placed inside a larger fermentation tube (e.g., 18×180 mm test tube) filled with basal medium containing a specific fermentable sugar (glucose, fructose, sucrose, maltose, lactose, galactose, trehalose, etc.) plus a pH indicator (Andrade's indicator — acid fuchsin turns pink at acidic pH) or bromocresol purple. After autoclaving, the Durham tube fills with liquid (inverted, no air bubble). After inoculation with yeast, the tube is incubated at 25–30°C. A positive fermentation result is indicated by: (1) Accumulation of CO₂ gas bubble in the inverted Durham tube (the gas produced by fermentation is trapped and cannot escape from the closed bottom of the inverted tube — it rises to fill the inverted tube). (2) Color change of pH indicator from purple/colorless to yellow/pink (acidification from organic acids produced during fermentation). Failure to produce gas indicates the yeast cannot ferment that specific sugar. This test differentiates yeast species and genera based on their fermentation spectrum (which sugars can be fermented), a key character in Bergey's/CBS classification. Fermentation of glucose but not lactose (which lacks β-galactosidase), for example, is characteristic of *S. cerevisiae*.

---

**Q8. What is the difference between fermentation and assimilation in yeast sugar utilization tests?**

Fermentation and assimilation are distinct physiological capacities that must be tested separately: *Fermentation* (anaerobic utilization) — the yeast converts a sugar to ethanol + CO₂ under anaerobic or micro-aerobic conditions; tested by Durham tube method with CO₂ bubble formation as indicator; requires sugar-specific permeases, kinases, and the complete glycolytic + fermentative pathway (PDC + ADH). *Assimilation* (aerobic utilization/growth) — the yeast can use a sugar as the sole carbon source for growth under aerobic (oxidative) conditions; tested by the Auxanographic (Wickerham) method: yeast is embedded in carbon-free agar, and sugar solutions are added to wells or as filter paper discs; growth halo around the disk/well indicates the yeast can assimilate that sugar. A sugar can be assimilated but not fermented (e.g., many yeasts assimilate but cannot ferment lactose without β-galactosidase for hydrolysis and the appropriate metabolic enzymes for anaerobic conversion). A sugar that is fermented can always be assimilated (since fermentation requires initial oxidative-equivalent utilization). The fermentation spectrum is therefore a subset of the assimilation spectrum. For industrial screening, fermentation of glucose, fructose, sucrose, and maltose (beer/bread yeast), or of xylose (lignocellulosic bioethanol), is the key criterion.

---

**Q9. What is the principle of the methylene blue viability test for yeast cells?**

Methylene blue is a redox dye used to assess yeast cell viability (live vs. dead discrimination). Live yeast cells have active NADH-dependent reductase activity in their cytoplasm; these enzymes reduce the oxidized (blue) form of methylene blue to its colorless, leuco-methylene blue form. Dead or metabolically inactive cells cannot perform this reduction; they remain stained blue. Procedure: mix equal volumes of yeast suspension and 0.01% aqueous methylene blue solution; allow 5 minutes contact time at room temperature; observe under microscope. Live cells appear colorless/transparent (unstained); dead cells appear blue. Count at least 200–300 cells; calculate: **% viability = (number of colorless cells / total cells counted) × 100**. Industrial fermentations require inoculum viability >90% (ideally >95%) for consistent fermentation performance. A viability below 80% leads to prolonged lag phase, slow fermentation rate, and reduced ethanol yield. Limitations of methylene blue: (1) Some metabolically stressed-but-viable cells may not reduce the dye rapidly (false dead), underestimating viability. (2) Some freshly dead cells may transiently maintain reductase activity (false viable). CFDA/PI (carboxyfluorescein diacetate / propidium iodide) flow cytometry is a more accurate modern alternative but requires specialized equipment.

---

**Q10. What is the Gomori Methenamine Silver (GMS) or India ink staining used in yeast identification and when is it indicated?**

India ink (nigrosin) staining is specifically used to visualize capsule production around yeast cells. The India ink particles (colloidal carbon black) are excluded by the polysaccharide capsule, creating a clear halo around the encapsulated yeast cell against a dark background. This test is most importantly used for *Cryptococcus neoformans* — an encapsulated basidiomycetous yeast and significant opportunistic pathogen (causes cryptococcal meningitis in immunocompromised patients); a prominent capsule (>2–5 μm) in India ink preparation of cerebrospinal fluid is highly diagnostic. For laboratory isolates from environmental sources, India ink preparation quickly distinguishes encapsulated yeasts from non-encapsulated fermentative yeasts (*S. cerevisiae*, *Pichia*, *Kluyveromyces* do not produce significant capsules). Gomori Methenamine Silver (GMS) staining is a histological stain used for tissue sections to detect fungal elements (both yeasts and molds) in clinical specimens — it silver-stains fungal cell walls black against a green background; it is not used for environmental isolation screening. For routine yeast identification in the microbiology lab, India ink, Gram staining, methylene blue, and slide culture morphology are the primary direct microscopic methods.

---

**Q11. What is ethanol tolerance in yeast and what mechanisms underlie it?**

Ethanol tolerance is the ability of a yeast strain to grow, ferment, and survive at elevated ethanol concentrations (typically >10–15% v/v in industrial contexts). It is a multi-factorial trait: (1) *Membrane composition* — ethanol intercalates into the phospholipid bilayer, increasing membrane fluidity and permeability; tolerant strains compensate by altering membrane lipid composition: increasing the proportion of longer-chain, more saturated fatty acids (C18:0 > C16:0) and ergosterol content, which stabilizes membrane structure. Unsaturated fatty acids (oleic acid, linoleic acid) supplementation in the medium improves ethanol tolerance in *S. cerevisiae*. (2) *Heat shock proteins (HSPs)* — ethanol induces a heat-shock-like stress response; upregulation of Hsp104, Hsp70 (Ssa1, Ssa2), and Hsp90 (Hsc82) chaperones prevents aggregation of ethanol-denatured proteins. (3) *Trehalose accumulation* — trehalose (a disaccharide) acts as a chemical chaperone protecting membrane integrity and protein structure under ethanol stress; Tps1 (trehalose-6-phosphate synthase) activity correlates with ethanol tolerance. (4) *Cell wall remodeling* — changes in glucan and mannoprotein content strengthen the cell wall against ethanol-induced disruption. (5) *Efflux pumps* — some studies suggest active efflux of ethanol, though this is energetically costly. Industrial high-tolerance strains (capable of >18–20% ethanol in VHG fermentation) have been selected by sequential adaptation or genome shuffling for superior tolerance mechanisms.

---

**Q12. What is osmotolerance in yeast and how is it relevant to fermentation of high-gravity media?**

Osmotolerance (also called osmophilicity in yeasts that thrive under high osmotic pressure) is the ability to grow and ferment at low water activity (high solute concentrations). In high-gravity (HG, 200–250 g/L sugar) and very high gravity (VHG, 270–350 g/L sugar) fermentations, the high initial sugar concentration creates severe osmotic stress: water is drawn out of yeast cells by osmosis, the cytoplasm dehydrates, enzyme activities decrease, and fermentation rate slows dramatically. Key osmotolerance mechanisms: (1) *Glycerol production* — the primary compatible solute in *S. cerevisiae*; glycerol accumulates in the cell to counterbalance external osmotic pressure; regulated by the HOG (High Osmolarity Glycerol) MAP kinase pathway (Ssk1→Pbs2→Hog1 cascade); however, glycerol production consumes carbon and NADH that could produce ethanol — a yield penalty of approximately 3–5% ethanol. (2) *Trehalose* — accumulates as an osmolyte under osmotic stress. (3) *Aquaporin modulation* — water channel proteins (Aqy1, Aqy2) regulate water flux across the plasma membrane. (4) *Ion homeostasis* — potassium transport (Trk1, Trk2) is critical for turgor maintenance. For industrial VHG fermentation, osmotolerant strains produce more ethanol per unit reactor volume (higher final ethanol titer) at the cost of longer fermentation time and potentially lower yield due to glycerol by-production.

---

### PART B: Media, Reagents & Procedure (Q13–Q28)

---

**Q13. What media are used for isolation, enumeration, and characterization of fermentative yeasts?**

(1) *Yeast Extract Peptone Dextrose (YEPD / YPD)* — Yeast extract (10 g/L), Peptone (20 g/L), Glucose (20 g/L), Agar (20 g/L), pH 6.5; the universal rich growth medium for yeasts; supports rapid growth of virtually all heterotrophic yeasts; used for maintenance, enumeration, and physiological tests. (2) *Malt Extract Agar (MEA)* — Malt extract (30 g/L), Mycological peptone (5 g/L), Agar (15 g/L), pH 5.4; slightly acidic medium that selects for fungi/yeasts over bacteria; widely used for isolation from food and fermentation environments. (3) *Wallerstein Laboratory Nutrient (WLN) agar* — a differential medium with agar, nutrient salts, glucose, and bromocresol green indicator; different yeast species produce colonies of characteristic color and morphology on WLN agar; used in brewing for quality control. (4) *Sabouraud Dextrose Agar (SDA)* — pH 5.6; selects for yeasts and molds over bacteria. (5) *Lysine Agar* — lysine as sole nitrogen source; *Saccharomyces* species cannot assimilate lysine as nitrogen source and fail to grow; non-*Saccharomyces* yeasts grow; used to differentiate *Saccharomyces* from non-*Saccharomyces* in mixed populations. (6) *Chloramphenicol (50–100 μg/mL) supplementation* is added to all isolation media to suppress bacterial growth. (7) *Bismuth sulphite agar* — used for enumerating osmotolerant yeasts from high-sugar environments (fruit juices, honey, molasses).

---

**Q14. Describe the isolation procedure for fermentative yeasts from a fruit sample.**

Complete isolation procedure: (1) *Sample preparation* — take 10 g of fruit (skin + pulp) in a sterile stomacher bag; add 90 mL sterile 0.85% saline + 0.1% Tween 80; homogenize in stomacher for 2 minutes (or mash with sterile mortar and pestle for 3 minutes). For liquid samples (fruit juice, toddy), use directly. (2) *Serial dilution* — prepare 10-fold dilutions from 10⁻¹ to 10⁻⁶ in sterile saline. (3) *Plating* — spread 0.1 mL of appropriate dilutions (typically 10⁻² to 10⁻⁵) onto YEPD + chloramphenicol (50 μg/mL) plates in duplicate. Additionally plate on MEA + chloramphenicol. (4) *Incubation* — at 25–28°C for 3–5 days. Yeast colonies appear in 2–3 days; distinctly smaller, smoother, and different from fungal colonies. (5) *Colony selection* — pick colonies of diverse morphology (white/cream, pink, orange; smooth vs. rough; different sizes); select 50–100 colonies representing all morphological types. (6) *Purification* — re-streak each selected colony 2–3 times on YEPD agar for pure culture; confirm purity by microscopy (single morphological yeast type). (7) *Preliminary screening* — check for fermentation by inoculating pure cultures into glucose-Durham tube broth; incubate 24–48 hours; retain all gas-producing (CO₂-positive) isolates as fermentative yeasts. (8) *Preservation* — prepare glycerol stocks (20% glycerol) and store at −80°C; maintain working cultures on YEPD slants at 4°C.

---

**Q15. How do you perform macroscopic and microscopic characterization of yeast isolates?**

*Macroscopic characterization* on YEPD agar after 3–5 days at 25°C: Record (1) Colony diameter (mm); (2) Colony color (white, cream, yellow, pink, orange, red); (3) Surface texture (smooth, rough, powdery, wrinkled, mucoid); (4) Colony margin (entire, undulate, lobate, filamentous); (5) Colony elevation (flat, raised, convex, umbonate); (6) Colony opacity (opaque, translucent); (7) Colony consistency (butyrous — buttery/easily emulsified; viscous — stringy; hard/friable). *Microscopic characterization*: (1) Prepare wet mount or Gram stain from 24–48 hour liquid YEPD culture. (2) Observe cell shape (spherical, ellipsoidal, cylindrical, ogival, elongated, lemon-shaped/apiculate); (3) Cell size (μm, measure 20 cells); (4) Budding pattern (multilateral — buds from multiple sites = *Saccharomyces*-type; polar/bipolar = *Hanseniaspora*/apiculate type; fission = *Schizosaccharomyces*); (5) Presence of pseudohyphae (elongated connected buds) or true hyphae; (6) Ascospore formation: inoculate on sporulation medium (V8 juice agar, acetate agar, potassium acetate agar) and observe for asci containing ascospores (1–4 per ascus; shape varies: spherical, hat-shaped, reniform, needle-shaped); (7) Capsule by India ink; (8) Vacuoles, lipid droplets, glycogen granules visible in older cells.

---

**Q16. How is the sugar fermentation profile determined for yeast characterization?**

Sugar fermentation profile (fermentation spectrum) is one of the key physiological characters for yeast classification. Method (Durham tube method): (1) Prepare a set of fermentation tubes each containing a single sugar as carbon source: D-glucose (2%), D-fructose (2%), D-galactose (2%), sucrose (2%), maltose (2%), D-lactose (2%), trehalose (2%), D-cellobiose (2%), D-melibiose (2%), raffinose (2%) in Yeast Nitrogen Base (YNB) or peptone-water base with a pH indicator (Andrade's indicator or bromocresol purple). Each tube contains a small inverted Durham tube. (2) Autoclave tubes at 115°C (to avoid caramelization of sugars). (3) Inoculate each tube with a loopful of yeast from 24-48 hour YEPD culture. (4) Incubate at 25°C for 2–4 weeks (some fermentations are slow; read at 1, 2, 3, 4 weeks). (5) Record: (+) for gas bubble in Durham tube AND acid indicator change; (−) for no gas and no color change; (v) for variable; (+/−) for weak positive. *Expected for S. cerevisiae*: glucose (+), fructose (+), galactose (+), sucrose (+), maltose (+), lactose (−), raffinose (+/−, ferments the sucrose portion only), melibiose (−), cellobiose (−). The complete fermentation table is compared against the CBS (Centraalbureau voor Schimmelcultures) or NCYC yeast species descriptions for identification.

---

**Q17. How is the sugar assimilation profile (auxanogram) performed for yeast characterization?**

The auxanogram (Wickerham method) tests aerobic assimilation of individual carbon or nitrogen sources: (1) *Carbon assimilation:* Melt YEPD or YNB agar without carbon source; cool to 45–50°C; inoculate with 1 mL of dense yeast suspension (10⁸ cells/mL from overnight culture) per 20 mL agar; pour into Petri dish; allow to solidify. Punch wells or place filter paper discs on the surface. Add 50–100 μL of filter-sterilized 10% solutions of each sugar (glucose, fructose, sucrose, maltose, lactose, galactose, xylose, arabinose, sorbitol, glycerol, etc.) to wells/discs. Incubate at 25°C for 3–5 days. Read: growth halo around well = positive assimilation; no growth = negative. (2) *Nitrogen assimilation:* Similarly, use YNB without nitrogen source agar; add ammonium sulfate, potassium nitrate, lysine, cadaverine, ethylamine, etc. as individual nitrogen sources to wells. Read halo = can use that nitrogen source. *Significance:* Assimilation patterns are a primary character in the CBS identification key; API 20C AUX (bioMérieux) is a standardized commercial auxanogram system for yeasts using 20 carbon sources; VITEK 2 YST card extends this to automated identification. API 20C AUX is the most commonly used manual identification system in teaching laboratories.

---

**Q18. How is ethanol tolerance of yeast isolates screened in the laboratory?**

Ethanol tolerance screening methods: (1) *Plate-based screening* — prepare YEPD agar plates supplemented with increasing ethanol concentrations (0, 5, 8, 10, 12, 14, 16, 18% v/v); spot 5 μL of standardized yeast suspension (10⁶–10⁸ cells/mL) onto each plate; incubate 48–72 hours at 30°C; score growth as: +++, ++, +, ± or − (no growth). The maximum ethanol concentration supporting visible growth is the ethanol tolerance threshold. This is rapid and allows simultaneous comparison of many isolates across multiple concentrations. (2) *Broth-based MIC approach* — prepare YEPD broth with 2-fold increasing ethanol concentrations; inoculate; incubate 24–48 hours; measure OD₆₀₀; plot growth curve against ethanol concentration; determine IC₅₀ (concentration inhibiting 50% growth) and MIC (no visible turbidity). (3) *Fermentation tolerance test* — inoculate yeast into fermentation medium (glucose 200 g/L, yeast extract, mineral salts) with 10–15% ethanol added to the starting medium, simulating late-fermentation conditions; monitor fermentation by CO₂ production or ethanol production by HPLC. Strains that initiate and complete fermentation under pre-added ethanol are classified as ethanol-tolerant. Industrial relevance: strains tolerating >15% ethanol are suitable for VHG ethanol fermentation; strains with lower tolerance (< 8%) are unsuitable for industrial applications.

---

**Q19. How is temperature tolerance of fermentative yeast isolates determined?**

Temperature tolerance screening: (1) *Growth temperature range* — inoculate standardized yeast suspension (OD₆₀₀ = 0.1) into YEPD broth in multiple tubes; incubate simultaneously at 15, 20, 25, 30, 35, 37, 40, 42, 45°C for 48–72 hours; record presence/absence of visible turbidity and measure OD₆₀₀. The temperature range from minimum to maximum supporting visible growth defines the growth temperature range; the temperature of maximum growth rate (fastest turbidity increase) is the optimal growth temperature. (2) *Plate-based temperature range* — spot inoculate YEPD plates incubated at different temperatures; observe colony formation. (3) *Thermotolerant fermentation test* — inoculate into glucose fermentation medium; incubate at 37°C, 40°C, 42°C; measure CO₂ evolution (gas trapped in Durham tube or measured by weight loss method) and final ethanol concentration. Strains fermenting efficiently at 37–40°C are classified as thermotolerant; *S. cerevisiae* typically grows up to 40–42°C (maximum); thermotolerant industrial strains and *Kluyveromyces marxianus* grow and ferment up to 45–50°C. Thermotolerance is industrially desirable because: fermentation at 37–40°C reduces cooling costs in tropical countries; simultaneous saccharification and fermentation (SSF) of starch operates more efficiently at higher temperatures where amylases work optimally; and contamination by lactic acid bacteria (which prefer lower temperatures) is reduced.

---

**Q20. Describe the rapid screening test for ethanol production potential (inverted tube / weight loss method).**

The inverted tube (CO₂ evolution) method screens ethanol production capacity of multiple isolates simultaneously: (1) Prepare fermentation tubes containing 10 mL glucose medium (glucose 20 g/L, yeast extract 10 g/L, peptone 20 g/L) with a Durham tube inside. (2) Inoculate each tube with 1 mL of standardized yeast inoculum (from overnight YEPD culture, OD₆₀₀ = 0.5–1.0). (3) Seal tubes with cotton plugs (allow CO₂ to escape but minimize evaporation). (4) Incubate at 30°C for 24–48 hours. (5) Observe Durham tube CO₂ accumulation: large gas bubble = active fermentation; no bubble or small bubble = poor fermentation. (6) Record time to fill Durham tube (faster = more active fermentation). *Weight loss method (more quantitative):* Seal fermentation flask with a cotton plug; weigh the flask + culture at time 0; weigh at intervals (12, 24, 48 h); weight loss = mass of CO₂ evolved; since 1 mol CO₂ = 1 mol ethanol (Gay-Lussac equation), weight of ethanol produced ≈ 1.04 × weight of CO₂ lost (using MW ratio: 46.07/44.01 = 1.047). This non-invasive method avoids sampling and allows continuous monitoring without opening the vessel, reducing evaporation artifacts.

---

**Q21. What is the spread plate method for yeast enumeration from fermented samples and how is it performed?**

Yeast enumeration from fermentation samples (e.g., fermenting toddy, wine must, jaggery solution): (1) Prepare 10-fold serial dilutions of the sample in sterile 0.85% NaCl saline + 0.1% Tween 80 (to prevent cell clumping). For active fermentation samples with high CO₂, allow the sample to degas before diluting. (2) Spread 0.1 mL of dilutions 10⁻³ to 10⁻⁶ onto YEPD + chloramphenicol agar plates in duplicate using a sterile L-shaped glass spreader or Drigalski spatula. (3) Incubate at 25–28°C for 48–72 hours (yeasts form visible colonies in this time). (4) Count plates with 30–300 colonies; calculate yeast CFU/mL = colony count × (1/dilution factor) × (1/volume plated in mL). (5) Note: in mixed fermentation samples, distinguish yeast colonies (cream/white/smooth, 1–5 mm, butyrous) from bacterial colonies (smaller, often more uniform) and mold colonies (fuzzy, filamentous margins). Chloramphenicol suppresses bacteria but not yeasts or molds; if molds are also present, oxytetracycline + chloramphenicol medium (OCTC agar) or dichloran rose bengal chloramphenicol agar (DRBC) can be used to suppress mold spreading. For quantitative comparison between samples, yeast CFU/mL is the appropriate unit; for total yeast biomass, dry cell weight is preferred.

---

**Q22. How is yeast identified to genus/species level using molecular methods?**

Molecular identification of yeasts relies on sequencing conserved genomic regions: (1) *Internal Transcribed Spacer (ITS) region* — the ITS1-5.8S-ITS2 region (approximately 500–800 bp) of the ribosomal RNA gene cluster is the primary barcode for fungal species identification (accepted as the universal fungal barcode by the ITS Consortium, 2012); amplified using universal primers ITS1 (5'-TCCGTAGGTGAACCTGCGG-3') and ITS4 (5'-TCCTCCGCTTATTGATATGC-3'). High variability within and between species allows genus and sometimes species-level identification. (2) *D1/D2 domain of 26S rRNA gene* — the variable D1/D2 domain (approximately 600 bp) of the large subunit rRNA is the recommended locus for yeast identification, with >1% sequence divergence typically indicating different species. Primers NL1 and NL4 are used. (3) *Combined ITS + D1/D2* — using both loci together increases resolution. Procedure: extract genomic DNA (CTAB method or commercial kit e.g., CTAB-chloroform method for yeast); PCR-amplify the target region; Sanger-sequence the PCR product (forward and reverse sequencing); assemble consensus sequence; BLAST against NCBI GenBank or CBS UNITE database; species identity confirmed at >99% sequence similarity to type strain. *MALDI-TOF MS* (Matrix-Assisted Laser Desorption/Ionization Time-of-Flight Mass Spectrometry) is an alternative rapid identification method that compares whole-cell protein profiles against a reference database and can identify most common yeasts in minutes.

---

**Q23. How is the API 20C AUX test system used for yeast identification?**

The API 20C AUX (bioMérieux, France) is a miniaturized standardized system for identifying yeasts based on assimilation of 19 carbon sources plus a negative control: (1) Prepare a suspension of the yeast in API Suspension Medium (turbidity matched to a 2 McFarland standard); mix suspension with API C Medium (minimal medium without carbon source). (2) Pipette 100 μL of the inoculated medium into each of the 20 cupules; cupule 0 (negative control, no carbon source); cupules 1–19 contain dehydrated carbon sources (glucose, glycerol, 2-keto-gluconate, arabinose, xylose, adonitol, xylitol, galactose, inositol, sorbitol, methyl-α-D-glucopyranoside, N-acetylglucosamine, cellobiose, lactose, maltose, sucrose, trehalose, melezitose, raffinose). (3) Overlay each cupule with sterile mineral oil to create anaerobic-like conditions (prevents surface evaporation and favors anaerobic assimilation assessment). (4) Incubate at 30°C for 48–72 hours (read at 48 h and 72 h). (5) Observe turbidity in each cupule vs. negative control cupule 0; turbid = positive assimilation; clear = negative. (6) Convert positive/negative pattern to a 7-digit numerical profile; look up profile in API database (online ATB system or apiweb); the database provides probable species identification with % confidence. API 20C is used widely in clinical and industrial labs; supplemented with additional tests (fermentation, morphology, temperature range) for definitive identification.

---

**Q24. What is the ethanol yield test in liquid fermentation for secondary screening of yeast isolates?**

Quantitative ethanol yield testing is performed after primary screening identifies fermenting isolates: (1) Inoculate each isolate into 100 mL of standard fermentation medium (glucose 200 g/L, yeast extract 5 g/L, peptone 10 g/L, (NH₄)₂SO₄ 2 g/L, KH₂PO₄ 1 g/L, MgSO₄ 0.5 g/L, pH 5.0) in 250 mL Erlenmeyer flasks sealed with cotton plugs or fermentation locks (water trap that allows CO₂ to escape while preventing air entry). (2) Standardized inoculum: 10⁶–10⁷ cells/mL, verified by haemocytometer count and methylene blue viability (>95% viable). (3) Incubate at 30°C, static or slow shaking (50–100 rpm) to maintain micro-aerobic conditions favoring fermentation over respiration. (4) After 48–72 hours (or until CO₂ evolution ceases indicating completion), centrifuge broth; collect cell-free supernatant. (5) Measure ethanol concentration: (a) by the dichromate oxidation method (colorimetric; ethanol reduces Cr₂O₇²⁻ to Cr³⁺, green color, read at 578 nm); (b) by GC (gas chromatography, most accurate; injecting supernatant with n-propanol as internal standard into a DB-WAX or Carbowax column); (c) by HPLC (Aminex HPX-87H, RI detector). (6) Measure residual glucose (DNS or glucose oxidase-peroxidase kit). (7) Calculate ethanol yield (g/g glucose), volumetric productivity (g/L/h), and specific ethanol production rate (g ethanol/g biomass/h).

---

**Q25. How is the haemocytometer used to count yeast cells and calculate inoculum density?**

The improved Neubauer haemocytometer is a thick glass slide with a precisely defined counting chamber of known depth (0.1 mm). Procedure: (1) Mix yeast suspension well to break clumps; dilute if necessary (optimal: 10–50 cells per small square). (2) Clean haemocytometer and coverslip with 70% ethanol; allow to dry. (3) Place the special, flat coverslip firmly over the raised edges of the chamber. (4) Apply 10 μL of diluted yeast suspension at the edge of the coverslip; capillary action draws the suspension under the coverslip to fill the counting chamber. (5) Allow cells to settle for 2–3 minutes. (6) Under 10× or 40× objective, count yeast cells in 5 large squares of the central grid (each large square = 1 mm², subdivided into 16 small squares; depth = 0.1 mm; volume per large square = 0.1 μL). Count cells touching the top and left boundary lines but not bottom and right. Include budding cells as one cell (count parent + bud as 1). (7) Calculate: **Cells/mL = (Total cells in 5 large squares / 5) × 10 × dilution factor × 10⁴** where: ÷5 gives average per large square; ×10 converts 0.1 mm depth to 1 mm (1 mL equivalent); dilution factor accounts for any dilution made; ×10⁴ converts to per mL (since each large square = 10⁻⁴ mL). For simultaneous viability: add methylene blue before loading; count blue (dead) and colorless (live) cells separately.

---

**Q26. How do you prepare a fermentation lock (water trap) and why is it used in yeast fermentation experiments?**

A fermentation lock (also called an airlock or water trap) is a one-way gas valve that allows CO₂ produced during fermentation to escape while preventing atmospheric oxygen from entering the fermentation vessel. It is essential for maintaining micro-aerobic or anaerobic conditions during ethanol fermentation screening because: (1) If the vessel is completely sealed, CO₂ pressure builds up and can rupture the flask or displace the stopper explosively. (2) If the vessel is open, atmospheric oxygen enters, activating the Crabtree-negative respiratory pathway in some yeasts, reducing ethanol yield and increasing biomass; also, ethanol evaporates, reducing measured titer. Simple laboratory fermentation lock: (1) Use a one-hole rubber stopper fitted to the flask neck. (2) Insert a bent glass tube or plastic tubing through the stopper hole. (3) Immerse the other end of the tubing in a small beaker or test tube of water (or glycerol solution for slow evaporation). CO₂ bubbles through the water; oxygen cannot enter because inward pressure would require pushing against the water column. Alternative simple method: cover the flask with a cotton plug (allows some gas exchange) or cling film pierced with a needle (partial gas exchange). For rigorous anaerobic control, a commercial S-shaped or two-bubble fermentation lock (plastic, used in wine/beer production) is the most reliable. Record CO₂ evolution by counting bubbles per minute as a fermentation activity indicator.

---

**Q27. What is the role of zinc in yeast fermentation and why is it included in some fermentation media?**

Zinc is an essential micronutrient for *S. cerevisiae* and other fermentative yeasts, required at trace levels (0.1–1 mg/L) for multiple physiological functions: (1) *Enzyme cofactor* — zinc is a structural and catalytic cofactor for alcohol dehydrogenase (ADH, the key enzyme of fermentation), carbonic anhydrase (CO₂ removal), RNA polymerase, and several metabolic dehydrogenases. Zinc deficiency severely impairs ADH activity, directly reducing ethanol production rate. (2) *DNA binding* — zinc finger domains in transcription factors (Gal4, Zap1) require Zn²⁺ for DNA binding; zinc deficiency impairs global gene regulation including fermentation gene expression. (3) *Cell wall integrity* — zinc is involved in cell wall chitin synthesis; deficiency weakens the cell wall. (4) *Membrane function* — zinc modulates fatty acid composition of membranes, affecting ethanol tolerance. In industrial fermentations using molasses (which may be zinc-deficient after ferrocyanide treatment to remove trace metals), zinc supplementation as ZnSO₄·7H₂O (0.5–2 mg/L) or zinc chloride significantly improves fermentation performance. In laboratory screening experiments, many synthetic fermentation media omit zinc from the mineral solution, which can give artificially low ethanol titers; including ZnSO₄ (0.3–1 mg/L) in the fermentation medium ensures zinc is not the limiting factor for fermentative capacity.

---

**Q28. What is the iodine test for glycogen detection in yeast and what is its significance?**

The iodine test for glycogen is performed by exposing yeast colonies (on agar) or liquid culture cells to Lugol's iodine (I₂ in KI solution): (1) Flood the agar plate surface with Lugol's iodine or add 1 drop to a wet mount slide of yeast suspension. (2) Observe immediately under microscope or macroscopically on plate: yeasts storing glycogen appear blue-black or brown-black; glycogen-negative yeasts remain unstained (pale yellow from iodine). *Significance in yeast characterization:* (1) *Taxonomic marker* — glycogen accumulation (amyloid reaction with iodine) is a species-level character; some *Saccharomyces* species are glycogen-positive; many non-*Saccharomyces* yeasts are negative. (2) *Metabolic indicator* — glycogen accumulation (alongside trehalose) indicates cells have entered a stressed or stationary phase (high carbohydrate storage reflects carbon excess relative to nitrogen or other limitations); inoculum from glycogen-rich, stationary-phase cultures tends to have faster lag phase recovery when reinoculated. (3) *Brewing context* — *S. cerevisiae* brewing strains are tested for glycogen levels as part of yeast quality assessment; high glycogen = yeast health; low glycogen = potential fermentation problems. (4) *Starch hydrolysis:* separately, *A. niger* and starch-utilizing yeasts that produce amylase can clear a starch agar plate around their colonies when flooded with iodine — this is the amylase screening test, analogous to caseinase detection in protease screening.

---

### PART C: Calculations & Data Interpretation (Q29–Q36)

---

**Q29. Calculate the theoretical ethanol yield from 200 g/L glucose fermentation and compare to an experimental yield of 75 g/L ethanol.**

From Gay-Lussac's stoichiometry:
**C₆H₁₂O₆ → 2 C₂H₅OH + 2 CO₂**
MW: 180.16 → 2 × 46.07 + 2 × 44.01

Theoretical ethanol yield = (2 × 46.07) / 180.16 = 92.14 / 180.16 = **0.511 g ethanol per g glucose**

From 200 g/L glucose:
Theoretical ethanol = 200 × 0.511 = **102.2 g/L** maximum possible

Experimental ethanol = 75 g/L

**% of theoretical yield = (75 / 102.2) × 100 = 73.4%**

This means 73.4% of the theoretical maximum was achieved. For comparison: industrial *S. cerevisiae* fermentations achieve 90–95% of theoretical; laboratory screening strains typically achieve 70–85% of theoretical. The remaining ~27% of carbon was diverted to: biomass synthesis (~5–8%), glycerol production (~3–5%), CO₂ from biosynthetic reactions, and other minor by-products (acetate, succinate, higher alcohols). A yield below 60% of theoretical suggests the isolate is a poor fermentative yeast or that fermentation conditions (nitrogen limitation, zinc deficiency, ethanol toxicity) prevented completion.

---

**Q30. Calculate the yeast cell density from the following haemocytometer count: In 5 large squares, you counted 45, 52, 48, 50, 43 cells respectively. The suspension was diluted 10-fold before counting.**

Total cells in 5 large squares = 45 + 52 + 48 + 50 + 43 = **238 cells**
Average per large square = 238 / 5 = **47.6 cells**

Cell concentration = Average per large square × 10 × 10⁴ × dilution factor
= 47.6 × 10 × 10⁴ × 10
= 47.6 × 10⁶
= **4.76 × 10⁷ cells/mL**

*If the formula is applied directly:*
Cells/mL = (238 / 5) × 10⁴ × 10 (dilution factor) × 10
= 47.6 × 10⁵ × 10 = **4.76 × 10⁷ cells/mL**

This cell density (4.76 × 10⁷ cells/mL) is suitable as an inoculum if the production fermentation requires 10⁶–10⁷ cells/mL; dilute 5-fold to achieve 9.52 × 10⁶ cells/mL. Viability should be simultaneously assessed by methylene blue staining on the same sample.

---

**Q31. From weight loss data in a fermentation experiment, calculate the ethanol produced.**

*Given:* Flask + medium + inoculum at time 0 = 255.40 g. After 48 hours = 253.82 g. Weight loss = 255.40 – 253.82 = **1.58 g** (= CO₂ evolved).

From Gay-Lussac stoichiometry: 1 mol CO₂ produced for every 1 mol ethanol
MW CO₂ = 44.01 g/mol; MW ethanol = 46.07 g/mol

Moles of CO₂ = 1.58 / 44.01 = **0.0359 mol CO₂**
Moles of ethanol = 0.0359 mol (1:1 ratio)
Mass of ethanol = 0.0359 × 46.07 = **1.655 g**

If fermentation volume = 100 mL = 0.1 L:
Ethanol concentration = 1.655 g / 0.1 L = **16.55 g/L**

*Note:* Weight loss method slightly underestimates ethanol because: (a) ethanol evaporates from the cotton plug, causing additional weight loss not attributable to CO₂; (b) water vapor is also lost with CO₂ bubbles. These factors cause overestimation of CO₂-attributed weight loss, so ethanol calculated from weight loss is typically 5–10% higher than actual ethanol measured by GC/HPLC. Use the correction factor by subtracting measured evaporation blank (sealed medium without yeast) from total weight loss.

---

**Q32. How do you calculate volumetric ethanol productivity and specific ethanol productivity?**

**Volumetric Productivity (Qp):**
Qp = Maximum ethanol concentration (g/L) / Fermentation time to maximum (h)

*Example:* 60 g/L ethanol achieved at 36 hours:
Qp = 60 / 36 = **1.67 g/L/h**

**Specific Ethanol Productivity (qp):**
qp = Qp / Biomass concentration (g DCW/L)

If DCW = 5 g/L at the time of maximum ethanol:
qp = 1.67 / 5 = **0.334 g ethanol/g DCW/h**

**Ethanol yield on substrate (Y_E/S):**
Y_E/S = Ethanol produced (g/L) / Glucose consumed (g/L)

If initial glucose = 200 g/L, residual glucose = 30 g/L, ethanol = 60 g/L:
Y_E/S = 60 / (200 – 30) = 60 / 170 = **0.353 g ethanol/g glucose**

% of theoretical = (0.353 / 0.511) × 100 = **69%** of theoretical maximum.

These three metrics (Qp, qp, Y_E/S) together comprehensively characterize a yeast strain's industrial ethanol production performance.

---

**Q33. How do you compare multiple yeast isolates in a screening program and select the best strain?**

Multi-criteria comparison protocol: (1) *Primary screening data:* Durham tube fermentation at 24 h, 48 h — record as +++ (large bubble, complete), ++ (medium), + (small), − (none). (2) *Secondary screening quantitative data (per isolate, n=3 replicates):* ethanol concentration (g/L), Y_E/S (g/g), Qp (g/L/h), residual sugar (g/L), DCW (g/L). (3) *Performance criteria:* record ethanol tolerance (maximum % v/v ethanol supporting growth), temperature tolerance (maximum °C supporting fermentation), osmotolerance (growth at 300 g/L glucose). (4) *Tabulate all results* in a comparative table; rank isolates on each criterion. (5) *Weighted scoring matrix:* assign weights to each criterion (e.g., ethanol titer 30%, Y_E/S 25%, ethanol tolerance 20%, temperature tolerance 15%, fermentation rate 10%); multiply each score by its weight and sum to give a composite score. Select the isolate with the highest composite score. (6) *Statistical validation:* one-way ANOVA for ethanol titer and Y_E/S across isolates; Tukey's test for pairwise significance. Only statistically significant differences (p < 0.05) justify ranking between isolates. (7) *Confirm identity* of selected top isolate(s) by 26S D1/D2 + ITS sequencing.

---

**Q34. If yeast produces 85 g/L ethanol from 200 g/L glucose in a 48-hour fermentation with a DCW of 6 g/L, calculate all relevant yield and productivity parameters.**

Given: Ethanol = 85 g/L; Glucose initial = 200 g/L; Glucose residual = 15 g/L (measured by DNS); DCW = 6 g/L; Time = 48 h.

Glucose consumed = 200 – 15 = **185 g/L**

**Y_E/S** = 85 / 185 = **0.459 g ethanol/g glucose**
**% Theoretical yield** = (0.459 / 0.511) × 100 = **89.8%** — excellent, approaching industrial benchmark.

**Y_X/S (biomass yield)** = 6 / 185 = **0.032 g DCW/g glucose** — low biomass yield, consistent with fermentation (Crabtree-positive, most carbon to ethanol not biomass).

**Qp (volumetric productivity)** = 85 / 48 = **1.77 g/L/h**

**qp (specific productivity)** = 1.77 / 6 = **0.295 g ethanol/g DCW/h**

**CO₂ produced** (stoichiometric): same moles as ethanol; mass = 85/46.07 × 44.01 = **81.1 g/L CO₂**

This strain shows outstanding performance: 89.8% of theoretical yield and 1.77 g/L/h productivity, comparable to industrial *S. cerevisiae* benchmark performance.

---

**Q35. How do you calculate the % volume/volume (v/v) ethanol concentration and convert between g/L and % v/v?**

Ethanol density at 20°C = **0.789 g/mL**

**Conversion: g/L ethanol → % v/v ethanol:**
% v/v = (g/L ethanol) / (density of ethanol, g/mL) / 10
= (g/L) / (0.789 × 10)
= (g/L) / 7.89

*Example:* 85 g/L ethanol:
% v/v = 85 / 7.89 = **10.77% v/v ethanol**

**Conversion: % v/v → g/L:**
g/L = % v/v × 0.789 × 10 = % v/v × 7.89

*Example:* 12% v/v ethanol:
g/L = 12 × 7.89 = **94.7 g/L**

In wine, beer, and spirits production, alcohol content is reported as % v/v (ABV — Alcohol By Volume). Industrial ethanol fermentation reports ethanol as g/L (analytical) or as % v/v for product specification. Knowing the interconversion is essential for comparing data reported in different units in the literature.

---

**Q36. How is the ethanol tolerance index (ETI) calculated and what does it indicate?**

The Ethanol Tolerance Index (ETI) is a composite measure of a yeast strain's ability to grow and ferment across a range of ethanol concentrations:

**ETI = Σ (OD₆₀₀ at concentration Cᵢ) / (OD₆₀₀ at 0% ethanol)**

measured across ethanol concentrations C₁, C₂,...Cₙ (e.g., 0, 5, 8, 10, 12, 14, 16% v/v).

*Example:*

| Ethanol (%) | OD₆₀₀ | Fraction of control |
|---|---|---|
| 0 | 1.80 | 1.000 |
| 5 | 1.72 | 0.956 |
| 8 | 1.55 | 0.861 |
| 10 | 1.20 | 0.667 |
| 12 | 0.65 | 0.361 |
| 14 | 0.18 | 0.100 |
| 16 | 0.02 | 0.011 |

ETI = (1.000 + 0.956 + 0.861 + 0.667 + 0.361 + 0.100 + 0.011) = **3.956**

A higher ETI indicates better ethanol tolerance. This normalized metric allows comparison between strains that may grow to different maximum densities. Strains with ETI > 4.0 (approximately) over the range 0–16% ethanol are considered highly tolerant industrial candidates.

---

### PART D: Troubleshooting (Q37–Q44)

---

**Q37. Durham tubes show no CO₂ in glucose fermentation medium after 48 hours. What are the possible reasons and how do you investigate?**

No gas in Durham tubes despite inoculation suggests: (1) *Yeast is dead or non-viable* — inoculum may have been killed by autoclave heat if added before sterilization; or stored at −20°C without glycerol cryoprotectant. Verify viability with methylene blue; if viability <50%, re-inoculate from a fresh culture. (2) *Air bubble trapped incorrectly* — if the Durham tube was not completely filled with liquid during autoclaving (was not submerged fully before autoclaving), a pre-existing air bubble is mistaken for CO₂. Re-check all Durham tubes before inoculation; any tube with pre-existing bubble must be discarded. (3) *The isolate is non-fermentative* — the strain may be a strictly respiratory yeast (Crabtree-negative, obligately aerobic; e.g., *Rhodotorula*, *Cryptococcus*); confirm by Warburg respiratory quotient test. (4) *Incubation temperature too high* — >42°C kills most yeast; check incubator thermometer. (5) *Medium pH extremes* — pH <2.0 or >8.0 inhibits yeast; check medium pH. (6) *Toxic medium components* — residual sterilization artifacts, excessive salt concentration, incorrect medium composition. Test with a known positive control (*S. cerevisiae* ATCC 9763). (7) *Insufficient incubation time* — some slow fermenters need 72–96 hours; extend incubation before concluding negative.

---

**Q38. Ethanol yield in secondary screening is much lower than expected from the primary Durham tube screen. How do you explain this?**

Discrepancy between positive Durham tube and low ethanol yield: (1) *Scale difference* — Durham tubes use small volumes (10 mL) with high surface-area-to-volume ratio; oxygen entry is higher, allowing partial respiration. In larger flasks (100 mL), if the fermentation lock is inadequate, oxygen can enter and divert carbon to respiration and biomass, reducing ethanol. Use proper fermentation locks in quantitative assays. (2) *Different glucose concentrations* — if Durham tube used 2% glucose (20 g/L) but production fermentation used 200 g/L, osmotic stress in the secondary screen reduces fermentation efficiency. Test at multiple glucose concentrations in secondary screening. (3) *Nitrogen limitation* — at very high glucose:nitrogen ratios in the production medium, nitrogen becomes limiting before all glucose is consumed, halting growth and reducing fermentation rate. Add more yeast extract or ammonium sulfate. (4) *Zinc deficiency* — laboratory fermentation medium without zinc may limit ADH activity. Add ZnSO₄ (0.3 mg/L) and compare. (5) *Ethanol accumulation toxicity* — at high initial glucose (200 g/L), ethanol accumulates to toxic levels; the isolate may have poor ethanol tolerance. Re-test at 100 g/L initial glucose. (6) *Assay error* — check ethanol measurement method calibration with known ethanol standards; ensure sufficient sample dilution for colorimetric assay linear range.

---

**Q39. On isolation plates, the cream-colored colonies you selected as yeasts turn out to be Gram-positive cocci on microscopy. How did this happen and how do you prevent it?**

Gram-positive cocci on isolation plates likely represent: (1) *Lactic acid bacteria (LAB)* — particularly *Leuconostoc*, *Lactococcus*, or *Weissella* from fruit/food samples; their colonies can be cream-colored, smooth, and resemble yeast at macroscopic level, especially on rich media. LAB are chloramphenicol-susceptible but if chloramphenicol was not included or was at insufficient concentration, they grow and mimic yeast colonies. Solution: ensure chloramphenicol (100 μg/mL) is present in all isolation plates. (2) *Micrococcus or Staphylococcus* — environmental Gram-positive cocci; cream/white colonies. Solution: lower medium pH to 4.5–5.0 (using tartaric acid or citric acid) — most bacteria cannot grow below pH 4.5 while yeasts grow well. Use Sabouraud's agar (pH 5.6) or WLN agar which favors fungi over bacteria. (3) *Failure to check iodine supplement in chloramphenicol stock* — chloramphenicol may have degraded; prepare fresh stock solution. Prevention: (a) Always include bacterial antibiotic (chloramphenicol 50–100 μg/mL); (b) Use acidified media (pH 4.5–5.5); (c) Perform quick Gram stain on any "yeast-like" colony before assuming it is yeast; (d) Check for budding cells under microscope immediately after colony picking.

---

**Q40. Yeast cultures show vigorous CO₂ production but the final ethanol titer is only 30 g/L from 150 g/L glucose. Where is the carbon going?**

Low ethanol despite vigorous fermentation (CO₂ evolution) indicates significant carbon diversion: (1) *Aerobic respiration* — if the fermentation vessel is not sufficiently sealed or aerated (e.g., shaken flask without fermentation lock at high rpm), oxygen enables aerobic oxidation of pyruvate → CO₂ + H₂O; CO₂ is produced but without stoichiometric ethanol. Install a proper fermentation lock; reduce agitation to 50 rpm or use static culture. (2) *High biomass production* — if the medium has very high nitrogen content (yeast extract > 20 g/L), carbon is diverted to biomass synthesis; measure DCW; if >20 g/L, reduce nitrogen in medium. (3) *Glycerol overproduction* — osmotolerant strains under high osmotic stress produce large amounts of glycerol (up to 10–20 g/L); measure glycerol by enzymatic assay; if high, reduce initial sugar to 100–120 g/L. (4) *Organic acid production* — some yeasts produce succinic acid, malic acid, and acetic acid as by-products of TCA cycle and pyruvate metabolism; measure by HPLC; if significant, screen for strains with lower organic acid production. (5) *Ethanol evaporation* — if fermentation flask is not properly sealed, ethanol evaporates (bp 78.4°C is lower than water; significant evaporation at 30°C with air flow); use sealed vessels with fermentation locks.

---

**Q41. Yeast isolates that grew well on YEPD agar fail to grow or grow very slowly in glucose fermentation medium. What could explain this?**

Poor growth in fermentation medium despite YEPD growth: (1) *Osmotic stress from high sugar* — if fermentation medium contains 200 g/L glucose but YEPD has only 20 g/L, the 10-fold higher osmolarity may inhibit growth; the isolate lacks osmotolerance for high-gravity fermentation. Test at lower glucose (50–100 g/L) to confirm osmosensitivity. (2) *Nutrient limitations* — fermentation medium may lack vitamins (biotin, pantothenic acid, thiamine) present in yeast extract in YEPD; add yeast extract (5 g/L) or vitamin mix to fermentation medium. (3) *pH stress* — if fermentation medium is pH 3.0–4.0 (acidified for contamination control), some isolates cannot initiate growth at this pH; start at pH 5.0 and allow natural drop. (4) *Inoculum preparation* — if inoculum from YEPD overnight culture is dense and in stationary phase, cells may need adaptation time to the new medium; use late log phase inoculum. (5) *Ammonium toxicity* — at pH <5.0, (NH₄)₂SO₄ can generate inhibitory free ammonia; use NH₄H₂PO₄ instead. (6) *Missing trace elements* — Zn²⁺, Mn²⁺, Cu²⁺ absence in defined fermentation media can limit specific enzyme activities; add YNB (Yeast Nitrogen Base, which contains complete vitamin and trace element mix) to fermentation medium.

---

**Q42. After 72 hours, fermentation appears to have stopped (no CO₂ from fermentation lock) but glucose is still present. What is "stuck fermentation" and how do you diagnose and restart it?**

Stuck fermentation is a fermentation that has ceased prematurely before all fermentable sugar is consumed — a major problem in wine and industrial ethanol production. Diagnosis: measure residual glucose (DNS or glucose oxidase test); if glucose > 10 g/L but CO₂ has ceased, fermentation is stuck. Causes and remediation: (1) *Ethanol toxicity* — if ethanol has reached the strain's tolerance limit (e.g., 12% v/v in a strain tolerating only 12%), fermentation stops even with remaining sugar. Remediation: add ethanol-tolerant reinoculant; or dilute fermentation with fresh medium. (2) *Nitrogen starvation* — yeast cells have consumed all nitrogen and cannot synthesize enzymes to continue fermentation. Remediation: add diammonium phosphate (DAP, 0.2–0.5 g/L) or yeast extract (1 g/L) to replenish nitrogen. (3) *Vitamin deficiency* — particularly thiamine (TPP is PDC cofactor) deficiency causes stuck fermentation; add thiamine (0.5 mg/L). (4) *Temperature extremes* — temperature drop (cooler season) or spike (cooling failure) can stop fermentation. Warm to 30°C and mix to resuspend settled yeast. (5) *Low pH (<2.0)* — excessive acidification below yeast tolerance; add small amount of CaCO₃ or K₂CO₃ to raise pH to 3.5–4.0. (6) *High osmotic pressure* — in VHG fermentation, osmotic pressure increases as water is consumed; add small volume of water. Restart: combine fresh, active yeast inoculum with nutrients; slowly mix into stuck fermentation at 1:10 ratio.

---

**Q43. You are trying to isolate yeasts from a fermented toddy sample but plates are overgrown with molds. How do you address this?**

Mold overgrowth is a common challenge with toddy (palmyra/coconut palm sap fermentation) and similar samples that contain mold spores: (1) *Increase antifungal antibiotics* — add natamycin/pimaricin (50 μg/mL, specific antifungal that does not inhibit yeast) or dichloran (2 μg/mL) to suppress mold spreading without affecting yeasts. (2) *DRBC (Dichloran Rose Bengal Chloramphenicol) agar* — rose bengal restricts mold colony spreading (does not kill molds but prevents spreading by absorbing into hyphal tips and causing photosensitization); dichloran similarly restricts mold spread; chloramphenicol suppresses bacteria. (3) *Plate at lower dilution* — if molds are abundant at 10⁻² dilution, use 10⁻⁴ or 10⁻⁵ dilution where mold counts are lower and individual yeast colonies are countable. (4) *Incubate at 35–37°C* — most environmental molds (Cladosporium, Penicillium) grow poorly above 35°C; yeasts grow well; this temperature bias enriches for yeasts. (5) *Use acidified YEPD (pH 4.0–4.5)* — most molds grow poorly below pH 4.5; fermentative yeasts tolerate it. (6) *Rapid plate reading* — examine plates after 24–36 hours and pick yeast colonies before molds spread; mark yeast colony positions with a permanent marker on the plate bottom. (7) *Pre-treatment of sample* — filter the toddy through a 3 μm membrane to retain mold spores while allowing yeast cells through; however, this may also retain some large yeast cells.

---

**Q44. Two yeast isolates show identical API 20C AUX profiles but different fermentation efficiencies. What additional tests would you perform for differentiation?**

Identical API 20C profiles but different performance indicates that the API system's 20-carbon-source resolution is insufficient to distinguish these strains. Additional discriminatory tests: (1) *Molecular identification* — sequence both ITS and 26S D1/D2 rRNA gene regions; even single nucleotide differences confirm different strains or genotypes; RAPD-PCR (Random Amplification of Polymorphic DNA) or RFLP (Restriction Fragment Length Polymorphism) of mitochondrial DNA distinguishes intraspecies strains. (2) *Extended sugar fermentation panel* — test fermentation of additional sugars (trehalose, cellobiose, melibiose, L-rhamnose, L-arabinose, D-xylose); minor fermentative differences not tested by API may distinguish them. (3) *Growth at temperature extremes* — test at 37°C, 40°C, 42°C; different strains of the same species (e.g., *S. cerevisiae*) show dramatically different thermotolerance. (4) *Ethanol tolerance test* — more discriminatory than sugar assimilation. (5) *Flocculation test* — different industrial strains of *S. cerevisiae* have highly variable flocculation characteristics (FLO genes). (6) *Killer toxin test* — killer/sensitive phenotype testing (K1, K2, K28 killer types in *S. cerevisiae*) is highly strain-specific. (7) *Microsatellite typing or whole-genome sequencing* — for definitive strain-level discrimination for patent or commercial purposes.

---

### PART E: Applications & Interpretation (Q45–Q50)

---

**Q45. What are the industrial applications of fermentative yeasts beyond bioethanol production?**

Fermentative yeasts have a remarkable breadth of industrial applications: (1) *Bread and bakery* — *S. cerevisiae* (baker's yeast) produces CO₂ that leavens dough; also produces flavor compounds (ethyl acetate, diacetyl, higher alcohols, esters) contributing to bread aroma; active dry yeast and instant dry yeast are multi-billion-dollar markets. (2) *Brewing (beer)* — top-fermenting *S. cerevisiae* (ale strains) and bottom-fermenting *S. pastorianus* (lager strains; a natural *S. cerevisiae × S. eubayanus* hybrid) convert wort to beer with specific flavor profiles; control of ester (isoamyl acetate, ethyl acetate) and higher alcohol production is critical for beer quality. (3) *Wine production* — *S. cerevisiae* (wine strains) and non-*Saccharomyces* yeasts (*Lachancea thermotolerans*, *Torulaspora delbrueckii*, *Metschnikowia pulcherrima*) contribute to wine fermentation, acidification, and flavor complexity in modern multi-strain fermentations. (4) *Distilled spirits* — whisky, rum, vodka, baijiu fermentations. (5) *Nutritional yeast and yeast extract* — inactivated yeast cells and autolysates used as food seasoning (umami flavor from glutamates), dietary supplement (B vitamins, beta-glucan), and cell culture medium component. (6) *Recombinant protein production* — *S. cerevisiae*, *Pichia pastoris* (*Komagataella phaffii*) are GRAS hosts for biopharmaceutical production (insulin, hepatitis B vaccine, Factor VIII). (7) *Probiotics* — *Saccharomyces boulardii* (a strain of *S. cerevisiae*) is used as a probiotic for prevention/treatment of diarrhea.

---

**Q46. What are the strategies for improving yeast ethanol tolerance through genetic engineering and adaptive evolution?**

Strategies to improve ethanol tolerance: (1) *Adaptive laboratory evolution (ALE)* — the most powerful and "evolution-guided" strategy; expose *S. cerevisiae* to progressively increasing ethanol concentrations over many generations (100–1000+ generations); mutants that survive and grow faster at each concentration are selected; the evolved strain's genome is sequenced to identify causative mutations (often in ergosterol biosynthesis genes, membrane lipid composition genes, or global transcriptional regulators). (2) *Overexpression of stress response genes* — overexpressing HSP104 (disaggregase), HSP70 family (Ssa1, Ssa4), or UBI4 (ubiquitin, for stress-denatured protein degradation) improves survival at high ethanol. (3) *Engineering membrane composition* — expression of bacterial fatty acid desaturase genes (e.g., *E. coli fabB* or *Streptomyces* desaturase) alters membrane fatty acid saturation ratio, improving membrane fluidity at high ethanol. (4) *Trehalose pathway upregulation* — overexpressing TPS1 (trehalose-6-phosphate synthase) increases trehalose accumulation, protecting membranes and proteins. (5) *Genome shuffling* — protoplast fusion of multiple ethanol-tolerant strains (from ALE or natural sources) creates hybrid genomes with combined tolerance traits; repeated cycles of shuffling progressively improve tolerance without requiring knowledge of specific genes. (6) *CRISPR-Cas9 multiplexing* — simultaneous editing of multiple loci (ergosterol pathway, membrane transport, HSP network) enables rational tolerance engineering.

---

**Q47. How are non-*Saccharomyces* yeasts relevant to modern wine fermentation and what properties make them valuable?**

The modern understanding of wine fermentation has shifted from a model of *S. cerevisiae* dominance to a complex multi-species succession: (1) *Fermentation succession* — freshly crushed grape juice (must) is initially dominated by non-*Saccharomyces* yeasts (Hanseniaspora/Kloeckera, Metschnikowia, Starmerella/Candida stellata, Torulaspora, Lachancea); these grow for the first 1–3 days, contributing flavor-active metabolites. As ethanol accumulates (>4–5% v/v), most non-*Saccharomyces* species are outcompeted, and *S. cerevisiae* dominates the latter fermentation phase. (2) *Technological properties of selected non-*Saccharomyces* species:* *Lachancea thermotolerans* — produces high lactic acid (natural acidification; useful in warm climates where must acidity is low); low ethanol yield; *Torulaspora delbrueckii* — low volatile acidity (less acetic acid than *S. cerevisiae*); fruity ester production; *Metschnikowia pulcherrima* — aroma enhancement; antimicrobial activity (kills other spoilage yeasts by iron sequestration via pulcherrimin); *Starmerella bacillaris* — produces high glycerol (rounder mouthfeel) with lower ethanol (health-conscious market appeal). (3) *Multi-strain inoculants* — commercial wine yeasts now include mixed *S. cerevisiae* + non-*Saccharomyces* starter cultures designed to enhance wine complexity and reduce alcohol content. Screening fermentative yeasts from grapes, wine barrels, and different wine regions identifies locally adapted strains with unique flavor profiles — "terroir yeasts" with commercial and sensory value.

---

**Q48. What is lignocellulosic bioethanol and why is xylose fermentation by yeast a key challenge?**

Lignocellulosic bioethanol (second-generation bioethanol) is produced from agricultural residues and woody biomass (corn stover, wheat straw, sugarcane bagasse, energy grasses) that contain cellulose (40–50%), hemicellulose (25–35%), and lignin (15–25%). Pretreatment (dilute acid, steam explosion, alkaline) and enzymatic hydrolysis (cellulases, hemicellulases) release a mixture of fermentable sugars dominated by glucose (from cellulose) and xylose + arabinose (from hemicellulose). The challenge: wild-type *S. cerevisiae* cannot ferment xylose (the second most abundant plant sugar, comprising 20–40% of hemicellulosic sugars) because it lacks functional xylose reductase (XR) and xylitol dehydrogenase (XDH) enzymes (the fungal pathway) or xylose isomerase (the bacterial pathway). This inability to ferment xylose wastes 25–40% of total carbon in the hydrolysate, making second-generation bioethanol economically uncompetitive. Solutions: (1) *Heterologous expression of XR/XDH* — from *Scheffersomyces stipitis* (*Pichia stipitis*), a naturally xylose-fermenting yeast; XR (Xyl1) reduces xylose to xylitol (using NADPH preferentially), XDH (Xyl2) oxidizes xylitol to xylulose (using NAD⁺); xylulose kinase (Xks1) phosphorylates xylulose to xylulose-5-phosphate for entry into PPP and glycolysis. The NADPH/NAD⁺ cofactor imbalance causes xylitol accumulation. (2) *Xylose isomerase (XI)* — bacterial XI (from *Thermus thermophilus*, *Clostridium phytofermentans*) directly isomerizes xylose to xylulose without cofactor imbalance; expressed in engineered *S. cerevisiae*, provides more balanced xylose fermentation.

---

**Q49. How is jaggery (used in Biotechnology Section VI on ethanol fermentation) related to yeast isolation and what yeast populations does it harbor?**

Jaggery (gur in India; panela in Latin America) is unrefined, concentrated sugarcane juice evaporated and molded into blocks; it retains the natural microflora of sugarcane juice since it is not pasteurized or chemically treated. Microbial populations in jaggery: (1) *Fermentative yeasts* — primarily *S. cerevisiae*, *Pichia fermentans*, *Candida tropicalis*, *Hanseniaspora uvarum*, and osmotolerant yeasts including *Zygosaccharomyces rouxii* (an osmophilic yeast specialized for high-sugar environments with sucrose up to 60%). (2) *Lactic acid bacteria* — *Lactobacillus plantarum*, *Leuconostoc mesenteroides* co-exist with yeasts. (3) *Bacillus* species — from soil contamination of cane. Jaggery is one of the best sources of osmotolerant, ethanol-tolerant fermentative yeasts adapted to high sucrose concentrations because the jaggery environment itself (60–70% sugar) selects for osmotolerant organisms. Yeasts isolated from jaggery in Biotechnology Section VI (Fermentation of Jaggery for Ethanol Production) are therefore pre-adapted to the fermentation substrate used in that experiment, increasing the chance of obtaining high-performing strains. *Zygosaccharomyces rouxii* isolated from jaggery, while highly osmotolerant, is only a weak ethanol producer; the best ethanol producers from jaggery are typically *S. cerevisiae* variants. Selection strategy: plate diluted jaggery solution on YEPD with chloramphenicol; pick fermenting isolates; screen by Durham tube at 60% glucose (osmotolerance) and at 15% ethanol (ethanol tolerance) to identify strains with both key industrial properties.

---

**Q50. Design a comprehensive experiment to isolate, characterize, and select the best fermentative yeast from three different sample sources (grape skin, fermenting toddy, and jaggery) for industrial ethanol production. Outline all stages.**

**Stage 1 — Sample collection and preparation:**
Collect grape skin scrapings (10 g, sterile scalpel, multiple grape varieties), fresh fermenting toddy (100 mL, sterile bottle), and jaggery (10 g, fresh block) from each source. Prepare homogenates/suspensions in sterile saline + Tween 80. Prepare serial dilutions 10⁻¹ to 10⁻⁶.

**Stage 2 — Isolation:**
Plate on YEPD + chloramphenicol (100 μg/mL) and DRBC agar. Incubate 25–28°C, 48–72 hours. Pick all morphologically distinct yeast colonies (target 30–50 per source = 90–150 total isolates). Purify by re-streaking; confirm yeast identity by Gram stain and microscopy (budding cells, no mycelium).

**Stage 3 — Preliminary characterization:**
(a) Gram stain + microscopy: cell shape, size, budding pattern, pseudohyphae. (b) Methylene blue viability. (c) Durham tube fermentation: glucose, fructose, sucrose, maltose fermentation at 30°C, 48 h. Retain only glucose-positive isolates (eliminates non-fermentative yeasts).

**Stage 4 — Primary fermentation screening:**
Inoculate fermenting isolates (n ≈ 80–120 after filtering non-fermenters) into 10 mL glucose medium (50 g/L, YEPD base) in tubes with Durham tubes; incubate 30°C, 24 h; rank by Durham tube CO₂ volume (large bubble = strong fermentation). Select top 30 by CO₂ production volume.

**Stage 5 — Ethanol tolerance and temperature tolerance screening:**
Spot assay on YEPD + 0, 8, 12, 15% ethanol plates; incubate 30°C, 48 h. Spot assay on YEPD at 30, 37, 40, 42°C. Score each isolate; retain top 15 with best combined ethanol and temperature tolerance.

**Stage 6 — Quantitative ethanol production assay:**
Culture top 15 isolates in 100 mL fermentation medium (glucose 200 g/L, yeast extract 5 g/L, peptone 10 g/L, NH₄H₂PO₄ 2 g/L, MgSO₄ 0.5 g/L, ZnSO₄ 0.3 mg/L, pH 5.0) in 250 mL sealed flasks with fermentation locks. Standardized inoculum: 10⁷ cells/mL, >95% viability. Incubate 30°C, 50 rpm, 72 hours. Measure: ethanol (GC or dichromate method), residual glucose (DNS), DCW, pH. Calculate Y_E/S, Qp, qp. Three biological replicates; ANOVA + Tukey's test.

**Stage 7 — Molecular identification of top 3 candidates:**
Extract genomic DNA; PCR-amplify ITS and 26S D1/D2; Sanger sequence; BLAST; confirm species identity.

**Stage 8 — Selection and preservation:**
Select the single best-performing isolate based on weighted scoring (Y_E/S 35%, ethanol tolerance 25%, Qp 20%, temperature tolerance 20%). Preserve as −80°C glycerol stocks (5 vials) and lyophilized preparation. Report identity, performance metrics, and source.

**Expected outcome:** Isolation of 1–3 *S. cerevisiae* strains (likely from grape skin or jaggery) achieving 85–95% of theoretical ethanol yield, tolerating ≥14% v/v ethanol, and fermenting at ≥37°C — suitable candidates for pilot-scale bioethanol production or fermented beverage applications.

---

*End of Biotechnology Section V — 50 Viva Questions & Answers*
*Next: Biotechnology Section VI — Fermentation of Jaggery for Ethanol Production*
