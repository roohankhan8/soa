# SOA Data Cleaning and Reporting Project

This repository houses a critical data cleaning and analysis pipeline, built using **Python and Jupyter Notebooks**, focused on preparing datasets for various reporting domains (Cargo, Equipment Failure, Interruption, Workers).

The project centralizes raw data, processing notebooks, filtered outputs, and final reporting artifacts.

## Key Features
- **Data Standardization:** Automated cleaning and preparation of raw input datasets.
- **Domain-Specific Analysis:** Dedicated Jupyter Notebooks for four distinct reporting domains.
- **Artifact Generation:** Outputs include filtered datasets, visualizations (graphs), and final summary reports (PDFs).

## Project Structure
| Folder | Purpose |
| :--- | :--- |
| `data/` | Stores the raw, unchanged input data files. |
| `data_filtered/` | Contains the cleaned and processed datasets ready for analysis. |
| `graphs/` | Generated charts and visualizations, grouped by domain. |
| `winning-reports/` | Final reports and summaries. |
| `docs/` | Supporting documentation and notes. |
| `.venv/` | Python virtual environment for dependencies. **(Exclude from source control)** |

## Core Notebooks
- `data-cleaning-cargo.ipynb`
- `data-cleaning-equipment-failure.ipynb`
- `data-cleaning-interruption.ipynb`
- `data-cleaning-workers.ipynb`

## Requirements
The project relies on a Python environment:
- **Python 3.x**
- **Jupyter Notebook** or **JupyterLab**
- **Core Libraries:** pandas, numpy, matplotlib, etc. (install via \`.venv\`)

## Usage Guide
1. **Activate Environment:** Ensure your Python virtual environment (\`.venv\`) is active.
2. **Run Analysis:** Open the relevant domain notebook (\`data-cleaning-*.ipynb\`).
3. **Execute Cells:** Run all cells sequentially (top-to-bottom) to:
    - Load data from \`data/\`.
    - Apply data cleaning and transformation steps.
    - Generate outputs in \`data_filtered/\` and \`graphs/\`.
4. **Review Outputs:** Check the generated datasets, graphs, and the final reports.

## Artifact Notes
The following PDF files were found in the root, which appear to be final reports or related documents:
- \`factuarial.pdf\`
- \`interstellar.pdf\`
- \`srcsc-2024-statsmart-solutions.pdf\`

## License
[Insert License Here]
