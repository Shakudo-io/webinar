![](rapids.png)

# Using Rapids 

These notebooks compare [RAPIDS](https://rapids.ai) on GPU's to conventional Python tools on CPU's.

### 1. cuDF compared to Pandas

The [movies](movies.ipynb) notebook compares the cuDF API to the Pandas API. In many cases switching code from CPU to GPU is seamless. In other cases some adjustments are required. Click here to [download](https://bsql.s3.amazonaws.com/data/rapids_intro/movies.csv) the data.

### 2. GPU compared to CPU

The [babynames](babynames.ipynb) notebook compares performance between a single GPU and a single CPU. All tests showed double digit performance improvements when run on a Tesla P4. Results will vary depending on the system environment. Click here to [download](https://www.ssa.gov/oact/babynames/state/namesbystate.zip) the data.

### 3. MultiGPU RAPIDS on [Hyperlane](shakudo.io)

The [haversine_distance](haversine_distance.ipynb) notebook performance multi-GPU haversine distance calculation with RAPIDS CuSpatial package on distributed dask cluster using Hyperplane. Test shows 1-liner scale up of distributed GPU dask cluster and 3x speed up with 2 remote GPUs compared to 1 local GPU. Click here to [download](https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2009-01.csv) the data.