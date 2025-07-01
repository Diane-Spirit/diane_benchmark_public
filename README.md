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

## Cite us
If you use this code in your work, please cite the DIANE project as follows:

```
@inproceedings{10.1145/3712676.3719263,
  author = {Barone, Nunzio and Brescia, Walter and Santangelo, Gabriele and Maggio, Antonio Pio and Cisternino, Ivan and De Cicco, Luca and Mascolo, Saverio},
  title = {Real-time Point Cloud Transmission for Immersive Teleoperation of Autonomous Mobile Robots},
  year = {2025},
  isbn = {9798400714672},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3712676.3719263},
  doi = {10.1145/3712676.3719263},
  booktitle = {Proceedings of the 16th ACM Multimedia Systems Conference},
  pages = {311–316},
  numpages = {6},
  keywords = {teleoperation, mobile robots, VR, point clouds, WebRTC},
  location = {Stellenbosch, South Africa},
  series = {MMSys '25}
}
```

or: 

DIANE: Distributed Immersive Platform for Robot Teleoperation. https://github.com/Diane-Spirit