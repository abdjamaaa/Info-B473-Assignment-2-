InfoB473 Assignment 2
Programmer
Abdul Djama
Language: Python
Version: 1.0
Submitted: September 29, 2026

About This Program
This program uses the chr1_GL383518v1_alt DNA sequence from Assignment 1.
It reads the sequence from the FASTA file, checks a few specific positions,
makes the reverse complement, and counts how many A, C, G, and T bases are
in each 1000-base section of the sequence.
The counts are stored in a nested dictionary and then converted into lists
so the totals for each kilobase can be checked.

Files
assignment2.py
Main Python file for the assignment.
chr1_GL383518v1_alt.fa
FASTA file containing the DNA sequence.

Requirements
- Python 3.10 or newer
- The Python file and FASTA file should be in the same folder

Running the Program
Open a terminal in the folder containing the files and run:
python assignment2.py
The results will print directly in the terminal.
What It Prints
The program prints:
- the 10th base in the original sequence
- the 758th base in the original sequence
- the 79th base in the reverse complement
- bases 500 through 800 of the reverse complement
- nucleotide counts for each kilobase
- a list of A, C, G, and T counts for each kilobase
- the sum of each kilobase list

Part 4 Results
A complete kilobase should add up to 1000 bases.
Kilobases 1 through 182 had totals of 1000.
Kilobase 183 had a total of 439 because it was the last section of the
sequence and did not contain a full 1000 bases.

Data
The sequence came from the UCSC Genome Browser hg38 chromosome data.
Sequence used: chr1_GL383518v1_alt
