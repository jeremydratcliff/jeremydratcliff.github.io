---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
---
My full publication list and various citation metrics are available on my [Google Scholar profile](https://scholar.google.com/citations?user=1CIn2dYAAAAJ&hl=en). All of my publications should be open-source, but please get in touch if there are any access issues. 

My research interests (generally) map to three core themes:

**Operationalizing Pathogen Genomics**

I am strongly of the belief that there is significant unmet potential in leveraging pathogen genomics to advance public health. The COVID-19 pandemic demonstated that the widespread deployment of sequencing enabled identification of novel characteristics of SARS-CoV-2, particularly for those with subtle signals. I see three sub-themes that independently and collectively expand the operational utility of pathogen genomics:

* Expanding global access to sequencing (i.e., better technology)
* Increasing volume and geographic diversity of sequence data (i.e., more samples)
* Generating novel insights from sequence data (i.e., better analyses)

I am very open to collaborations that tackle one or more of these sub-themes, **particularly those that integrate language models and genomics for analysis**.

Within evolutionary virology, my technical work is heavily influenced by the research of my PhD supervisor Prof. Peter Simmonds on the non-random distribution of dinucleotides in viral genomes. My experience in the Simmonds lab cultivated a high proficiency in defining testable null hypotheses for various phenomena in genomics. I have applied this framework to detecting APOBEC-like mutations in SARS-CoV-2 genomes ([Ratcliff and Simmonds, 2020](https://www.sciencedirect.com/science/article/pii/S0042682220302658?via%3Dihub)), comparative analysis of Oxford Nanopore sequencing performance in different kit chemistries ([Ratcliff et al., 2023](https://www.biorxiv.org/content/10.1101/2023.09.30.560331v1)), and characterizing the outputs of transformer models for synthetic bacteriophage genome sequences ([Ratcliff, 2024](https://www.biorxiv.org/content/10.1101/2024.03.19.585716v1)).

**Public Health Intelligence**

Through my work at APL, I've been privileged to support federal responses to three infectious disease emergencies: COVID-19 (with FEMA, CDC, and ASPR), mpox (with CDC and ASPR), and the 2023-2024 respiratory virus outbreak (with CDC). I also have a fairly extensive publication record in studying responses to emergencies and other critical events (read [here](https://www.cambridge.org/core/journals/disaster-medicine-and-public-health-preparedness/article/abs/use-of-big-data-and-information-and-communications-technology-in-disasters-an-integrative-review/23B2807AE283BB7A7FDB4BE48DD01058), [here](https://www.cambridge.org/core/journals/disaster-medicine-and-public-health-preparedness/article/technologies-enabling-situational-awareness-during-disaster-response-a-systematic-review/4B303623ECEF3F0413C68F1462DFC00F), and [here](https://apps.dtic.mil/sti/trecms/pdf/AD1143415.pdf)). My experience on all three federal responses have been consistent in that the first challenge is always insufficient data. This limited information leads to (a) decision-making under uncertainty, (b) efforts to increase the "actionability" of available information, and (c) prioritization of refining existing and establishing novel data streams. For topic (a), I have published on incorporating uncertainty in [infectious disease modeling and forecasting for decision-making](https://www.liebertpub.com/doi/full/10.1089/hs.2023.0033). As responses mature, challenges shift toward interpretating potentially conflicting signals from multiple data streams. Appropriately weighing evidence requires rich metadata (and context), which are often woefully inadequate as indicated in our commentary on [data standards during COVID-19](https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(20)30635-6/fulltext).

I deem this theme "intelligence" as it incorporates all of the actions that enable data to decisions within response environments. It's an incredibly complex system with many, many entry points. The vast spread of activities that can support public health intelligence result in some overlap with the other two themes articulated on this page.

**Counterproliferation of Biological Weapons**

My personal assessment is that the risk of development and deployment of biological weapons (BW) is higher for state actors than for non-state actors. My view on effective counterproliferation strategies for state actors is informed primarily by *The Soviet Biological Weapons Program: A History* by Leienberg, Zilinskas, and Kuhn. In particular, I view the USSR program of *Biopreparat* to be a model for how nation states may currently disguise BW development.

In 1974, the USSR established *Biopreparat* to secretly lead the nation’s BW program. The agency employed civilian and military scientists to conduct research at the behest of the 15th main directorate under the cover of being a collection of civilian R&D institutions. With only limited staff read in to the true activities of *Biopreparat*, a substantial number of civilian scientists were unknowingly contributing to a BW research portfolio. 

The benefits of obscuring BW development within civilian R&D institutions are clear but hint at opportunities for their detection. Capital costs are lowered as expensive laboratory equipment kept outside of BSL-3 or BSL-4 laboratories, such as sequencers and mass spectrometers, can be shared by civilian and military research teams (and purchased by the former). The specialist knowledge of civilian scientists can be more easily leveraged, with or without their knowledge as to the program they are supporting. Lastly, activities can be concealed from international oversight by housing them within facilities with well-established covers. Physical waste streams, significant foot traffic, and restricted access control can be explained away as normal research practices. Therefore, limiting the ability of nation-states to leverage their civilian R&D infrastructure for BW development would increase the cost and complexity for managing such an enterprise. 

I view public dissemination of methods to detect markers of BW development as potentially more effective than their actual deployment. This belief is due to the acknowledgement of a method's existence forcing a bad actor to develop countermeasures to evade detection *in all of their research programs*. The arms race in this instance is inherently assymetric in favor of the algorithm development. A single algorithm that can detect BW contamination in open-source research products can motivate the purchase of new capital equipment exclusively for a single secret lab. This could easily cost a research program million to tens of millions of dollars, not to mention ballooning personnel costs. I have several nascent concepts related to the development of algorithms for detecting these footprints. Check back later to see if any of them acquire funding!

As a parting shot, I have a strong research interest in whether genomic language models will accelerate the design of high consequence pathogens for nefarious use. While I am skeptical that the risk comes from generative models specifically ([described in the discussion here](https://www.biorxiv.org/content/10.1101/2024.03.19.585716v1)), my concerns arise from the ability of encoder models to identify novel functional properties of subsequences within genomes. Please reach out for collaborations in this space.