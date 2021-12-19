# CS466-Project
Implementation and Extension of the Nussinov Algorithm
The source file cs466_nussinov.py contains 3 main components:
(1) An implementation of the Nussinv algorithm as discussed in the CS466 lecture slides
(2) A tracback to enumerate all secondary structures given by the Nussinov algorithm
(3) A basic visualizer to plot the backtrace using matplotlib

The code is in the form of an interactive Jupyter notebook, and can be run on a Jupyter server. 
The function nussinovDP takes in an RNA sequence as argument and outputs the Nussinov Table. 
The function test_seq_enum also takes in a RNA sequence as argument and outputs all optimal solutions.
Finally, the function visualizer takes in the sequence, Nussinov table and an array of base pair indicies and saves a plot in 'output.png'. Currently, the function doesn't work for large sequences and nested loops, and was included only to add some basic visualization to the project as it works for simple sequences such as the example included.
