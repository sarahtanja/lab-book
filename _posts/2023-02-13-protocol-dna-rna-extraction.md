---
title: "Dual DNA & RNA Extraction Protocol"
date: 2023-01-13T00:00:00-00:00
categories:
  - protocols
toc: true
toc_label: "Table of Contents" # default: Content
toc_icon: "heart"  # corresponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc
tags:
  - DNA extraction
  - RNA extraction
---



The aim of this protocol is to take coral fragments that have been snap-frozen in liquid nitrogen and extract both DNA for downstream archaea & bacteria microbiome 16S Microbiome Sequencing and RNA for downstream coral-host tissue Tag-seq or RNA-seq analysis. 

>  In plain, I want to answer 'who is there?' regarding the bacterial community, and 'what is the coral doing?' regarding gene expression. 

The benefits of doing DNA and RNA extraction together are that it saves time, money, & sample material. It also facilitates paired sample analysis, where each data point in one dataset is uniquely paired to a data point in the second dataset because we are making duplicate measurements on the *same sample*. 

The challenge is lysing the sample enough to get the bacterial DNA (busting open all those layers of cell membranes!) and retaining host (coral) RNA integrity. 

This protocol relies heavily on the Zymo Research [Protocol PDF](https://files.zymoresearch.com/protocols/_d7003t_d7003_quick-dna-rna_miniprep_plus_kit.pdf) & URI Putnam Lab Emma Strand's notebook post on '[Zymo-Duet-RNA-DNA-Extraction-Protocol](https://emmastrand.github.io/EmmaStrand_Notebook/Zymo-Duet-RNA-DNA-Extraction-Protocol/)', with a few alterations suggested by Zymo tech on [March 28th 2023](https://sarahtanja.github.io/lab-book/blog/daily-log/#28-mar-2023-t) regarding [optimized lysis protocols](https://files.zymoresearch.com/documents/bead_beating_short_protocol_tables.pdf).

📞Zymo is very responsive to phone calls! Any questions on the kit you can call **888-882-9682** and reference catalog number **D7003** to ask technical questions galore. 



## Advanced Prep

### Biological Sample Info

- liquid-nitrogen snap-frozen ~3cm *Montipora capitata* coral fragments held at -80°C

### Background

👀 WATCH ➡️ [Bumbling Biochemist 'Spin column purification of nucleic acids'](https://www.youtube.com/watch?v=Y_-xP60SYe0) on YouTube

👀 WATCH ➡️ [Bumbling Biochemist 'tips for working with DNA/RNA spin columns'](https://www.youtube.com/watch?v=MBnuae5aWg4) on YouTube

📖 READ ➡️  [CAN CORAL DNA MEASURE OCEAN HEALTH?](https://biolinkk.com/posts/can-coral-dna-measure-ocean-health/) on biolinkk

### Materials List

####  *Extraction Kit* 

- [ ] Zymo Research [Quick-DNA/RNA Miniprep Plus Kit](https://www.zymoresearch.com/products/quick-dna-rna-miniprep-plus-kit) (50 prep D7003, or 10 prep D7003T)*1 prep = 1 sample that results in DNA in one tube, and RNA in another*
  *includes:*
  - [ ] DNA/RNA Lysis Buffer
  - [ ] DNA/RNA Prep Buffer
  - [ ] DNase/RNase-Free Water
  - [ ] DNase I2 (lyophilized... aka freeze-dried)
  - [ ] DNA Digestion Buffer
  - [ ] DNA/RNA Shield (2X concentrate)
  - [ ] PK Digestion Buffer
  - [ ] Proteinase K3 (lyophilized... aka freeze-dried) 
  - [ ]  Proteinase K3 Storage Buffer
  - [ ] Spin-Away Filters
  - [ ] Zymo-Spin IIICG Columns
  - [ ] Collection Tubes
- [ ] [ZR BashingBead  Lysis 2mL Tubes with 0.1 & 0.5mm beads](https://www.zymoresearch.com/collections/lysis-tubes/products/zr-bashingbead-lysis-tubes-0-1-0-5-mm), 1 per prep
- [ ] [DNase/RNase/nuclease-Free Tubes](https://www.zymoresearch.com/products/dnase-rnase-free-tubes), 3 per prep
- [ ] [DNase/RNase-Free Tubes](https://www.zymoresearch.com/products/dnase-rnase-free-tubes), 3 per prep

#### *PPE*
- [ ] nitrile gloves
- [ ] liquid-nitrogen & cold storage handling gloves
- [ ] lab coats

#### *Lab Equipment*
- [ ] [ethanol-proof lab markers](https://www.amazon.com/dp/B09L3Q99WL/ref=sspa_dk_hqp_detail_aax_0?psc=1&sp_csd=d2lkZ2V0TmFtZT1zcF9ocXBfc2hhcmVk&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyWUpaVTc1M0pRMVImZW5jcnlwdGVkSWQ9QTAxMTgzODBJOFI3QlZFQ0pKQUsmZW5jcnlwdGVkQWRJZD1BMDc2MTE0M1ExRUdBSkEwOFBBRiZ3aWRnZXROYW1lPXNwX2hxcF9zaGFyZWQmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

- [ ]  [1.5mL microcentrifuge tube racks](https://www.southernlabware.com/80-well-micro-tube-racks-assorted-5-pacl.html?gclid=CjwKCAiAjPyfBhBMEiwAB2CCIkxZXHoOz72MNKvsWFcKscbsG8H5wIyMEw974wfKSvbU2W5a4Tk2IRoCBtEQAvD_BwE) 

- [ ] lab mortar & pestle sets

- [ ] lab label tape

- [ ] centrifuge

- [ ]Beckman Coulter Microfuge 16](https://www.beckman.com/landing/ppc/cent/benchtop/microcentrifuges?utm_source=google&utm_medium=cpc&utm_term=microcentrifuge&gclid=CjwKCAjw586hBhBrEiwAQYEnHYq-F4WNopG5rWYG4Bb0YjPlfXL7pVCESNmTwqyT6Cgxty-Si8AAdhoC8I0QAvD_BwE) 
  
- [ ] mortexer / homogenizer

  - [Mortexer Vortex Mixer](https://www.southernlabware.com/mortexertm-vortex-mixer-115v.html?gclid=CjwKCAjw586hBhBrEiwAQYEnHZGNGUTMUHNWEHBx5r2Ig9BZSuRVSnvE2_OV6n0mGga5fqV8DPcjfRoCsNoQAvD_BwE) with included Multi-Head to hold 8 microcentrifuge tubes (this is what we have)

    ...OR...

  - Vortex Genie 2 with [Horizontal Microtube Holder](https://www.zymoresearch.com/products/horizontal-microtube-holder) (recommended by [Zymo optimized lysis protocols](https://files.zymoresearch.com/documents/bead_beating_short_protocol_tables.pdf))

- [ ] liquid-nitrogen (stored in dewer or tank)

- [ ] small liquid-nitrogen thermos (1L)

- [ ] small cooler (for dry ice and samples)

- [ ] ##### dry-ice 

  - Biochemistry Store in hallway adjacent to Room J-014, Health Sciences Building
  
  - The entrance can be found at the [Health Sciences Building loading dock](https://goo.gl/maps/hYnYcm6EiTHGEE4SA) across NE Boat St. from Saint Bread, NE of the Ocean Sciences Building 
  - must have UW Husky Card to fob-activate doors leading from loading dock and interior hall
  - bring well-insulated foam or hard cooler. First weigh empty cooler, add dry-ice, then weigh again and record final weight, budget#, PI, and name on the clipboard near the dry-ice station
  - probably best to drive rather than carry a cooler of dry-ice for three blocks
  

#### *Reagents* 

- [ ] nuclease free ([DEPC-treated](https://www.thermofisher.com/order/catalog/product/4387937#:~:text=DEPC%2Dtreated%20water%20is%20autoclaved,%2C%20exonuclease%2C%20and%20RNase%20activity.)) autoclaved water
- [ ] 95% (190 proof) - 99.5% (200 proof) ethanol 

#### *Sterilizing* 

- [ ] 10% bleach in spray-bottle
- [ ] 70% ethanol in spray-bottle
- [ ] DI water in spray-bottle
- [ ] RNase away in spray-bottle
- [ ] Kimwipes/paper towels

#### *Pipettes & Tips*

  - [ ] P10 + filtered tips *DNase/RNase free*
  - [ ] P100 + filtered tips *DNase/RNase free*
  - [ ] P1000 + filtered tips *DNase/RNase free*
  - [ ] P5000  + tips (for buffer prep)

### Randomize Sample Processing

Make sure to randomize which samples are processed in each batch to reduce 'batch effects'!

See ['Randomize Sample Processing'](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/rand-sample-processing.Rmd) script as an example.

Think about how many samples you can process at once, and your kit, centrifuge, and homogenizer capacity.



## Lab Setup

### Sterilize 

1. Don lab coat 🥼 & tie hair back , glove up 🧤

2. Spray down `benchtop`, `microcentrifuge tube racks`, `pipettes`, and `pipette tip boxes` with: 

   - `10% bleach` in spray-bottle, then wipe with Kimwipe

   - `DI water` in spray-bottle, then wipe with Kimwipe

   - `70% ethanol`in spray-bottle, then wipe with Kimwipe

3. Spray down `mortars & pestles` , `scoopulas`, and `forceps` with:

   - `10% bleach` in spray-bottle, then wipe with Kimwipe

   - `DI water` in spray-bottle, then wipe with Kimwipe

   - `70% ethanol` in spray-bottle, then wipe with Kimwipe
   - `RNase away` in spray-bottle, then wipe with Kimwipe

4. Spray Kimwipe with `RNase away` and wipe down equipment buttons/handles/surfaces that may have been touched by ungloved hands

5. Spray `RNase away`on gloves and rub hands together

### Arrange Lab Bench

This extraction protocol can be split into two main phases: 1. lysing and 2. purification. I setup the lab bench with each phase occupying a station on the bench, with materials used in each phase arranged accordingly. Make sure you have trash, pipette disposal, and waste disposal containers within easy reach of the workstation.

Lysing Station

- liquid nitrogen dewer
- dry-ice bucket with samples

- mortars & pestles
- Mortexer

Purification Station

- centrifuge
- microcentrifuge tube racks 

### Label Tubes

The samples originate from their 1.5mL cryo-vials, which are labelled with their cryo_id. Since it's important to keep track of which samples were extracted using the same kit, the same reagents, the same day, etc.  for batch effects, I use extraction IDs (extr1, extr2, extr3 , etc.) to label samples that were processed together. 

Each sample will need the following  7 tubes labelled:

![label-7-tubes-diagram]({{ site.url }}{{ site.baseurl }}/assets/images/label-tube-diagram.jpeg)

You can also label an additional qubit tube if you are moving straight from extraction to quantification. 

>  Only thin-wall, clear 0.5 mL PCR tubes are appropriate for use in the Qubit® fluorometer. Acceptable tubes include **[Qubit® assay tubes](https://www.thermofisher.com/order/catalog/product/Q32856?gclid=CjwKCAjwuqiiBhBtEiwATgvixAYKxw1FwdqIxIiPSxZ-ngW738s6bl94L2cdLCFjXfosHgMX1hyAShoCv9cQAvD_BwE&ef_id=CjwKCAjwuqiiBhBtEiwATgvixAYKxw1FwdqIxIiPSxZ-ngW738s6bl94L2cdLCFjXfosHgMX1hyAShoCv9cQAvD_BwE:G:s&s_kwcid=AL!3652!3!529745253294!p!!g!!qubit%20tubes!7851124045!80648205054&cid=bid_pca_aqb_r01_co_cp1359_pjt0000_bid00000_0se_gaw_bt_pur_con) (Invitrogen Cat.** **no.** **Q32856, 500 tubes) or [Axygen PCR-05-C tubes](https://us.vwr.com/store/product?keyword=10011-830)(VWR, part number 10011-830)**.

The qubit tube should only be labelled on the top; the sides should be clear so that the qubit fluorescence can be  read without impedance.

The intermediate tubes and qubit tubes should be labelled with the `cryo_id` & `extraction_id` , such as: `1Ea extr1`. 

The **FINAL** tubes should be labelled with `cryo_id`, `DNA/RNA`, `extraction_id`, `date (ddMMMyy)`, & `initials`, such as:

```
1Ea
RNA
extr1
10APR23
SST
```
⚠️**Important Notes! ⚠️**

- **Use [ethanol-proof lab markers](https://www.amazon.com/dp/B09L3Q99WL/ref=sspa_dk_hqp_detail_aax_0?psc=1&sp_csd=d2lkZ2V0TmFtZT1zcF9ocXBfc2hhcmVk&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyWUpaVTc1M0pRMVImZW5jcnlwdGVkSWQ9QTAxMTgzODBJOFI3QlZFQ0pKQUsmZW5jcnlwdGVkQWRJZD1BMDc2MTE0M1ExRUdBSkEwOFBBRiZ3aWRnZXROYW1lPXNwX2hxcF9zaGFyZWQmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl) to label tubes** *(ethanol is added to the green spin away collection tube)*
- **Label collection tubes, not filters!**
- **Always wear lab gloves that have been sterilized before handling tubes!**
- **Shake tubes out of their bags onto sterilized surface, don't 'reach in' (this reduces potential contamination)**

### Prepare Buffers 

- [ ] If using the 50-prep kit (D7003), add `96 ml 100% ethanol (104 ml 95% ethanol)` to the 24 ml DNA/RNA Wash Buffer concentrate. 

  ​		*If using the 10-prep kit, DNA/RNA Wash Buffer (D7003T) is supplied ready-to-use and does not require the addition of ethanol.*
- [ ] Reconstitute `lyophilized DNase I` with `DNase/RNase-Free Water` and mix by gentle inversion. Use immediately or store frozen aliquots. 

  - [ ] 50-prep, add 275 µl water 
  - [ ] 10-prep, add 55 µl water 

- [ ] Reconstitute `lyophilized Proteinase K` at 20 mg/ml with `Proteinase K Storage Buffer` and mix by vortexing. Use immediately or store frozen aliquots. 

  - [ ] 50-prep, (60 mg), add 3.12 ml buffer 
  - [ ] 10-prep, (5 mg), add 0.26 ml (260 ul) buffer 

- [ ] To prepare a 1X solution of `DNA/RNA Shield™`, add an equal volume (5mL for the whole solution) of `nuclease-free water` (not provided) to the `DNA/RNA Shield™` (2X concentrate) (1:1) and mix with a quick pulse on the vortexer.

## Extraction Steps

### Grind/Homogenize: Mortar & Pestle Samples

1. Take [dry-ice](#dry-ice) cooler to -80 freezer,  pull out frozen samples and place them in the dry-ice cooler. Work quickly and carefully to sort through the vials and select the ones that you are working with. Nest the selected sample vials in the dry ice, and return the rest back to the -80 freezer. Bring working samples on dry-ice back to the lab bench.

2. Don cryo-gloves over nitrile gloves and ⚠️carefully⚠️ dispense a small amount (no more than 1L) of liquid nitrogen (LN2) into the transfer thermos. **Everyone working with LN2 should have taken the Liquid Nitrogen Online Safety Course found [HERE](https://www.ehs.washington.edu/training/liquid-nitrogen-safety)**
3. Grind each sample with mortar & pestle on LN2 -

   1. ⚠️carefully⚠️ pour a small amount of LN2 into a [sterilized](#sterilize) mortar
   2. Using  [sterilized](#sterilize) forceps, pluck out coral fragments from the cryo vial and place in the mortar until you have as much material as about the size of an M&M (roughly a 16mm diameter sphere). Material amount does not have to be precise. 
   3. Pestle the coral fragment until it is ground to a powder. Work quickly to ensure the sample remains frozen. Add more LN2 when it evaporates from the mortar. This step is challenging! LN2 evaporates very quickly and must be replenished multiple times. 


### Lyse: Bead-Bash Samples

1. Use  [sterilized](#sterilize) scoopula to transfer the sample powder to its correspondingly labelled [bead bashing tube](https://www.zymoresearch.com/collections/lysis-tubes/products/zr-bashingbead-lysis-tubes-0-1-0-5-mm)

2. Aim to transfer 500uL of volume to each tube 
3. Add 500uL of `DNA/RNA Shield` to each 2mL (0.1 - 0.5mm) bead-bashing tube with powdered sample and vortex to ensure powder is submersed in `DNA/RNA Shield`
4. Set bead-bashing tubes in Mortexer and vortex at high speed for 40 minutes

### Proteinase-K Digestion

1. After bead bashing tubes are ['intensely bubbly'](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Larvae-Ex-Protocol/#:~:text=Tubes%20after%20vortexing%20are%20intensely%20bubbly)

2. To tamp down bubbles, centrifuge in the mini-centrifuge for 1-2 minutes
3. Add Proteinase K & Buffer
   - Add the appropriate volume of  Pro K buffer and Proteinase K (Proteinase K is stored in the -20 after being reconstituted)
   - (10:1 ratio of sample:digestion buffer) & (2:1 ratio of digestion buffer:Proteinase K)
   - For tubes with 500ul add:
     - 50ul pro k buffer
     - 25ul proteinase K
   - If you have tubes with a larger volume you can scale up the volumes (ex for 700ul, you would use 70ul buffer and 35ul pro k)
4. Let incubate at room temperature for 2 hours

OR.. alternate protocol according to Putnam Lab Members [Kevin Wong Porites Extractions](https://kevinhwong1.github.io/KevinHWong_Notebook/20201027-DNA-RNA-Extractions-Porites-July-Bleaching-Experiment/) and  [M.E. Schedl's Porites Extractions ](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/porites-zymo-rna/)...

> 2. Add 500uL of RNA/DNA shield into each bead bashing tube
> 3. Using sterile forceps, add 0.25mm of coral fragment directly to bead bashing tube
> 4. Vortex at max speed for 2 minutes
> 5. Remove 400 μl of the supernatant and transfer to a new centrifuge tube
> 6. Centrifuge at 9000 rcf for 3 minutes
> 7. Transfer 300 μl supernatant to a new centrifuge tube and discard the old tube with pellet
> 8. Add 30 μl of Proteinase K digestion buffer (10:1 ratio of sample:digestion buffer), and > 15 μl of Proteinase K (2:1 ratio of digestion buffer:Proteinase K) to each sample
> 9. Vortex to spin down
> 10. Add 345 μl of lysis buffer



<span style="color:#E4D00A">some *citrine* text</span>
<span style="color:#93C572">some *pistachio* text</span>

<span style="background-color:#E4D00A">This text is highlighted in citrine.</span>
<span style="background-color:#93C572">This text is highlighted in pistachio.</span>

### Purify DNA & RNA

## End Products

The end products are two 1.5mL vials per sample that contain:

1. 100ul of DNA in nuclease-free water 
2. 100ul of RNA in nuclease-free water. 

Place these vials on ice and for RNA proceed with [Qubit RNA Broad Range Protocol](https://sarahtanja.github.io/lab-book/protocols/protocol-qbit/) , for DNA proceed with Nanodrop DNA 

OR, to continue lab-work later, 

 Place them in a wax freezer box, label the box, and freeze them in the -80C. 

