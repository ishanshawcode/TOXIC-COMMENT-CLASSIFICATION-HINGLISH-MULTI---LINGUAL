# TOXIC-COMMENT-CLASSIFICATION-MULTI---LINGUAL
Uses BiLSTM Model to classify toxic comments. Integrated with Deep Translate , can be uses for more Hindi , Hinglish and other languages.

Toxicity File is used to train the model using jigsaw-toxic-comment-classification-challenge dataset. 
    It conatins code to test the model in English only.
    Reccomended epochs >10
    Train, save and run the model on same version of tensorflow.
    The Given model (toxicity.keras) is of Tensorflow version 2.9.3.
    For running my model on newer verions goto branch 2.

The MAIN file contain code to load the model and use Deep Translate library to make it of use in other languages including hindi.
    If used correctly Deep translate can be also be used to transliterate( ye ek udharan hai  -> 'ये एक उधरण है')
    For more on Deep translate goto branch 3.
    Toxic comments in Google tranlsate or GPT or other library would just censor them.
