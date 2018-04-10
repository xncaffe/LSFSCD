# LSFSCD
1. Please refer to ssd installation method to compile ssd-caffe.

Get the SSD code. We will call the directory that you cloned Caffe into $SFD_ROOT

git clone https://github.com/weiliu89/caffe.git
cd $SFD_ROOT
git checkout ssd

The website is https://github.com/weiliu89/caffe/tree/ssd


2. Unzip the penlu.tar.gz file from this project. Then place the file in the corresponding location in ssd-caffe. Then recompile the new caffe.


3. Extract the LSFSCD_train_test.tar.gz file from this project. This includes the data and network structure.


4. After the third step of decompression, the corresponding path in each file is edited according to the actual situation of the reader. Execute the file train_val/VGG_VEDAI512_512x512.sh to train the model.


5. After the training model is over, use LSFSCD_detect.py to test to evaluate our model.


6. It should be noted that the training model requires fine tuning using VGG_ILSVRC_16_layers_fc_reduced.caffemodel.
