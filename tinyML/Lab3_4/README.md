## 作業 readme

## Hw1 : Images Classification 
1. change the model architecture (add / remove some layer) in `train_with_cifar10.ipynb`
2. compare the new model's(add/remove) `Inference Time` , `Arena size` , `Model size` with origin one in non-quant / quant / quant + CMSIS condition

### you need to complete the following table
| Method | Time(us) | Model size | Arena Size |
|--------------------|----------|------------|------------|
| remove layer float | - | - | - |
| remove layer quant | - | - | - |
| remove layer quant + CMSIS | - | - | - |
| origin float | - | 318332 bytes | - |
| origin quant | - | 95784 bytes | - |
| origin quant + CMSIS | 393667 us | 95784 bytes | 55108 bytes |
| add layer float | - | 328272 bytes | - |
| add layer quant | - | 99280 bytes | - |
| add layer quant + CMSIS | - | 99280 bytes | - |



