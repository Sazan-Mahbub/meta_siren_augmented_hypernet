# Meta-SIREN Augmented Hyper-Network
This is the official implementation of our proposed method _Meta SIREN Augmented Hyper-Network_ ([first draft]()), an attempt to speed up hyper-network training.

Please note that, this project extensively uses code from the following two repositories. If you use any code from our repository, please cite the papers mentioned below.
1. https://github.com/vsitzmann/metasdf (Paper: MetaSDF: Meta-learning Signed Distance Functions. Vincent Sitzmann*, Eric Ryan Chan*, Richard Tucker, Noah Snavely
Gordon Wetzstein)
2. https://github.com/vsitzmann/siren (Paper: Implicit Neural Representations with Periodic Activation Functions. Vincent Sitzmann*, Julien N. P. Martel*, Alexander W. Bergman, David B. Lindell, Gordon Wetzstein)

This repository contains jupyter notebooks for three experiments with three different architectures we compared in our study. We also provided the notebook with our cross-attention based improvement of hyper-network that we are currently experimenting with.
1. Original Hyper-Network: [MetaSDF_on_HyperNet_from_Original_2.ipynb](https://github.com/Sazan-Mahbub/meta_siren_augmented_hypernet/blob/master/MS-A-HN/MetaSDF_on_HyperNet_from_Original_2.ipynb)
2. Meta-SIREN Augmented Hyper-Network (without custom loss): [MetaSDF_on_HyperNet_from_SIREN.ipynb](https://github.com/Sazan-Mahbub/meta_siren_augmented_hypernet/blob/master/MS-A-HN/MetaSDF_on_HyperNet_from_SIREN.ipynb)
3. Meta-SIREN Augmented Hyper-Network (with custom loss): [MetaSDF_on_HyperNet_from_SIREN-SSIM_loss.ipynb](https://github.com/Sazan-Mahbub/meta_siren_augmented_hypernet/blob/master/MS-A-HN/MetaSDF_on_HyperNet_from_SIREN-SSIM_loss.ipynb)
4. Meta-SIREN Augmented Hyper-Network (with custom loss): [MetaSDF_on_HyperNet_from_SIREN-CrossAttention.ipynb](https://github.com/Sazan-Mahbub/meta_siren_augmented_hypernet/blob/master/MS-A-HN/MetaSDF_on_HyperNet_from_SIREN-CrossAttention.ipynb)

