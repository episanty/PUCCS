PUCCS
=====

Perceptually Uniform Cyclic Color Scale

© Emilio Pisanty, 2018, released under the MIT license



PUCCS is a cyclic color scale that attempts to keep a better perceptual uniformity than the standard hue map. It has been designed using some of the tools provided by Peter Kovesi in 'Good Colour Maps: How to Design Them' ([arXiv:1509.03700](https://arxiv.org/abs/1509.03700), 2015).

It consists of the following files:

 - The main notebook file, `PUCCS.nb`, a Mathematica notebook containing the function definitions and some benchmark plots.
 - A plaintext (`.m`) printout of the main notebook file.
 - A data file, `Data.csv` containing the color points of the function, in CIE LAB and RGB spaces. (Both coordinates in Mathematica conventions - you may need to multiply the LAB values by 100 and the RGB values by 255, or convert to hexadecimal, to import them into your application.)
 - Several benchmarking images:
 
 <img src="https://github.com/episanty/PUCCS/blob/master/Benchmarks/strip.png" width="600">
 
 <img src="https://github.com/episanty/PUCCS/blob/master/Benchmarks/washboard.png" width="600">
 
 <img src="https://github.com/episanty/PUCCS/blob/master/Benchmarks/circle.png" width="600">
 
 <img src="https://github.com/episanty/PUCCS/blob/master/Benchmarks/LGdonut.png" width="600">




