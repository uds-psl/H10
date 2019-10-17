# Hilbert's tenth problem in Coq

Dominique Larchey-Wendling <dominique.larchey-wendling@loria.fr>, Yannick Forster <forster@ps.uni-saarland.de>

This repository contains the Coq formalisation of the paper ["Hilbert's tenth problem in Coq"](http://drops.dagstuhl.de/opus/frontdoor.php?source_opus=10534), accepted for publication at the 4th International Conference on Formal Structures for Computation and Deduction (FSCD 2019).

## How to compile the code

Clone the repo using `git clone https://github.com/uds-psl/H10.git`, then `cd H10` and `make -j 5` should do the job. The files are tested to compile with `The Coq Proof Assistant, version 8.8.2 (October 2018)`.

The compiled HTML version of the files can be found [here](https://uds-psl.github.io/H10/website/toc.html) or in the `website` subdirectory of this repository.

# A Coq library of undecidable problems

This repo is a static snapshot of our [library of undecidable problems](https://github.com/uds-psl/coq-library-undecidability) together with the html version of the code. Note that the repository also contains other, unrelated parts of the library, contributed by Yannick Forster, Edith Heiter, Dominik Kirst, Dominique Larchey-Wendling, and Gert Smolka.

An overview over the code is in Appendix A of the ([paper](https://members.loria.fr/DLarchey/files/papers/H10_FSCD19.pdf)).
