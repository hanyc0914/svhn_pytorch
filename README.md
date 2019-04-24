# svhn_pytorch

## Usage for python code

#### 0. Requirement

* python 3.5
* anaconda 4.4.0
* tensorflow 1.2.1
* keras 2.1.1
* opencv 3.3.0
* imgaug
* Etc.

```
$ pip install tensorflow==1.2.1
$ pip install keras==2.1.1
$ pip install opencv-python
$ pip install imgaug
$ pip install pytest-cov
$ pip install codecov
$ pip install h5py
$ pip install protobuf
$ pip install lmdb
```

### 1. Run code
  * `` python convert_train_to_lmdb.py``
  * `` python convert_test_to_lmdb.py``
  * `` python train.py``
  * `` python eval.py``
  * `` python plot_loss.py``
