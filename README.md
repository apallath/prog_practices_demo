# Programming Practices Demo

This GitHub repository accompanies my July 2021 tutorial on 'Good Programming
Practices' for new members of the Patel Group.

Using an example Python program to calculate the radius of gyration of a small polymer
and a small peptide, this repository (and the accompanying slides) cover the
following topics:

## Modular programming (functions, classes, and objects)
- No modularity:
    - `examples/rg_no_modular/`

- Modularity using functions:
    - `examples/rg_functions/`

- Object-oriented programming:
    - `examples/rg/`
    - `analysis_demo/rg.py`

## Testing
`tests/unit/test_rg.py` demonstrates unit testing.
`tests/integration/test_poly.py` and `tests/integration/test_peptide.py` demonstrate the use of 'gold standard' integration tests.

## Documentation
Scripts to generate documentation from `rmsd_demo`'s docstrings are in `docsource/`.
GitHub pages documentation is hosted from the `docs/` folder.

## Continuous integration
See GitHub Actions for this repository.
