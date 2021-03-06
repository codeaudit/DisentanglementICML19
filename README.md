# Learning Discrete and Continuous Factors of Data via Alternating Disentanglement
## Dependency
- python=3.5
- tensorflow version = 1.4
- CUDA 8.0
- cuDNN 6.0
- Environment detail is listed in `ex.yml'

## Citing this work
```
@inproceedings{jeongICML19,
    title={
        Learning Discrete and Continuous Factors of Data via Alternating Disentanglement
    },
    author= {Yeonwoo Jeong and Hyun Oh Song},
    booktitle={International Conference on Machine Learning (ICML)},
    year={2019}
}
```

## Dataset(dSprites)
- Download from [https://github.com/deepmind/dsprites-dataset](https://github.com/deepmind/dsprites-dataset)

## Edit path
- Edit path in 'config/path.py'
- ROOT - (directory for experiment result)
- DSPRITESPATH - (directory for downloaed dsprites)

## Run model
- Dsprites_exp/CascadeVAE/main.py
- Dsprites_exp/CascadeVAE-C/main.py

## License
MIT License 
