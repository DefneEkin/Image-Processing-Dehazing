# Image-Processing-Dehazing

This report presents our findings from integrating three spatial-domain image processing techniques to remove haze from RGB images.

Hazy images suffer from reduced contrast and color distortion due to atmospheric light scattering, which negatively affects both human perception and automated vision systems. This study investigates the use of spatial-domain image enhancement techniques for de-hazing, aiming to restore visual quality without relying on frequency-domain or learning-based approaches. Multiple enhancement algorithms were implemented and evaluated using Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM) to measure reconstruction accuracy against ground-truth images.

In addition, the effect of de-hazing on downstream scene recognition was examined by performing histogram-based classification in the HSI color space using several similarity measures. Experimental results demonstrate the relationship between restoration quality and classification performance, revealing trade-offs between perceptual enhancement and recognition accuracy. Overall, the findings provide insight into the effectiveness of spatial-domain methods for real-world image recovery and their broader impact on higher-level computer vision tasks.
