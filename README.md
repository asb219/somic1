# somic1

Author Dominic Woolf (d.woolf@cornell.edu)

Provides source code and example data for versions 1.0 and 1.1-asb219 of the SOMic microbial soil carbon model. C++ source code can be found in the source directory.

* To install the R package for version 1.0 as published in Woolf \& Lehmann (2019)[^1], use `devtools::install_github('asb219/somic1@v1.0')`
* To install the R package for version 1.1 as modified by Alexander S. Brunmayr (asb219@ic.ac.uk), use `devtools::install_github('asb219/somic1@v1.1-asb219')`

For a demonstration of using the model on long-term data-sets, run `demo(SOMIC)`

**New things in version 1.1-asb219** :
Allow distinct initial <sup>14</sup>C for each pool.
Option to track Fraction Modern instead of <sup>14</sup>C age.
Some variable names and input arguments have changed.


[^1]: Woolf, D., & Lehmann, J. (2019). Microbial models with minimal mineral protection can explain long-term soil organic carbon persistence. _Scientific Reports, 9_(1), 6522. DOI: [10.1038/s41598-019-43026-8](https://doi.org/10.1038/s41598-019-43026-8)\ 
