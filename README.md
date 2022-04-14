# IOSDA

An unsupervised domain adaptation with input and output space alignment for joint optic disc and cup segmentation

---
Architecture of IOSUDA

![](https://github.com/EdisonCCL/IOSUDA/blob/master/images/IOSUDA.png)
---
## Train

train a new model:

`python train.py`

---
## Test

test the trained model:

`python test.py`

---
## Metric

Left subfigure is jaccard index of OC and right subfigure is jaccard index of OD on RIM-ONE_r3 dataset.

![](https://github.com/EdisonCCL/IOSUDA/blob/master/images/training_process.png)

---
BibTeX Citation
```
@article{chen2021iosuda,
  title={IOSUDA: an unsupervised domain adaptation with input and output space alignment for joint optic disc and cup segmentation},
  author={Chen, Chonglin and Wang, Gang},
  journal={Applied Intelligence},
  volume={51},
  number={6},
  pages={3880--3898},
  year={2021},
  publisher={Springer}
}
```
