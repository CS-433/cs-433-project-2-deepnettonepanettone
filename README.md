# PneumoNet: Neural networks for the detection of pneumonia from digital lung auscultation audio


add abstract copy here


## Environment setup

 You can use the notebooks directly on a local directory or on google colab in order to use their free GPUs.

In both scenario, please :
```
git clone https://github.com/CS-433/cs-433-project-2-deepnettonepanettone
cd cs-433-project-2-deepnettonepanettone/src
```

at the source of the repo add a link or copy of this google drive folder (preporcessed dataset) :
```
https://drive.google.com/drive/folders/1akCqrEMU8lgYp0bHNEoPEUQdTjKwGur2?usp=sharing
```

## Dependencies

make sure the python environment has : 

* numpy
* scipy
* librosa
* maplotlib
* tensorflow - keras

only if you want to test data augentation technics
* nlpaug

only if you want to test Grad-Cam class activation 
* tf-keras-vis

use pip or conda install


>
> Warining : the processed dataset is huge more than 30 GB
> All the following run can take up to 40 min just in data processing
> Prepare a cofee if you plan to train them from scratch :) 
>


## Where to find the best models

in src/model/ you can find the most succeful models

* best model for GVA with the model by Patient : 
* best model for GVA with the model by Position : 

* best model for POA with the model by Patient : 
* best model for POA with the model by Position : 


You can also find all the saved models we used for the paper in this model/ folder

## Run the best model

> you can adapt the all notebooks with the model weights you are curious to test

run the notebooks for

* best model for GVA with the model by Patient with : 
* best model for GVA with the model by Position with : MPO_10fold_cross_validation_and_prediction.pynb

* best model for POA with the model by Patient with :
* best model for POA with the model by Position with : MPO_10fold_cross_validation_and_prediction.ipynb

## Test our validation methods

* 10fold cross valudation : MPO_10fold_cross_validation_and_prediction.ipynb
* data augmentation :
* Grad-Cam class activation :
* different types of spectrogram :  
* position relevance : Remove_Position_Analysis.ipynb

## Authors

* Sara Pagnamenta
* Luka Chinchaladze
* Etienne Salimbeni

## Acknowledgements

Thank you !!!!