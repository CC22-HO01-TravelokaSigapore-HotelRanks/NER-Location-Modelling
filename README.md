# Named Entity Recognition (Location Only)

Notebooks of our research and modelling of Named Entity Recoginition for detecting location name learned from the datasets.
The model trained using tensorflow manual train API and from the dataset that can be found [here](https://www.kaggle.com/datasets/namanj27/ner-dataset). 
  
| Information     | Value                                                           |
|-----------------|-----------------------------------------------------------------|
| Model Structure | Embedding - BiLSTM - LSTM - Time Distributed (Dense)            |
| Model Input     | List of strings, uncased (lower string), alphabetic (word only) |
| Model Output    | Classification of each word is a location or not                |
| Vocabulary Size | 25000                                                           |
| Training Method | Sliding Window Word Classification                              |

This model may not be implemented in our application because of limitation of the location it can detect is limited, thus we share it here and hoping this can help others.  

CC22-HO01 ML Teams.