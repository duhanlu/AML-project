# AML_project

## Training
The file called fans_.py is used to train unsupervised GANs. But a features.csv, which is the feature representation generated from MoCo model, is needed to be the input to the GANs model. 

## Test Model
load_model.py can be used to load the trained model and generate images within 10 classes, in which 0 to 9 represents airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck seperatively. By changing the model name with the model name listed below, different model can be play around with.  

## Models at 200 epoches
* Original GANs model: gans.h5
* Unsupervised GANs model with pretrained MoCo: ugans_g.h5
* Unsupervised GANs model with newly trained MoCo: ugans_nm_g.h5

## Result
* The loss graph for three gans models are compared in the graph called 3loss.png.
* Moco loss is shown as the picture called moco_loss.png
* Clustering for training images and labels generated from MoCo model are shown in cluster1.png and cluster2.png seperately. Cluster1 is the clustering for pretrained moco, and cluster2 is from newly trained moco. 
