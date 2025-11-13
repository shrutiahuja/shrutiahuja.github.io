---
layout: archive
title: "Academic Research Projects"
permalink: /academic-projects/
author_profile: true
---

## Rationale

The first successful implementation of wastewater surveillance occurred in 2003 when WHO formally adopted wastewater-based epidemiology (WBE) for poliovirus surveillance, contributing significantly to its eradication efforts. The emergence of the Severe Acute Respiratory Coronavirus 2 (SARS-CoV-2) in 2019 brought about an unprecedented acceleration in the global application of WBE in several countries, triggering a renaissance in population-scale pathogen surveillance. Countries such as the United Kingdom, United States, and Australia rapidly established national-level programs to monitor viral spread through wastewater, forming critical pillars of their public health response systems. However, large scale implementation of wastewater surveillance programs especially in populous lower middle income countries faced challenges due to the limited availability of reagents that were similar for clinical or environmental surveillance. Additionally, after the pandemic subsided the high capital cost and per test cost further hindered wastewater monitoring efforts. 

**To address these constraints my research focuses on developing end-to-end wastewater surveillance platform technology.**

## Developing paper dipstick and PTFE membrane filtration(PMF) method for pathogen capture and nucleic acid extraction from wastewater samples

🔗 [*Quick video link for dipstick method*](https://drive.google.com/file/d/15ZRzOavn9dTrZP22ZmL-JWBVlMZy3BsD/view?usp=drive_link)

🔗 [*Published paper on this work*](https://doi.org/10.1016/j.scitotenv.2024.170347) 


***Research gap***: 

The primary challenge in developing  an end-to-end surveillance system lies in achieving efficient pathogen concentration and nucleic acid extraction. Low pathogen concentration, sample heterogeneity and complexity, and large variety in the types of organisms make it difficult to concentrate pathogens and extract nucleic acid rapidly and in a cost-efficient manner. Although multiple concentration strategies exist such as skimmed milk flocculation, aluminum polychloride flocculation, and PEG precipitation-based concentration their capture efficiencies are considerably low and exhibit significant variations. Moreover, their processing times are considerably long 8 hours for skim milk flocculation and 9–24 hours for PEG precipitation.  Furthermore, many processes involved in these methods, such as ultrafiltration, ultracentrifugation, adsorption-extraction, and PEG/aluminium-based precipitation, require laboratories equipped with the necessary sophisticated equipment and skilled personnel to execute the process. These significant challenges prevent scale-up and adoption of these methods for on-field surveillance in LMICs. Paper and filter membrane-based concentration methods of pathogens show promise for integration into an in-field automated surveillance system. However, electropositive and electronegative filtration have low and variable capture efficiencies. Commercially available filter papers such as FTA cards and Whatman Fusion 5 have been extensively utilized for the capture and preservation of nucleic acids from diverse bodily fluids however their utility with wastewater samples remain limited. 

Cellulose filter papers have also been explored for the purification of nucleic acids from a wide variety of samples. The cellulose paper dipstick provides a rapid, high-throughput method for nucleic acid extraction that does not require the use of specialized equipment. However, its potential for detecting pathogens within wastewater environments remains largely unexplored.

**To overcome the primary challenge of microbial concentration of we have explored the use of paper and PTFE filter membrane-based concentration and nucleic acid extraction methods to detect pathogens in wastewater and benchmarked their performance against commercially available kits.**

- The PMF method relies on size-based capture of pathogens from wastewater. Integrated into a peristaltic pump setup, the system filters 40–100 mL of wastewater, followed by washing and nucleic acid elution.

- To eliminate instrumentation and simplify workflow, we designed **cellulose paper dipsticks** with wax handles that capture and isolate nucleic acids from 1 mL of wastewater in minutes. This approach builds on the long-established property of cellulose matrix to selectively capture and retain large nucleic acid molecules.

- The **dipstick workflow** integrates thermal cell lysis, inspired by the HUDSON (Heating Unextracted Diagnostic Samples to Obliterate Nucleases) principle. Heat treatment lyses viral and bacterial particles while deactivating nucleases. The resulting lysate undergoes RNA capture on the dipstick, followed by washing and direct elution into the cDNA master mix for amplification. Optimization of RNase inhibition was critical to preserving RNA integrity and enabling efficient downstream amplification.

![Workflow for PMF and dipstick based pathogen capture from wastewater samples](/assets/img/graphical_abstract.png)

## Product validation: Validating field-utility of dipstick method as per industrial standards

Given the manual nature of the dipstick workflow, operator-induced variability poses a potential challenge for on-site application. To evaluate this, we conducted a multi-operator study at the IIT Bombay sewage pumping station, collecting wastewater samples in triplicates before and during semester breaks to detect changes PMMoV load with fluctuations in population density. Three operators independently processed each sample in triplicates using the dipstick method, followed by triplicate amplification runs.The resulting Ct values served as the response variable, and the effects of operator, sample, dipstick, and operator–sample interaction were analyzed using two-way ANOVA and crossed gage R&R analysis using the JMP software.

While the dipstick method proved effective for viral RNA, direct elution into the amplification mix inhibited PCR for bacterial DNA. To overcome this we optimised the dipstick method including the dipstick preparation and protocol to concentrate bacteria and isolate DNA. The optimised dipstick method and PMF method have been utilised for 16S rRNA sequencing for metagenomic profiling from wastewater samples collected from different residential complexes in Mumbai. The bacterial abundance and prevalence for the two methods was compared with a commercial kit method. 

***Key outcomes***: 

- **SARS-CoV-2 detection**: PMF and dipstick methods successfully detected SARS-CoV-2 in wastewater, with Ct values comparable to those from commercial extraction kits.

- **Simultaneous multiple pathogen detection**: PMF method enabled simultaneous detection of *E.coli*, PMMoV, and bacteriophage Phi6 with recovery efficiencies similar to commercial kits.

- **Population correlation**: PMMoV load fluctuations detected using the dipstick method corresponded with population density changes across sampling periods.

- **Product validation**: Dipstick method exhibited **<30% variability**, within acceptable product variability as per Wheeler’s Gage R&R industrial standards.

- **Metagenomic profiling**: The optimised dipstick and PMF method have been used for 16S rRNA sequencing.

## End-Point Pathogen Detection Using Electroless Nickel Immersion Gold (ENIG) PCB Electrodes

🔗 [*Published paper on this work*](https://www.nature.com/articles/s41598-022-12818-w) 

Conventional pathogen detection techniques rely on quantitative PCR (qPCR/qRT-PCR), the gold standard for sensitivity and specificity. However, these assays demand skilled personnel, controlled laboratory environments, and costly instrumentation—making large-scale, on-site deployment difficult. Low-cost nucleic-acid electrochemical biosensors offer a promising alternative, but conventional electrodes are often functionalized with complementary oligonucleotides, reducing the shelf life and stability of the sensor. To address this limitation, we developed a label-free electrochemical DNA-sensing approach using unmodified ENIG PCB electrodes with methylene blue (MB) as the redox indicator. A 5 µL MB–DNA complex was drop-casted on ENIG-PCB electrodes, and Differential Pulse Voltammetry (DPV) and Cyclic Voltammetry (CV) measurements were performed. The system successfully differentiated no-template controls, positive controls, and environmental Phi6 samples, confirming its capability for endpoint DNA quantification.

<p align="center">
  <img src="/assets/img/longer.png" width="550">
</p>

***Understanding the mechanism of ENIG-PCB electrochemical sensing***:

The ENIG-PCB electrode was thoroughly characterised as a DNA sensor while studying the influence of DNA concentration, amplicon length and ionic strength on sensor response. We observed increasing trend in the peak current for DPV and CV measurements for lower concentrations of DNA, with the increase more pronounced for the longer ~500 bp DNA fragment as compared to the 117 bp fragment due to Adsorption of the MB-DNA complex facilitates charge transfer at the electrode. However, for higher DNA (>2ng ng/ul) concentrations we observed a decrease in peak current for both amplicons, in DPV as well as CV measurements. This is because MB saturates and intercalates between the base pair of the DNA, causing *steric inhibition* of redox activity of reducible groups in MB. While the addition of salt markedly reduced the peak current at DNA concentrations below 2 ng/µL, it had negligible effect at higher concentrations, where electrostatic interactions no longer significantly influence the sensor response.

***Key outcomes***: 

- ENIG PCB based electrochemical sensing of viral nucleic acid from lake water samples.

- Evaluated the mechanism of MB-DNA sensing on unmodified ENIG-PCB electrodes.

- Evaluated the influence of amplicon legth, DNA concentration and ionic strength on sensor response.

- Low-cost of implementation, with potential for integration into fully-automated surveillance systems.

We also evaluated **DNA detection using probe-modified ENIG PCB electrodes**, using faradaic electrochemical impedance spectroscopy (EIS) to improve sensor sensitivity.

🔗 [*Published paper on this work*](https://doi.org/10.1016/j.biosx.2024.100569)

EIS provides high analytical sensitivity and can distinguish bioelectrochemical circuit elements across a wide frequency spectrum. However, conventional Faradaic EIS depends on charge-transfer resistance for analyte quantification, and acquiring measurements at very low frequencies (≈0.1 Hz) substantially prolongs analysis time and accelerates ENIG degradation through gold dissolution and copper corrosion.

To address these limitations, we introduce the use of the constant phase element (CPE) within the equivalent electrical circuit for DNA sensing. In this work, ENIG PCB electrodes were functionalized with thiolated single-stranded DNA probes targeting the uidA gene of E. coli. We assessed assay specificity using a 166 bp complementary amplicon and compared responses to non-complementary amplicons of varying lengths from *E.coli* and bacteriophage Phi6. Operating at higher frequencies (≥10 Hz) enables CPE-based analysis to shorten measurement times and reduce PCB damage.

## Integration Towards an End-to-End Platform

The dipstick-based nucleic acid extraction method was integrated with the ENIG-PCB electrochemical sensor, establishing a proof-of-concept end-to-end wastewater surveillance platform for bacteriophage Phi6 detection. This integration demonstrates the feasibility of combining rapid, paper-based nucleic-acid capture with low-cost electrochemical quantification for field-deployable surveillance systems. 







