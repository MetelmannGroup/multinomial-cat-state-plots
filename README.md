This repository contains a Jupyter notebook .ipynb file that has been used to plot figures for the paper "Dissipative preparation and stabilization of $d$-mode multinomial cat states". The codes are written using Jupyter notebook 6.5.7 and Qutip 5.3.

# Reading the notebook
To run the file, you need the Jupyter notebook (offline version) installed on your desktop, or simply use google colab (online version).

# Installation
For Windows users, it is recommended to install Anaconda, which includes Python and Jupyter Notebook by default.

## 1. Install Anaconda
Download Anaconda from the official website:
[https://www.anaconda.com/download](https://www.anaconda.com/download)
Follow the installation instructions for Windows.

## 2. Launch Jupyter Notebook
After installation, you can start Jupyter Notebook using either:
  **Option A: Anaconda Navigator**
  * Open Anaconda Navigator
  * Click Launch under Jupyter Notebook
  
  **Option B: Command line (Anaconda Prompt)**
  ```bash
  jupyter notebook
  ```
This will open Jupyter Notebook in your browser.

## 3. Install QuTiP (Quantum Toolbox in Python)
QuTiP can be installed using the conda-forge channel.
Official QuTiP conda-forge page:
[https://anaconda.org/channels/conda-forge/packages/qutip/overview](https://anaconda.org/channels/conda-forge/packages/qutip/overview)


To install QuTiP, run:
```bash
conda install -c conda-forge qutip
```

## Alternative (pip)
```bash
pip install qutip
```

## Verification (optional)
```python
import qutip
print(qutip.__version__)
```

## Summary
* Install Anaconda (includes Jupyter Notebook)
* Launch Jupyter Notebook via Navigator or terminal
* Install QuTiP using conda-forge:
  [https://anaconda.org/conda-forge/qutip/overview](https://anaconda.org/conda-forge/qutip/overview)
* Verify installation in Python

# Usage
To use the code, simply open the .ipynb file using Jupyter notebook, and evaluate the cells sequentially to obtain the results. In particular:
  * Cell 1: installing qutip and importing all necessary packages.
  * Cell 2: plotting Figure 1
  * Cell 3: data for plotting Figure 2
  * Cell 4: data for plotting Figure 3
  * Cell 5: data for plotting Figure 5
  * Cell 6: data for plotting Figure 6
  * Cell 7: data for plotting Figure 7

You can change the parameters, Hamiltonians, and operators in the code to obtain the results for your case. The current defined set-ups in the code can be used to reproduce their corresponding figures in our manuscript.

Please let us know if you have any comments/suggestions.
If you use this code for your work, please cite the following paper :
Dissipative preparation and stabilization of $d$-mode multinomial cat states (link to be added).

# License
This work is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. See https://creativecommons.org/licenses/by/4.0/ 
