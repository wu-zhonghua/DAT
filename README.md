# Dual Adaptive Transformations for Weakly Supervised Point Cloud Segmentation (ECCV 2022)


# Installation

This implementation has been tested on Ubuntu 18.04. Details are provided in [INSTALL.md](./INSTALL.md).

# Experiments

## Preparing Dataset

Processed S3DIS dataset can be downloaded <a href="https://www.dropbox.com/sh/hedb6yilh9v7fw4/AACrljL1t7SzOdx8WNPrLK84a?dl=0">here</a>. Download the dataset and move it to `Data/`.

## Training

Simply run the following script to start the training:

        python train_S3DIS.py

## Testing

To test the trained model, please run the script:

        python test_models.py


# Citation

If you find this project useful, please consider citing:
```
@article{wu2022dual,
  title={Dual Adaptive Transformations for Weakly Supervised Point Cloud Segmentation},
  author={Wu, Zhonghua and Wu, Yicheng and Lin, Guosheng and Cai, Jianfei and Qian, Chen},
  journal={arXiv preprint arXiv:2207.09084},
  year={2022}
}
```