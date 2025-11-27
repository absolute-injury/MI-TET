## File Discriptions

### Code
**Numerical Simulation**: The main simulation is executed by the code `Numerical_Simulation`.
* **Data Writing**: The `Data Writing` script post-processes the training logs and organizes them into a clean CSV format.
* **Data Plotting**: Scripts named `Data Plotting *` (or similar) read the CSV files to visualize and generate the figures presented in the paper.

### Data (CSV Files)
The CSV files are categorized based on the **bin count** parameter (10 or 50) used during the simulation:
* **Bin Count 10**: Files are saved with the prefix `resuls_*`.
* **Bin Count 50**: Files are saved with the prefix `results_*`.
