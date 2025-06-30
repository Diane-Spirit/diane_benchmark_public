# diane-benchmark

This repository contains benchmarking data, analysis scripts, and notebooks for the DIANE project. The project focuses on collecting, merging, and analyzing network performance and latency data from various test scenarios.

## Repository Structure

- `guildford_data/`  
  Contains raw and merged data from multiple test scenarios, including:
  - `iperf3/`: Network throughput test results (images).
  - `tracert/`: Traceroute results (images).
  - `TEST-01/` to `TEST-12/`: Each folder contains merged CSVs and subfolders with detailed logs and latency results for each test.

- `notebooks/`  
  Jupyter notebooks for data analysis and visualization:
  - `classic_diane vs kde_diane.ipynb`
  - `diane_classic.ipynb`
  - `diane_multiBW.ipynb`
  - `guildford_nb.ipynb`
  - `latency_plot.ipynb`

