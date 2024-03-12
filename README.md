# Motif searching algorithm
This algoirthm finds motifs present in DNA sequences. A motif is a short, recurring pattern of nucleotides and it is presumed that these sites have some kind of biological function.

  Script takes two instances - in one of them information about the order of nucleotides is present, while in other the quality value, or credibility threshold, of every nucleotide in the first instance. 

  Information inside those files is processed and in turn the nucleotides, which have quality value lower than credibility threshold set by user, are removed from the analysis.
  
  Then, motifs of length declared by the user are searched between sequences only if they are not further from each other than by 10 times the length of motif.
  If said motif is found in an instance, it gets outputted into the terminal.
