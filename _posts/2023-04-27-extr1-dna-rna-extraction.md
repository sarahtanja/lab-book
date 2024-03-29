---
title: "Dual DNA & RNA Extraction #1 (ex1)"
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

Notebook post detailing lab-work conducted on April 25th, 2023 (4/25/2023)

This lab extraction follows the [Dual DNA & RNA Extraction Protocol](https://sarahtanja.github.io/lab-book/protocols/protocol-dna-rna-extraction/) with any deviations, exceptions, or notes explained in detail.

## Samples

-   3-CA1a

-   3-Ea

Samples were randomly selected for processing given constraints explained in [this RMarkdown document](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/rand-sample-processing.Rmd).

Metadata and notes are also recorded in the [extr1_21APR23.csv](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/extr1_21APR23.csv)

## Key Results

| cryo_id | extr_date | qubit_rna_run_date | qubit_rna_1 | qubit_rna_2 | qubit_rna3 | qubit_dna_run_date | qubit_dna_1 | qubit_dna_2 | qubit_dna_3 |
|---------|-----------|--------------------|-------------|-------------|------------|--------------------|-------------|-------------|-------------|
| 3-CA1a  | 4/21/2023 | 4/25/2023          | 12.4        | 14          | 12.4       | 5/4/2023           | 72.8        | 75          | 74.4        |
| 3-Ea    | 4/21/2023 | 4/25/2023          | 0.0         | 0           | 0          | 5/4/2023           | 39          | 38.4        | 39          |

-   qubit_rna_1 was run by SST and NAH at 1140 on 25APR2023, Run ID 2023-04-25-110503

-   qubit_rna_2 and qubit_rna_3 were run on 2 separately prepared technical replicates by SST at 1340 on 25APR2023, Run ID 2023-04-25-133744

-   exported RNA Qubit Data file **(Run ID 2023-04-25-133744 & 2023-04-25-110503)** with more details can be found [HERE](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/data/QubitData_2023-04-25/QubitData_2023-04-25_13-41-07.csv)

-   qubit_dna was checked on 5/4/2023 because we were waiting for the Thermo Qubit DNA Broad Range (BR) Assay Kit to be delivered. Samples were frozen in a -80C freezer between extraction and being checked by Qubit for quantity

-   exported DNA Qubit Data file **(Run ID 2023-05-02-102849)** with more details can be found [HERE](https://github.com/sarahtanja/coral-DNA-RNA-lab-extractions/blob/main/data/QubitData_2023-05-02/QubitData_2023-05-02_10-32-16.csv)

Samples are stored in -80C 'sucks' freezer in respective `Eluted-DNA` or `Eluted-RNA` wax freezer boxes with the labels:

| Freezer    | Wax-Box    | Vial                                              |
|------------|------------|---------------------------------------------------|
| -80C sucks | Eluted-DNA | 3CA1a<br/>DNA<br/>extr1<br/>21APR23<br/>NAH + SST |
| -80C sucks | Eluted-DNA | 3Ea<br/>DNA<br/>extr1<br/>21APR23<br/>NAH + SST   |
| -80C sucks | Eluted-RNA | 3CA1a<br/>RNA<br/>extr1<br/>21APR23<br/>NAH + SST |
| -80C sucks | Eluted-RNA | 3Ea<br/>RNA<br/>extr1<br/>21APR23<br/>NAH + SST   |

#### [Sterilized Lab Bench](https://sarahtanja.github.io/lab-book/protocols/protocol-dna-rna-extraction/#sterilize)

-   used RNAse away only on gloves and items that were touching the sample (scoopula, mortar, pestle, forceps)

#### [Labelled Tubes](https://sarahtanja.github.io/lab-book/protocols/protocol-dna-rna-extraction/#label-tubes)

cryo_ID's :

-   `3-CA1a`

-   `3Ea`

#### [Prepared Buffers](https://sarahtanja.github.io/lab-book/protocols/protocol-dna-rna-extraction/#prepare-buffers)

-   Used instruction for the 10-prep kit, (D7003T)
-   Used buffers fresh, stored extra `DNase 1` and `Proteinase K` in -20C after use on 4/25/2023

## Extraction Steps

### [Pestled Samples](https://sarahtanja.github.io/lab-book/protocols/protocol-dna-rna-extraction/#grindhomogenize-mortar--pestle-samples)

![mortar-and-pestle-with-cryogloves](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/thesis-labwork/PXL_20230421_213402619.jpg)

-   `3-CA1a` pestled 1st, half of the material in the cryo vial was used. Half remains in the freezer.
-   `3-Ea` pestled 2nd, all of the material in the cryo vial was used, but half fell on the floor and had to be thrown out.
-   LN2 evaporates very quickly and had to be replenished multiple times
-   We did this best with two people (NAH to grind, SST to carefully dispense LN2)

⚠️**Warning⚠️:** The coral is very hard to pestle and prone to 'squirting out' from under the pestle, much like the gif below! Learned that it is better to leverage whole body weight above the mortar and work to crush the coral fragment like a hydraulic press. When 'attacking' sample 3-Ea at an angle, half of the material from shot out of the mortar and ended up on the floor, resulting in less starting material left to use in the mortar. **This could be a reason why 3-Ea had 'out of range, too low' result for Qubit!** {: .notice--warning}

![pirates-jack-sparrow-in-davy-jones-locker-with-a-single-peanut](https://64.media.tumblr.com/tumblr_lzjqxk7t0K1qjhjdwo1_500.gifv)

-   [x] Use [sterilized](#sterilize) scoopula to transfer the sample powder to its correspondingly labelled [bead bashing tube](https://www.zymoresearch.com/collections/lysis-tubes/products/zr-bashingbead-lysis-tubes-0-1-0-5-mm).

For this step we made small disposable funnels from lab weigh-paper and label tape to try and make this easier. Unfortunately, ⚠️**this didn't work very well!** See warning below...

![mortar-transfer-diagram](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/images/funnel.png)

**⚠️Warning⚠️:** Finely ground powder melts fast and the cold from the LN2 means that all the moisture in the lab is condensing on the sample. As soon as it is removed from the mortar by the scoopula it begins to melt, condense water vapor, and turn into a sticky booger! It doesn't slide nice and dry down the paper funnel. We had to tamp it vigorously to get it into the bead bashing tube. We will modify protocol next time to first chill the scoopulas on dry-ice, and use a small metal funnel chilled on dry-ice, with the goal being to **keep the powder cold during the transfer from the mortar to inside the bead bashing tube**. {: .notice--warning}

-   [x] Once sample powder was in the bead bashing tube, we quickly added `750uL` of `DNA/RNA Sheild` to the bead bashing tube, shook it vigorously & vortexed it to ensure the sample was submersed in `DNA/RNA Sheild`

**⚠️Warning⚠️:** In hindsight this was too much volume for the bead bashing tube! After bead beating tube was very very bubbly! Would suggest centrifuging after the bead-beating homogenization 'shaker' step prior to opening tube lid and/or use `500uL` of `DNA/RNA Sheild`, and putting it in the bead bashing tube before the sample in future extractions. {: .notice--warning}

-   [x] We then set bead-bashing tubes in the `Mortexer` and let it mix at max speed for **40 mins**

### Proteinase-K Digestion

-   [x] First added `30uL` of Proteinase-K Digestion Buffer directly to the bead bashing tube
-   [x] Then added `15uL` of Proteinase-K directly to the bead bashing tube
-   [x] Vortexed to mix
-   [x] Incubated (left to sit) at room temp for **30 minutes**

![start-of-pk-incubation](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/thesis-labwork/PXL_20230421_222407558.jpg)

![](%7B%7B%20site.url%20%7D%7D%7B%7B%20site.baseurl%20%7D%7D/assets/thesis-labwork/PXL_20230421_214010536.jpg)

## 

-   [x] Centrifuged at max-speed (16,160xg) for 30 seconds

![]()

[some *citrine* text]{style="color:#E4D00A"} [some *pistachio* text]{style="color:#93C572"}

[This text is highlighted in citrine.]{style="background-color:#E4D00A"} [This text is highlighted in pistachio.]{style="background-color:#93C572"}

### Purify DNA & RNA

## End Products

The end products are two 1.5mL vials per sample that contain:

1.  100ul of DNA in nuclease-free water
2.  100ul of RNA in nuclease-free water.

Place these vials on ice and for RNA proceed with [Qubit RNA Broad Range Protocol](https://sarahtanja.github.io/lab-book/protocols/protocol-qbit/) , for DNA proceed with Nanodrop DNA

OR, to continue lab-work later,

Place them in a wax freezer box, label the box, and freeze them in the -80C.
