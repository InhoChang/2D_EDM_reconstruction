# 2D edm reconstruction 
2D EDM reconstruction for human pose estimation using transposed CNN

### Requirments 
- python 3.6 
- tensorflow-gpu 1.11 
- h5py 
- PIL 

### 1. save_img.py 
To make sparse(occlusion) EDM, randomly select joint numbers and make EDM value as zero. (num_zeros = 1, 2, 3) 
After making sparse(occlusion) EDM, save as Image file (.png) in below directory.  
```
img/ 
  zeros_1/ 
    tr/
     img/ 
        zeros_1_img_0 
        ...
     label/ 
        zeros_1_label_0
        ...
           
  
  
   zeros_2/ zeros_3/ 
    tr/ dev/ tt/ 
      img/
        ...
      label/ 
        ...       
   
   
```

### 2. train.py 

train and reconstruct occlusion edm using simple Fully Convolutional Network(FCN) 

2 convolution layers follow with 2 transposed convolution layers 


### 3. Evaluation

~ing 





