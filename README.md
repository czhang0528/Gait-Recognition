# Gait-Recognition
Released caffe model of ICASSP 2016 on siamese network based gait recognition for human identification. 
```
C. Zhang, W. Liu, H. Ma, and H. Fu, “Siamese neural network based gait recognition for human identification,” in IEEE ICASSP, pp. 2832–2836, 2016
```
## Model
Clone and build the caffe model from [here](https://github.com/BVLC/caffe).

Extract features based on models and prototxt files

model_iter_50000.caffemodel and model_iter_50000.solverstate: well trained model based on caffe

train_test.prototxt: training prototxt file

siamese_deploy.prototxt: testing prototxt file

The framework is as follows:

## Performance

## Citation
Please cite the following if you find it useful.
```
@inproceedings{zhang2016siamese,
      title={Siamese neural network based gait recognition for human identification},
      author={Zhang, Cheng and Liu, Wu and Ma, Huadong and Fu, Huiyuan},
      booktitle={ICASSP},
      pages={2832--2836},
      year={2016},
      booktitle={IEEE}
}
```

## Contact
[Cheng Zhang](https://github.com/czhang0528) (zhang.7804@osu.edu)
