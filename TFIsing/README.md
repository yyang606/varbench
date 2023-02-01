# Transverse-Field Ising Model

The model is defined on the edges of an arbitrary graph and reads
$$H = \Gamma \sum_i \sigma^x_i + V \sum_{\langle i, j \rangle} \sigma^z_i \sigma^z_j$$
where we take Pauli matrices $\sigma^{x, y, z}_i$.
It is assumed that the unit of energy is $V = 1$.

## Naming

The names of the data files follow the convention `lattice_N_Gamma.md`

* `lattice` is the lattice geometry (see `lattice.md`)
* `N` is the number of spins
* `Gamma` is the transverse field $\Gamma$