# Radio Bridge Injection and Analysis

This repository contains a Python-based workflow for simulating and analyzing **radio bridge emission**.  
The analysis demonstrates how to:

- Work with **FITS files** using `astropy`
- Inject visibilities into model images
- Create mosaics from restored images with varying spectral index
- Apply masks to isolate **radio bridge regions**
- Compute flux density ratios:$R(\alpha) = \frac{S^{injected}_{400}}{S_{400}}$
---

## Analysis
While the astrophysical context is radio astronomy, this notebook also showcases:
- **Data wrangling** with NumPy and Astropy
- **Image processing** and masking operations
- **Scientific computing** with Python
- Handling complex data formats (FITS)

---

## Tools & Libraries
- `numpy`, `scipy`, `matplotlib`
- `astropy` (FITS handling, coordinate systems)
- `regions` (masking sky regions)
- Standard Python for-loop & workflow automation

---

## Context
This workflow is motivated by research in **cosmic bridges** between galaxy clusters.  
Scientific computing and reproducible research with Python.
