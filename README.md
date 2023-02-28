# GraphFeatureExtractor

This repo is a python implementation of graph feature extraction using the graph neural networks. 


## Requirements

#### Required Packages
* **python** 3+
* **TensorFlow** 1.14.0 (tf2.0 is not supported)
* **keras** 2.2.4 with TensorFlow backend
* **sklearn** 0.20.2
* **docopt** as a command-line interface parser 

Run the following script to install the required packages.
```shell
pip install --upgrade pip
pip install tensorflow==1.14.0
pip install keras==2.2.4
pip install scikit-learn==0.20.2
pip install docopt
```

## Running project
* To run the program, use this command: python MPGNN.py.

Examples:
```shell
python MPGNN.py --random_seed 9930 --thresholds 0.45
```

** Note: we present an example for extracting the graph feature of the reentrancy vulnearbility.
