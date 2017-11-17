# CitationHelper
Helps create wikipedia citations from academic publications.

Justification: I wanted to improve a citation that on Wikipedia. There were 75 authors, and it's a bit tedious to add them manually. This takes a string of comma-separated names, and creates a new string in the appropriate style:

	source = r"Alpha Beta, Gamma Delta"

becomes

	| last0 = Beta | first0 = Alpha
	| last1 = Delta | first1 = Gamma

The initial version uses as an example the 75 authors of [In-Datacenter Performance Analysis of a Tensor Processing Unit™](https://arxiv.org/pdf/1704.04760.pdf)
