This project presents a computational study of 2D site percolation on a square lattice, a fundamental model in statistical physics for understanding phase transitions and connectivity.

Using Monte Carlo methods with Python, NumPy, and SciPy, this analysis covers three core aspects of the percolation model:
1.  **Visualization:** Demonstrating the qualitative difference between the subcritical, critical, and supercritical phases.
2.  **Susceptibility Analysis:** Quantitatively identifying the critical probability threshold `p_c` by finding the peak of the mean finite cluster size (susceptibility).
3.  **Fractal Dimension:** Calculating the fractal dimension `D_f` of the spanning cluster at `p_c` using the box-counting method.

---
### **Application in Undergraduate Research**

This simulation, developed in **2023**, served as the foundational work for my undergraduate research project, which applied percolation theory to model urban traffic dynamics.

The concepts explored here were adapted to analyze traffic flow. In the model, the lattice represented a city grid, the occupation probability `p` corresponded to vehicle density, and the "spanning cluster" was analogous to a city-wide traffic jam. This foundational code was essential for understanding the critical thresholds that lead to large-scale jamming transitions.