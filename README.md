# Automatic Text Summary Generation

## Project on automatic abstractive text generation on Cornell Newsroom dataset

## PyTorch

The aim of our project is to increase the accu-racy  of abstractive  text  summarization by  takinghelp of extractive summarization technique as, inpractice, extractive summarization performs betterthan abstractive summarization.

The baseline model is trained on two data sets, asmentioned  in  section  3.1.  A common vocabulary is built for encoder and decoder of our base-line  model.    The  vocabulary  consists  of  all  thewords present in either text or summary in train-ing  data. All theword embedding are randomly initialized and arelearnt during training. In order to quan-tify the quality of the summary generated by ourbaseline model, we are using ROUGE-1, ROUGE-2 and ROUGE-L scores.

Several  variants  of  model  and  baseline  model are compared
* seq2seq model with random word embeddingand copy mechanism
* seq2seq model with ELMO word embedding
* seq2seq  model  with  intermediate  extractive summarization and random word embedding
* seq2seq  model  with  intermediate  extractivesummarization and random word embeddingwith copy mechanism
* seq2seq  model  with  intermediate  extractivesummarization and ELMO word embeddingwith copy 
