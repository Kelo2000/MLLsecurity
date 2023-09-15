# Useful links: 
## German Traffic Sign Dataset(GTSD) 
* This Dataset was used for Training  and Testing:
* The Link to the dataset:
 https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?resource=download

* Click on the “Download section at the top”
* After zipping the data, rename the main folder name to similar name used in jupyter notebook  
* For Training and Testing, we are loading the images directly 
* We need the test.csv to get the groun truth values for the Test 
* Download the label.csv file that contain all the labels here:
* To read more about the dataset, go to their homepage:
    Link{https://benchmark.ini.rub.de/gtsrb_dataset.html#Downloads}
## Pytorch:
Useful link to the pytorch for understaning how training works 
* https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html 

## Resnet from scratch implementation on Kaggle:
A look at a jupyter notebook implementation of the resnet model from scratch with the code to train the model using GTSD
* https://www.kaggle.com/code/mohamedmagdy191/traffic-signs-recognition-resnet-from-scratch/notebook 

## Backdooring
The file "backdoor.ipyn" add a patch to images in a director. Make sure to specify the input image director, the path to the patch(could be a yellow square). In the future, we should change the size of the patch, position, color and type of the patch we use.

