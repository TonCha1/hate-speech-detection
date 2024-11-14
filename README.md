# hate-speech-detection
The aim is to use LLM to categorize a tweet message into hate speech, offensive language, or neither.

There are 5 main steps done in this project. Please allow me to walk through each step briefly. 
  The first step: Understand limitations of each type of BERT- family model. Source: https://arxiv.org/abs/2104.02041

  The Second step: Select the model. DistillBERT is selected based on its fastest tuning time and less parameters in the architecture. 

  The third step: Find the dataset. Here the dataset is from Kaggle. Source: https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset/data. 

  The fourth step: Explaning the dataset. The tweet in each rows are annotated by a group of people to either be 'hate speech', 'offensive language', or 'neither'. 
                   So, there could be different judgements on the same tweet where one annotator judge it to be 'hate speech' but other judge it as 'offensive language' 

  The fifth step: is the start of the project which follows the CRISP-DM method of Data understanding/ Data Preprocessing/ Modeling/ Evaluation. 
    
  
