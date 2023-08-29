# Chem 274A - Lab 1

In this lab, you will be using the molecular simulation code we wrote in Chem 280 - Foundations of Molecular Modelling and Software Engineering.

## Exercises

### Section 1 - Makefile (Spend 30 minutes max on this)
1. Use the `makefile` to create an environment for this lab.
    ```
    cd mcsim_python
    make environment
    ```
2. Activate the environment created by the `makefile`
    ```
    conda activate chem274A_lab1
    ```
3. Use the `makefile` to install `mcsim`
    ```
    make install
    ```

4. Review the Makefile in `mcsim_python`. Write a comment above each target explaining what the target does. Make a note of any questions you have in your `README.md`(this file).

### Section 2 - Runnning Simulations
1. Use the notebook `run_mcsim.ipynb` to run Monte Carlo simulations. Follow the instructions in the notebook.