# Machine_Learning
# this project will contain some of the most important machine learning and data-analysis techniques
## When the new files will be added, corresponding description will also be added with file name and DDMMYY. 
### base of these programs are machine learning codes influenced from Muller's Machine Learning with Python book. Later on many extra techniques are implemented. \
*PCA_Muller.py 190818:* Principal component analysis example with breast cancer data-set. Detailed description of this code is discussed in here https://towardsdatascience.com/dive-into-pca-principal-component-analysis-with-python-43ded13ead21 . After this un-supervised machine learning technique, we will move to some very well known supervised machine learning methods like KNearestNeighbor and LinearRegression and so on. \ 

*270918: RidgeandLin.py, LassoandLin.py:* Lasso and Ridge regression examples: From coefficient shrinakge in Ridge to feature selection in Lasso are shown in the code. The concepts and discussion of the results are shown here (https://towardsdatascience.com/ridge-and-lasso-regression-a-complete-guide-with-python-scikit-learn-e20e34bcbf0b). \    

*081018: bank.csv*, data set of portuguese company selling products to random customer over a phone call. Detailed description are available here http://archive.ics.uci.edu/ml/datasets/Bank+Marketing \

*161018: gender_purchase.csv*, data-set of two columns describing customers buying a product depending on gender.\

*111118: winequality-red.csv*, red wine data set, where the output is the quality column which ranges from 0 to 10. This output is unbalanced as most of them are normal. So be careful!!\

*121118: pipelineWine.py*, this program contains a simple example of applying pipeline and gridsearchCV together using the red wine data. More description can be found here https://towardsdatascience.com/a-simple-example-of-pipeline-in-machine-learning-with-scikit-learn-e726ffbb6976 \

*24112018 lagmult.py*, this program just solves constrained optimization problem using plots. Basically contains an example of Lagrange's multiplier method. \

*11122018 Consumer_Complaints_short.csv* contains 3 columns describing the complaints, product_label and category (i.e. product label categorized). The real data file can be obtained from https://catalog.data.gov/dataset/consumer-complaint-database/resource/2f297213-7198-4be1-af1e-2d2623e7f6e9 . File size is around 650 MB. More details about the usage of this file will be uploaded soon when the text classification program is ready. \

*13122018: Text-classification_compain_suvo.py*, this is a program to classify the consumer complaints data, which is already described above. The file deals with the complete data-set (650 MB), and we considered only the complain and category columns to classify some random complains into different categories. After testing several ML algorithms, Linear Support Vector Machine works the best on both train and test data. Higher the computer resources, higher amount of rows can be considered for TfidfVectorizer. \

*1912018: SVMdemo.py*, this program shows the effect of using RBF kernel to map from 2d space to 3d space. It also includes animation which requires ffmpeg in your unix system. \ 
