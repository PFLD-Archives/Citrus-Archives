# CITRUS TECHNOLOGIES INC.
## TECHNICAL DATASHEET: SYNTHETIC FUSION MODULATOR (S.F.M x20)
**Document Ref:** CTI-SFM-X20-TECH
**Security Clearance:** LEVEL 3 (FAIRVIEW RESEARCH COMPLEX PERSONNEL)
**Authored By:** Citrus Technologies Inc., Advanced Reactor Division
**In Association With:** National Electrodynamics / Parafield Corp.
**Date:** 2013


## 1. OVERVIEW & ORIGIN

The **Synthetic Fusion Modulator (S.F.M)** is a sustained-reaction fusion system developed by Citrus Technologies following independent research into Parafield Corp.'s proprietary synthetic isotope series.

Where the S.F.R relies on discrete high-intensity laser pulses, the S.F.M achieves fusion through **Proximity Lattice Reaction (PLR)**, a passive self-sustaining process that requires no bombardment array. Peak output is lower than the S.F.R by design, but the safety profile is considerably stronger and the system is built for continuous uptime rather than cycled ignition.

The **x20** designation refers to the reactor's 20-rod fuel configuration.


## 2. FUEL ROD ARCHITECTURE

Each fuel element is a solid synthetic isotope rod seated inside a reinforced zirconium alloy cladding. The cladding keeps the isotope core isolated from direct coolant contact and is rated for prolonged neutron bombardment and thermal cycling.

The rod itself is a [REDACTED] compound derivative, re-engineered by Citrus from Parafield's existing isotope series for low-flux sustained output rather than pulse ignition. Once cladded, each rod is submerged in a continuously circulated cold water jacket. The water handles two jobs at once: it keeps the cladding surface temperature in range, and it acts as a neutron moderator, slowing flux enough to prevent the reaction from running away on its own.


## 3. PROXIMITY LATTICE REACTION (PLR)

The S.F.M does not ignite fuel like the S.F.R. It instead positions by making the rods close enough.

When two or more rods are brought within Critical Proximity of each other, the heavy-nucleus lattice in the isotope cores begins exchanging neutron flux. That mutual excitation is enough to start a slow, self-sustaining fusion reaction across the cluster. Output is controlled directly by rod spacing: tighter proximity means higher neutron exchange and more energy yield, wider spacing throttles it back down.

The water jacket is what makes this inherently stable. Any thermal spike increases moderation automatically, which slows the reaction rather than feeding it. The S.F.M does not escalate under disturbance the way the S.F.R does.

### 3.1 Rod Configuration

The 20 rods are split into four independent groups of five, designated **Clusters A through D**. Each cluster can be brought online or pulled offline without affecting the others, which gives operators real load flexibility. Minimum viable output needs at least two active clusters. Full power runs all four at calibrated proximity.


## 4. OPERATIONAL SPECIFICATIONS

| Variable | Standard Value | Critical Threshold |
| :--- | :--- | :--- |
| **Rod Proximity** | 40 to 80 cm | Below 20 cm (Runaway Risk) |
| **Coolant Temperature** | 15°C to 40°C | Above 80°C (SCRAM Trigger) |
| **Neutron Flux Index (NFI)** | 1.0 to 3.5 | Above 5.0 (Auto-SCRAM) |
| **Cladding Integrity** | 90% to 100% | Below 60% (Cluster Offline) |

Peak output is sufficient to supply approximately 90% of Fairview Research Complex under full four-cluster operation.


## 5. SAFETY SYSTEMS

The S.F.M's passive design removes most of the failure vectors that made the S.F.R dangerous. That said, a tiered emergency protocol is still mandatory.

### 5.1 Primary: SCRAM

When NFI exceeds 5.0 or coolant temperature exceeds 80°C, control room personnel initiate SCRAM. If no action is taken within 15 seconds of threshold breach, the F.R.C. Facility AI takes over and executes AUTO-SCRAM without waiting for operator input. AUTO-SCRAM drives all clusters to maximum rod separation and bumps coolant circulation to emergency flow rate.

### 5.2 Secondary: Emergency Rod Separation (E.R.S.)

If SCRAM does not bring NFI below 5.0 within 30 seconds, hydraulic separation arms physically drive all 20 rods past critical proximity at once. The system is spring-loaded and requires no facility power to trigger, meaning a full blackout still engages it automatically. The reaction attenuates to zero within roughly 45 seconds of full separation.

### 5.3 Tertiary: Boron Curtain Injection (B.C.I.)

If E.R.S. is mechanically compromised and separation is incomplete, concentrated boron solution is pumped directly into the water jacket across all active clusters. Boron absorbs neutron flux aggressively, chemically killing the reaction and forcing NFI to zero. The reactor will be contaminated afterward and requires full decontamination before returning to service. Estimated downtime is 3 to 6 weeks.


## 6. COMPARATIVE NOTES

| | S.F.R Mark I | S.F.M x20 |
| :--- | :--- | :--- |
| **Reaction Type** | Pulsed ICF (Laser) | Sustained PLR (Proximity) |
| **Fuel Format** | Discrete pellet cells | Solid zirconium-clad rods |
| **Peak Output** | ~80% of United Columbus | ~90% of Fairview R.C. |
| **Primary Risk** | Laser symmetry / timing error | Rod proximity miscalibration |
| **Passive Safety** | None, disturbance escalates | Yes, disturbance attenuates |
| **Worst Case** | Thermal Runaway / Superstructure loss | Chemical contamination (BCI) |


**END OF DOCUMENT**
*Citrus Technologies Inc., Advanced Reactor Division*
*All isotope data remains property of Parafield Corp. Used under research licensing agreement with National Electrodynamics.*
