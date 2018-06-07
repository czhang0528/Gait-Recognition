# Gait-Recognition
Released caffe model of ICASSP 2016 on siamese network based gait recognition for human identification. 
* C. Zhang, W. Liu, H. Ma, and H. Fu, “[Siamese neural network based gait recognition for human identification](http://web.cse.ohio-state.edu/~zhang.7804/Cheng_ICASSP2016.pdf),” in IEEE ICASSP, pp. 2832–2836, 2016

## Dataset
* The paper evaluates the proposed approach on the OULP-C1V1-A dataset from the [OU-ISIR LP gait benchmark](http://www.am.sanken.osaka-u.ac.jp/BiometricDB/GaitLP.html), which contains
the world’s largest number of subjects with a wide age and an almost balanced gender ratio. Our model is trained on gallery set.

## Model
* Clone and build the caffe model from [here](https://github.com/BVLC/caffe).
* Extract features based on models and prototxt files

      model_iter_50000.caffemodel and model_iter_50000.solverstate: well-trained model based on caffe
      train_test.prototxt: training prototxt file
      siamese_deploy.prototxt: testing prototxt file
* The framework is as follows:
      <center><img src="https://github.com/czhang0528/Gait-Recognition/blob/master/fig1.png" width="90%"/></center>

## Performance
    
   <center><img src="https://github.com/czhang0528/Gait-Recognition/blob/master/fig2.png" width="80%"/></center>

   <center><img src="https://github.com/czhang0528/Gait-Recognition/blob/master/fig3.png" width="50%"/></center>

## Citation
Please cite the following papers if you find it useful.
```
@inproceedings{zhang2016siamese,
      title={Siamese neural network based gait recognition for human identification},
      author={Zhang, Cheng and Liu, Wu and Ma, Huadong and Fu, Huiyuan},
      booktitle={ICASSP},
      pages={2832--2836},
      year={2016},
      booktitle={IEEE}
}

@article{Liu2018LearningES,
      title={Learning Efficient Spatial-Temporal Gait Features with Deep Learning for Human Identification},
      author={Wu Liu and Cheng Zhang and Huadong Ma and Shuangqun Li},
      journal={Neuroinformatics},
      year={2018},
      pages={1-15}
}
```

## Contact
[Cheng Zhang](https://github.com/czhang0528) (zhang.7804@osu.edu)
