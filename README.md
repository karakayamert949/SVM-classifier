# SVM-classifier

# Overview
Implementation of linear SVM classifier for CIFAR-10 dataset. I implemented analytical gradient and stochastic mini-batch.
Example accuracy vs epoch and loss vs epoch graphs are in the graphs folder.
Performance of the classifier is in the first markdown of SVM.ipynb, and in the Results part of the README

# Libraries
numpy,os,pickle,matplotlib

# Usage
Execute TrainMain() to train get weight matrix
Execute ValidMain() to validate Validaiton dataset
Execute TestMain() to test Test dataset

# Results
<h2>Train results:<h2>

<h3>Mini-batch size 256<h3>
<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 1e-6<h4>

THETA = 1e-5
In epoch 1000, loss is 5.291985059220746
In epoch 1000 accuracy is 0.346075

THETA = 1e-4
In epoch 1000, loss is 5.292198365836736
In epoch 1000 accuracy is 0.348175

THETA = 1e-3
In epoch 1000, loss is 5.296268629829621
In epoch 1000 accuracy is 0.34815

THETA = 1e-2
In epoch 1000, loss is 5.297345092785761
In epoch 1000 accuracy is 0.347775

<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 8e-5<h4>
THETA = 1e-3
In epoch 1000, loss is 6.837051169043007
In epoch 1000 accuracy is 0.413175

<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 1e-5<h4>

THETA = 1e-5
In epoch 1000, loss is 4.473005846222188
In epoch 1000 accuracy is 0.387375

THETA = 1e-4
In epoch 1000, loss is 4.4734887011987485
In epoch 1000 accuracy is 0.3884

THETA = 1e-3
In epoch 1000, loss is 4.4808710837865116
In epoch 1000 accuracy is 0.385575

THETA = 1e-2
In epoch 1000, loss is 4.501979782009769
In epoch 1000 accuracy is 0.38755

<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 1e-4<h4>

THETA = 1e-5
In epoch 1000, loss is 4.195538879880822
In epoch 1000 accuracy is 0.401625

THETA = 1e-4
In epoch 1000, loss is 4.118187725967621
In epoch 1000 accuracy is 0.4106

THETA = 1e-3
In epoch 1000, loss is 4.187295139050325
In epoch 1000 accuracy is 0.40025

THETA = 1e-2
In epoch 1000, loss is 4.246982001690002
In epoch 1000 accuracy is 0.41245

<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 1e-3<h4>

Too much unstable!!!!
THETA = 1e-5
In epoch 1000, loss is 8.297607196745993
In epoch 1000 accuracy is 0.329675

<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 7e-5<h4>
THETA = 1e-4
In epoch 1000, loss is 5.174179245491815
In epoch 1000 accuracy is 0.412975

<h3>Mini-batch size 512<h3>
<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 1e-4<h4>

THETA = 1e-5
In epoch 1000, loss is 4.077958433569045
In epoch 1000 accuracy is 0.40925

THETA = 1e-2
In epoch 1000, loss is 4.62524982252704
In epoch 1000 accuracy is 0.393

<h3>Mini-batch size 128<h3>
<h4>Fixed: EPOCHS = 1000,LEARNING_RATE = 5e-5<h4>

THETA = 1e-4
In epoch 1000, loss is 4.328775130110178
In epoch 1000 accuracy is 0.393875

<h2>Validation Results:<h2>
<h3>Mini-batch size 256<h3>
THETA = 1e-4
LEARNING_RATE = 7e-5
EPOCHS = 1000
Loss is 5.305431801173743,Accuracy is 0.3993

THETA = 1e-3
LEARNING_RATE = 8e-5
EPOCHS = 1000
Loss is 6.92635428403829,Accuracy is 0.4024

<h2>Test Results:<h2>
<h3>Mini-batch size 256<h3>
THETA = 1e-3
LEARNING_RATE = 8e-5
EPOCHS = 1000
Loss is 6.95635111972989,Accuracy is 0.3975
