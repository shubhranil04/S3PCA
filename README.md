# Superpixel-Based Unsupervised PCA Methods for Hyperspectral Image Classification  
*Shubhranil Chatterjee*  

This project explores dimensionality reduction techniques for hyperspectral images (HSIs), focusing on superpixel-based approaches such as **SuperPCA** and **S3-PCA**. These methods utilize spatial-spectral segmentation (e.g., ERS and SLIC) to form meaningful clusters and extract localized low-dimensional representations for improved classification performance.

In addition to replicating experiments from the original paper, we further evaluate the impact of:
- Segmentation technique (ERS on principal projection vs. full HSI, and SLIC),
- Reconstruction criteria (spectral, spatial, and combined proximity),
- Parameter tuning for optimal performance.

All code, data, and results are part of the course project for **IE506 - Machine Learning Principles and Techniques**, conducted in Spring 2025 at **IIT Bombay**.

References:

Jiang, Junjun, et al. "SuperPCA: A Superpixelwise PCA Approach for Unsupervised Feature Extraction of Hyperspectral Imagery." IEEE Transactions on Geoscience and Remote Sensing, vol. 56, no. 8, 2018, pp. 4581–4593. DOI: 10.1109/TGRS.2018.2828029

Zhang, Xin, et al. "Spectral–Spatial and Superpixelwise PCA for Unsupervised Feature Extraction of Hyperspectral Imagery." IEEE Transactions on Geoscience and Remote Sensing, vol. 60, 2022, pp. 1-10. DOI: 10.1109/TGRS.2021.3057701

Liu, Ming-Yu, et al. "Entropy rate superpixel segmentation." CVPR 2011, 2011, pp. 2097-2104. DOI: 10.1109/CVPR.2011.5995323

Achanta, Radhakrishna, et al. "SLIC Superpixels Compared to State-of-the-Art Superpixel Methods." IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 34, no. 11, 2012, pp. 2274-2282. DOI: 10.1109/TPAMI.2012.120
