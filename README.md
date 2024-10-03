# DLMiniProject# resnet_cifar10 - Deep Learning Mini Project

DL_mini_project_adadelta_lr_0.1.ipynb -  Has the highest Accuracy  

The hyperparameters that were used during the project were -   
•	N - No. of layers   
•	Bi - No. of residual blocks in i’th layer     
•	Ci - No. of channels in i’th layer     
•	Fi - Convolutional kernel size in i’th layer      
•	Ki - Skip connection kernel size in i’th layer   
•	P - Avg pool kernel size   
Learning rate and optimizers were also changed to observe different scenarios  
We used the Adam, Adadelta and Adagrad optimizers with learning rates 0.1, 0.01 and 0.001

We created our models and trained them to classify im-ages utilizing the CIFAR-10 dataset.    
Employing our model with 4,935,242 parameters, we were able to reach the best accuracy of 91.29%. Below are the values of the hyperparameters -   
•	Learning rate = 0.1   
•	Weight Decay = 0.0001       
•	Optimizer = Adadelta   
•	Scheduler = Cosine Annealing    
•	N = 4   
•	B = [3,3,2,3]   
•	C = [64,128,128,256]   
•	F = [3,3,3,3]   
•	K = [1,1,1,1]   
•	P = 4   

Final Results: 
| Optimizer | Learning Rate	| Test Accuracy |
|----------|----------|----------|
| Adadelta | 	0.1	| 91.29% |
| Adadelta |	0.01 |	91.13% |
| Adadelta |	0.001 |	90.40% |
| Adagrad |	0.01 |	86.87% |
| Adagrad |	0.001	| 88.66% |
| Adam |	0.01 |	74.07% |
| Adam |	0.001	 |88.47% |
