---
layout: project
title: "Identifying context of mutation signatures in cancer genomes"
tagline: ""
handle: 
image: /assets/images/projects/
category: project
tags: [cancer, mutations, genomics]
people: B Ravindran, Raghunathan Rengaswamy, Karthik Raman, Ashok Venkitaraman (MRC Cambridge)
---
{% include JB/setup %}

Genomic instability is a defining hallmark of cancer cells. Previous studies have identified “signatures” or patterns of mutations in different forms of cancer that gives us clues regarding the underlying mechanisms that trigger these alterations.  In this project, we look at the genomic context of the cancer-associated mutations.  The context used in our analysis is that of bases in the immediate neighborhood (5’ and 3’ end) of the mutated base. A count of these is recorded for a given mutated base, developing a mutation matrix which is decomposed into a mutational signature matrix and contribution matrix, using non-negative matrix factorization. This is how we obtain our signatures.
