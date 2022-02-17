![](rapids_shakudo.png)

# Scaling machine learning with multi-GPU RAPIDS
### NVIDIA & [Shakudo](https://bit.ly/3FdAeRu) joint webinar held on Feb. 16. 2021
This repository contains example notebooks from the demo portion of the webinar.
Some of the packages used is specific to the Hyperplane platform and may not be replicable on other environements. 

# Using Rapids 

These notebooks compare [RAPIDS](https://rapids.ai) on GPU's to conventional Python tools on CPU's and multi-node-multi-GPU [RAPIDS](https://rapids.ai) compared to single-GPU RAPIDS.

### 1. # Scale Out Demo: K-means (CPU-to-GPU-to-MNMG)
This notebook introduces scaling out with RAPIDS and Dask. It introduces how Dask works "under the hood" and shows how to modify Python code to leverage RAPIDS and Dask.

### 2. GPU compared to CPU

The [multi-CPU example](multiCPU.ipynb) notebook scales Kmeans from single CPU node to distributed nodes with Dask and Hyperplane APIs.

### 3. MultiGPU RAPIDS on [Hyperlane](https://bit.ly/3GWTymp)

The [multi-GPU example](multiGPU_rapids.ipynb.ipynb) notebook scales Kmeans from single GPU node to distributed GPU nodes with Dask and Hyperplane APIs and acheved ~50x speed up compated to multi-CPU and 2x speed up compared to single GPU RAPIDS.