---
layout: post
title: Poc ID for SM Ulithi Samples
date: '2024-04-29'
categories: Sanger
tags: [DNA, Gel, PCR, Pocillopora, mtORF]
---

#Identification of Pocillopora species from Ulithi

# Supplies

- DNA Extraction Individual Samples [Zymo Research Quick-DNA™ Miniprep plus kit extraction Cat D4068](https://github.com/hputnam/Putnam_Lab_Notebook/blob/master/images/d4068_d4069_quick-dna_miniprep_plus_kit.pdf) 
- Proteinase K [Zymo Proteinase K with Storage BufferZymo D3001-2-20](https://www.zymoresearch.com/products/proteinase-k-w-storage-buffer-set)
- PK Digestion Buffer [Zymo PK Digestion Buffer R1200-1-20](https://www.zymoresearch.com/products/pk-digestion-buffer)   
- Foward primer [FatP6.1 200µM Stock IDT](https://github.com/hputnam/Putnam_Lab_Notebook/blob/master/images/Fatp6.1_IDT_Spec_328104852.pdf) 
- Reverse primer [RORF 200µM Stock IDT](https://github.com/hputnam/Putnam_Lab_Notebook/blob/master/images/RORF_IDT_Spec_328104853.pdf)         
- Master Mix [EmeraldAmp GT PCR Master Mix RR320A](https://github.com/hputnam/Putnam_Lab_Notebook/blob/master/images/TaKaRa_Emerald_RR320A_DS.pdf)
- Gel Ladder [Zymo 5006-50 1kb ladder ready to load](https://www.zymoresearch.com/products/zr-1-kb-dna-marker)
- KapaPure Beads Fisher 50-196-5220 [Roche Diagnostics 07983280001](https://www.fishersci.com/shop/products/kapa-pure-beads-4/501965220) 

Stephane completed DNA extractions

## Nanodrop

Sample ID |  ng/µl | A260/280 | A260/230|
---|---|---| ---|
sog poci 1 |   5.0|1.87|0.24|
sog poci 2 |   3.2|1.88|0.13|
sog poci 3 |  16.2|1.96|0.32|
sog poci 4 |   1.9|3.27|0.12|
sog poci 5 |   1.6|3.05|0.10|
sohng poci 1 | 2.1|2.49|0.17|
sohng poci 2 |22.2|1.81|0.05|
sohng poci 3 | 1.6|42.64|0.01|
sohng poci 4 | 2.0|2.42|0.66|
sohng poci 5 | 1.2|9.89|0.97|


## PCR
### Prepare Reagents
Primers - [Flot et al. 2008](https://www.sciencedirect.com/science/article/pii/S1631069107003812?via%3Dihub)   
- Forward primer FatP6.1	(Added 50µl of stock 2mg/ml plus 950µl of Nuclease Free water and made 3 aliquots of ~320µl each and stored in reagent box at -20)   
- FatP6.1 (5′-TTTGGGSATTCGTTTAGCAG-3′)    
- Reverse primer RORF	(Added 50µl of stock 2mg/ml plus 950µl of Nuclease Free water and made 3 aliquots of ~320µl each and stored in reagent box at -20)     
- RORF (5′-SCCAATATGTTAAACASCATGTCA-3′)    
- Master Mix [EmeraldAmp GT PCR Master Mix]()
- ```EmeraldAmp GT PCR Master Mix is a loading-dye-added version of EmeraldAmp MAX PCR Master Mix that is optimized for great performance and convenience in both standard and high-throughput PCR applications.```
**EmeraldAmp GT PCR Master Mix was recieved warm on arrival and stored at -20°C**

### Master Mix: For 12 rxns +2 = 14 

Reagent | 1Rxn µl | 14 Rxn µl |  
---|---|---|
EmeraldAmp GT Mix (2x)| 		12.5	|	175|
F primer FatP6.1 (10µM) |	0.3	|	4.2
R primer RORF		(10µM)  |	0.3	|	4.2
DNA		|				1		| NA	
H2O			|			10.9	|	152.6
Total volume 		|	25		|	336

24µl of master mix added to each of the tubes and 1 µl of DNA. 


### Thermal Cycling Conditions 
- [94°C 60 secondes] 1 cycle
- [94°C 30 sec,53°C 30 sec, 72°C 75 sec] 30 cycles
- [72°C 5 minutes] 1 cycle
- [4°C infinity]

### PCR Gel protocol
DNA was assessed with a 1.5% agarose gel in 1x TAE buffer (1.15g agarose in 75ml of 1X TAE, Tris base, acetic acid and EDTA) run at for 30 mins at 100 V and stained with 2µl Biotium GelGreen Nucleic Acid Gel Stain (10,000X in Water Fisher Cat NC9728313). 4µl of sample or ladder were added to each well of the gel.

### Gel Results
   
![Pocillopora mtORF PCR Ulithi](https://github.com/hputnam/Putnam_Lab_Notebook/blob/master/images/20240429_Stephane_mtORF_gel.jpg?raw=true)

[Pocillopora mtORF PCR Ulithi](https://github.com/hputnam/Putnam_Lab_Notebook/blob/master/images/20240429_Stephane_mtORF_gel.jpg?raw=true)


Bands of ~1000 bp are present in all samples except the negative control for the mtORF amplicons. Sog poci 2 Sog poci 4 are faint and all bands are lighter than last Poc PCR, so I am adding a higher concentration of PCR product to the Sanger sequence prep below.  


# PCR Cleanup
- Made fresh 80% ethanol by adding 8ml 100% ethanol and 2ml of nucelase free water for 10mL total

- Added 20µl of KapaPure beads  to each of 10 PCR samples and pipetted up and down to mix and bind DNA to the beads

-  Incubated the samples at RT for 10 minutes 

- After incubation, placed the plate on the magnet for 1min until the solution was clear and removed the supernatant from every well into the waste trough

- Added 200ul of freshly made 80% EtOH to each well carefully without disturbing the beads. 

- Removed the clear supernatant from each well without disturbing the beads and discard into the waste trough.

- Repeated the 80% ethanol washes and removals for a total of 2 times. 

- While the plate was on the magnet used the p20 multichannel pipette to remove any remaining ethanol at the bottom of the wells of the plate 

- Waited ~3-5 minutes to let any residual ethanol to dry and took the plate off the magnet into a regular rack.

**Do not overdry the beads**

- Added 20ul of Zymo Elution Buffer to each well of the plate and mixed beads into resuspension by pipetting.

- Removed 20ul of clear supernatant from each well and into a new tubes

- set up a Sanger sequencing 


### Sanger sequencing setup
- set up a Sanger sequencing 

- Diluted FatP6.1 Forward primer to 3.2 µM (50µL 10µM primer + 100µL of nucelase free water)

- Added 5µl of nucease free water, 5µl from each sample, and 2µL of FatP6.1 Forward primer (at 3.2 µM) into tubes

- Labelled the tubes HP1 - HP10 and submitted to Parmacy building URI CRCF 

   
Sample ID |  Sequencing Label | mtORF Seq Outcome |
---|---|----|
sog poci 1 |   HP01_240430| P. verrucosa|
sog poci 2 |   HP02_240430| short and dirty |
sog poci 3 |   HP03_240430| P. verrucosa|
sog poci 4 |   HP04_240430| short and dirty |
sog poci 5 |   HP05_240430| dirty |
sohng poci 1 | HP06_240430| P. verrucosa|
sohng poci 2 | HP07_240430| P. verrucosa|
sohng poci 3 | HP08_240430| P. verrucosa|
sohng poci 4 | HP09_240430| P. verrucosa|
sohng poci 5 | HP10_240430| P. verrucosa|


ITS2


Plate 1 - full plate

Plate 2 - partial plate

### Master Mix: For X rxns +2 = 140 

Reagent | 1Rxn µl | 140 Rxn µl |  
---|---|---|
Phusion Master Mix (2x)| 		12.5	|	x|
F primer x (10µM) |	0.3	|	x
R primer x	(10µM)  |	0.3	|	x
DNA		|				1		| x	
H2O			|			6.9	|	x
Total volume 		|	25		|	x

21µl of master mix added to each of the tubes and 4 µl of DNA. 


### Thermal Cycling Conditions for ITS2
- [94°C 60 secondes] 1 cycle
- [94°C 30 sec,53°C 30 sec, 72°C 75 sec] 30 cycles
- [72°C 5 minutes] 1 cycle
- [4°C infinity]

### PCR Gel protocol
DNA was assessed with a 1.5% agarose gel in 1x TAE buffer (2.25g agarose in 150ml of 1X TAE, Tris base, acetic acid and EDTA) run at for 60 mins at 45 V and stained with 3µl Biotium GelGreen Nucleic Acid Gel Stain (10,000X in Water Fisher Cat NC9728313). 4µl of sample or ladder were added to each well of the gel. Sample was mixed with 1µl purple loading dye NEB
