# Supercapacitor CV Analysis

Python-based analysis of cyclic voltammetry (CV) data from
asymmetric supercapacitor cells (e.g. Fe₃O₄ // Ni).

## Features
- Import EC-Lab `.txt` CV files
- Plot current vs potential
- Clean, reproducible workflow for electrochemical analysis

## Example
```python
plt.plot(cvdata['Ewe/V'], cvdata['<I>/mA'])
