# UnLoc-PyTorch
This repository contains the test codes implemented with PyTorch for the paper [Virtual Training for a Real Application: Accurate Object-Robot Relative Localization without Calibration](http://imagine.enpc.fr/~loingvi/unloc/).

## Data and Trained models
UnLoc dataset is composed of three sub-datasets ('lab', 'field', 'adv'). They can be downloaded [here](http://imagine.enpc.fr/~loingvi/unloc/UnLoc.tar.gz).

Trained models presented in the paper can be download [here](http://imagine.enpc.fr/~loingvi/unloc/unloc_trained_models.tar.gz). 

CAD models of the ABB IRB120 robot are available on this [page](https://new.abb.com/products/robotics/industrial-robots/irb-120/irb-120-cad).

Clamp 3D models are available here: [[clamp.stl]](http://imagine.enpc.fr/~loingvi/unloc/clamp.stl)[[clamp.3ds]](http://imagine.enpc.fr/~loingvi/unloc/clamp.3ds)[[clamp.obj]](http://imagine.enpc.fr/~loingvi/unloc/clamp.obj)

## Test
The programming language is Python with the PyTorch 0.4 framework. 

You can test these trained models on the UnLoc dataset. For example, for coarse estimation on the 'lab' dataset, put 'model_coarse_estimation.tar' file in the same folder as the test code and launch:

```
python coarse_estimation.py
```

## Acknowledgement
The original test code is implemented by Vianney Loing with Torch and this is a PyTorch version of it. Some parts of the code come from  [PyTorch official example code](https://github.com/pytorch/examples/tree/master/imagenet).
