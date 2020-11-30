[![DOI](https://zenodo.org/badge/DOI/10.1103/PhysRevE.102.053216.svg)](https://doi.org/10.1103/PhysRevE.102.053216)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/valenpe7/wakefield_polarity_reversal/main?urlpath=lab/tree/wakefield_polarity_reversal.ipynb)

# Polarity Reversal of Wakefields Driven by Ultrashort Pulse Laser

This repository contains supplementary material for the work entitled "*Polarity Reversal of Wakefields Driven by Ultrashort Pulse Laser*" that has been published in APS **Physical Review E** (https://doi.org/10.1103/PhysRevE.102.053216).

The supplementary material consists of the raw data computed by the **[EPOCH](https://cfsa-pmw.warwick.ac.uk/EPOCH)** code (v4.17.10) and the **[Jupyter](https://jupyter.org/)** notebook with the set of commands that have been used for developing the analytical model and generating the figures.

The analysis is performed using Python 3 programming language and relies on several Python packages: [numpy](https://github.com/numpy/numpy), [scipy](https://github.com/scipy/scipy), [matplotlib](https://github.com/matplotlib/matplotlib), and [sdf](https://github.com/keithbennett/SDF).

### How to obtain the data:

Due to its size (7.4 GB), the raw data used in this work is stored on **Zenodo**. You may download the data as a .zip archive on the following link: https://zenodo.org/record/4298843#.X8UqaGieFaQ.

### How to obtain the notebook:

The notebook `wakefield_polarity_reversal.ipynb` is stored in this GitHub repository. You may either download the whole repository as a .zip archive by selecting "Code" and then "Download ZIP", or use `git`:

1. Clone the repository: ``` $> git clone https://github.com/valenpe7/wakefield_polarity_reversal.git ```
2. Pull in new changes: ``` $> git pull ```

### How to launch the notebook:

If you have downloaded the notebook and the data and have all the requirements installed on your computer, you may launch the notebook locally. Alternatively, if you do not have installed all the requirements, you may launch the notebook on-line using
* **Jupyter NBViwever** (non-interactive): https://nbviewer.jupyter.org/github/valenpe7/wakefield_polarity_reversal/blob/main/wakefield_polarity_reversal.ipynb

* **Binder** (interactive): https://mybinder.org/v2/gh/valenpe7/wakefield_polarity_reversal/main?urlpath=lab/tree/wakefield_polarity_reversal.ipynb

### How to cite:

Cite as: P. Valenta et al., *Phys. Rev. E* **102**, 053216 (2020).
```
@article{doi:10.1103/PhysRevE.102.053216,
        author = {Valenta, P. and Esirkepov, T. Zh. and Koga, J. K. and Necas, A. and Grittani, G. M. and Lazzarini, C. M. and Klimo, O. and Korn, G. and Bulanov, S. V.},
        title = {Polarity reversal of wakefields driven by ultrashort pulse laser},
        journal = {Physical Review E},
        volume = {102},
        issue = {5},
        pages = {053216},
        numpages = {5},
        year = {2020},
        month = {Nov},
        publisher = {American Physical Society},
        doi = {10.1103/PhysRevE.102.053216},
        url = {https://link.aps.org/doi/10.1103/PhysRevE.102.053216}
}
```

### Acknowledgements:

This work was supported by ERDF (CZ.02.1.01/0.0/0.0/15_003/0000449), MEYS (LM2015070), and EPSRC (EP/G054950/1, EP/G056803/1, EP/G055165/1, EP/M022463/1).

---

In case of any questions, please contact the corresponding author or submit an **[issue](https://github.com/valenpe7/wakefield_polarity_reversal/issues)** to this GitHub project repository.
