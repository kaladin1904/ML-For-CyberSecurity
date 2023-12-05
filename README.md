# ML-For-CyberSecurity
Assignment 4 : Backdoor Attacks  
Name: Ishan Miglani  
NetID: im2410  
 

Change the paths for the data accordingly in cells 3 and 4

I. Dependencies

Python 3.6.9  
Keras 2.3.1  
Numpy 1.16.3  
Matplotlib 2.2.2  
H5py 2.9.0  
TensorFlow-gpu 1.15.2  

II. Data
The data for this notebook is available at https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master/lab3

The dataset contains images from YouTube Aligned Face Dataset. We retrieve 1283 individuals and split into validation and test datasets.
bd_valid.h5 and bd_test.h5 contains validation and test images with sunglasses trigger respectively, that activates the backdoor for bd_net.h5.




Change the below code in cells 3 & 4 accordingly  
#paths for local compilation  
clean_validation_path = '/data/cl/valid.h5'  
bad_validation_path = '/data/bd/bd_valid.h5'  
bad_model_path ='/models/bd_net.h5'  
evaulation_script_path = 'eval.py'  
clean_test_path = '/data/cl/test.h5'  
bad_test_path = '/data/bd/bd_test.h5'  

All thes files can be found at the github link for the lab : https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master/lab3  


Please see attached PDF Report for results and methodology  
Also attached are the 3 pruned models created after pruning and reduction in validation accuracy of 2%, 4% and 10% respectively



