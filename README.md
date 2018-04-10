# LSFSCD
#This is a research project on the use of a single regression convolutional neural network to detect small vehicle targets in aerial photography. The corresponding paper is under review. If it is published, we will update it here.

1. Please refer to ssd installation method to compile ssd-caffe.

The website is https://github.com/weiliu89/caffe/tree/ssd


2. Unzip the penlu.tar.gz file from this project. Then place the file in the corresponding location in ssd-caffe. Then recompile the new caffe.


3. Please download the data and training file LSFSCD_train_test.tar.gz at https://pan.baidu.com/s/1w-Mk_2cSrVSmIf58pvqXOQ (password: cb8t)


4. Extract the LSFSCD_train_test.tar.gz file from this project. This includes the data and network structure.


5. After the third step of decompression, the corresponding path in each file is edited according to the actual situation of the reader. Execute the file train_val/VGG_VEDAI512_512x512.sh to train the model.


6. After the training model is over, use LSFSCD_detect.py to test to evaluate our model.


7. It should be noted that the training model requires fine tuning using VGG_ILSVRC_16_layers_fc_reduced.caffemodel.
