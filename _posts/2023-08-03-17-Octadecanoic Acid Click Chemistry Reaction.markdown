layout: "post"
title: "20230803 Terminal Alkyne 17-Octadecanoic Acid Click Chemistry Reaction"
date: "2023-08-03 15:00"
categories: protocol
---

**Purpose**

This protocol is designed to perform a Copper (II) mediated cyclo addition of a fluorescent probe to a terminal alkyne (17-ODYA) molecule. The cyclo addition will result in the reduction of the alkyne to an alkene tagged with the probe. This will ultimately result in a mass spectrometer independent detection method for alkyne molecules.

**Reaction Stock Solutions**

Reagents needed for the reaction:
| Reagent         | Stock Concentration    | Final Reaction Concentration | Amount added to Reaction (uL) |
| :-------------  | :--------------------- | :----------------------------| :-----------------------------|
| Azide           | 4mM                    | 2mM                          | 10                            |
| 17-ODYA         | 800uM                  | 200uM                        | 5                             |
| Cu/Ascorbate    | 4mM/8mM                | 1mM/2mM                      | 5                             |

Two azide probes used: sulfocyanine 3 azide and azide-fluor 488.

**Preparation of Stocks**

Copper (II) sulfate -> 5mg/15.9 = 315uL of H2O for a 100mM solution
  (M1)(V1) = (M2)(V2)
   100*315 = 40*X
     31500 = 40X
   787.5uL = X = 40mM

   This was then diluted to a 10mM concentration at 1mL volume by diluting 250uL into 750uL H2O.

Ascorbate -> 5mg/17.6 = 284uL of H2O for a 100mM solution
  (M1)(V1) = (M2)(V2)
   100*284 = 80*X
     28400 = 80X
     355uL = X = 80mM

   This was then diluted to a 20mM concentration at 1mL volume by diluting 62.5uL into 937.5 H2O.

Copper/Ascorbate Mix:
  100uL of 10mM Copper
+ 100uL of 20mM Ascorbate
+ 50uL of H2O

17-Octadecanoic Acid -> 5mg tube.
  Dissolved in ethanol pursuant to solubility. 1mol is 280g. Dissolved into 1.125mL, for an 16mM solution.
  This was then diluted 20X to 800uM by taking 50uL and adding it to 950uL of H2O.

Sulfocyanine 3 azide -> 1mg tube.
  Dissolved in water pursuant to solubility. 1mol is 737g. Dissolved into 335uL, for an 4mM solution.

Azide-fluor 488
  Dissolved in water pursuant to solubility. 1mol is 574g. Dissolved into 435uL, for an 4mM solution.

**Experiment Notes**

After the stock solutions were made I set up the reactions. For each of the probes I prepared a control without copper, which is needed to stabilize the probe alkyne interaction transition. Therefore, without copper, there should be not reactant degradation. Sulfocyanine probe visibly red and 488 is a neon yellow-ish/green color.

Reaction scheme:
| Reaction        | Probe                | Alkyne  | Copper |Ascorbate |
| :-------------  | :--------------------| :-------| :------|:---------|
| 1               | Sulfocyanine 3 azide | 17-ODYA | Yes    | Yes      |
| 2               | Sulfocyanine 3 azide | 17-ODYA | No     | Yes      |
| 3               | Azide-fluor 488      | 17-ODYA | Yes    | Yes      |
| 4               | Azide-fluor 488      | 17-ODYA | No     | Yes      |

All reactions were complete at 2:20PM and placed in the drawer away from light. Ascorbate was discarded and other stock solutions were put in a box and placed in the 4 degree fridge.
The reaction will be quenched 50X by diluting into 480uL of 40:40:20 the following day.
