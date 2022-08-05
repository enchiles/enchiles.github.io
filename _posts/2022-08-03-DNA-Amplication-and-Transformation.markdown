layout: "post"
title: "20220803 DNA Amplification, DNA Cleanup Transformation (ORT1 Insertion into E.coli)"
date: "2022-08-03 11:56"
categories: protocol
---

**Purpose**

This protocol is designed to describe how to amplify DNA from purchase primers for insertion into vectors that will then be transformed into E coli. This experiment used primers XSp072 (p426 GPD forward), XSp073 (Reverse), and XSp074 (p426 GAL1 forward) to inset ORT1 into the GPD and GAL1 plasmids.

![p426 GAL1 plasmid from ATCC](images/p426-gal1-plasmid-from-atcc.png)


**Steps for Q5 PCR reaction**

This reaction will cut the curcular plasmid into a linear one and then amplify the DNA primers.

Ragents needed from the (blank) kit:
| Reagent     | Reaction Volume (uL)   |
| :------------- | :------------- |
| Water      | 37     |
| 5X Q5 Reaction Buffer      | 10      |
| Fwd Primer (50uM)     | 0.5      |
| Reverse Primer (50uM)       | 0.5      |
| Templater (20ng/uL)      | 0.5      |
| dNTP (10mM)     | 1      |
| Q5 Enzyme       | 0.5      |

The primers arrive as pellets and will need to be diluted into sterile water to the correct concentration. Dry concentration is listed on the side in nmols. X nmols*1000 = X,000 pmols/50 uM = the volume in uL of water needed.

PCR machine cyles:
| Temp     | Time   |
| :------------- | :------------- |
| 98 C     | 30 seconds     |
| 98 C     | 10 seconds     |
| 60 C     | 30 seconds     |
| 72 C     | 60 seconds     |
| 72 C     | 2 minutes      |
| 4 C      | indefinitely   |

There should be 30 cycles from step 2-4.

**Making and running a gel**

After the DNA amplification, the insertion should be a longer fragment of about 1 kB. This can be verified by running a gel.

1. Put the gel tray in the plate sideways to start with the wide toothed side of the comb in the plate.
2. Measure out 1% by volume (1g per 100mL) of Agar for gel to be prepared.
3. Add in the appopriate volume of TAE buffer.
4. Cook in them microwave about 1 minute then gentle swirl. Repeat for short spurts for another 30 seconds or so. Check to make sure Agar is dissolved.
5. Add 2 uL of Ethylene bromide (located in Svetlana's fridge door).
6. Pour into plate to let solidify for about an hour.
7. When gel solidified and cool, turn the tray the proper way and submerge in TAE buffer.
8. Load 5 uL of ladder DNA to know the size of the band in lane 1.
9. Load 5 uL of PCR product DNA with 5uL of loading dye to the next lanes.
10. Run the gel at 120V for 40 minutes with the black wire on top and the red wire on the bottom.
11. Then take a picture of the image using the ChemDoc, being sure to denote that Ethylene bromide was used.

![ORT1 GPD and GAL1 Gel Plate -20220803](images/ort1-gpd-and-gal1-gel-plate-20220803.png)

**DNA Cleanup**

This purifies the newly amplified DNA using the following kit:
![DNA Cleanup Kit](images/dna-cleanup-kit.png)

Instrucions are in the kit covering the following steps:

1. Mix 45 uL equal volumes of both the remaining PCR product and the membrane wash solution from the kit.
2. Best to label to lip of the inner tube that pokes out of the receptacle tubes.
3. Add solution directly to the center of the tube membrane to ensure it all gets wets.
4. There are series of steps where the samples alternate sitting on ice and then getting Centrifuged.

**To Measure DNA concentration**

Use the plate reader instrument at the end of the Su Lab bench.

1. Use the Gen.5 Program -> Nucleic Acid Quant. -> Sample Type dsDNA.
2. Deselect everything except the two dots in the first two row. These are the blank rows.
3. 1 uL of water gets pipetted into the center of these four spots.
4. 1 uL of purified DNA gets pipetted into the spots on the following rows.
5. Load the tray metal flap facing upwards going in the instrument first.
6. Need to take 2 readings. The first reading is for the blanks and the second reading actually gives the DNA concentration.

DNA concentrations:
| DNA     | concentration (ng/uL)  |
| :------------- | :------------- |
| p426 GAL1     | 134    |
| ORT1 GAL1     | 75     |
| p426 GPD      | 70     |
| ORT1 GPD      | 65     |

Assembly Stepts:
Actually inserts the ORT1 into the GAL1 or GPD vector. The total volume is 5 uL and the volume of insert and vector to use is calculated using a calculator made by Xiaoyang. The insert and vector will be 2.5 uL and the remaining volume will come from the addition of water.
DNA concentrations:
| Plasmid    | Insert (uL)  | Vector (uL)  |
| :------------- | :------------- |
| GAL1     | .9    | 1.6    |
| GGPD     | .6    | 1.9    |

Insertion sequence is inserted into the plasmid using the following kit:
![DNA Assembly Kit](images/dna-assembly-kit.png)

1. Add DNA, then vector, the Master Mix
2. Incubate in the PCR machine at 50 C for 15 minutes.
3. Control sample was prepared with no insert

**Transformation**

Actully grows the assembled plasmids with the ORT1 inserts in competent 10G E coli cells. Competent cells are very sensitive so they must be kept on ice.

1. In Eppendorf Tube then transfered to a chilled 15mL Connical tube.
2. 25 uL competent cells are combined with 1 uL of DNA.
3. Allow to sit on ice in Connical for ~10 minutes.
4. Agitated in the incubator for ~30 minutes.
5. 100 uL was then spread on to an Amp - plate.

![ort1 Transformed E. coli plates](images/ort1-transformed-e-coli-plates.png)

NOTES:
Plate order top row: p426 GPD-, p426 GPD SLC45A4-HA 1X, p426 GPD SLC45A4-HA 100X
Plate order bottom row: p426 GAL1-, p426 GAL1 SLC45A4-HA 1X, p426 GAL1 SLC45A4-HA 100X

The genes for Amp resistance is one the p426 plasmid. It is hard for this plasmid to be taken up in the linear form, therefore only the plasmids that have successfully taken up the ort1 and recircularized should grow.
Ideally, there should be no growth on the GPD- and GAL1- plates. Growth on these plates is likely to do plasmids that were incompletely cut at the Bam1 site during the amplification preparation. In any event, They grew much less than the SLC45A4 transformed cells.
There is low colony growth on the dilution plates. Given the low growth percentage of the GPD- and GAL1- plates, there is high confidence that the few colonies that appeared on the dilution plates are mostly SLC45A4+ containing the ort1 insert.

**Next Steps**

Cells will be taken from the dilution plate and sent for sequencing to confirm that the are SLC45A4 positive.
