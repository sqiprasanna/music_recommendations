# Music Recommendation

### Abstract
This project aims to develop a music recommendation system using the Million Song Dataset, specifically the Taste profile dataset. The dataset consists of real user-song-play count triplets, artist and song metadata such as artist name, title, artist hotness, year of release, duration, etc., The project involves tasks such as data preprocessing, exploratory data analysis, feature engineering, and building and evaluating different recommendation algorithms such as Neural Collaborative Filtering, hybrid recommender system using autoencoders, and Singular Value Decomposition (SVD) with neural network-based approach. The project also explores incorporating additional metadata such as artist and genre information to enhance the recommendation quality. The performance of different models is evaluated using common evaluation metrics such as rmse and mae.

### Dataset Description:
The Million Song Dataset (MSD) is a large-scale music dataset that contains audio features and metadata for one million popular songs. It is created by The Echo Nest and available for research and non-commercial use [1]. The dataset includes 48,373 unique songs, 1,019,318 unique users, and 48,373,586 listening events. The user-song interaction data is a subset of the main dataset that contains real user, song, and play count triplets and can be primarily used for collaborative filtering [1]. This subset contains features such as artist name, song name, user request, and play count. The MSD also includes additional metadata for each song, including artist, title, tempo, key, loudness, and many other audio features extracted using music information retrieval (MIR) techniques [1].
The MSD also contains a dataset of song lyrics and artist biographies, called the MusiXmatch dataset, which can be linked to the MSD using song and artist identifiers [2]. The MusiXmatch dataset contains over one million song lyrics and metadata, including information such as artist, album, language, and lyrics themselves. The dataset is made available for research purposes only and can be used in combination with the MSD to build more comprehensive music recommendation systems that take into account song lyrics and artist biographies [2].

### Code structure
- codes
    - EDA
    - Baselines
    - NCF
    - Hybrid RS with Autoencoders
    - SVD and NN approach
    - Artist Popularity Predictions using Lyrics


### Algorithms 
1. Neural Collaborative Filtering
2. Hybrid Recommendation System using AutoEncoders
3. SVD and Neural Network based-approach
4. NCF based artist popularity prediction



### Packages installed
* Tensorflow
* Keras
* Surprise
* gensim
* word2vec
* glove
* TfIdf
* fasttext

### References
* http://millionsongdataset.com/tasteprofile/ 
* http://millionsongdataset.com/pages/getting-dataset/#subset 
* http://millionsongdataset.com/musixmatch/ 