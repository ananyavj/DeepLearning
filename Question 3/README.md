### 3A. Implement credit card fraud detection for given credit card fraud detection Kaggle dataset using Autoencoder and build the model by using the following steps:

• Dataset: The dataset contains transactions labeled as fraudulent or non-fraudulent, with a severe class imbalance.  
• Goal: Identify fraudulent transactions by training an autoencoder only on nonfraudulent transactions.  

Steps:  
• Preprocess the data by scaling features (features are already PCA-transformed, so they’re anonymized).  
• Train an autoencoder on non-fraudulent transactions to learn typical spending patterns.  
• Calculate reconstruction errors for transactions and set a threshold to detect fraud.  
• Compile the models with Optimizer, Loss, and Evaluation Metrics  

### 3F. Using the Sign Language MNIST dataset, select any one of the 24 alphabet classes (label Y-24) as an anomaly. Train an Autoencoder–Decoder model using the remaining 23 classes and detect the selected class as an anomaly based on reconstruction error.
