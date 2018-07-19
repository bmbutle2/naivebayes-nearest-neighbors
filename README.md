# Naive Bayes Nearest Neighbor Classifier (NBNN)

A robust, non-parametric, and learning-free algorithm for image classification.

## Summary

The NBNN algorithm is based on the work of O Boiman [[1]] and uses a kd-tree nearest neighbor search scheme and the SIFT algorithm [[2]] for calculating image descriptors.

NBNN is a non-parametric, learning-free approach that does not require any training or hyperparameter tuning. The primary computational cost lies in constructing kd-trees and performing nearest neighbor searches. By using SIFT descriptors it is robust against image distortion, noise, rotation, illumination, etc.

As written, this implementation is stricly intended for multi-class classification problems in which every class is well-defined. It may be extended to accommodate other types of problems.

## References

[[1]] O Boiman et al. In Defense of Nearest-Neighbor Based Image Classification. *IEEE Conference on Computer Vision and Pattern Recognition*, 2008.

[[2]] David G Lowe. Distinctive Image Features from Scale-Invariant Keypoints. *International Journal of Computer Vision*, 2004.

More about SIFT here: [Introduction to SIFT](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_sift_intro/py_sift_intro.html)


[1]: http://www.wisdom.weizmann.ac.il/~irani/PAPERS/InDefenceOfNN_CVPR08.pdf
[2]: https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf
