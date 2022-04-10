# Phishing-Website-Detection-using-Machine-Learning-Models
In the present century, the Internet has grown to be an important part of our everyday lives. With such a large number of people using the Internet on a regular basis, it is a repository for massive volumes of user data. The more user information there is, the more possibilities there are to steal it. Phishing is the hazardous illegal operations on the internet right now. It takes advantage of social engineering and other methods to fool users into giving over their bank account or other personal information. Phishing efforts involve a variety of tactics, including manipulation of link, forging of websites, social engineering and evading of filter. The most prevalent method is to create a spoofing website that looks to be genuine. Because of a lack of user knowledge, phishing assaults are becoming increasingly successful. Because phishing attacks take use of user weaknesses, it's tough to avoid them.
ML algorithms have been an effective process for recognizing of data and its traits, and these approaches have been used to identify phishing websites by detecting some of the most common phishing characteristics. Machine learning refers to a collection of algorithms that analyse previous data to draw conclusions or make predictions about future data

# Data Set
To evaluate the detection approach, the phishing  dataset datset.csv from an online  website (Kaggle) is used. The dataset consisted of 31 columns and 11055 URLs (4898 legitimate, 6157 phishing). The value presented in each attribute was -1, 0, and 1. -1 represented legitimate, 0 represented suspicious and 1 represented phishing. The dataset is split into 60-40 ratio for the training and the testing respectively, so that the machine learning algorithms learn from the data and make predictions. 

The dataset malicious_phish.csv is also taken from Kaggle which consists of 651,191 URLs, out of which 428103 benign or safe URLs, 96457 defacement URLs, 94111 phishing URLs, and 32520 malware URLs. 

The third dataset feature.csv has benign, defacement, malware, phishing, spam files which has features like body length, bscr, dse, entropy, hasHttp, hasHttps and others

# Results

The efficacy of machine learning algorithms in detecting phishing websites is evaluated in this project. Based on the results, it is possible to infer that the Random Forest Classifier delivers the best and greatest accuracy (96.834%). Collaborative algorithms, on the other hand, have been demonstrated to be beneficial since they are fast and perform well, employ several classifiers for prediction, and produce better results
