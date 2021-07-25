# Efficient UNet for Few Shot Segmentation

## UNet Architecture

![UNet](https://github.com/Rituraj-commits/Efficient-UNet-for-few-shot-segmentation/blob/main/Unet.png)




## EfficientNet

A comparision of EfficientNet

![EfficientNet](https://github.com/Rituraj-commits/Efficient-UNet-for-few-shot-segmentation/blob/main/flops.png)

|     Model       |  Parameters   |
| -------------   | ------------- |
| EfficientNet-B0 |     5.3M      |
| EfficientNet-B1 |     7.8M      |
| EfficientNet-B2 |     9.2M      |
| EfficientNet-B3 |     12M       |
| EfficientNet-B4 |     19M       |
| EfficientNet-B5 |     30M       |
| EfficientNet-B6 |     43M       |
| EfficientNet-B7 |     66M       |


### Dependencies

```
pip install efficientnet-pytorch
```


### Executing program

* Download FSS-1000 dataset for training scripts  [FewShot.zip](https://drive.google.com/file/d/1rgqhrt9E5_B4wSn9A1Vot0tg_JDt6AkH/view?usp=sharing)
* Download FSS-1000 dataset for Evaluate Script  [fewshot.zip](https://drive.google.com/file/d/16MFtVhkBm7_8OE41zLIwwFRmIMWF2oCp/view?usp=sharing) 
* Train-Test split file : fss_test_set.txt

## Acknowledgements

* [FSS-1000](https://github.com/HKUSTCV/FSS-1000)
* [EfficientNet](https://github.com/lukemelas/EfficientNet-PyTorch)
