# Iris-Neural-network

## French description  
C'est un projet personnel implémentant un réseau de neurones simple pour classifier les fleurs d'iris en utilisant TensorFlow/Keras. Ce projet démontre les fondamentaux de la construction, de l'entraînement et de l'évaluation d'un modèle de classification multi-classes sur le célèbre dataset Iris.  

**Dataset**  
Le célèbre dataset Iris utilisé en machine learning : 
- 150 échantillons  
- 4 caractéristiques : Longueur du sépale, Largeur du sépale, Longueur du pétale, Largeur du pétale (en cm)  
- 3 classes : Setosa, Versicolor, Virginica  
- Séparation Train/Test : 80/20  

**Spécifications du Modèle**  
- Couche d'entrée : (4,) - quatre mesures de la fleur  
- Couche masquée : 10 neurones avec activation ReLU  
- Couche de sortie : 3 neurones avec Softmax (distribution de probabilité sur 3 classes)  
- Optimiseur : Adam  
- Fonction de perte : Sparse Categorical Crossentropy  
- Métrique : Précision (Accuracy)  

**Configuration d'Entraînement**  
- Epochs : 50  
- Taille de batch : 8  
- Validation : Validation en temps réel sur le set de test pendant l'entraînement  

**Fonctionnalités**
1. Entraînement et Évaluation du Modèle : Entraînement du modèle sur les mesures de fleurs d'iris
Validation en temps réel pendant l'entraînement
Évaluation des performances du modèle sur le set de test
Affichage des probabilités de prédiction pour des échantillons individuels  

2. Fonction de Prédiction Personnalisée : pythonpredict (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm)
Permet la prédiction sur de nouvelles mesures de fleurs en fournissant les quatre caractéristiques.
3. Export des Résultats : Les prédictions sont exportées vers resultats_iris.csv
Inclut à la fois les vraies étiquettes (y_true) et les étiquettes prédites (y_pred)
Permet des analyses et visualisations supplémentaires  

**Dépendances**  
- tensorflow  
- scikit-learn  
- numpy  
- pandas  

**Installation**  
pip install tensorflow scikit-learn numpy pandas  



## English description
This is a personal project implementing a simple neural network to classify iris flowers using TensorFlow/Keras. This project demonstrates the fundamentals of building, training, and evaluating a multi-class classification model on the classic Iris dataset.

**Dataset**  
The famous Iris dataset used for machine learning :  
- 150 samples  
- 4 features: Sepal length, Sepal width, Petal length, Petal width (all in cm)  
- 3 classes: Setosa, Versicolor, Virginica  
- Train/Test split: 80/20  

**Model Specification**  
- Input shape: (4,) - four flower measurements  
- Hidden layer: 10 neurons with ReLU activation  
- Output layer: 3 neurons with Softmax (probability distribution over 3 classes)  
- Optimizer: Adam
- Loss function: Sparse Categorical Crossentropy
- Metric: Accuracy  

  
**Training Configuration**
- Epochs: 50  
- Batch size: 8  
- Validation: Real-time validation on test set during training  

  
**Features**  
1. Model Training and Evaluation : 
Train the model on iris flower measurements
Real-time validation during training
Evaluate model performance on test set
Display prediction probabilities for individual samples    
2. Custom Prediction Function : 
pythonpredict (SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm)
Allows prediction on new flower measurements by providing the four features.  
3. Results Export : 
Predictions are exported to resultats_iris.csv
Includes both true labels (y_true) and predicted labels (y_pred)
Enables further analysis and visualization  

**Dependencies**
- tensorflow  
- scikit-learn  
- numpy  
- pandas  

**Installation**   
pip install tensorflow scikit-learn numpy pandas  
