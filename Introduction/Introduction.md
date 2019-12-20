# Introduction

## 1950-1970: The origins

1952, the role of DNA as a genetic information encoding molecule was validated by Hershey and Chase.

1953, the doble-helix structure of DNA was solved by Waston, Crick and Franklin.

1953, the first sequence of a protein, insulin, was published by Sanger.

1949, The **Edman degradation** method emerged as a simple method that allows protein sequencing. The amino-terminal residue from N-terminus is labeled ana cleaved from the peptide. The theorarical maximum of 50-60 amnio acids can be sequenced in a single Edman reaction.

1962, the *Comprotein* program was designed to determine protein primary structure by Dayhoff and Ledley, using Edman sequencing data.

1968, the one-letter amino acid code was developed by Dayhoff.

1963, Zuckerkandl and Pauling coined the term **Paleogenetics** to introduce the novel branch of evolutionary biology.

1970, the concept of orthology was defined by Walter M. Fitch to describle homology that resulted from a speciation event.

1970, the first sequence-based phylogenetic studies was developed by Haber and Koshland.

1970, the first dynamic programming algorithm for **pairwise aligments** of protein sequence was developed by Neeldeman and Wunsch.

1985, the first multiple sequence alignment (MSA) algorithm was generalization of Needlman-Wunsch algorithm by Murata. It requires the running time of  $O(L^{N})$, where $L$ is the sequence length and $N$ is the amount of sequences.

1987, the first truly practical approach to **MSA** was developed by Da-Fei Feng and Russell F. Doolitle. The approach was called "progressive sequence alignment", consisted of 1) performing Needleman-Wusch aligment for all sequence pairs, 2) extracting pairwise similarity scores for each pairwise alignment, 3) using those scores to build a guide tree, 4) aligning the two most similar sequences, and then the next more similar sequence, and so on.

1988, the popular MSA software *Clustal* was developed as a simplification of the Feng-Doolittle algorithm.

1978, Dayhoff, Schwartz and Orcutt developed the first probabilistic model of amino acid substitutions. The result was a $20\times 20$ asymmetric **substitution matrix** that contained probability values based on the observed point accpeted mutations (PAMs) of each amino acid. The PAM matrix introduced the of substitutions as the measurement of evolutionary change.

## 1970-1980: Paradigm shift from protein to DNA analysis

*Paradigm shift* is a fundamental change in the basic concepts and experimental practices of a scientific discipline.

1968, all of the 64 codons of the genetic code were deciphered.

1976, the first **DNA sequencing method** to be widely adopted was the Maxam-Gilbert sequencing method.

1977, Sanger developed the "plus and minus" DNA sequencing method, the first to rely on primed synthesis with DNA polymerase. From the whole-genome DNA sequence, one can predict the primary structure of all proteins expressed by an organism through translatioin of genes present in the sequence.

1979, the first software dedeicated to analyzing the Sanger sequencing reads was published by Roger Staden. The software included 1) search for overlaps between Sanger gel reading, 2) verifty, edit and join sequence reads into contigs, 3) annotate and manipulate sequence file.

1981, the first molecular phylogenetic trees were reconstructed from protein sequences, and typically assumed maximum parsimony as the main mechanism driving evolutionary change by Joseph Felsenstein. The **parsimony-based method** assume that change is improbable a priori. If the amount of change is small over evolutionary times being considered, it will be well-justified statistical methods. Most data involve moderate to large amounts of change, and it is in such cases that parsimony methods can fail.

1981, Felsenstein was the first to develop a maximum likelihood (ML) method to infer phylogenetic trees from DNA sequences. Unlike parsimony-based method. ML method involves finding the evolutionary tree which yields the highest probability of evolving the observed data.

1996, the Bayesian statistics was applied in molecular phylogeny.

## 1980-1990: Parallel advances in biology and computer science

1972, Jackson, Symons and Berg isolated and amplified of genes independently from their source organism. However, Berg called for a moratorium on the use of recombination DNA because of worries about the potential ethical issues.

1975, Berg chaired the Asilomar conference and established a series of guidelines on practice of genetics.

1987, the second milestone in manipulating DNA was the **polymerase chain reaction (PCR)** by Kary Mullis, which allows to amplify DNA without cloning procedures.

1977, the three first computers, Commodore PET, Apple II and Tandy TRS-80, were small, inexpensive and relatively user-friendly hit the consumer market.

1984, the University of Wisconsin Genetics Computer Group published the eponymous *GCG* software suite. It was a collection of 33 command-line tools to manipulate DNA, RNA and protein sequence.

1984, another sequence manipulation suite, *DNASTAR*, was developed after *GCG*. It was popular in the 1980s and 1990s for its capabilities in assembling and analyzing Sanger sequencing data.

1985, Richard Stallman published the **GNU Manifesto**, which outlined his motivation for creating a free Unix-based operating system called GNU (GNU's Not Unix).

1987, the European Molecular Biology Laboratory (EMBL), GenBank and DNA Data Bank of Japan (DDBJ) sequence databases have united in order. Today this union is represented by the International Nucleotide Sequence Database Collaboration (INSDC).

1985, the journal *Computer Application in the Biosciences (CABIOS)* was established, now named *Bioinformatics*.a

1987, **Perl (Practical Extraction and Reporting Language)**, a high-level, multiparadigm, interpreted scipting language, was developed by Larry Wall. *GeneQuiz*, *LabBase*, *Swissknife*, *MUMmer*, etc. software were written in Perl. Then until the late 2000s, Perl was undoubtedly the *lingua franca* of bioinformatics, due to its great flexibility. However, Perl's heavily punctuated syntax could easily result in low code readability. This makes Perl code maintenance difficult.

1987, **Python**, like Perl, a high-level, multiparadigm programming language, was first implemented by Guido van Rossum. Python was especially designed to have a simpler vocabulary and syntax to make code reading and maintenance simpler. Python became a major programming language in bioinformatics until late 2000s, because the implementation of specialized bioinformatics libraries.

## 1990-2000: Genomics, structual bioinformatics and the information superhighway

1951, the first milestones concerning the prediction of a protein structure were laid by Pauling and Corey.

1991, the Human Genome Project was initiated by the U.S. National Institutes of Health.

1992, the GenBank database became the responsibility of the National Center for Biotechnology Information (NCBI).

1993, the first nucleotide sequence database, the EMBL Nucleotide Sequence Data Library (include SWISS-PROT and REBASE) was made available on the Web.

1994, the well-known website of the NCBI was made available online. Then came the establishment of several major database Genomes (1995), PubMed (1997) and Human Genome (1999).

1995, the first complete genome sequencing of a free-living organism was sequenced by the Instituted for Genomic Research (TIGR) led by geneticist J. Craig Venter.

1995, the NIH-funded human genome sequencing project made its data publicly available.

1990s, force fields have been developed to describe the interactions between atomes, allowing the release of tools to model the molecular dynamics of proteins.

1998, Celera Genomics (a biotechnology firm) led a rival, private effort to sequence and assemble the human genome.

2009, the DNA sequencing by capillary electrophoresis was developed. These had a maximum throughput of 96 reads of 800 bp length per gun.

## 2000-2010: High-throughput bioinformatics

2004, BOINC developed a collaborative platform that allows users to make their computers available for distributed calculations for different projects. Several projects like protein-ligand docking, simulations related to malaria and protein folding are now available.

2005, DNA sequencing was democratized with the advent of second-generation sequencing (also called **next-generation sequencing**) that started with the "454" pyrosequencing technology. This technology allowed sequencing thousands to milestones of DNA molecules in a single machine run.

Since 2008, the Moore's Law stopped and this resulted in an expoential increase of sequences in public databases such as GenBank and WGS. The scientific community has now generated data beyond the exabyte level.

## 2010-Today: Present and future perspectives

A recent evolution related to bioinformatics is the emergence of researchers specialized in this field: bioinformatics.

There is a significant increase in 1) user-friendly tools, often available through integrative Web servers like Galaxy, 2) helping communities such as SEQanswers and BioStar, 3) explosive need for bioinformatician on the job market in academic, private and governmental sectors.

Bioinformatics user: 1) using current techniques skills, and tools necessary for computational biology practice, 2) applying statistical research methods in the contexts of molecular biology, genomics, medical, and population genetics research, 3) applying knowledge of general biology, in-depth knowledge of at least on area of biology, and understanding of biological data generation technologies.

Bioinformatics scientist: analyzing a problem and identify and define the computing requirements appropriate to its solution.

Bioinformatics engineer: applying mathematical foundations, algorithmic principles, and computer science theory in the modeling and design of computer-based systems in a way that demostrates comprehension of the tradeoffs involved in design choices.
