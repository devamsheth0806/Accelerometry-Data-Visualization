# RAW ACCELEROMETRY DATA ANALYSIS
This project focuses on analyzing readings from an accelerometer of 32 adults while they carried out different outdoor activities like walking, driving, and climbing stairs. This analysis will provide useful insights regarding the movements of different body parts  and help in learning the body's reactions to those activities. The goal of this project is also to identify the relations between the users' demographic data with their corresponding outdoor activities.

## Dataset Description
The dataset comprises of raw labeled accelerometer readings captured from 32 healthy individuals while they were walking outdoors, climbing stairs, and driving. The accelerometer data was simultaneously recorded at four body positions: the left wrist, left hip, left ankle, and right ankle, with a sampling rate of 100 Hz. Thus, the dataset was found to be longitudinal, with more than 2 dimensions.  
Dataset Source: https://physionet.org/content/accelerometry-walk-climb-drive/1.0.0/#files-panel

## Project Description
This project focuses on five different algorithms to be applied to the dataset as follows:  
1. Short-term Frequency Transformation (STFT): A mathematical technique used to determine the sinusoidal frequency and phase content of local sections of a signal as it changes over time. It provides a way to see how different frequencies in a signal vary at different moments, which is particularly useful for signals whose properties evolve, like music or speech.
2. Principal Component Analysis (PCA): The key concept in PCA is to find a linear combination of features that maximizes the variance between classes while minimizing the within-class scatter. It is a linear dimensionality reduction algorithm that projects data onto a new set of orthogonal axes (principal components) that capture the most variance in the data.
3. IsoMap: Isomap stands for “Isometric Mapping”. It is a non-linear dimensionality reduction technique. Isomap excels at capturing non-linear relationships in the data, which is essential when linear methods like PCA fall short. It is a manifold learning algorithm that unravels underlying low-dimensional structure (manifold) in high-dimensional data.
4. t-distributed Stochastic Neighbor Embedding (t-SNE): t-SNE is a popular dimensionality reduction technique used in machine learning and data visualization. It is particularly effective at reducing high-dimensional data into a lower-dimensional space while preserving the local structure and relationships between data points.
5. Linear Discriminant Analysis (LDA): A statistical method used for dimensionality reduction and classification tasks. It aims to find a linear combination of features that maximally separates different classes in the data. It is also known as Fisher’s Linear Discriminant. LDA helps us identify the most relevant features that contribute to class separation, improving the accuracy of classification models.

Rest Details can be found in the project report: https://github.com/devamsheth0806/Accelerometry-Data-Visualization/blob/master/Accelerometry-data-analysis-project%20report.pdf
