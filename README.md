# AAMFixer

Tool for fixing atom-to-atom mapping on the basis of set of predefined rules. The approach is highly based on CGRtools library (https://github.com/cimm-kzn/CGRtools) [1] and uses its embedded features. 

Important! Atoms should follow the same order, only AAM should differ. For corresponding reactions with wrong and correct AAM, reagent mapping should coincide. Otherwise, remapping rule will fail.

`notebook.ipynb` - contains example Python code:
- to generate remapping rules from reactions with wrong and correct mapping.
- to apply generated rule to fix mapping in new reaction.
- to import and export rule set for further usage.

`RULES.pickle` - contains rule set extracted from "Golden" mapping dataset [2].

References:
1. R.I. Nugmanov, R.N. Mukhametgaleev, T. Akhmetshin, T.R. Gimadiev, V.A. Afonina, T.I. Madzhidov et al., CGRtools: Python Library for Molecule, Reaction, and Condensed Graph of Reaction Processing, J. Chem. Inf. Model. 59 (2019), pp. 2516–2521. http://pubs.acs.org/doi/10.1021/acs.jcim.9b00102
2. A. Lin, N. Dyubankova, T. Madzhidov, R. Nugmanov, A. Rakhimbekova, Z. Ibragimova et al., Atom-to-Atom Mapping: A Benchmarking Study of Popular Mapping Algorithms and Consensus Strategies, ChemRxiv Prepr. 13012679 (2020), pp. 1–20. https://chemrxiv.org/articles/preprint/Atom-to-Atom_Mapping_A_Benchmarking_Study_of_Popular_Mapping_Algorithms_and_Consensus_Strategies/13012679/1

Dependencies

* installed NodeJS

Installation

    pip install CGRtools[clean2d]

Citation:
1. CGRtools: Python Library for Molecule, Reaction, and Condensed Graph of Reaction Processing. Journal of Chemical Information and Modeling 2019 59 (6), 2516-2521. DOI: 10.1021/acs.jcim.9b00102
2. A. Lin, N. Dyubankova, T.I. Madzhidov, R.I. Nugmanov, J. Verhoeven, T.R. Gimadiev, V.A. Afonina, Z. Ibragimova, A. Rakhimbekova, P. Sidorov, A. Gedich, R. Suleymanov, R. Mukhametgaleev, J. Wegner, A. Varnek. Atom-to-atom mapping: a benchmarking study of popular mapping algorithms and consensus strategies. Molecular Informatics 2021. submitted
