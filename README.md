# DL4H_final



## Code 

- Citation to the original paper

  Fatemeh Amrollahi et al. “Contextual embed-
  dings from clinical notes improves prediction
  of sepsis”. In: AMIA Annual Symposium Pro-
  ceedings. Vol. 2020. American Medical Infor-
  matics Association. 2020, p. 197

  

- Dependencies

  1. Text preprocessing: text/preprocessing_notes.ipynb to clean the notes, and then use text/to_embeddings.ipynb to convert the BERT embeddings. text/to_tfidf.ipynb to calculate the TF-IDF
  2. data to tensor: produce_tensor/Check features in chartevents.ipynb and store_data_in_tensor_5-8-22.ipynb.
  3. dataloader, training model: training/training_BERT_structured.ipynb, training/training_structured.ipynb

  

- Data download instruction

  Data is available in the website (see https://physionet.org/
  content/mimiciii/1.4/) once you pass the train-
  ing courses (see https://eicu-crd.mit.edu/
  gettingstarted/access/).

  