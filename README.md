# Low-Cost-Methods-BERT
### High Level: 
We are interested in exploring low-cost methods for increasing classification accuracy of toxic comments using BERT

### Abstract: 
Classification is a popular task in Natural Language Processing that has large policy implications, especially when it involves controversial issues like toxicity. The factors that determine whether a comment is toxic or not have been hotly contested in recent years, and their identification is exacerbated by the rapid evolution of the language of toxicity itself. These difficulties are at least somewhat reflected in language models’ performances on toxicity classification. State-of-the-art models, such as BERT which is the focal model of this paper, perform various classification tasks (including toxicity classification) with close to 100% accuracy; however, most models are still hovering below this benchmark. We explore low-cost solutions, including log-odds ratios and simulated hand annotation, that could improve accuracy for researchers interested in toxicity classification and, potentially, classification tasks more generally. 

### Findings: 
While our experiments didn’t result in improved accuracy, a refocus on lower false negative detection with a combination of a few methodological tweaks to our logical framework could help in the development of new low-cost methods for toxic comment classification. 

# Implementation Details

Prior to running any code, please download the data files from https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data. Once downloaded, please open and run Low_Cost_Methods.ipynb in Google Colab.

A write-up of our design, results, and discussion can be found in low_cost_methods.docx.
