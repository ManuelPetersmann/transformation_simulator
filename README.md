# FEM grain structure strain energy minimizer

Given a grain structure, where each grain can have 1...N grain different grain strains.
<img src="https://raw.githubusercontent.com/ManuelPetersmann/FEM_grain_structure_strain_energy_minimizer/master/img17.png" width="400">
<!-- ![](https://raw.githubusercontent.com/ManuelPetersmann/FEM_grain_structure_strain_energy_minimizer/master/img17.png | width=100)  -->

and under suitable boundary conditions (e.g. periodic boundary conditions, or embedding the grain structure into a matrix like shown here)
<img src="https://raw.githubusercontent.com/ManuelPetersmann/FEM_grain_structure_strain_energy_minimizer/master/img16.png" width="400">
<!-- ![test](https://raw.githubusercontent.com/ManuelPetersmann/FEM_grain_structure_strain_energy_minimizer/master/img16.png | width=100)  -->

the given phython scripts transform each grain, one by one, trying out all possible transformation strains a grain can have in the following energy-minimizing manner:

<img src="https://raw.githubusercontent.com/ManuelPetersmann/FEM_grain_structure_strain_energy_minimizer/master/procedure_IEMA.JPG" width="400">

## Reference
If you've found this useful please consider referencing this repository in your own work
```
@software{manuel_petersmann_2017a,
  author       = {Petersmann, M.; Antretter, T.; Waitz, T. & Fischer, F. },
  title        = {A new approach predicting the evolution of laminated nanostructures-Martensite in NiTi as an example},
  year         = 2017,
  publisher    = {Modelling and Simulation in Materials Science and Engineering},
  doi          = {10.1088/1361-651X/aa5ab4},
  url          = {https://doi.org/10.1088/1361-651X/aa5ab4}
}
```
