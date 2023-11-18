## 作業 readme

## Hw1 : Images Classification 
1. change the model architecture (add / remove some layer) in `train_with_cifar10.ipynb`
2. compare the new model's(add/remove) `Inference Time` , `Arena size` , `Model size` with origin one in non-quant / quant / quant + CMSIS condition

### you need to complete the following table
| Method | Time(us) | Model size | Arena Size |
|--------------------|----------|------------|------------|
| remove layer float | 3852521 us | 170056 bytes | 201040 bytes |
| remove layer quant | - | 56480 bytes | - |
| remove layer quant + CMSIS | 3853592 us | 56480 bytes | 198912 bytes |
| origin float | 4636166 us | 318332 bytes | 201696 bytes |
| origin quant | 4672189 us | 95784 bytes | 54452 bytes |
| origin quant + CMSIS | 393667 us | 95784 bytes | 55108 bytes |
| add layer float | 5537261 us | 328272 bytes | 201984 bytes |
| add layer quant | 5579919 us | 99280 bytes | 54724 bytes |
| add layer quant + CMSIS | 464783 us | 99280 bytes | 55380 bytes |



