
# Additive Manufacturing — Sol-Gel Knowledge Hub

<details>
<summary><strong>🔬 Additive Manufacturing & Sol-Gel Science</strong></summary>

This knowledge hub explores advances in additive manufacturing, sol-gel
processing, functional materials, and AI-assisted manufacturing.
It connects materials science with process development, characterisation,
and engineering applications.

<details>
<summary>📑 Table of Contents</summary>

1. [Introduction to Sol-Gel Science](./Introduction-to-Sol-gel.md)
2. [Supercapacitors via Sol-Gel and MOF-Assisted Synthesis](./Supercapacitors-via-Sol-gel-MOP.md)

</details>

---

<details>
<summary>🧪 Introduction to Sol-Gel Science</summary>

### What is Sol-Gel Science?

Sol-gel processing transforms molecular or colloidal precursors into
inorganic or hybrid networks through hydrolysis, condensation, gelation,
drying, and, where required, thermal treatment.

A **sol** is a colloidal suspension of solid particles in a liquid.
A **gel** is a network extending throughout a liquid-containing system.
The final material's composition, porosity, and microstructure depend on
precursor chemistry and processing conditions.

For pore-free ceramics, heat treatment may promote sintering and
densification.

[Read the full article](./Introduction-to-Sol-gel.md)

</details>

---

<details>
<summary>⚡ Supercapacitors via Sol-Gel — MOF-Derived Fe-Co-S@gC/rGO</summary>

### Executive Summary

This article examines a reported iron–cobalt sulfide, graphitic carbon,
and reduced graphene oxide (rGO) hybrid for electrochemical energy storage.
The synthesis uses a metal–organic framework (MOF)-assisted precursor
strategy followed by thermal treatment and sulfurisation.

### Characterisation Methods

- **XRD:** Phase identification and crystallinity.
- **FESEM/TEM:** Particle morphology and nanoscale architecture.
- **Raman/FTIR:** Carbon structure and chemical bonding.
- **BET:** Specific surface area and pore-size analysis.
- **EDX/XPS:** Elemental distribution and chemical states.

### Reported Electrochemical Results

| Parameter | Reported value |
|---|---:|
| Specific capacitance | 1827 F g⁻¹ at 0.5 A g⁻¹ |
| Capacitance retention at 10 A g⁻¹ | 69.76% |
| Charge-transfer resistance | 0.09 Ω |
| Electrode cycling retention | 97.96% after 12,000 cycles |
| Asymmetric-device voltage window | 0–2.0 V |
| Reported device energy density | 541.2 Wh kg⁻¹ |
| Reported power density | 8213.4 W kg⁻¹ |

**Scientific caution:** Verify the energy density, device capacitance,
mass basis, and calculation method against the original publication
before making performance comparisons.

### Reference

Gholizadeh, A., & Mazaheri, E. (2026).
*MOF-derived hierarchical FeCo₃S₄@graphitic carbon/rGO nanoarchitectures
for high-energy and high-power supercapacitors.*
Journal of Sol-Gel Science and Technology, 120, 7.

[Read the paper](https://doi.org/10.1007/s10971-026-07246-5)

[Read the full article in this repository](./Supercapacitors-via-Sol-gel-MOP.md)

</details>

</details>



# Comprehensive Scientific Analysis: Sol–Gel Synthesized $\text{Ni}$-Doped $\text{ZnO}$ Nanoparticles

This document provides a rigorous, deep-dive scientific analysis of the physical, electrical, dielectric, and magnetic mechanisms occurring in $20\%$ $\text{Ni}$-doped zinc oxide ($\text{Ni}_{20\%}\text{-ZnO}$) nanoparticles, based on the research published by Alqarni et al. (2026).

---

<details>
<summary><b>1. Executive Summary & Core Research Motivation</b></summary>

### 1.1 The Technological Dilemma of Pristine $\text{ZnO}$
Zinc oxide ($\text{ZnO}$) is an established direct wide bandgap ($E_g \approx 3.37\text{ eV}$) II-VI semiconductor exhibiting a large exciton binding energy ($\sim 60\text{ meV}$) at room temperature. Despite its chemical stability, optical transparency, and cost-effectiveness, two major physical limitations hinder its deployment in next-generation spintronic, electromagnetic, and low-power electronic devices:
1. **Intrinsic Diamagnetism:** Absence of net localized spin moments due to fully filled $d^{10}$ electronic configurations of $\text{Zn}^{2+}$ ions.
2. **Restricted Electrical Transport:** Low intrinsic carrier density and high grain boundary scattering barriers under un-doped conditions.

### 1.2 The $20\%$ $\text{Ni}$-Doping Strategy
To circumvent these barriers, transition metal (TM) doping—specifically targeting a high concentration of $20\text{ mol}\%$ $\text{Ni}^{2+}$—was executed via a critical sol-gel pathway combined with supercritical drying.

```
       [ Sol-Gel Matrix Synthesis ]
                    │
                    ▼
       [ Supercritical Drying (EtOH) ]
                    │
                    ▼
        [ Air Annealing (400 °C) ]
                    │
      ┌─────────────┴─────────────┐
      ▼                           ▼
[ Electronic Modulation ]    [ Magnetic Transition ]
• Ni 3d - O 2p Hybridization • Diamagnetic → Superparamagnetic
• Defect State Generation    • Localized Spin Alignments
• Ea Reduced to 84 meV       • Ms = 6.0 emu/g (5 K)
```

</details>

<details>
<summary><b>2. Synthesis Protocol & Phase-Structural Physics</b></summary>

### 2.1 Synthesis Thermodynamics & Kinetics
The sol-gel synthesis utilizes zinc acetate dihydrate $[\text{Zn(CH}_3\text{COO)}_2\cdot2\text{H}_2\text{O}]$ and nickel chloride hexahydrate $[\text{NiCl}_2\cdot6\text{H}_2\text{O}]$ dissolved in methanol with a stoichiometric molar ratio:
$$\text{Ratio} = \frac{[\text{Ni}]}{[\text{Zn}]} = 0.20$$

The critical drying phase under ethanol ambient ($T_c = 243^\circ\text{C}$, $P_c = 63.6\text{ bar}$) prevents capillary forces from collapsing the pore network during solvent removal. Subsequent air annealing at $400^\circ\text{C}$ for $2\text{ hours}$ promotes crystallization.

### 2.2 Crystal Structure & Phase Quantification (XRD Analysis)
* **Primary Phase:** Hexagonal Wurtzite structure of $\text{ZnO}$ (Space Group $P6_3mc$, JCPDS No. 36-1451).
* **Lattice Planes:** (100), (002), (101), (102), (110), (103), and (112).
* **Secondary Phases:** High dopant concentration ($20\%$) exceeds the solid solubility limit of $\text{Ni}^{2+}$ inside the $\text{ZnO}$ host lattice, giving rise to minor secondary phase reflections:
  1. Metallic $\text{Ni}$ (FCC structure, JCPDS No. 04-0850) observed via (111) and (200) planes.
  2. Hexagonal $\text{Ni(OH)}_2$ (JCPDS No. 14-0117) detected along (100), (101), and (110) planes.

### 2.3 Microstructural Metrics
The mean crystallite size ($D$) was evaluated using the classical Scherrer equation applied to the dominant (101) reflection peak:
$$D = \frac{k\cdot\lambda}{\beta \cdot \cos\theta}$$

Where:
* $k \approx 0.9$ (shape factor)
* $\lambda = 1.54056\text{ \AA}$ ($\text{Cu-}K\alpha$ radiation)
* $\beta$ = Full width at half maximum (FWHM) in radians

$$\mathbf{D \approx 64\text{ nm}}$$

SEM/EDS micrographs confirm submicron, spherical, agglomerated morphologies driven by high nanostructural surface energy without grain cracking or structural collapse.

</details>

<details>
<summary><b>3. Electrical Transport Mechanisms & Defect Engineering</b></summary>

### 3.1 AC Conduction Mechanics & Universal Power Law
The frequency-dependent AC conductivity ($\sigma_{ac}$) spans $100\text{ Hz}$ to $1\text{ MHz}$ across a temperature window of $160\text{ K}$ to $380\text{ K}$. It adheres strictly to Jonscher's Universal Power Law:
$$\sigma_{ac}(\omega) = \sigma_{dc} + A\omega^s$$

Where:
* $\sigma_{dc}$ is the DC (frequency-independent) conductivity.
* $A$ is a temperature-dependent coefficient.
* $s$ ($0 < s < 1$) is the dimensionless frequency exponent reflecting charge carrier interaction strength.

At lower frequencies, $\sigma_{ac}$ exhibits a flat plateau ($\sigma_{dc}$) governed by long-range percolation paths. At higher frequencies, $\sigma_{ac}$ increases dispersion due to localized short-range hopping motion of polarons over potential barriers.

### 3.2 Temperature Dependence & Activation Energy Analysis
The DC conduction displays classic semiconducting thermally activated transport. The relationship between $\sigma_{dc}$ and absolute temperature ($T$) follows the Arrhenius equation:
$$\sigma_{dc}\cdot T = \sigma_0 \exp\left(-\frac{E_a}{k_B T}\right)$$

```
  ln(σ_dc * T)
       │
       │  \
       │   \  Slope = -Ea / kB
       │    \
       │     \
       └────────────────── 1000/T (K⁻¹)
```

* **Extracted Activation Energy ($E_a$):**
$$\mathbf{E_a = 84\text{ meV}}$$

* **Physical Origin:** Incorporating $\text{Ni}^{2+}$ creates shallow donor defect states (e.g., oxygen vacancies $V_O$, interstitial zinc $\text{Zn}_i$, or localized $\text{Ni}^{2+}/\text{Ni}^{3+}$ energy levels below the conduction band minimum). This low barrier ($84\text{ meV}$) allows charge carriers to easily undergo thermally assisted small polaron hopping.

</details>

<details>
<summary><b>4. Impedance Spectroscopy & Dielectric Relaxation Formalism</b></summary>

### 4.1 Real ($Z'$) and Imaginary ($Z''$) Impedance Response
Complex impedance $Z^*(\omega) = Z'(\omega) - j Z''(\omega)$ separates bulk (grain) and grain boundary transport processes:

1. **Real Impedance ($Z'$):** Higher temperatures drop $Z'$ drastically in the low-frequency region due to enhanced carrier mobility and liberation of trapped charges.
2. **Imaginary Impedance ($Z''$):** Exhibits distinct broad relaxation peaks that shift toward higher frequencies with increasing temperature. This confirms thermally activated relaxation satisfying the resonance condition:
$$\omega_{max} \cdot \tau = 1 \implies 2\pi f_{max} \tau = 1$$

### 4.2 Nyquist Analysis ($Z'' \text{ vs. } Z'$)
The Nyquist plot displays asymmetric, depressed semicircular arcs centered below the real axis ($Z'$). This non-ideal response denotes non-Debye relaxation with a distribution of relaxation times within the polycrystalline matrix.

* **Comparison (Pristine vs Doped at $300\text{ K}$):**
  * Pristine $\text{ZnO}$: Extends to large arc diameters ($> 1.6 \times 10^8\ \Omega$), representing high internal grain/grain-boundary resistance.
  * $\text{Ni}_{20\%}\text{-ZnO}$: Arc diameter collapses to $< 8.0 \times 10^6\ \Omega$. This order-of-magnitude resistance drop confirms massive carrier injection and barrier attenuation across grain boundary boundaries.

### 4.3 Electric Modulus Formalism ($M^*$)
To eliminate interfacial space-charge/electrode polarization effects, the electric modulus $M^*(\omega) = \frac{1}{\epsilon^*(\omega)} = M'(\omega) + j M''(\omega)$ was calculated:
* **Real Modulus ($M'$):** Asymptotically approaches zero at low frequencies, proving complete suppression of electrode capacitance contributions.
* **Imaginary Modulus ($M''$):** Peak frequency shifts yield a relaxation-derived activation energy through:
$$\tau = \tau_0 \exp\left(\frac{E_a}{k_B T}\right)$$

Extracted value from $\ln(\tau)$ vs. $1000/T$ slope:
$$\mathbf{E_a = 84 \pm 8\text{ meV}}$$

The exact concurrence of activation energy values derived independently from DC conductivity ($\sigma_{dc}$) and dielectric relaxation ($\tau$) proves that **both transport and relaxation are governed by the same physical mechanism: defect-mediated polaron hopping**.

</details>

<details>
<summary><b>5. Magnetic Phenomenology: Superparamagnetic Transition</b></summary>

### 5.1 Magnetic Ordering Shift
Pristine $\text{ZnO}$ is intrinsically diamagnetic due to paired shell structures. Doping with $20\%$ $\text{Ni}$ transforms the system into a **superparamagnetic-like semiconductor**.

```
    Pristine ZnO                    Ni-Doped ZnO (20%)
┌───────────────────┐              ┌───────────────────┐
│ Diamagnetic       │              │ Superparamagnetic │
│ (No net spin)     │ ───────────► │ Magnetic moments  │
│                   │              │ coupled via 3d-2p │
└───────────────────┘              └───────────────────┘
```

### 5.2 Isothermal Magnetization Loops ($M \text{ vs. } B$)
S-shaped hysteresis curves recorded up to magnetic field strengths of $10\text{ T}$ yield the following critical quantitative metrics:

| Temperature ($T$) | Saturation Magnetization ($M_s$) | Remanent Magnetization ($M_r$) | Coercive Field ($B_c$) |
| :---: | :---: | :---: | :---: |
| **$5\text{ K}$** | $6.00\text{ emu g}^{-1}$ | $2.15\text{ emu g}^{-1}$ | $0.036\text{ T}$ |
| **$300\text{ K}$** | $1.50\text{ emu g}^{-1}$ | $0.85\text{ emu g}^{-1}$ | $0.026\text{ T}$ |

### 5.3 Quantum Interaction Mechanics
1. **At Low Temperatures ($5\text{ K}$):** Thermal kinetic energy ($k_B T$) is insufficient to randomize magnetic moments. Unpaired $\text{Ni}^{2+}$ ($d^8$) electronic spins aligned with nearby secondary metallic $\text{Ni}$ clusters lead to a high saturation magnetization ($6.00\text{ emu g}^{-1}$).
2. **At Room Temperature ($300\text{ K}$):** Thermal fluctuations overcome single-domain magnetic anisotropic barriers ($K V < k_B T$). The magnetic moments fluctuate rapidly, suppressing overall coercivity ($0.026\text{ T}$) and remanence, which produces a classic superparamagnetic-like response.
3. **Exchange Mechanism:** Magnetism originates from $p\text{-}d$ exchange interactions between the localized $d$-electrons of $\text{Ni}$ ions and oxygen $p$-band holes/vacancies ($V_O$), combined with localized magnetic contributions from nano-sized metallic $\text{Ni}$ inclusions.

</details>

<details>
<summary><b>6. Synthesis of Critical Metrics & Multifunctional Applications</b></summary>

### 6.1 Master Physical Parameter Summary Table

| Parameter / Feature | Value / Observation | Analytical Technique |
| :--- | :--- | :--- |
| **Crystal Phase** | Hexagonal Wurtzite ($P6_3mc$) | XRD |
| **Average Crystallite Size ($D$)** | $\sim 64\text{ nm}$ | Scherrer Equation (XRD) |
| **Secondary Phases** | Metallic $\text{Ni}$ (FCC) & $\text{Ni(OH)}_2$ | XRD / EDS Mapping |
| **AC Conductivity Law** | $\sigma_{ac} = \sigma_{dc} + A\omega^s$ | Impedance Analyzer |
| **Transport Activation Energy ($E_a$)** | $84\text{ meV}$ | Arrhenius Fit ($\sigma_{dc} \text{ vs. } 1/T$) |
| **Relaxation Activation Energy ($E_a$)**| $84 \pm 8\text{ meV}$ | Modulus Fit ($\tau \text{ vs. } 1/T$) |
| **Low-Temp Saturation Magnetization** | $6.00\text{ emu g}^{-1}$ ($5\text{ K}$) | VSM ($10\text{ T}$) |
| **Room-Temp Saturation Magnetization**| $1.50\text{ emu g}^{-1}$ ($300\text{ K}$) | VSM ($10\text{ T}$) |
| **Magnetic Ordering Type** | Superparamagnetic-like | ZFC-FC / $M\text{-}B$ Hysteresis |

### 6.2 Target Multifunctional Applications
* **Spintronic Devices:** Low coercivity combined with room-temperature magnetic responses allows potential spin injection and transport tuning.
* **Gas Sensors & Catalysis:** Lowered carrier hopping activation barriers ($84\text{ meV}$) and high defect density ($V_O$) accelerate surface redox reactions and charge separation.
* **Magnetic Hyperthermia:** Moderate $M_s$ and superparamagnetic-like behavior prevent remanent aggregation in zero-field conditions while generating heat under alternating fields.

</details>

---
*Document Compiled for GitHub Knowledge Base Documentation.*
```

The comprehensive scientific analysis summary has been formatted into Markdown with tree dropdown sections using HTML `<details>` and `<summary>` tags.
