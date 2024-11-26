### Explored various Optimization algorithms and LR Scheduler

    1. Stochastic Gradient Descent (SGD)
    2. Adaptive Gradient Algorithm (Adagrad)
    3. Adam (Adaptive Moment Estimation)

## Analysis: 
When using SGD, an accuracy of 93.13% is obtained. After changing the optimizer from SGD 
to Adam the accuracy increases from 93.13% to 94.12% (2% increase) and then to 96.53% 
accuracy when switching to Adagrad. Same goes for the loss i.e. it decreases from optimizer 
to optimizer. So, we can clearly see that the tuning the optimizer we can increase the 
performance of the model. 

On the other hand, when we introduce the method of LR scheduler, we can change the LR 
hyperparameter during training phase. The accuracy results also change with SGD giving 
93.31% (improvement from 93.13%), Adam giving 94.28% (improvement from 94.12%) and 
Adagrad giving 96.60% (improvement from 96.53%). Here to the loss also decreases. Hence 
this clearly shows that the performance of the model can be improved by understanding the 
model architecture and tuning the hyperparameters based on it. 
