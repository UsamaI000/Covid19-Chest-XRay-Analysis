# Mscs19008_COVID19_DLSpring2020
“This   repository   contains   code   and   results   for   COVID-19   classification   assignment   by   Deep   Learning   Spring   2020   course   offered   at   Information   Technology   University,   Lahore,   Pakistan.   This   assignment   is   only   for   learning   purposes   and   is   not   intended   to   be   used   for   clinical   purposes.”   

## Dataset: 
   Link: https://drive.google.com/drive/u/1/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR?authuser=1

## Model used:
   1) Vgg 16
   2) Resnet 18
    
## Exerimental Setup:
   For different experimentations on the dataset different models and hyper-parameters were chosen. These are given below.
   
   • Pre-trained models Vgg16 and Resnet18.
   
   • First task was to perform experiments on both models with the CNN part freeze and only FCN unfreeze.
   
   • Second task was to perform experiments on both models with CNN and FCN both unfreeze and also, CNN partially freeze.
   
   • The FCN part of the both networks were altered according to given assignment. The problem was binary so output layer had to be           changed. Also, the number of neuron in hidden layers were also changed.
       
   • Learning rates used were 0.001, 0.0001, and 0.00001.
   
   • Momentum used was 0.9.
   
   • Batch sizes used were 60, 120.
   
   • Loss used was Cross-Entropy.
   
   • Optimizer used was SGD.

## Results:

   ### Task 1
   The best performance on Task 1 that I got is
   ![](images/task1%20best.png)
   ![](images/task1%20train%20acc.png)

   ### Task 2
   The best performance on Task 2 that I got is
   ![](images/task2%20best.png)
   ![](images/task2%20train%20acc.png)
