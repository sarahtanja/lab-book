---
title: "Dual DNA & RNA Extraction #1 (extr1)"
date: 2023-01-13T00:00:00-00:00
categories:
  - lab records
toc: true
toc_label: "Table of Contents" # default: Content
toc_icon: "heart"  # corresponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc
tags:
  - DNA extraction
  - RNA extraction
---

This lab extraction follows the [Dual DNA & RNA Extraction Protocol](https://sarahtanja.github.io/lab-book/protocols/protocol-dna-rna-extraction/) with any deviations, exceptions, or notes explained in detail. 

## Samples

Samples were randomly selected for processing given constraints explained in [this RMarkdown document](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/rand-sample-processing.Rmd).

Metadata and notes are also recorded in the [extr1_21APR23.csv](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/extr1_21APR23.csv)

Key Results: 

| cryo_id | extr_date | qubit_rna_1 | qubit_rna_2 | qubit_rna3 |
| ------- | --------- | ----------- | ----------- | ---------- |
| 3-CA1a  | 21APR2023 | 12.4        | 14          | 12.4       |
| 3-Ea    | 21APR2023 | 0.0         | 0           | 0          |

- qubit_rna_1 was run by SST and NAH at 1140 on 25APR2023, Run ID 2023-04-25-110503 

- qubit_rna_2 and qubit_rna_3 were run on 2 separately prepared technical replicates by SST at 1340 on 25APR2023, Run ID 2023-04-25-133744

The exported Qubit Data file with more details can be found [here](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/data/QubitData_2023-04-25/QubitData_2023-04-25_13-41-07.csv)



> HAVE NOT YET CHECKED DNA! WAITING FOR DNA ASSAY KIT.... will update



Samples are stored in -80C 'sucks' freezer in respective `Eluted-DNA` or `Eluted-RNA` wax freezer boxes with the labels:

| Freezer    | Wax-Box    | Vial                                              |
| ---------- | ---------- | ------------------------------------------------- |
| -80C sucks | Eluted-DNA | 3CA1a<br/>DNA<br/>extr1<br/>21APR23<br/>NAH + SST |
| -80C sucks | Eluted-DNA | 3Ea<br/>DNA<br/>extr1<br/>21APR23<br/>NAH + SST   |
| -80C sucks | Eluted-RNA | 3CA1a<br/>RNA<br/>extr1<br/>21APR23<br/>NAH + SST |
| -80C sucks | Eluted-RNA | 3Ea<br/>RNA<br/>extr1<br/>21APR23<br/>NAH + SST   |



## Prepare Buffers

- [x] Used the 10-prep kit, DNA/RNA Wash Buffer (D7003T) supplied ready-to-use

- [x] Reconstitute `lyophilized DNase I` with `DNase/RNase-Free Water` and mix by gentle inversion. Use immediately or store frozen aliquots. 

  - [ ] 50-prep, add 275 µl water 
  - [x] 10-prep, add 55 µl water 

- [x] Reconstitute `lyophilized Proteinase K` at 20 mg/ml with `Proteinase K Storage Buffer` and mix by vortexing. Use immediately or store frozen aliquots. 

  - [ ] 50-prep, (60 mg), add 3.12 ml buffer 
  - [x] 10-prep, (5 mg), add 0.26 ml (260 ul) buffer 

- [x] To prepare a 1X solution of `DNA/RNA Shield™`, add an equal volume (5mL for the whole solution) of `nuclease-free water` (not provided) to the `DNA/RNA Shield™` (2X concentrate) (1:1) and mix with a quick pulse on the vortexer.

## Extraction Steps

### Mechanically Lyse Samples

- [x] Take [dry-ice](#dry-ice) cooler to -80 freezer,  pull out frozen samples and place them in the dry-ice cooler. Work quickly and carefully to sort through the vials and select the ones that you are working with. Nest the selected sample vials in the dry ice, and return the rest back to the -80 freezer. Bring working samples on dry-ice back to the lab bench.

- [x] Don cryo-gloves over nitrile gloves and ⚠️carefully⚠️ dispense a small amount (no more than 1L) of liquid nitrogen (LN2) into the transfer thermos. **Everyone working with LN2 should have taken the Liquid Nitrogen Online Safety Course found [HERE](https://www.ehs.washington.edu/training/liquid-nitrogen-safety)**

- [x] One at a time, grind each sample with mortar & pestle on LN2 -

    1. ⚠️carefully⚠️ pour a small amount of LN2 into a [sterilized](#sterilize) mortar
    
    2. Using  [sterilized](#sterilize) forceps, pluck out coral fragments from the cryo vial and place in the mortar until you have as much material as about the size of a single shelled peanut. 
    

![ pirates-jack-sparrow-in-davy-jones-locker-with-a-single-peanut]https://64.media.tumblr.com/tumblr_lzjqxk7t0K1qjhjdwo1_500.gifv
    
3. Pestle the coral fragment until it is ground to a powder. Work quickly to ensure the sample remains frozen. Add more LN2 when it evaporates from the mortar. 

   ![]({{ site.url }} {{ base.url  }}\assets\thesis-labwork\PXL_20230421_213402619.jpg)

This step is challenging! LN2 evaporates very quickly and had to  be replenished multiple times. We did this best  with two people (NAH to grind, SST to carefully dispense LN2). The coral is also very hard and prone to 'squirting out' from under the pestle, much like the gif of the peanut above! This happened to sample 3-Ea, and half of the material shot out of the mortar and ended up on the floor, resulting in less starting material. This could be a reason why 3-Ea had 'out of range, too low' result for Qubit!
{: .notice--warning}

- [x] Use  [sterilized](#sterilize) scoopula to transfer the sample powder to its correspondingly labelled [bead bashing tube](https://www.zymoresearch.com/collections/lysis-tubes/products/zr-bashingbead-lysis-tubes-0-1-0-5-mm). *We made a small funnel made from lab weigh-paper and label tape to try and make this easier.*

![mortar-transfer-diagram]({{ site.url }}{{ site.baseurl }}/assets/images/funnel.png)

Finely ground powder melts fast and the cold from the LN2 means that all the moisture in the lab is condensing on the sample. As soon as it is removed from the mortar by the scoopula it begins to melt, condense water vapor, and turn into a sticky booger! It doesn't slide nice and dry down the paper funnel. We had to tamp it vigorously to get it into the bead bashing tube. We will probably modify protocol next time to first chill the scoopulas on dry-ice, and use a small metal funnel chilled on dry-ice, to keep the powder cold during the transfer from the mortar to inside the bead bashing tube. 
{: .notice--warning}

- [x] Once sample powder is in the bead bashing tube,  quickly added `750uL` of `DNA/RNA Sheild` to the bead bashing tube & inverted to mix



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

