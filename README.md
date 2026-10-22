# 🐴 Automatic Pain Assessment in Equines
This repository accompanies our work on automatically assessing equine pain from facial images using head-pose estimation, facial landmarks, and pain classification.

## Libraries
```
pip install statsmodel
pip install opencv-python==3.4.2.16
pip install opencv-contrib-python==3.4.2.16
pip install keras
pip install pickle-mixin
pip install tensorflow
pip install tensorflow-gpu-estimator
pip install flickrapi #to download images from flickr

conda install scikit-learn=0.21.3

conda install -c conda-forge menpo opencv menpo menpofit

```

To train the Supervised Descent Model: (Not necessary to run the pipeline)
```
conda install -c menpo cyvlfeat
```

**To get 3D Landmarks**
Install PyGem and dependencies
```
conda install opencv
pip install trimesh
```

**New environment**
```
conda create -n horses_final python=3.6
pip install opencv-python==3.4.2.16
pip install flickrapi #to download images from flickr
conda install scikit-learn=0.21.3
conda install -c conda-forge menpo opencv menpo menpofit
pip install trimesh
conda install matplotlib
conda install -c conda-forge trimesh
pip install networkx

conda install pytorch==0.4.1 -c pytorch
conda install xlrd
conda install -c conda-forge scikit-image
```

## Citation

Pessanha, F., Salah, A. A., van Loon, T., & Veltkamp, R. (2023). *Facial Image-Based Automatic Assessment of Equine Pain*. **IEEE Transactions on Affective Computing, 14**(3), 2064–2076. [https://doi.org/10.1109/TAFFC.2022.3177639](https://doi.org/10.1109/TAFFC.2022.3177639)

```
bibtex
@article{Pessanha2023Facial,
  author    = {Pessanha, Francisca and Salah, Albert Ali and van Loon, Thijs and Veltkamp, Remco},
  title     = {Facial Image-Based Automatic Assessment of Equine Pain},
  journal   = {IEEE Transactions on Affective Computing},
  year      = {2023},
  volume    = {14},
  number    = {3},
  pages     = {2064--2076},
  month     = jul,
  doi       = {10.1109/TAFFC.2022.3177639},
  url       = {https://doi.org/10.1109/TAFFC.2022.3177639}
}
```

