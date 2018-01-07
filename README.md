# transfer-learning-with-gluon
This project shows how to apply transfer learning with MXNet Gluon

## Prerequisite 
1. install MXNet: `pip install mxnet`
2. install Jupyter Notebook: `pip install jupyter`

## Project structure
1. `data` directory: 
   1. `img`: image data to be used in generating `rec` file
   2. `train`, `sample`, `test`, `validation`: rec files for training
2. `prepare-dataset.ipynb`: preprocess and prepare datasets for training 
3. `train.ipynb`: build model and define training process
4. `generate_rec.sh`: script to generate rec files
5. `im2rec.py`: script provided by [MXNet tools](https://github.com/apache/incubator-mxnet/blob/master/tools/im2rec.py)

## How to use this project
This project provides the simple guidance to apply transfer learning. 

Users are expected to gather their own dataset and follow the notebooks.

For more details, please refer to this post: 
