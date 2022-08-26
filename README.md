# ReadMe
## step up
Make sure your computer is with a GPU, unless will cost a lot of time to train on CPU. The experiments are done on Intel Core i7-7700HG CPU, 16 GB of RAM, and an NVIDIA GeForce GTX 1080 8 GB graphics card.
1. mkdir dataset
2. cd dataset
3. down load data set from kaggle
4. setup environment(Pytorch 1.8.1) by this command:
 `conda install pytorch==1.8.1 torchvision==0.9.1          torchaudio==0.8.1 cudatoolkit=11.3 -c pytorch -c      conda-forge`
5. run the jupyter notebook to get results
## Dataset description
The dataset we used is COVID-19 Radiography Database, which can be download by kaggle. https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
For more details about the description, please check in the dissertation. 

## Result
* The results of performance will be Slightly different since the adma optimazer change the larning rate automatically for each training phase, but all the errors are in acceptable.
![](https://i.imgur.com/9WgoONU.png)

* consusion matrix 
![](https://i.imgur.com/yGRwf7r.png)

* Accuracy curve
![](https://i.imgur.com/nM5ykdz.png)