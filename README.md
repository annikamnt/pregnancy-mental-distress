# Mental Distress in Expecting Parents: Detecting Anxiety and Depression in Pregnancy-Related Reddit Posts

## About the Project

This was a personal machine learning project conducted in **May 2025** to learn more about natural language processing.

In this project, we seek to explore whether thoughts and behaviors related to anxiety and depression are prevalent in pregnancy-related posts on Reddit using **multi-label classification**. It uses the dataset from the study of [Dhankar & Katz (2023)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10684261/), which extracted Reddit posts from pregnancy- and mental health-related subreddits. It was conducted in **Python**, using libraries such as `numpy`, `pandas`, `matplotlib`, and `seaborn` to analyze and visualize data, and `sklearn` and `torch` to perform the machine learning methodologies. We created two models using **Term Frequency-Inverse Document Frequency (TF-IDF) with Logistic Regression (LogR)** and **Bidirectional Encoder Representations from Transformers (BERT)**, which were evaluated using a classification report (housing metrics such as **precision**, **recall**, and **F1 score**), and the **Hamming loss**. The TF-IDF with LogR model was chosen because of its ability to make predictions well (with scores of 80\% and above) while maintaining computational efficiency for this use case. The model was then applied onto the pregnancy-related Reddit posts to analyze the signs of mental distress in these online spaces. 

## Instructions

In running the Jupyter notebook for the first time, please conduct the following preliminaries:
1. Download the dataset from the [Open Science Framework](https://osf.io/w45nr/files/osfstorage?view_only=).
2. Install all the relevant libraries, which can be found in the first block of code in the Jupyter notebook.
3. For the BERT model, fit the data to the model by setting `retrain = True`. For subsequent runs, set `retrain = False` to evaluate the model and make predictions.

## Contact

You may contact me about the project on the following channels:
* LinkedIn: https://www.linkedin.com/in/annikamnt/
* Project Link: https://github.com/annikamnt/pregnancy-mental-distress
