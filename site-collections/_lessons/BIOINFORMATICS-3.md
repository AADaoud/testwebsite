---
layout: single
---

Global alignment is the name of the first type of algorithm we learned. It initializes the sequence with gap penalties and fills in the sequence procedurally. 

![[BIOINFORMATICS-1#Fragment assembly]]

# Semi-global alignment:
- Do not penalize gaps in the first row of the matrix.
- Do not penalize gaps in the last row of the matrix.
- Do not penalize gaps in the first column of the matrix.
- Do not penalize gaps in the last column of the matrix.

Sample exam question:
1. Find two sequences that have two best semi-global alignments and three best global alignments.

This question should be approached by solving the semi-global alignments first, this is done by creating a sequence that ends and one that starts in a repeating sequence. The key understanding is to ensure that there is one additional letter in one of the sequences which can match with two (or however many specified) identical letters in the second sequence:

			    C G G T - - - - - -
	- - - - - C G T

Three global alignments can be done by matching creating 3 potential combinations between the two sequences:

# Local alignment:
Local alignment is used to determine regions that match in a large sequence. It's similar to semi-global in addition to not penalizing mismatches as well. The highest scores in the entire matrix are used.

1. Two sequences with 5 local alignments and 3 best global alignments.

# How to weight scorings:
- Databases are used to determine the amino acid 

==Similarity scores, similarity scoring matrix, and BLOSUM==



# Additional Information
---
