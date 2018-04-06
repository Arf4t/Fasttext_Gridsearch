# Fasttext_Gridsearch
Finding good parameters for fasttext to classify 20 news group data set

<h2>Among these parameters for fasttext </h2>

**dim**=[10,25,50,100,200,250,300]

**epoch**=[5,20,25,50,100]

**ws**=[5,10]

**lr**=[0.05,0.025,0.075,0.1,0.150,0.175]

<h2>Best Accuracy score was for the following parameter pair among 420 pairs of above values </h2>

**parameters:** {'dim': 50, 'epoch': 100, 'ws': 5, 'lr': 0.075} -------------------->>>>      **score** : 0.705




