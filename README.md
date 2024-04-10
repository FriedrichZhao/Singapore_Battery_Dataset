## SingaporeBatteryDataset

In this study, we conducted data collection and prepared an in-house battery-type database. We searched from various sources such as Google Images and online shopping websites with battery images and the image selection is based on different practical settings. Each image is manually labelled as 9 specific battery types and the label is verified by a different researcher before the image is included in the dataset. It is impractical to enumerate all battery types due to technical and cost constraints. In BatSort, we incorporate a comprehensive range of common battery types. The dataset is balanced with about 50 images for each battery type. We consider common battery types in Singapore, including:

1. Duracell (alkaline), 
2. IKEA (alkaline), 
3. Energizer (alkaline), 
4. Energizer (industrial), 
5. Energizer (lithium), 
6. Exell (Ni-MH), 
7. Exell (Ni-CD), 
8. GP (alkaline), 
9. Klarus, 
10. Others.

For those outside this scope, we introduce a general category termed as "Others". A group for miscellaneous other battery types with 50 images is included and they are used in model performance evaluation. Altogether we have ∼500 images. All images undergo data cleaning and pre-processing.

## Citation

If you find this work helpful, please consider to star this repository and cite our paper:

*BatSort: Enhanced Battery Classification with Transfer Learning for Battery Sorting and Recycling* [[arXiv: 2404.05802](https://arxiv.org/abs/2404.05802)]

```
@misc{zhao2024batsort,
      title={BatSort: Enhanced Battery Classification with Transfer Learning for Battery Sorting and Recycling}, 
      author={Yunyi Zhao and Wei Zhang and Erhai Hu and Qingyu Yan and Cheng Xiang and King Jet Tseng and Dusit Niyato},
      year={2024},
      eprint={2404.05802},
      archivePrefix={arXiv},
      primaryClass={cs.CE}
}
```