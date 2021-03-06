# Robust 3D Face Alignment with Efficient Fully Convolutional Neural Networks - Pytorch
Accepted in: The 10th International Conference on Image and Graphics(ICIG2019)-Oral

## Note
In 'Demo.py' file, you will find how to run these codes.
In 'FaceSwap/Demo2.py' file, you will find how to run face swap code.

## Abstract
In this paper proposes a novel and efficient end-to-end 3D face alignment framework.We build an efficient and stable network model through Depthwise Separable Convolution
and Densely Connected Convolutional,named MobDenseNet. Simultaneously,different loss functions are used to constrain 3D parameters based on 3D Morphable Model (3DMM) and 3D vertices

### The framework of ours proposes method
![](https://github.com/LeiJiangJNU/R3FA/blob/master/figures/framework01.png)

### MobDenseNet Structure
![](https://github.com/LeiJiangJNU/R3FA/blob/master/figures/MobDenseNet.png)

### Layer3 Structure-DenseBlock
![](https://github.com/LeiJiangJNU/R3FA/blob/master/figures/layer3.png)

## Experimental results

### Comparison on other method
![](https://github.com/LeiJiangJNU/R3FA/blob/master/figures/nme01.png)

### Comparison on different network structures
![](https://github.com/LeiJiangJNU/R3FA/blob/master/figures/nme02.png)

### 3D Face Alignment Results
![](https://github.com/LeiJiangJNU/R3FA/blob/master/figures/results.png)

If you have any question about this code, feel free to reach me(ljiang_jnu@outlook.com)


# Citation

If you find this repository useful for your research, please cite the following paper:
```
@inproceedings{jiang2019dual,
  title={Dual Attention MobDenseNet (DAMDNet) for Robust 3D Face Alignment},
  author={Jiang, Lei and Wu, Xiao-Jun and Kittler, Josef},
  booktitle={Proceedings of the IEEE International Conference on Computer Vision Workshops},
  pages={0--0},
  year={2019}
}
```
```
@inproceedings{jiang2019robust,
  title={Robust 3D Face Alignment with Efficient Fully Convolutional Neural Networks},
  author={Jiang, Lei and Wu, Xiao-Jun and Kittler, Josef},
  booktitle={International Conference on Image and Graphics},
  pages={266--277},
  year={2019},
  organization={Springer}
}
```
