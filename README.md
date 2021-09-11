# FaceRecognition-FaceNet
face recognition based on Facenet model and cosine similarity metric

FaceNet is a face recognition system that was described by Florian Schroff, et al. at Google in their 2015 paper 
titled “FaceNet: A Unified Embedding for Face Recognition and Clustering.”
It is a system that, given a picture of a face, will extract high-quality features from the face 
and predict a 128 element vector representation these features, called a face embedding.

### Requirements:
pip install Pillow (version used : 8.3.2) : https://pypi.org/project/Pillow/    

pip install mtcnn (version used : 0.1.1)  : https://pypi.org/project/mtcnn/     

### this program included 3 main steps:
#### 1. Face Detection
#### 2. Extract face embedding using FaceNet model
#### 3. Comparing facial features(embeddings) with using cosine_similarity metric

### Note:
If you see lots of warning after running the 5th and 7th cell in Google colab, These warnings are related 
to the implementation of tensorflow in the Google colab and there is no big problem.
The warnings will not hurt performance.

#### codes in Google colab are available:

https://colab.research.google.com/drive/10qOymIYU68qYY38pIN9r1Dq7Z_iLlrz4?usp=sharing
