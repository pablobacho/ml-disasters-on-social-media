# Disasters on Social Media

This is my capstone project for Udacity Machine Learning nanodegree.

I picked one of Kaggle’s “Getting Started” competitions on Natural Language Processing for my capstone project. The competition is ​Real or Not? NLP with Disaster Tweets​, and can be found on Kaggle’s website at: https://www.kaggle.com/c/nlp-getting-started/overview/evaluation

The goal of this project is to build a machine learning model that predicts which Tweets are about real disasters and which ones aren’t.

Watch a video of it working: https://www.youtube.com/watch?v=lzGzzTPXokE

## Software and libraries used

I implemented this solution on Amazon Sagemaker. No special libraries have been used that are not included in Amazon Sagemaker.

## Description of notebooks

**cp00-data-analysis.ipynb:** This notebook is used to analyze the dataset and generate the information included in the related section of the report.

**cp01-pytorch-bagofwords.ipynb:** This notebook contains the code for the first model I built, based on PyTorch and bag-of-words technique with single words.

**cp02-pytorch-2grams.ipỳnb:** Similarly to the previous one, this notebook contains the code for the second model, that uses 2-grams instead of single words.

**cp03-blazingtext.ipynb:** This notebook uses BlazingText algorithm to solve the problem.

**cp99-leaderboard-analysis.ipynb:** Analysis of the leaderboard studying the performance of the model built.

## Folders

**input:** Contains all datasets needed to run the notebooks.

**train:** Contains code needed to create the PyTorch model.

**data:** Temporary folder to store model resources.

## Other files

**website.html:** Website to make predictions using the model. The endpoint is not online and it cannot be tested without setting it up.

**proposal.pdf:** Project proposal.

**report.pdf:** Project report.