# Molecular Biology — Section I: Calibration of Micropipette
## 50 Viva Questions with Detailed Answers (Masters Level)

---

### BASIC PRINCIPLES

---

**Q1. What is a micropipette and what is its fundamental working principle?**

A micropipette is a precision laboratory instrument used to transfer very small, accurately measured volumes of liquid, typically in the range of 0.1 µL to 1000 µL. It operates on the **air displacement principle**, where a piston moves within a cylinder to create a partial vacuum (negative pressure) that draws liquid into a disposable plastic tip. When the piston descends, it expels the trapped air volume, and this displaced air pulls liquid up into the tip. The accuracy of the instrument depends on the precision of piston travel distance, which is calibrated to correspond exactly to a defined volume. Environmental conditions such as temperature, altitude (atmospheric pressure), and liquid viscosity can influence the actual volume dispensed.

---

**Q2. What is the difference between accuracy and precision in the context of micropipette calibration?**

**Accuracy** refers to how close the measured (dispensed) volume is to the true or target volume — it is a measure of systematic error or bias. **Precision** (also called reproducibility or repeatability) refers to how consistently the same volume is dispensed across multiple repetitions, regardless of whether that volume matches the target — it reflects random error. A pipette can be precise but inaccurate (e.g., consistently dispensing 98 µL when set to 100 µL), accurate but imprecise (values scattered around 100 µL), or ideally both accurate and precise. Calibration primarily corrects for accuracy, while precision reflects the mechanical condition of the piston and spring mechanism. Both parameters are evaluated during calibration using statistical analysis of repeated measurements.

---

**Q3. Why is calibration of a micropipette necessary in molecular biology?**

Molecular biology experiments such as PCR, gel electrophoresis, spectrophotometric DNA quantitation, and restriction digestion require extremely precise volumes — even a 5–10% error can lead to failed reactions, incorrect molar ratios of reagents, or misinterpretation of results. Calibration ensures that the volume set on the pipette dial corresponds exactly to the volume actually dispensed. Over time, seals, O-rings, and piston mechanisms wear out, leading to inaccurate delivery. Calibration also ensures compliance with ISO/IEC 17025 and Good Laboratory Practice (GLP) standards required in research and diagnostic laboratories. Uncalibrated pipettes are a leading cause of irreproducible results and experimental failure.

---

**Q4. What are the international standards governing micropipette calibration?**

The primary standard is **ISO 8655**, which specifies performance requirements and testing methods for piston-operated volumetric instruments including micropipettes. It defines acceptable limits for systematic error (inaccuracy, *Es*) and random error (imprecision, *Cv*) at different volume settings. The **ASTM E1154** standard is also used, particularly in the United States. Calibration laboratories must comply with **ISO/IEC 17025** for testing and calibration competence. The **Joint Committee for Guides in Metrology (JCGM)** provides guidance on uncertainty of measurement (GUM). These standards specify that pipettes should be calibrated at minimum volume, mid-range volume, and maximum volume settings, with at least 10 replicates per setting.

---

**Q5. Explain the concept of systematic error (Es) and coefficient of variation (Cv) in micropipette calibration.**

**Systematic error (Es)**, also called inaccuracy or bias, is calculated as:

> **Es (%) = [(V_mean − V_nominal) / V_nominal] × 100**

where *V_mean* is the mean measured volume and *V_nominal* is the set (nominal) volume. It indicates how far the average dispensed volume deviates from the intended volume. The **Coefficient of Variation (Cv)**, also called imprecision, is:

> **Cv (%) = (Standard Deviation / V_mean) × 100**

It quantifies the variability among repeated measurements. According to ISO 8655, acceptable *Es* is typically ≤ ±0.5–1.0% and *Cv* ≤ 0.2–0.5% depending on pipette type and volume range. Both values together give a complete picture of pipette performance.

---

### PROCEDURE

---

**Q6. What is the gravimetric method of micropipette calibration and why is it the gold standard?**

The **gravimetric method** involves dispensing water into a tared weighing vessel on an analytical balance and converting the measured mass to volume using the known density of water. It is considered the gold standard because it uses a physical property (mass) that can be measured with very high accuracy using a calibrated analytical balance, avoiding errors inherent in volumetric glassware. The volume is calculated as:

> **V = m / ρ**

where *m* is the measured mass (in grams) and *ρ* is the density of water at the measurement temperature (e.g., 0.99704 g/mL at 25°C). This method is referenced in ISO 8655 and is traceable to national metrology standards, making it suitable for regulatory compliance.

---

**Q7. What type of water must be used in micropipette calibration and why?**

**Distilled or deionized water (Type 1 or Type 2, per ISO 3696)** must be used because its density is accurately known at various temperatures and it does not contain salts or contaminants that would alter its density or surface tension. The density of water is temperature-dependent and well-documented (e.g., 0.99821 g/mL at 20°C, 0.99704 g/mL at 25°C), allowing precise volume calculation from mass. Tap water has variable dissolved solids that affect density unpredictably. Using the wrong water would introduce a systematic error in all volume calculations. Water and the environment must be temperature-equilibrated (usually at 20 ± 0.5°C or 25 ± 0.5°C) before calibration begins.

---

**Q8. Step by step, how do you perform gravimetric calibration of a P200 micropipette?**

1. **Equilibrate** the distilled water and pipette to room temperature (20–25°C) for at least 30 minutes.
2. **Record** the ambient temperature to select the correct water density value.
3. **Tare** an analytical balance (readable to 0.0001 g) with an appropriate small beaker or weighing vessel.
4. **Set** the micropipette to the desired volume (e.g., 200 µL, 100 µL, 20 µL for a P200).
5. **Attach** a new, appropriate tip (e.g., yellow tip for P200).
6. **Pre-wet** the tip by aspirating and expelling water 3 times to saturate the air column.
7. **Aspirate** slowly and smoothly, hold vertically, and wait 1 second before withdrawing from the liquid.
8. **Dispense** into the tared vessel held at 45°, pressing to the first stop, then to the second stop (blow-out).
9. **Record** the mass displayed on the balance.
10. **Repeat** steps 6–9 at least 10 times.
11. **Calculate** mean volume, SD, Es%, and Cv% using the appropriate water density.

---

**Q9. What is the significance of pre-wetting the pipette tip before calibration?**

Pre-wetting (also called priming) involves aspirating and expelling the liquid 2–3 times before taking the actual measurement. This is critical because the plastic tip initially contains dry air, which can absorb water vapor from the aspirated liquid, causing the liquid surface to recede and resulting in less volume being dispensed than intended — a phenomenon called **vapor deficit**. Pre-wetting saturates the air inside the tip with water vapor, equilibrating the humidity so that subsequent aspirations are not affected by evaporation into the dry air column. Skipping this step leads to falsely low first measurements, increasing apparent imprecision and inaccuracy. This is particularly important for volatile liquids and for small volumes where the ratio of air to liquid is high.

---

**Q10. How do you handle the two-stop mechanism during dispensing in calibration?**

Micropipettes have a **two-stop piston system**: the **first stop** expels the set volume (working volume), and the **second stop** (blow-out position) expels the small residual volume remaining in the tip. During calibration using the gravimetric method, dispensing should be done by pressing to the **first stop only** for measurements intended to reflect normal working conditions, OR to the **second stop** if the protocol being calibrated uses the blow-out feature. The ISO 8655 standard specifies using the first stop for routine calibration measurements. If the second stop is used inconsistently across replicates, it introduces variability in the data. The tip should be gently touched to the inner wall of the vessel during dispensing to eliminate droplet retention.

---

**Q11. What is the role of temperature in micropipette calibration and how is it accounted for?**

Temperature affects calibration in two ways: it changes the **density of water** (used to convert mass to volume) and affects the **thermal expansion of the air column** inside the pipette tip. Water density at 20°C is 0.99821 g/mL, while at 25°C it is 0.99704 g/mL — using the wrong value introduces a measurable error. ISO 8655 provides a table of water density values (Z-factors) at each temperature from 15°C to 30°C, accounting for both density and air buoyancy correction. The formula used is:

> **V = m × Z**

where Z is the temperature-dependent conversion factor. If calibration is performed outside the 20–25°C range without correction, volumes will be systematically over- or underestimated. Both the water and the pipette must be at the same ambient temperature to avoid air expansion/contraction errors.

---

**Q12. What is the Z-factor in ISO 8655 calibration?**

The **Z-factor** is a combined conversion factor used in ISO 8655 to convert the mass of water dispensed into volume, accounting for:
1. The **density of water** at the measurement temperature
2. The **buoyancy correction** for air (since the balance weighs in air, not vacuum)
3. The **nominal density of brass weights** used to calibrate the balance

The formula is: **V (µL) = m (mg) × Z (µL/mg)**

At 20°C, Z ≈ 1.0034 µL/mg; at 25°C, Z ≈ 1.0041 µL/mg. Using this factor eliminates the need for separate buoyancy corrections, simplifying calculation while maintaining traceability. The Z-factor values for each degree Celsius from 15–30°C are tabulated in ISO 8655-6.

---

**Q13. How many replicates are required for a statistically valid micropipette calibration, and at how many volume settings?**

According to **ISO 8655**, a minimum of **10 replicates** per volume setting is required to calculate a statistically meaningful mean, standard deviation, and coefficient of variation. Calibration must be performed at a minimum of **three volume settings**: the **nominal maximum volume** (e.g., 200 µL for P200), **50% of maximum** (e.g., 100 µL), and **10% of maximum** (e.g., 20 µL). These three points cover the typical working range and detect volume-dependent non-linearity. In practice, many laboratories add a fourth point at 25% of maximum for greater rigor. Using fewer than 10 replicates significantly increases the uncertainty of the Cv calculation due to poor statistical power with small sample sizes.

---

**Q14. What analytical balance specifications are required for micropipette calibration?**

The analytical balance must have a **readability (resolution) of at least 0.1 mg (0.0001 g)** for calibrating micropipettes dispensing volumes ≥10 µL. For sub-microliter volumes, a **microbalance with 0.001 mg readability** is necessary. The balance must be **calibrated and traceable** to national standards, placed on a **vibration-free anti-vibration table**, and enclosed in a **draft shield** to prevent air currents from affecting readings. The balance should be **leveled** using the bubble level and leveling feet before use. It must be warmed up for at least 30 minutes and zero-checked before each weighing session. Environmental factors like electromagnetic fields, temperature fluctuations, and air movement are the primary sources of balance measurement uncertainty.

---

**Q15. What is the role of a draft shield/evaporation trap during calibration?**

A **draft shield** on the analytical balance prevents air currents from the HVAC system, nearby people, or pipette movement from disturbing the balance pan and causing fluctuating readings. Additionally, an **evaporation trap** (a small container with water placed inside the balance chamber, or using a covered weighing vessel) prevents the dispensed water droplets from evaporating between dispensing and recording the mass — evaporation would cause the balance to show decreasing mass over time, falsely lowering the apparent dispensed volume. These precautions are especially important for small volumes (< 10 µL) where evaporation represents a significant fraction of the total volume and for calibrations performed in warm, dry environments with low humidity.

---

### CALCULATIONS

---

**Q16. A P1000 micropipette is calibrated gravimetrically at 1000 µL. The masses measured in 10 replicates (in mg) are: 997, 1002, 998, 1001, 999, 1003, 1000, 998, 1001, 999. Calculate mean volume, SD, Es%, and Cv% at 25°C (Z = 1.0041 µL/mg).**

**Step 1 — Convert mass to volume:** Multiply each mass by Z = 1.0041:
997×1.0041 = 1001.09; 1002×1.0041 = 1006.11; 998×1.0041 = 1002.09; 1001×1.0041 = 1005.10; 999×1.0041 = 1003.10; 1003×1.0041 = 1007.11; 1000×1.0041 = 1004.10; 998×1.0041 = 1002.09; 1001×1.0041 = 1005.10; 999×1.0041 = 1003.10

**Step 2 — Mean (V̄):** Sum = 10,038.99 µL; Mean = 10,038.99 / 10 = **1003.90 µL**

**Step 3 — Es%:** Es = [(1003.90 − 1000) / 1000] × 100 = **+0.39%** ✓ (within ISO 8655 limit of ±1.0%)

**Step 4 — SD:** Deviations from mean, squared, averaged, square-rooted ≈ **1.84 µL**

**Step 5 — Cv%:** Cv = (1.84 / 1003.90) × 100 = **0.18%** ✓ (within ISO 8655 limit of 0.3%)

---

**Q17. How do you calculate the uncertainty of measurement for a calibrated micropipette?**

Measurement uncertainty (U) is calculated following the **GUM (Guide to the Expression of Uncertainty in Measurement)** framework. The combined standard uncertainty (*uc*) includes contributions from:
1. **Repeatability (Type A)**: *u₁* = SD / √n
2. **Balance resolution**: *u₂* = resolution / (2√3)
3. **Water density uncertainty**: *u₃* (usually negligible if temperature is controlled)
4. **Evaporation**: *u₄* (estimated experimentally)

These are combined as: **uc = √(u₁² + u₂² + u₃² + u₄²)**

The **expanded uncertainty (U)** is reported at 95% confidence as: **U = k × uc**, where coverage factor *k* = 2 for approximately normal distributions. The final result is expressed as: **V = V̄ ± U (µL), at 95% confidence level.** This uncertainty statement is required in ISO/IEC 17025 calibration certificates.

---

**Q18. What is the acceptable systematic error (Es%) and CV% for a P10 micropipette according to ISO 8655?**

ISO 8655 specifies tighter tolerances for smaller volume pipettes because small absolute errors represent large relative errors at low volumes. For a **P10 micropipette (0.5–10 µL)**:
- At **10 µL**: Es ≤ ±1.0%, Cv ≤ 0.6%
- At **5 µL**: Es ≤ ±1.5%, Cv ≤ 1.0%
- At **1 µL**: Es ≤ ±3.0%, Cv ≤ 2.0%

These limits reflect the practical difficulty of accurately measuring very small volumes, where surface tension, tip geometry, and operator technique have a proportionally larger influence. Compare this to a P1000 at 1000 µL where Es ≤ ±0.6% and Cv ≤ 0.2% — demonstrating that absolute precision is harder to maintain at the extremes of the pipette's range.

---

**Q19. A P100 micropipette is set to 100 µL. After 10 measurements, V̄ = 96.5 µL and SD = 0.8 µL. Is this pipette within ISO 8655 limits? What should be done?**

**Es%** = [(96.5 − 100) / 100] × 100 = **−3.5%** — This **FAILS** ISO 8655 (limit ±1.0% at 100 µL)
**Cv%** = (0.8 / 96.5) × 100 = **0.83%** — This also likely **FAILS** (limit ~0.5% for this range)

The pipette consistently under-delivers, indicating a **systematic negative bias** caused by:
- Worn or damaged piston seal (most common)
- Improperly adjusted volume stop
- Bent or contaminated piston shaft
- Air leak due to cracked tip ejector or housing

**Action required:** The pipette should be **removed from service**, labeled "OUT OF CALIBRATION — DO NOT USE", sent for **service and recalibration** by a qualified technician. All results obtained with this pipette since its last valid calibration must be reviewed and potentially repeated.

---

**Q20. If you are calibrating a P20 at 2 µL (10% of range), what special challenges arise in the calculation?**

At 2 µL, the dispensed mass is only approximately **2 mg** (2 µL × ~1 mg/µL). This is extremely close to the readability limit of standard analytical balances (0.1 mg), meaning balance uncertainty is a major contributor to overall measurement uncertainty. An error of just 0.1 mg (one resolution unit) represents a **5% error in volume**, which is unacceptably large. Additionally, **evaporation** of 2 µL water can occur in seconds under laboratory conditions, artificially reducing the measured mass. **Surface tension** causes liquid to cling to the tip rather than fully dispensing. For volumes < 5 µL, a **microbalance (0.001 mg resolution)** is mandatory, an **evaporation trap** is essential, and dispensing must be done inside a **humidity-controlled enclosure**. Statistical outlier testing (e.g., Grubbs' test) is particularly important at these volumes.

---

### TROUBLESHOOTING

---

**Q21. What are the most common causes of inaccuracy (high Es%) in a micropipette?**

Common causes of systematic inaccuracy include:
1. **Worn or degraded piston seal / O-ring** — causes air leaks, reducing aspirated volume
2. **Contamination of piston shaft** — protein or salt deposits alter piston travel
3. **Incorrect volume setting** — user error in reading the dial
4. **Temperature mismatch** — pipette/water not equilibrated to room temperature
5. **Incorrect tip** — using a non-matched tip causes poor seal and air leakage
6. **Bent or scored piston** — disrupts smooth linear travel
7. **Failure to pre-wet** — especially affects first measurement
8. **Pipetting at wrong angle** — aspirating at >20° from vertical affects meniscus reading

Negative bias (dispensing less than set) usually indicates a leak, while positive bias (more than set) can result from a stretched spring or pressure buildup.

---

**Q22. What causes high imprecision (high Cv%) in a micropipette and how is it diagnosed?**

High Cv% (poor reproducibility) is caused by factors introducing **random variability** between measurements:
1. **Air bubble formation** in the tip due to rapid or jerky aspiration
2. **Inconsistent blow-out** — operator sometimes using first stop, sometimes second stop
3. **Liquid remaining on tip exterior** — carries over inconsistently
4. **Balance instability** — air drafts, vibrations
5. **Tip not fitting consistently** — loose attachment varies between replicates
6. **Internal contamination** building up progressively during measurement series
7. **Operator fatigue** — variable hand pressure on the plunger button

Diagnosis involves examining the pattern of values: if early measurements differ from later ones, progressive contamination or warming is suspected. If variation is random throughout, air bubble or operator technique is more likely.

---

**Q23. During calibration, you notice that the first 2–3 measurements are consistently lower than the rest. What is the explanation?**

This pattern is characteristic of **failure to pre-wet the tip**. The dry tip contains unsaturated air that absorbs water vapor from the aspirated liquid upon first contact, causing a slight reduction in the actual liquid column due to vapor pressure equilibration. After 2–3 aspirations, the air inside the tip becomes saturated with water vapor and the phenomenon ceases, explaining why later measurements stabilize. The solution is to always pre-wet (prime) the tip 2–3 times before collecting calibration measurements. This issue is more pronounced in:
- Very dry laboratory environments (low humidity)
- Warm temperatures (higher evaporation)
- Volatile liquids (high vapor pressure)
- Small volumes where the air-to-liquid ratio is high

---

**Q24. How does atmospheric pressure (altitude) affect micropipette performance?**

Micropipettes operating on the air displacement principle are sensitive to **atmospheric pressure**. At high altitudes, atmospheric pressure is lower, which means the partial vacuum created by the piston is insufficient to fully overcome the ambient pressure differential needed to aspirate the calibrated volume — in practice, **more liquid than intended is aspirated** at high altitude because the expanded air column in the tip draws in more liquid to equalize pressure. Pipette manufacturers calibrate instruments at sea level (~1013 hPa). At high altitudes (e.g., >1500 m), correction factors must be applied, or **positive displacement pipettes** (which are pressure-independent) should be used. ISO 8655 notes that calibrations performed at significantly different altitudes from standard conditions must account for atmospheric pressure differences.

---

**Q25. A technician is calibrating a pipette and gets inconsistent results even though the pipette is new. What factors related to technique could be responsible?**

Even new pipettes can show poor calibration results due to **operator-dependent technique errors**:
1. **Plunger depression speed** — depressing too fast causes turbulence and air bubbles; too slow leads to dripping before aspiration
2. **Immersion depth** — the tip should be immersed 2–3 mm for P2-P20, 2–4 mm for P20-P200, and 3–6 mm for P200-P1000; too deep immersion causes extra liquid to be drawn in by hydrostatic pressure
3. **Pause after aspiration** — not waiting 1 second after reaching the aspirating depth causes incomplete liquid rise
4. **Tip touch angle on dispensing** — not touching the vessel wall consistently
5. **Removal of tip from liquid** — tilting during withdrawal drags extra liquid
6. **Pipette not vertical during aspiration** — gravity affects the liquid column

Standardized training and the use of calibration SOPs minimize operator-dependent variability.

---

**Q26. What is the effect of liquid viscosity on micropipette accuracy and how should it be managed?**

Pipettes calibrated with water perform differently with **viscous liquids** (glycerol, serum, concentrated DNA, SDS solutions) because viscous liquids flow more slowly through the narrow tip orifice. During aspiration, the liquid may not fully reach the set volume before the piston stops moving, causing **under-aspiration**. During dispensing, viscous liquid clings to the tip walls longer, leading to **under-delivery**. Solutions include:
- **Slow aspiration and dispensing** — allow extra equilibration time
- **Positive displacement pipettes** — use a capillary piston that contacts the liquid directly, eliminating air column issues
- **Reverse pipetting technique** — aspirate more than needed (to the blow-out stop), then dispense to the first stop, leaving the excess in the tip
- **Pre-wetting multiple times** with the viscous liquid before measuring

Volume delivery errors for viscous liquids can exceed 5–10% if standard technique is used.

---

**Q27. What is positive displacement pipetting and when is it preferred over air displacement?**

**Positive displacement pipettes** (e.g., Eppendorf Combitips, Hamilton syringes) have a **capillary piston that directly contacts the liquid** — there is no air cushion between the piston and the liquid. This eliminates errors due to air compression, viscosity, vapor pressure, and atmospheric pressure. They are preferred for:
- **Volatile liquids** (organic solvents, radioactive materials) — air displacement tips allow vapor to escape
- **Highly viscous liquids** (glycerol, wax) — viscosity errors are eliminated
- **Aerosol-producing samples** (infectious or radioactive materials) — the piston-in-capillary design contains the liquid
- **High altitude** laboratories
- **Highly precise dispensing** of expensive reagents

The main disadvantage is higher cost of consumables (capillary pistons are not reusable) and that a separate piston is needed for each sample, increasing per-assay cost.

---

**Q28. You observe that a pipette consistently over-delivers when set to maximum volume but performs well at mid-range. What does this indicate?**

This pattern of **volume-dependent systematic error** — accurate at mid-range but positively biased at maximum — suggests:
1. **Worn or stretched piston spring** — the spring that limits piston travel has lost tension, allowing the piston to travel slightly further than calibrated at maximum stop position
2. **Miscalibrated upper volume stop** — the mechanical stop defining maximum volume has slipped
3. **Swollen piston seal** — absorbing solvents or cleaning agents, increasing its volume and effectively reducing tip air space, pushing out more liquid
4. **Incorrect maximum volume setting by user** — accidentally set above the stated maximum

This type of failure highlights why ISO 8655 requires calibration **at maximum volume** specifically — failures affecting only the extremes of the range would be missed if calibration is only done at mid-range.

---

### APPLICATIONS AND INTERPRETATION

---

**Q29. How frequently should micropipettes be calibrated in a molecular biology laboratory?**

The calibration frequency depends on the laboratory's **risk assessment, usage frequency, and regulatory requirements**. General guidelines are:
- **Every 3–6 months** for frequently used pipettes in critical applications (PCR, quantitative assays)
- **Every 12 months** for lightly used pipettes in non-critical applications
- **After any incident** — dropping, autoclaving, servicing, abnormal results
- **Before critical experiments** — if results will be used in publications or regulatory submissions
- **Upon receipt of new pipettes** — to verify manufacturer's calibration
- **After autoclaving** (some pipettes are autoclavable but calibration must be verified afterward)

GLP and ISO 17025 require documented calibration records with unique pipette IDs, calibration dates, results, and next calibration due dates. Many laboratories use color-coded calibration stickers for quick visual status checks.

---

**Q30. How would improper pipette calibration specifically affect a PCR experiment?**

In PCR, the volumes of template DNA, primers, dNTPs, buffer, Mg²⁺, and polymerase must be added in precise ratios. Incorrect volumes affect:
- **Template DNA** — over-delivery inhibits PCR (too much template causes primer competition and non-specific amplification); under-delivery reduces sensitivity
- **MgCl₂** — critically concentration-sensitive; even ±10% shifts the optimal Mg²⁺ concentration, changing primer annealing specificity and polymerase activity
- **Primers** — incorrect ratio affects amplification efficiency
- **Total reaction volume** — affects final concentrations of all components

A pipette with a −5% bias on a 20 µL reaction would deliver only 19 µL, concentrating all components by ~5%. While this may seem small, it can cause consistently suboptimal or failed PCR, particularly for amplification of long fragments or when using hot-start enzymes with narrow activity windows. Calibration errors are a frequently overlooked cause of PCR irreproducibility.

---

**Q31. What is the difference between calibrating a single-channel and a multi-channel micropipette? What additional challenges exist for multi-channel pipettes?**

A **single-channel pipette** has one piston and is calibrated by measuring one dispense per replicate. A **multi-channel pipette** (8 or 12 channels) has multiple independent pistons that must all deliver the same volume simultaneously. Calibration challenges for multi-channel pipettes include:
- Each **individual channel** must be tested separately (usually using a multi-well balance plate or weighing each channel's dispense individually)
- **Channel-to-channel variability (CCV%)** must be calculated in addition to mean Es% and Cv%
- One leaking seal in any channel can reduce accuracy for that channel without affecting others
- **Tip attachment uniformity** across all channels is critical — uneven tip seating causes channel-to-channel variation
- ISO 8655 requires that multi-channel pipettes meet both **within-channel** and **between-channel** precision limits

Multi-channel calibration is more time-consuming and requires specialized balance equipment (row or column weighing plates).

---

**Q32. What is the significance of calibrating a pipette at 10% of its nominal volume?**

Calibration at **10% of the maximum volume** (e.g., 10 µL on a P100, 100 µL on a P1000) is the most demanding test point because:
- **Absolute errors** at small volumes are harder to control — the same mechanical imprecision represents a much larger percentage error
- **Air column effects** are proportionally larger at small volumes
- The piston travel distance is very short, making the calibration sensitive to **worn mechanical stops** and **spring fatigue**
- Tip surface tension effects and evaporation contribute disproportionately to error at low volumes

If a pipette only passes at maximum volume but fails at 10% minimum, it should not be used for small-volume applications. Reporting only maximum-volume calibration and claiming full-range accuracy is a common but improper practice in poorly run laboratories.

---

**Q33. How is micropipette calibration linked to traceability in a quality management system?**

**Metrological traceability** means that calibration results can be linked through an unbroken chain of comparisons to a national or international measurement standard. In practice:
- The **analytical balance** used in calibration must itself be calibrated with weights traceable to the **International Prototype Kilogram (IPK)** or national standard
- The **thermometer** used to measure water temperature must be traceable to national temperature standards
- The **calibration laboratory** performing the balance calibration must be accredited (ISO/IEC 17025)
- **Calibration certificates** for each reference instrument must be on file with uncertainty values

When all these links exist, the micropipette's calibration is traceable to SI units (the litre, defined through the metre). This traceability is legally required for laboratories performing clinical diagnostic testing and for GLP compliance in pharmaceutical research.

---

**Q34. What is the protocol for calibrating an electronic (electronic repeater) pipette vs. a manual pipette?**

**Electronic pipettes** (e.g., Eppendorf epMotion, Rainin E4) use a **motorized piston** rather than manual thumb pressure, providing more consistent aspiration and dispensing speed, which reduces operator-dependent variability. Calibration is performed by the **same gravimetric method** as manual pipettes. Advantages of electronic pipettes in calibration include:
- Motor-controlled speed eliminates aspiration rate variability
- Programmed dispensing sequences improve consistency
- Some models have built-in calibration adjustment software

Differences in calibration protocol:
- The dispensing mode (aspiration speed, dispensing speed) must be standardized before calibration begins
- Electronic pipettes often have **user-adjustable calibration factors** stored internally — the software offset must be documented
- Battery charge level can affect motor speed on some models — always calibrate with a fully charged battery

---

**Q35. What is a calibration certificate and what information must it contain?**

A **calibration certificate** is a formal document issued by an accredited calibration laboratory documenting the outcome of calibration. According to ISO/IEC 17025, it must include:
1. Name and address of the calibrating laboratory and its accreditation number
2. **Unique identification** of the pipette (serial number, manufacturer, model)
3. **Date of calibration** and calibration due date
4. **Environmental conditions** (temperature, humidity, atmospheric pressure)
5. **Method used** (ISO 8655 gravimetric method)
6. **Results**: volume settings tested, number of replicates, mean volume, SD, Es%, Cv%
7. **Pass/Fail** status against ISO 8655 limits
8. **Measurement uncertainty** with coverage factor and confidence level
9. **Traceability statement** linking to national standards
10. Signature and stamp of the calibrating laboratory

This certificate must be retained for as long as the pipette is in service plus a defined retention period per the laboratory's QMS.

---

**Q36. What is the difference between "as found" and "as left" calibration?**

**"As Found"** calibration is performed on a pipette in the condition it arrives for servicing — before any adjustments, cleaning, or maintenance. This establishes whether the pipette was in-specification during the period since its last calibration and is important for **out-of-calibration impact assessment** (determining which experiments may have been affected). **"As Left"** calibration is performed after all maintenance, cleaning, and adjustments, confirming that the pipette is now within specification before being returned to service. Both sets of data are documented on the calibration certificate. If the "as found" data shows the pipette was outside ISO 8655 limits, a **corrective action report** must be filed documenting which experiments were performed with the non-conforming pipette and whether results need to be repeated.

---

### ADVANCED / APPLICATION QUESTIONS

---

**Q37. How would you validate a newly purchased micropipette before putting it into routine laboratory use?**

Validation of a new pipette goes beyond manufacturer-provided calibration documentation and includes:
1. **Verify manufacturer's calibration certificate** — confirm it meets ISO 8655 and is dated within acceptable timeframe
2. **Perform independent gravimetric calibration** at 3 volume settings (10%, 50%, 100% of range) with 10 replicates each
3. **Compare results** to ISO 8655 acceptance limits and manufacturer's specifications
4. **Check physical condition** — tip ejector, volume lock, piston smoothness, digit wheel alignment
5. **Assign a unique ID number** and enter into the laboratory asset register
6. **Label** with calibration status sticker and next calibration due date
7. **Create a calibration record** in the laboratory information management system (LIMS)
8. **Train users** on proper technique specific to that model

Only after all these steps is the pipette formally approved for use. In pharmaceutical and clinical laboratories, this process is part of **instrument qualification (IQ/OQ/PQ)**.

---

**Q38. What is the "reverse pipetting" technique and when is it used?**

**Reverse pipetting** involves depressing the plunger to the **second stop (blow-out position) before aspirating** liquid, then aspirating and dispensing only to the **first stop**, leaving the excess liquid in the tip. This technique is used for:
- **Viscous liquids** — the pre-loaded excess compensates for the slow drainage of viscous liquid, ensuring the first stop volume is fully dispensed
- **Foaming solutions** (detergent-containing buffers, serum) — avoids foam formation by eliminating blow-out
- **Volatile liquids** — reduces evaporation by not expelling extra air at the end
- **Very small volumes** — reduces surface tension effects

The volume dispensed in reverse pipetting equals the set volume (first stop volume), but the calibration must be confirmed using this specific technique since it gives slightly different results than standard forward pipetting. This technique is not used in routine calibration unless the laboratory specifically wants to validate pipette performance under reverse pipetting conditions.

---

**Q39. How do filter tips differ from standard tips in terms of calibration relevance?**

**Filter tips** contain a hydrophobic polyethylene frit (filter) inside the tip, designed to prevent aerosol contamination of the pipette body (important for PCR, radioactive, or infectious samples). The filter adds slight **flow resistance**, which can affect aspiration dynamics in air-displacement pipettes. Calibration studies have shown that switching from standard to filter tips can result in a **volume difference of 0.5–2%** in some pipette models, which may be significant for quantitative applications. Therefore:
- Calibration should be performed **with the same tip type** to be used in the actual experiment
- If a laboratory switches from standard to filter tips for all workflows, pipettes should be **re-calibrated with filter tips**
- Manufacturers typically specify which tip brands are validated for use with each pipette model

Using off-brand or non-validated tips is a common cause of unexpected inaccuracy even on a well-maintained pipette.

---

**Q40. Explain the concept of "pipette qualification" in a GMP pharmaceutical laboratory.**

In **GMP (Good Manufacturing Practice)** environments, pipettes undergo a formal **instrument qualification** process consisting of:
- **Design Qualification (DQ)**: Verifying the pipette design meets the user requirements specification (URS)
- **Installation Qualification (IQ)**: Confirming the pipette is correctly installed, all documentation received (manuals, calibration certificates), assigned a unique equipment ID, and entered into the asset register
- **Operational Qualification (OQ)**: Demonstrating the pipette performs within specified parameters (ISO 8655 limits) under laboratory conditions — this is essentially calibration with formal documentation
- **Performance Qualification (PQ)**: Ongoing demonstration of consistent performance over time through periodic calibration records

Any deviation from specification triggers a **deviation report** and **CAPA (Corrective Action/Preventive Action)** investigation. All records are subject to **21 CFR Part 11 (FDA)** electronic records requirements if maintained digitally. GMP pipette records typically have a minimum 5-year retention requirement.

---

**Q41. How does tip immersion depth affect aspiration accuracy in quantitative molecular biology?**

The correct immersion depth is critical to avoid two types of errors:
- **Too shallow immersion**: As the liquid is aspirated, the tip may aspirate air (especially if the container is nearly empty), causing an air gap in the tip — liquid volume aspirated is less than set, giving falsely low volumes
- **Too deep immersion**: Hydrostatic pressure from the liquid column above the tip opening adds to the aspiration force, pulling in slightly more liquid than the piston travel dictates — liquid volume aspirated is slightly more than set, causing positive bias

Recommended immersion depths (ISO 8655):
- 0.5–10 µL: 1–2 mm
- 10–100 µL: 2–3 mm
- 100–1000 µL: 2–4 mm
- 1–10 mL: 3–6 mm

Immersion depth errors of even a few millimeters can cause 1–3% volume errors in small volumes — significant for quantitative assays. Standardized immersion depth is also required to minimize operator-dependent Cv%.

---

**Q42. What is the impact of using a pipette that was stored at a different temperature from the calibration environment?**

If a pipette stored in a 4°C cold room is brought to a 25°C laboratory and used immediately, the air column inside the tip is **cold and contracted**. As it warms, the air expands, **expelling some of the aspirated liquid** — causing under-delivery. This effect is quantified by the **ideal gas law**: V₂ = V₁ × (T₂/T₁) in Kelvin. A 10°C temperature change from 15°C (288 K) to 25°C (298 K) would cause a volume change of ~3.5% — exceeding ISO 8655 limits for all pipette ranges. Solution: Allow the pipette (and solutions) to equilibrate to room temperature for ≥30 minutes before use. This is also why molecular biology reagents from the freezer must be thawed and equilibrated before pipetting.

---

**Q43. What is the role of a Standard Operating Procedure (SOP) for micropipette calibration in a quality management system?**

A **calibration SOP** is a controlled, version-managed document specifying:
1. **Scope**: which instruments are covered
2. **Frequency**: how often calibration is performed
3. **Materials required**: balance specification, water grade, thermometer, recording sheets
4. **Step-by-step procedure**: in sufficient detail for any trained person to perform consistently
5. **Acceptance criteria**: ISO 8655 limits for each pipette model
6. **Actions on failure**: quarantine, tagging, investigation, CAPA
7. **Record-keeping requirements**: form number, retention period, electronic vs. paper
8. **Roles and responsibilities**: who calibrates, who approves, who performs impact assessment on out-of-calibration findings
9. **References**: ISO 8655, relevant manufacturer manuals

The SOP must be reviewed and re-approved at defined intervals (typically annually) and all staff must be trained on it with documented evidence. Without a validated SOP, calibration results cannot be used to demonstrate compliance during regulatory audits.

---

**Q44. Compare the gravimetric method with the photometric (spectrophotometric) method of micropipette calibration.**

| Feature | Gravimetric Method | Photometric Method |
|---|---|---|
| Principle | Mass of water converted to volume | Absorbance of a dye solution compared to a standard |
| Reference standard | ISO 8655 | ASTM E1154 |
| Equipment needed | Analytical balance, thermometer | UV-Vis spectrophotometer, reference dye (e.g., tartrazine) |
| Accuracy | Highest — traceable to mass standard | Good, but depends on dye stability and spectrophotometer calibration |
| Suitable for | All volumes | Best for 1–1000 µL range |
| Speed | Slower (individual weighing) | Faster (batch processing with plate reader) |
| Volatile liquids | Not suitable (evaporation errors) | Better suited |
| Regulatory acceptance | Primary method (ISO 8655) | Secondary, used for quick checks |

The photometric method is useful as a **rapid field check** but the gravimetric method remains the reference for formal calibration certificates.

---

**Q45. How would you investigate and manage a situation where a pipette passed calibration but PCR results using that pipette are non-reproducible?**

This scenario suggests the calibration is acceptable but the pipette is introducing variability through a **different mechanism**. Investigation steps:
1. **Repeat calibration** — confirm the pipette genuinely meets specifications
2. **Evaluate operator technique** — observe the user's pipetting in real time; even with a calibrated pipette, poor technique causes poor reproducibility
3. **Check tip compatibility** — if non-validated tips are used in PCR but validated tips in calibration, differences may exist
4. **Evaluate PCR-specific factors** — template inhibition, primer dimers, polymerase batch variation (calibration wouldn't catch these)
5. **Check the other reagents** — if the mastermix pipette is problematic, all reactions are affected
6. **Use control reactions** — run a known positive control to separate pipetting from reaction chemistry issues
7. **Test tip-to-tip variation** — replicates with the same pipette but different tips to assess tip lot variability

Most often, PCR irreproducibility attributed to pipetting is actually due to **operator technique, template quality, or reagent variability** rather than pipette calibration failure.

---

**Q46. What is the effect of autoclaving on micropipette calibration?**

Some micropipettes are marketed as "autoclavable" — typically the lower assembly (shaft and tip ejector) can be autoclaved at 121°C, 15 psi for 15–20 minutes, while the upper body (volume mechanism, handle) cannot. The effects of autoclaving on calibration include:
- **Thermal expansion** of piston materials (stainless steel, PTFE seals) — may alter piston geometry temporarily
- **Degradation of PTFE O-rings** or piston seals if repeated too frequently
- **Moisture entry** into the upper mechanism if not properly capped before autoclaving

Most manufacturers recommend **verifying calibration after autoclaving** before returning the pipette to service. Multiple autoclaving cycles accelerate wear and may necessitate more frequent calibration intervals. For contamination control, using **filter tips** with non-autoclavable pipettes is preferable to autoclaving the instrument.

---

**Q47. What is the role of humidity in micropipette calibration and how is it controlled?**

**Relative humidity (RH)** affects calibration through two mechanisms:
1. **Evaporation rate of dispensed water**: In low-humidity environments (RH < 40%), droplets on the balance pan evaporate rapidly, reducing the apparent dispensed mass. This causes falsely low volume calculations and inflated Cv%
2. **Pre-wetting effectiveness**: In dry conditions, the tip air absorbs more water vapor per aspiration cycle, meaning more pre-wetting cycles are needed before measurements stabilize

ISO 8655 recommends calibration at **45–75% relative humidity** and mandates that the balance be shielded from drafts (draft shield) and used with an evaporation trap. In very dry laboratories (deserts, heavily air-conditioned spaces in summer), it may be necessary to add a small dish of water inside the balance chamber during calibration to create a locally saturated microenvironment. Humidity is monitored with a **calibrated hygrometer** and recorded on the calibration sheet.

---

**Q48. What is a micro-volume spectrophotometer (e.g., NanoDrop) and how does it differ from conventional micropipette-dependent quantitation in terms of volume requirements?**

A **NanoDrop (Thermo Fisher) or similar microvolume spectrophotometer** measures absorbance of **1–2 µL samples** retained on a measurement pedestal by surface tension, eliminating the need for cuvettes and dramatically reducing sample consumption. Unlike conventional spectrophotometry where typically 1–3 mL is needed in a cuvette (requiring multiple 100–1000 µL pipette steps), the NanoDrop uses 1–2 µL pipetted with a P2 or P10. This means:
- **Pipetting accuracy at 1–2 µL is critical** — a 10% error (0.1–0.2 µL) would significantly affect the optical path length and thus the calculated concentration
- The instrument itself compensates for varying path lengths using a pedestal measurement of sample height
- Calibration of the P2 or P10 used for NanoDrop loading should be verified at 1–2 µL specifically, a range where many laboratories do not routinely check accuracy

This illustrates how modern instruments that use very small volumes have made micropipette calibration at the low end of the range more important than ever.

---

**Q49. How do you assess the impact on experimental results when a pipette is found to be out of calibration upon its periodic check?**

When a pipette fails calibration, an **impact assessment** must be performed:
1. **Identify the out-of-calibration period**: When was the last successful calibration? All work performed since that date with this specific pipette is potentially affected.
2. **Identify the affected experiments**: Review lab notebooks and LIMS records for all experiments where this pipette was used during the non-conforming period
3. **Calculate the potential volume error**: Using the As Found Es% and Cv%, estimate the likely volume error in each experiment
4. **Assess criticality**: Some experiments (qualitative PCR, routine gel checks) may be tolerant of 1–3% volume error; others (qPCR standard curves, ELISA quantitation, clinical samples) may not
5. **Document findings**: Record all affected experiments in a **Non-Conformance Report (NCR)**
6. **Decide on action**: Repeat critical experiments if possible; issue a data qualification statement for published or reported results if repetition is not possible
7. **Root cause analysis**: Determine why the pipette failed (dropped? overused? contaminated?) and implement corrective action

This process is mandatory in GLP and GMP environments and is good practice in any research laboratory.

---

**Q50. Design a complete calibration program for a molecular biology laboratory with 20 micropipettes of various ranges. What documentation, SOPs, and quality controls would you implement?**

A comprehensive calibration program would include:

**Inventory Management:**
- Assign unique **equipment IDs** to all 20 pipettes; maintain a master equipment list in LIMS
- Categorize by risk level (critical-use pipettes for qPCR, clinical samples vs. general-use pipettes)

**Calibration Schedule:**
- Critical-use pipettes: calibrate every **3 months**
- General-use pipettes: calibrate every **6 months**
- All pipettes: calibrate **after any incident** (drop, repair, autoclave)

**SOPs Required:**
- Micropipette Calibration SOP (gravimetric method, ISO 8655)
- Analytical Balance Calibration SOP
- Out-of-Calibration Investigation and Impact Assessment SOP
- Pipette Maintenance and Cleaning SOP

**Calibration Execution:**
- Perform at 3 volume settings, 10 replicates each, using ISO 8655 Z-factor
- Use a calibrated analytical balance (0.0001 g readability, traceable to national standards)
- Record temperature, humidity, atmospheric pressure for each session
- Generate calibration record form with pass/fail determination against ISO 8655 limits

**Documentation:**
- Calibration certificates filed per pipette ID
- Calibration stickers (color-coded by quarter) on each pipette body
- Electronic records in LIMS with audit trail (21 CFR Part 11 if applicable)
- Periodic trend analysis of Es% over time to detect gradual deterioration

**Quality Controls:**
- Annual review of calibration data trends for each pipette
- Participation in **external proficiency schemes** (e.g., pipette calibration inter-laboratory comparison)
- Annual training refresher for all staff on proper pipetting technique

This program ensures traceability, regulatory compliance, and protection of experimental data integrity across the entire laboratory.

---

*End of Section I: Calibration of Micropipette — 50 Questions & Answers*
*Masters Level | Molecular Biology Practical Viva Preparation*
