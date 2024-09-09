# Introduction
The ARTIC network is developed to process samples from viral outbreaks and understand fast-evolving RNA viruses [1]. This is based on a single-molecule portable long-read sequencing instrument, Nanopore MinION. Because of that, it can be used in remote and resource-limited locations. Researchers in Brazil already used this ARTIC network to analyze the first COVID-19 case in Brazil [2]. In order to help me to get familiar with the Nanopore long-read sequencing, I read ARTIC protocol to assembly COVID-19 virus genome and to compare with the original virus (Wuhan-Hu-1).

# Methodology
Theoretically, we can do direct RNA sequencing on COVID-19 by using Nanopore long-read technology [3]. But this approach used primers to amplify different region in order to improve the sensitivity of virus mutation. They kept updating the primer version from version 1 to version 4 in order to improves the performance in some regions that are hard to amplify. Here, I used the v3 primer scheme and assembled all the amplicons together to get consensus sequence. Based on that, I can compare the sequence to the original virus (Wuhan-Hu-1) and understand the location of different mutation [4].

# Reference
[1] https://artic.network/ncov-2019  
[2] https://virological.org/t/first-cases-of-coronavirus-disease-covid-19-in-brazil-south-america-2-genomes-3rd-march-2020/409  
[3] https://nanoporetech.com/document/direct-rna-sequencing-sqk-rna002  
[4] https://www.ncbi.nlm.nih.gov/nuccore/MN908947
