saveR
=====

Save MATLAB workspace variables to an `R` data file.

`saveR('FILENAME')` saves all MATLAB workspace variables to the "R-file" named `FILENAME`.

`saveR('FILENAME', 'X', 'Y', 'Z')` saves `X`, `Y`, and `Z`.

saveR can handle scalars, vectors, matrices, and cell arrays of strings. NaN's are saved as NA. Since R cannot handle structures, they will not be saved and a warning will be given.

Useful if you do not wish to load variables directly in R using a COM based interface (using [MATLAB R-link](http://www.mathworks.com/matlabcentral/fileexchange/5051-matlab-r-link)) or if you wish to use [JAGS](http://sourceforge.net/projects/mcmc-jags), for instance.

Also available on [MATLAB File Exchange](http://www.mathworks.com/matlabcentral/fileexchange/28370).

Licence: BSD
