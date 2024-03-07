# Portfolio optimization

This is the origin Pytorch implementation of *Portfolio optimization*.

**News**(03, 08, 2024): Will be updated.
 

## Get Started

1. Install Python 3.6, PyTorch 1.9.0.
2. Will be updated

### Reproduce with Docker

To easily reproduce the results using Docker, conda and Make,  you can follow the next steps:
1. Initialize the docker image using: `make init`. 
2. Download the datasets using: `make data`.
3. Will be updated
```
for file in `ls scripts`; do make run_module module="bash runfile/runfile"; done
```

## Baselines

We will keep adding Predicting movements of asset prices models to expand this repo:

- [x] Historical covariance (HC) 
- [x] The shrinkage method (SM) of Ledoit and Wolf (2004)
- [x] The Gerber Statistic (GS) of Gerber, Markowitz, Ernst, Miao Sargen (2021)
- [x] SimStock (SS) of Hwang et al (2023)

## Citation

If you find this repo useful, please cite our paper. 

```
Will be update
```

## Contact
If you have any questions or want to use the code, please contact `yoontae@unist.ac.kr`. 

## Data
The data are not provided for legal reasons.
