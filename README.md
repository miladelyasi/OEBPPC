# Open-End Bin Packing Problem with Conflicts (OEBPPC)

This repository contains benchmark instances and GVNS results related to the paper:

**Open-End Bin Packing Problem with Conflicts**  
*Ece Nur Balık, Ali Ekici, Milad Elyasi, Okan Örsan Özener*  
Department of Industrial Engineering, Özyeğin University, Istanbul, Turkey

## Overview

The **Open-End Bin Packing Problem with Conflicts (OEBPPC)** extends the classical bin packing problem by introducing conflict constraints between items and allowing a subset of items to remain unpacked (open-ended structure). This repository includes:

- Modified Falkenauer instances adapted for OEBPPC
- GVNS solution results for the modified instances

These resources support the computational study in the aforementioned paper.

## Repository Contents

- 🗂 `Falkenauer_instances_modified_uXXX.zip`: Sets of modified instances with different item counts (e.g., `u120`, `u250`, `u500`, `u1000`, `u2000`)
- 📊 `GVNS Results.xlsx`: Best solutions (number of bins used) obtained using our GVNS algorithm
- 📄 `README.md`: This file

## Instance Format

Each `.zip` file contains multiple `.txt` instances. The naming follows this format:


Where:
- `XXX`: Instance size
- `YY`: Instance number
- `Z`: Seed or variation index

## GVNS Results

The `GVNS Results.xlsx` file includes:
- `instance`: Path and name of the instance
- `Z_GVNS`: Best objective value (i.e., number of bins used) obtained by the GVNS

## How to Use

1. Download and extract the relevant instance set.
2. Use your own bin packing solver to run the instances.
3. Compare your solutions with the `Z_GVNS` values in the Excel file.

## Citation

If you use the instances or results in your research, please cite our paper:

> E. N. Balık, A. Ekici, M. Elyasi, and O. Ö. Özener. *Open-End Bin Packing Problem with Conflicts*. Department of Industrial Engineering, Özyeğin University.

*(Update with official DOI or conference/journal citation once published.)*

## License

This project is licensed under the MIT License.
