# Introduction
The ARTIC network is developed to process samples from viral outbreaks and understand fast-evolving RNA viruses by using Nanopore sequencing [1]. Nanopore sequencing is a single-molecule portable long-read sequencing instrument and it can be used in remote and resource-limited locations. Researchers in Brazil already used this ARTIC network to analyze the first COVID-19 case in Brazil [2]. In order to get familiar with Nanopore long-read sequencing, I read the ARTIC protocol to assemble the COVID-19 virus genome and compare it with the original virus (Wuhan-Hu-1).

# Methodology
We can do direct RNA sequencing on RNA viruses by using Nanopore long-read technology [3]. However, this approach used primers to amplify different regions in order to improve the sensitivity of virus mutation detection. Since the COVID-19 outbreak in 2020, they have kept updating the primer version from version 1 to version 4 to improve the performance in some regions that are hard to amplify. I used the v3 primer scheme and assembled all the amplicons together to get a consensus sequence. Based on that, I can compare the sequence to the original virus (Wuhan-Hu-1) and understand the location of different mutations [4]. Based on this tool, we can detect virus outbreaks in a lost low-cost manner and remote locations.

# Reference
[1] https://artic.network/ncov-2019  
[2] https://virological.org/t/first-cases-of-coronavirus-disease-covid-19-in-brazil-south-america-2-genomes-3rd-march-2020/409  
[3] https://nanoporetech.com/document/direct-rna-sequencing-sqk-rna002  
[4] https://www.ncbi.nlm.nih.gov/nuccore/MN908947
