# Protocol Template


### Quick Links:

- [MIOP](#Minimum-Information-about-an-Omics-Protocol-(MIOP))
- [Background](#BACKGROUND)
- [Equipment](#EQUIPMENT)
- [Standard Operating Procedure](#STANDARD-OPERATING-PROCEDURE)

## Minimum Information about an Omics Protocol (MIOP)

See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

| MIOP Term  | Value |
| ------------- | ------------- | 
| methodology category  | omics analysis |
| project  | NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program Protocols |
| purpose  | PCR [OBI:0000415] |
| analyses  | PCR [OBI:0000415] |
| geographic location  | North East Pacific Ocean [GAZ:00013765] |
| broad-scale environmental context  | oceanic epipelagic zone biome [ENVO:01000035], marine biome [ENVO:00000447] |
| local environmental context  | oceanic epipelagic zone biome [ENVO:01000035] |
| environmental medium  | sea water [ENVO:00002149] / DNA extraction [OBI:0000257] |
| target  | Cytochrome C Oxidase Subunit 1 [NCIT:C128943] |
| creator  | [Shannon Brown](https://github.com/Brown-NOAA), [Han Weinrich](https://github.com/HanWeinrich), and [Zachary Gold](https://github.com/marinednadude) |
| materials required  | agarose gel electrophoresis system [OBI:0001134] / PCR instrument [OBI:0000989] |
| skills required  | sterile technique, pipetting skills, and standard molecular technique |
| time required  | 330 |
| personnel required  | 1 |
| language  | en |
| issued  | 2024-02-02	 |
| audience  | scientists |
| publisher  | NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program |
| hasVersion  | 1 |
| license  | CC0 1.0 Universal |
| maturity level  | mature |

--------


## AUTHORS

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2024-02-02|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | Pending |2024-02-02|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2024-02-02|
|Matt Galaska	|Ocean Molecular Ecology, NOAA PMEL|	0000-0002-4257-0170	|2024-02-02|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2024-02-02|


-------------

## RELATED PROTOCOLS

| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE|
| ------------- | ------------- | ------------- | ------------- |
| Environmental DNA (eDNA) COI metabarcoding Illumina MiSeq NGS PCR Protocol V2 | https://github.com/MBARI-BOG/MBON-Protocols/blob/main/eDNA_COI_PCR_V2.md | V2 | 2018-03-20 |



---
# BACKGROUND

## Summary

This protocol is for amplifying the cytochrome c oxidase subunit I (COI) mitochondrial gene in eukaryotes. The primers (forward: mlCOIintF, reverse: HCO2198) were first presented in [Leray et al. 2013](https://doi.org/10.1186/1742-9994-10-34) (forward) and [Folmer et al. 1994](https://www.researchgate.net/publication/15316743_DNA_primers_for_amplification_of_mitochondrial_Cytochrome_C_oxidase_subunit_I_from_diverse_metazoan_invertebrates#fullTextFileContent) (reverse). The HCO2198 primer used in this protocol has 7 fewer degenerate base pairs than the jgHCO2198 primer used in Leray et al. 2013. The target amplicon size is 313 base pairs.

This primer set targets metazoan organisms (e.g., molluscs, arthropods, and vertebrates). Important note, this primer also amplifies non-target organisms including single-celled phytoplankton (e.g., dinoflagellates, diatoms, and haptophytes). 

The amplification presented here is intended as the first of a two-step PCR protocol for Illumina Nextera Unique Dual Index sequencing library preparation. Our written protocol does not include the second PCR step in which sample-specific barcodes are attached.

## Method description and rationale

This protocol was chosen because it is widely and historically used in marine eDNA time series by the Monterey Bay Aquarium Research Institute (MBARI), a leader in the field of eDNA research and an important partner in the Marine Biodiversity Observation Network (MBON) and West Coast Ocean Biomolecular Observing Network (WC-OBON). Our protocol uses the same primers, polymerase, and thermocycling conditions as MBARI and MBON. This amplification protocol is accessible to most molecular biology labs.

## Spatial coverage and environment(s) of relevance

This protocol has been used to amplify extracted DNA from filtered sea water samples taken from Northeastern Pacific coastal stations off the western coast of North America (primarily off California, Oregon, Washington,and Alaska).

## Personnel Required

One person with molecular biology experience.

## Safety

This protocol does not involve any hazardous chemicals, although standard precautions including wearing PPE should be taken to avoid skin and eye exposure to chemical reagents.

## Training requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

## Time required to execute the procedure

PCR preparation and running the PCR protocol for a single 96-well plate takes 3.5 hours. Additional plates can be run simultaneously without greatly increasing the time required. 

-----
# EQUIPMENT


| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment**|
|Pipetter: 1-10 μl|Pipetman P10L|Gilson|1|Can be substituted with any accurate pipettor.|
|Pipetter: 20 - 200 uL	|Pipetman P200L|Gilson|	1|Can be substituted with any accurate pipettor.|
|Pipetter: 100-1000 uL	|Pipetman P1000	|Gilson	|1|Can be substituted with any accurate pipettor.|
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted.|
|Thermocycler|Veriti 96-well thermal cycler |Applied Biosystems| 1|	Can be substituted.|
| Mini-centrifuge | Personal mini centrifuge  | BioExcell | 1 | Can be substituted with generic, but needs to fit 1.5-2.0 mL tubes. |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic. |
| Plate spinner | [Salad spinner]( https://doi.org/10.3390/mps3020041) | Cuisinart | 1| Can be substituted with generic or plate centrifuge. |
| Foil roller | Rubber roller | Generic | 1 ||
| PCR cooler rack | PCR cooler 0.2-0.5 mL | Eppendorf | 1 | Can be substituted with generic.|
| 1.5 mL tube cooler rack | Benchtop cooler | Thermo Scientific  | 1 | Can be subsituted with generic. Store in the fridge to avoid refreezing reagents. |
| 2 mL tube rack | Microcentrifuge tube rack | VWR | 1 | Can be substituted with generic. |
| 0.2 mL PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Fisher Scientific | 1 | Can be substituted with generic. |
| **Consumable equipment** |
| 1000 μL pipette tips | TipOne RPT filter tips 1000 μL XL graduated | USA Scientific | 4 | Can be subsituted with generic. Must be sterile and filtered. |
| 200 μL pipette tips  | TipOne RPT filter tips 200 μL graduated| USA Scientific |4 | Can be subsituted with generic. Must be sterile and filtered. |
| 10 μL pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be subsituted with generic. Must be sterile and filtered. |
| PCR plates | Twin.tec LoBind PCR plates, semi-skirted (96-wells)| Eppendorf | 1 | Must be DNA low retention if subsituted. |
| PCR aluminum foil | Adhesive sterile PCR foil seals | VWR| 1 | Can be subsituted with generic. Must be sterile. |
| 2 mL tubes | Snap cap DNA LoBind 2.0 mL tubes, PCR-clean| Eppendorf |5 | Can be substituted with generic. Must be sterile. |
| 1.5 mL tubes | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean| Eppendorf |2 | Can be substituted with generic. Must be sterile. |
| Kimwipes | Delicate task wipes | Kimtech | 5 | Can be substituted with similar lint-free delicate task wipe.|
|**Optional Equipment**|||			
|Repeater Pipetter: 10-300  μL|E1-ClipTip electronic single channel pipette, 10-300 μL|ThermoFisher|	1|Not required but reduces protocol time.|
| 300 μl repeater pipette tips | ClipTip 300 filtered sterile tips| Thermo Scientific| 2| Must fit repeater pipette. Must be sterile and filtered. |
|8-channel multichannel pipetter: 1-10 μL| Pipetman Multichannel P8X10|	Gilson|	1|Not required but reduces protocol time.|
| **Chemicals** |
| PCR master mix 2x|AmpliTaq Gold Fast PCR master mix | Applied Biosystems | 1300 μl per plate | Stored at 4°C. |
| Forward primer | Custom oligo | IDT |104 μl per plate|Store at -20°C.|
| Reverse primer| Custom oligo | IDT | 104 μl per plate |Store at -20°C.
| Nuclease free water | UltraPure DNase/RNase-free distilled water | ThermoFisher | 884 μl per plate| Store 1.5 mL aliquots at 4°C.|
| Positive control| gBlocks HiFi Gene Fragments | IDT | 2 μl per plate| Store at -20°C |
| 70% EtOH | Molecular grade ethanol| Generic | 20 mL | |
| 10% bleach| Hypochlorite bleach |Clorox| 10 mL | Recommend remaking every ~5 days as it decomposes quickly at 10% concentration. |

------
# STANDARD OPERATING PROCEDURE

### Preparation


**Before PCR Setup:**

1. Sterilize workspaces and durable equipment, including pipettes within the BSC with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
4. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes. [NOAA-PMEL-OME-Sterilization-Protocol pending] 
5. Run the UV light in the BSC for 30 minutes before starting work.

### PCR

**Primer Sequences without Adapters**: PCR primer sequences (**target sequence bolded**)

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
| Leray F / mICOlinF| Forward | **GGWACWGGWTGAACWGTWTAYCCYCC** |
| Folmer R / HCO2198 | Reverse | **TAAACTTCAGGGTGACCAAAAAATCA** |

\
**Primer Sequences Used**: PCR primer sequences with Illumina Adapters 
(Adapter seqeuence + **target sequence bolded**)
| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ------------ | --- | ----- |
| Leray F / mICOlinF| Forward | TCGTCGGCAGCGTCAGATGTGTATAAGAGACAG**GGWACWGGWTGAACWGTWTAYCCYCC** |
| Folmer R / HCO2198 | Reverse | GTCTCGTGGGCTCGGAGATGTGTATAAGAGACAG**TAAACTTCAGGGTGACCAAAAAATCA** |

\
**Reaction Mixture**: PCR reagents, volumes, initial and final concentrations

| Reagent | Volume (μL) per plate | Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ------ | ----- | ----- |----- |
| AmpliTaq Gold Fast PCR master mix |1300 | 12.5 | 100% |50% |
| Forward Primer |104  | 1|5 μM |0.2 μM |
| Reverse Primer |104| 1|5 μM |0.2 μM |
| Nuclease-Free Water |884| 8.5 | N/A|N/A |
| Template DNA|-| 2 | 100%|8% |
| **Total**| **2392** | **25** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells),  each reagent volume was multipled by 104 (8 extra sample volumes accounts for pipetting error) when preparing the final master mix.

**PCR Cycling Program**: 

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|10 min|	1X
|**Touchdown Cycling**|(changes -1°C per cycle)|||
|Denaturation|	94°C|	10 sec|	16X|
|Annealing|	Start @ 62°C <br> decrease by -1°C each cycle <br>end @ 47°C|	30 sec	|16X|
|Extension	|68°C	|60 sec	|16X|
|**Normal Cycling**||||
|Denaturation	|94°C|	10 sec|	25X|
|Annealing	|46°C	|30 sec	|25X|
|Extension	|68°C	|60 sec	|25X
|Final extension	|7°C	|10 min	|1X|
|Hold	|4°C	|∞	||

**Step-by-Step Instructions:**

*When possible, PCR set-up should be carried out in a separate space from where the thermocyclers are located and post-PCR processing is performed. No equipment should be shared.*

1. Set out primers and positive control to thaw.
2. Vortex and spin down thawed positive control, primers, and nuclease free water. Then tap/flick AmpliTaq rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make final master mix, as denoted in above in reagent mixture table.
4. Set out template DNA to thaw if frozen.
5. Aliquot 23 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2 μL DNA template to each well, but reserve two wells for the positive control and a no template control (NTC). 
8. Add 2 μL of the positive control and 2 μL of nuclease-free water for the NTC.
9. Seal the PCR plate with foil.
10. Spin down the plate, and then transport in cooler blocks before placing in thermocycler.
14.  Run thermocycler protocol.


## Quality control

1. Plates should be removed from the thermocycler  after the run completes and stored at 4°C until run on a gel. Storing the PCR product at -20˚C is ideal for 1-6 month term storage, while -80˚C is ideal for long-term storage.
2. Run gel visualization to confirm successful PCR. [NOAA-PMEL-OME-GelVisualization-Protocol pending]

**Positive Control**

A positive control is used in every PCR run to verify success of the PCR reaction. In place of template DNA, 2 μL of positive control diluted to 10^3 copies/µL is used. One well per plate is alotted for the positive control. The positive control used for COI is the extinct Moa (*Dinornis giganteus*). The reference mitogenome used to develop the positive control sequence can be found on Genbank [(Accession AY016013.1)](https://www.ncbi.nlm.nih.gov/nuccore/AY016013.1). 

|Positive Control Sequence|
|--------------------------|
|CCACTATTGAAGCTGGAGCAGGAACAGGATGAACAGTATACCCCCCACTAGCCGGAAACCTGGCTCATGCGGGTGCCTCCGTGGACCTTACTATCTTCTCACTCCACCTGGCCGGTGTATCCTCCATCCTAGGAGCTATCAACTTTATTACCACAGCAATTAACATAAAACCTCCAGCCCTCTCACAATACCAAACTCCATTATTTGTATGATCCGTACTAATCACTGCCATCCTCCTACTACTATCCCTCCCAGTACTTGCTGCCGGTATCACTATACTGCTCACAGACCGGAACCTAAACACCACATTCTTCGACCCTGCTGGAGGAGGGGACCCTATTCTATACCAACACCTCTTCTGATTTTTTGGTCACCCTGAAGTTTACATTCTCATTCTTCCTGGCT|


**Negative Control**

Nuclease-free water is used as a no template control when setting up each PCR plate. One well per plate is alloted to a no template control. NTCs should be run in addition to both field blanks and extraction blanks.

## Basic troubleshooting guide

**Issue 1**: Streaking is observed for sample wells in gel but positive control is a normal band. 

**Solution**: Dilute the DNA sample to a 1:10 dilution with nuclease-free water. If smearing continues, dilute the DNA samples to a 1:100 dilution. If the samples do not amplify under these conditions the sample likely is inhibited or has too little target DNA and is unlikely to produce results. Alternative solutions include cleaning DNA extractions with a commercial clean up kit.

**Issue 2**: No bands were observed in the PCR, including the positive control.

**Solution**: The PCR likely failed. Check reagents to confirm they were not mishandled or expired and rerun. If positive control fails again, reagents are likely compromised. 

**Issue 3**: Band observed in no template control.

**Solution**: The PCR was likely contaminated. Sterilize lab space thoroughly and rerun with new aliquots of reagents.


## ACRONYMS AND ABBREVIATIONS

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|eDNA	|environmental DNA|
|PCR| Polymerase chain reaction |
|PPE    | Personal protective equipment |
|EtOH| Ethanol|
|COI / CO1 / cox1 |Cytochrome oxidase subunit I
|IDT| Integrated DNA Technologies
|NTC	|No template control
|BSC	|Biosafety cabinent
|OME	|Ocean Molecular Ecology
|PMEL	|Pacific Marine Environmental Laboratory
|NOAA|National Oceanic and Atmospheric Administration
|UW| University of Washington
|CICOES| Cooperative Institute for Climate, Ocean, & Ecosystem Studies
|MBON	|Marine Biodiversity Observation Network|
|MBARI| Monterey Bay Aquarium Research Institute|
|WC-OBON|West Coast Ocean Biomolecular Observing Network|

## GLOSSARY

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Field blank  | Sampling negative control. Typically distilled or reverse osmosis water run through a filter to control for contamination in the field sampling step.  |
| Extraction blank  | Extraction negative control. Typically nuclease-free water or empty filter run through the DNA extraction process to control for contamination in the DNA extraction step.  |
| No template control | PCR negative control. Typically nuclease-free water loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically a synthetic DNA strand or non-indigenous DNA extract loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |

## REFERENCES

1. Leray et al. 2013. A new versatile primer set targeting a short fragment of the mitochondrial COI region for metabarcoding metazoan diversity: application for characterizing coral reef fish gut contents. Frontiers in Zoology. 10 (34). https://doi.org/10.1186/1742-9994-10-34
2. Folmer et al. 1994. DNA primers for amplification of mitochondrial cytochrome c
oxidase subunit I from diverse metazoan invertebrates. Molecular Marine Biology and Biotechnology 3 (5): 294-299. PMID: 7881515  [Link](https://www.researchgate.net/publication/15316743_DNA_primers_for_amplification_of_mitochondrial_Cytochrome_C_oxidase_subunit_I_from_diverse_metazoan_invertebrates#fullTextFileContent)
## APPENDIX A: DATASHEETS
[Protocol Sample Sheet](https://docs.google.com/spreadsheets/d/1cVP8Pum9eyOAgBLqu9X48TsRJWtoMAENNBskbYGYz28/edit?usp=sharing)