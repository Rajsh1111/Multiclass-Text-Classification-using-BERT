# Multiclass-Text-Classification-using-BERT
**Business Objective for Multiclass Text Classification using BERT Project**
This project  covers the application of the BERT base model concerning text classification in detail. We will witness how this state-of-the-art Transformer model can achieve extremely high-performance metrics for a large corpus of data comprising more than 100k+ labeled training examples.
**Data Description for the BERT Text Classification Project**
For our case study, we have used the hugging face library datasets.
The BERT model is built on the AG News dataset.
•	AG News (AG’s News Corpus) is a sub-dataset of AG's corpus of news articles constructed by assembling titles and description fields of articles from the 4 largest classes
•	The four classes are: World, Sports, Business, Sci/Tech
•	The AG News contains 30,000 training and 1,900 test samples per class. 

**Aim of the Project Using BERT Model for Multiclass Classification**
The project aims at building, training, and fine-tuning the BERT model with respect to classification on the AG News dataset.

**Data Science Solution Approach for Project on Multiclass Classification using BERT is as follows:**
•	Checking the hardware acceleration settings.
•	Installing the required libraries
•	Checking for the available dataset from the hugging face library
•	Importing the required dataset
•	Loading the train and test data
•	Creating dataframe objects for train and test data.
•	Performing data pre-processing
•	Creating the BERT model.
•	Compile the BERT model.
•	Training the BERT model on some defined hyperparameters.
•	Evaluating the performance metrics
•	Saving the model.
 ***Tech Stack for Multiclass Text Classification Python Project***
•	Language - Python
•	Libraries – ktrain, transformers, datasets, numpy, pandas, tensorflow, timeit
•	Environment- Jupyter Notebook


# Text Classification using BERT pre-trained model
This repository contains the code for text classification using pre-trained BERT model.

### Installation
To install the dependencies run:
```buildoutcfg
pip install -r requirements.txt
```

### Dataset
The [dataset](https://catalog.data.gov/dataset/consumer-complaint-database) is a collection of complaints about consumer financial products and services that we sent to companies for response. The actual text of the compalint by the consumer is given in the `Consumer complaint narrative` column. The dataset also has a `product` column which contains the product for which the consumer is raising the complaint. We are going to build a model to predict the product given the complaint text. 

### Preprocessing the data
To pre-process the data and the embeddings, run:
```buildoutcfg
python processing.py
```

### Train the model
To train the model, run:
```buildoutcfg
python Engine.py 
```

### Predictions
To make prediction on a new review, run:
```buildoutcfg
python predict.py --test_complaint "I am a victim of Identity Theft & currently have an Experian account that I can view my Experian Credit Report and getting notified when there is activity on my Experian Credit Report. For the past 3 days I've spent a total of approximately 9 hours on the phone with Experian. Every time I call I get transferred repeatedly and then my last transfer and automated message states to press 1 and leave a message and someone would call me. Every time I press 1 I get an automatic message stating than you before I even leave a message and get disconnected. I call Experian again, explain what is happening and the process begins again with the same end result. I was trying to have this issue attended and resolved informally but I give up after 9 hours. There are hard hit inquiries on my Experian Credit Report that are fraud, I didn't authorize, or recall and I respectfully request that Experian remove the hard hit inquiries immediately just like they've done in the past when I was able to speak to a live Experian representative in the United States. The following are the hard hit inquiries : BK OF XXXX XX/XX/XXXX XXXX XXXX XXXX  XX/XX/XXXX XXXX  XXXX XXXX  XX/XX/XXXX XXXX  XX/XX/XXXX XXXX  XXXX XX/XX/XXXX"
```
