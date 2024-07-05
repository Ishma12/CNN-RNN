# CNN-RNN

#Flower Classification with Convolutional Neural Network:
The visualization explores the application of convolutional neural networks (CNNs) for flower classification, utilizing a dataset comprising 4,312 images across five distinct flower classes: daisy, dandelion, sunflower, tulip, and rose. With 3,881 images allocated for training and 1,293 for validation, the CNN model is structured with layers for rescaling, convolution, max pooling, flattening, dense connections, and dropout mechanisms. Training involves 10 epochs using the 'adam' optimizer and 'SparseCategoricalCrossentropy' loss function. Despite strong performance overall, the model occasionally misclassifies tulips as roses, evidenced by a confusion matrix and heatmap analysis. Additionally, transfer learning with the ResNet-50 architecture demonstrates robust accuracy of 94%, highlighting its efficacy in leveraging pre-trained models for improved classification.

#Sentiment Analysis on Twitter Data with LSTM:
The focus shifts to sentiment analysis using an LSTM-based neural network applied to Twitter data. The dataset consists of 31,962 tweets categorized into positive and negative sentiments. Initial data preprocessing involved text cleaning to remove emojis, special characters, and normalization. The LSTM model architecture includes embedding layers, LSTM cells for sequence learning, dropout layers for regularization, and dense layers for binary classification. Training utilized the Adam optimizer and binary cross-entropy loss function across 10 epochs, with early stopping implemented for model convergence monitoring. Achieving a high accuracy of 97.92%, the model demonstrates strong performance in sentiment classification, supported by metrics such as precision, recall, and F1 score, as detailed in the confusion matrix analysis.






