# DNA Sequence Generator

A generator for random DNA sequences. Output is a file in FASTA format containing the sequences and their titles. The sequences are split into series of lines at 80 characters following the norm. The title of the sequences begins with an '>'.

## Input
>python main<span></span>.py \<sequenceLength> \<sequenceNumber>

## Example
A small example of generating a random DNA sequence with a sequence length of 240.

### Example Input
>python main<span></span>.py 240 1

### Example Output
>\>Sequence 1 of 1
>AGAAGCATTAAAACGGCCACCATGGCTCCGGACTTCATTTCATGTTTCGGATTCGCAATTAGGTTGGTGGTGGCATTACAGGACTCCCTCAAGCGGGTGCGTATGTTACTAGGAAGATTTCTCATGGGTTGGTGCAGATCTTGATCAATTGATGCGATACACAGAGATTTGAACTCTGCATTGCACACTTCTTGTCGGTTTCAACCGGCGATGCAGAGACCCTGGTCTGTTCGAGCCGCC

