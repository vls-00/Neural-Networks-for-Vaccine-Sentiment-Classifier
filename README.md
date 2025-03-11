# A.I Movie Recommender
In this project I used deep neural-networks to train a classifier model that will be able to tell if a user will like a movie or not and recommend movies to users based on their past ratings. The point and the fun of this project is making a movie recommendation system, do not bother with the metrics too much 😊. 

* The recommendation function is also provided inside the notebook where someone can change the `userId` in the last cell and get recommendations for another user.
* You can also add YOUR recommendations into the dataset and play around. What movies will the system will recommend you? 😎

## 🛠️ Installation / Run
You can download, open and run the jupyter notebook in any platform that supports it. You will also need to install tensorflow, numpy and pandas for python. The dataset is in the link below.

## 📝 Dataset
Used the popular MovieLens 100k dataset from https://grouplens.org/datasets/movielens/latest/

## 🔄 Data Pre-Processing
The data pre-processing stage involves multiple modifications like one-hot encodings, transforming, normalization, cleanup and scaling of the data.

## 🔠 Clustering
    ▶️Clustering Function: HDBSCAN
    ▶️Minimum Cluster Size: 20
### Metrics:
```
✅Silhouette Score: 0.42885184579313873
✅Davies-Bouldin Index Score: 0.8235000921376852 
✅Number of Clusters: 193
✅Noise: 23%
```

## 📎 Neural Network
### Classifier
    ▶️Embedding Layers: 2 (User embedding & Movie Embedding)
    ▶️Embedding Dimensions: 16, 8
    ▶️Neuron Layers: 2
    ▶️Size of Neuron Layers: 16 -> 8 -> 1(output)
    ▶️Dropout Layers: 30% (16)
    ▶️Learning Rate: 0.0001
    ▶️Loss Function: Cross Entropy Loss  
    ▶️Optimizer: Adam
    ▶️Batch size: 32
    ▶️Epochs: 50
    ▶️Also used:  feature extraction, feature normalization, built-in sigmoid function
### Metrics:
```
✅Accuracy: ~71%
✅AUC: 0.7693
```
    
 ## Built With
<p float="left">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/110px-Python-logo-notext.svg.png" alt="MarineGEO circle logo" style="height: 100px; width:100px;"/>  
 </p>
