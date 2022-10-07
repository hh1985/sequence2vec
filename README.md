# Sequence2Vec
Sequence2Vec is a tool providing alignment free precessing of NGS data. The central idea of sequence2vec is graphical embedding of the entities during NGS data processing. It may change the ways bioinformatical conclusions are driven.
### kmer2vec
kmer2vec is an algorithm providing short seqeuence (k <= 10) embedding strategy, so that reads which share overlapping sequences tend to be "close" in _N_ dimentional space.
### read2vec
Read2Vec is an algorithm providing read-level (n = 150, 250, or 300) embedding strategy, so that reads which share overlapping sequences tend to be "close" in _N_ dimentional space.
### contig2vec
contig2vec is an algorithm which clusters and "assemble" reads based on graphical feature of reads and biological evidence (e.g. paired end reads). Segments from the same genome should be "close" to each other.
