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
| origin float | - | - | - |
| origin quant | - | - | - |
| origin quant + CMSIS | 393667us | 95784bytes | 55108bytes |
| add layer float | - | - | - |
| add layer quant | - | - | - |
| add layer quant + CMSIS | - | - | - |



# hello world lab
## Train the tf model with Sin function & Compile to bin file
1. import ```hello_world_lab/compile.ipynb``` on colab
2. run the code and it will start training & compile
2. after alll , download ```hello_world.bin ``` 
## inference on F767ZI
1. connect the F767ZI with your computer
2. download termite
3. open termite & set the baod rate 9600
4. copy the .bin file into F767ZI
5. see the output in termite
