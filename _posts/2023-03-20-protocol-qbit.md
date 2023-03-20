---
title: "Qubit RNA Broad Range Protocol"
categories:
  - protocols
tags:
  - Qubit
  - RNA extraction
toc: true
toc_label: "Table of Contents" # default: Content
toc_icon: "heart"  # corresponding Font Awesome icon name without the "fa" prefix
toc_sticky: true   # enables sticky toc
---

The aim of this protocol is to take the extracted RNA from the [Dual DNA & RNA Extraction Protocol](https://sarahtanja.github.io/lab-book/protocols/lab/protocol-DNARNAextraction/) step and check it for **integrity & quality**. This is a necessary quality check (QC) because we want to make sure the samples we send for sequencing actually have enough good RNA in them to sequence. 

The Qubit allows us to measure RNA integrity & quality (IQ) extracted in our samples.  For high-quality RNA, we're looking for long and intact strands of RNA.

## Background

![qbit ]({{ site.url }}{{ site.baseurl }}/assets/images/qbit-rna-iq.png)*infographic sourced from [Thermo Fisher](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FBID%2Fposters%2Fqubit-rna-iq-assay-fluorometric-rna-quality-assessment-poster.pdf)*

👀[Qubit RNA Broad Range (BR) Assay Kit Manual](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FLSG%2Fmanuals%2FQubit_RNA_BR_Assay_UG.pdf)

👀[Qubit RNA Broad Range (BR) Assay Kit Quick Reference](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FLSG%2Fmanuals%2FQRC10210.pdf)

## Materials List

- [ ] [Qubit Fluorometer](https://www.thermofisher.com/order/catalog/product/Q33238?SID=srch-srp-Q33238) 

- [ ] [Qubit Broad Range Assay Kit](https://www.thermofisher.com/order/catalog/product/Q10210) 

  **Warning Notice:** Standards must be stored in a refrigerator! Kits are stable for 6 months
  {: .notice--warning}

  **Danger Notice:** Kit contains DMSO 67-68-5 in the RNA dye Reagent 200X concentrate, a combustible liquid that is a mild skin and eye irritant and may be absorbed into the body through the skin. If accidental contact with skin or eye happens, rinse with plenty of water, immediate medical attention is not required (according to the [SDS](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FLSG%2FSDS%2FQ10210COMPONENTA_MTR-NALT_EN.pdf))
  {: .notice--danger}

- [ ] [Qubit Assay Tubes](https://www.thermofisher.com/order/catalog/product/Q32856?SID=srch-srp-Q32856) 

- [ ] 15mL Falcon tube (to prepare working solution) 🧪

- [ ] 0.5mL PCR tube rack

- [ ] P2 pipette + tips

- [ ] P10 pipette + tips

- [ ] P1000 pipette + tips

- [ ] nitrile gloves 🧤

- [ ] safety glasses 👓

- [ ] vortexer

- [ ] USB thumb-drive

## Protocol

### Quick-Reference Overview

![qbit ]({{ site.url }}{{ site.baseurl }}/assets/images/qbit-quick.png)*infographic sourced from [Qubit RNA Broad Range (BR) Assay Kit Quick Reference](https://www.thermofisher.com/document-connect/document-connect.html?url=https://assets.thermofisher.com/TFS-Assets%2FLSG%2Fmanuals%2FQRC10210.pdf)*

### Step 1. Set up 2 assay tubes for the standards and 1 tube for each sample

- [ ] label assay tube lids

**Warning Notice:** Label only the cap of the assay tube, the sides need to remain 	 clear for the fluorometer to penetrate through and read the sample
{: .notice--warning}

- [ ] rip off sheet of foil to cover sample tube rack to protect from light

**Warning Notice:** Qubit RNA BR dye-reagent (component A) is light sensitive, and must be kept in the dark (tube wrapped in foil)
{: .notice--warning}

### Step 2. Prepare Working Solution

**tldr:** For 8 samples and 2 standards, you will need 2mL of working solution, to prepare it in a 1:200 dilution of dye-reagent to buffer, pipette 10uL of Qubit dye-reagent plus 1990uL of Qubit buffer into a 15mL falcon tube, cap & invert to mix.
{: .notice--success}

- [ ] calculate volume of working solution you need

  > standard #1 - 190uL working solution, 10uL standard
  >
  > standard #2 - 190uL working solution, 10uL standard
  >
  > sample 1      - 199uL working solution, 1uL sample
  >
  > sample 2      - 199uL working solution, 1uL sample
  >
  > sample 3      - 199uL working solution, 1uL sample
  >
  > .. etc.
  >
  
  $$
  2*190uL + no. of samples *199uL = Working-Solution-Volume
  $$

**Note:** The final volume in each tube must be 200 µL. Each standard tube requires 190 µL of Qubit™ working solution, and each sample tube requires anywhere from 180–199 µL. Ensure that you have sufficient Qubit™ working solution to accommodate all standards and samples, with a little 'extra'. For example, to prepare enough working solution for 2 standards and 8 samples: $ 2*190uL + 8*199uL = 1972uL = 1.972mL \approx 2mL $
{: .notice--info}

- [ ] calculate a 1:200 dilution of dye-reagent to buffer

  - Divide working solution volume in uL by 200 to find volume in uL of dye-reagent, then subtract volume in uL of dye-reagent from working solution volume to get buffer volume. 

  - For a 2mL volume, a 1:200 dilution of dye-reagent:buffer would be 10uL of Qubit dye-reagent plus 1990uL of Qubit buffer.

- [ ] take 15mL falcon tube, dilute above volumes of dye-reagent with buffer to get the final working solution volume. Cap & invert falcon tube to mix. 

### Step 3. Pipette Working Solution, Standards, & Samples into assay tubes

#### Standard tubes

- [ ] Add 190uL of working solution to each standard tube
- [ ] Add 10uL of standard (#1 & #2) to each correspondingly labelled tube

#### Sample tubes

- [ ] Add 199 uL of working solution into each sample tube
- [ ] Add 1uL of sample into each correspondingly labelled tube (P2 pipette)

**Warning:** temperature affects pipetting accuracy, which is very important when pipetting tiny amounts (1uL!!), so make sure sample is on ice, but well-thawed.
{: .notice--warning}

### Step 4. Vortex standards and samples for 2–3 seconds and let sit at room temperature for 2 minutes

### Step 5. Read Samples

- [ ] Select RNA Broad Range Assay on the Qubit® 2.0 Fluorometer to calibrate with standards 

**Warning Notice:** Qubit™ assays delivers optimal performance when all solutions are at room temperature; temperature fluctuations can influence the accuracy of the assay. To minimize temperature fluctuations, insert all assay tubes into the Qubit™ Fluorometer only for as much time as it takes for the instrument to measure the fluorescence; the Qubit™ Fluorometer can raise the temperature of the assay solution significantly, even over a period of a few minutes. Do not hold the assay tubes in your hand before reading because this warms the solution and results in a low
reading.
{: .notice--warning}

- [ ] After calibration, read the samples with the same RNA Broad Range Assay selection on the Qubit Fluorometer. Cross your fingers they are in desired range 🤞

- [ ] Record RNA IQ values

  > ------
  >
  > | sample | qubit-rna-iq | qubit-run-date |
  > | ------ | ------------ | -------------- |
  > |        |              |                |
  > |        |              |                |
  > |        |              |                |
  >
  > 

- [ ] Download RNA IQ values using USB thumb-drive

  
