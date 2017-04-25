# CycleGAN-Models
Models generated by [CycleGAN](https://github.com/junyanz/CycleGAN).

## bear2panda
This translates bear to panda in image.

![screenshot](https://github.com/tatsuyah/CycleGAN-Models/blob/master/images/bear2panda/bear2panda-1.png)
![screenshot](https://github.com/tatsuyah/CycleGAN-Models/blob/master/images/bear2panda/bear2panda-2.png)
![screenshot](https://github.com/tatsuyah/CycleGAN-Models/blob/master/images/bear2panda/bear2panda-3.png)
![screenshot](https://github.com/tatsuyah/CycleGAN-Models/blob/master/images/bear2panda/bear2panda-4.png)


## Prerequisits
 * CycleGAN (See the [README](https://github.com/junyanz/CycleGAN) for installation)

## Usage
```
mv ./model_dir/ path/to/models_dir/
cd path/to/cyclegan-root/
DATA_ROOT=/path/to/data/ name=model_dir th train.lua
```

## Citation
```
@article{CycleGAN2017,
  title={Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks},
  author={Zhu, Jun-Yan and Park, Taesung and Isola, Phillip and Efros, Alexei A},
  journal={arXiv preprint arXiv:1703.10593},
  year={2017}
}
```
