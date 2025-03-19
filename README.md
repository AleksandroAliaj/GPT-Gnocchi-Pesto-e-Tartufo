# GPT-Gnocchi-Pesto-e-Tartufo
Natural Language Processing, 2023/24, Group Assignment

THE TASKS
The aim of the assignment is to apply the techniques to analyse one of the text
datasets described below. The exact tasks performed may depend on the dataset chosen, but we would
expect to see some of the following:
1. Preliminary analysis:
Briefly describe the dataset:
- what type of documents does it contain?
- how many documents are there?
- calculate and visualise some simple statistics for the collection, e.g. the average document length,
the average vocabulary size, etc.
Play around with documents, using some of the code from the early parts of the course. You could, for
example:
- cluster the documents and visualise the clusters to see what types of groups are present (or
whether the known classes can be found);
- index the documents so that you can perform keyword search over them;
- train a Word2Vec embedding on the data and investigate the properties of the resulting
embedding.
2. Training models:
Each of the datasets comes with a particular task that you need to perform, so:
- train a model to perform that task (by fine-tuning models on the training data);
- test pre-trained models on the task (if they already exist); and
- evaluate different models and compare their performance.
HINT: as a minimum here we would expect to see a linear classifier trained on the data (if an appropriate
for the task) and compare it with deep learning model, such as BERT.
3. Possible extensions:
Depending on the dataset chosen there will be many additional investigations that you can perform, e.g.:
• investigate another task on the same dataset,
• investigate the same task on another related dataset,
• use text-to-speech and speech-to-text models to create a voice interactive system,
• create your own dialog dataset by transcribing audio conversations (e.g. using MS Teams).

THE DATASET
OpenOrca-SlimOrca
• Website: https://huggingface.co/datasets/Open-Orca/SlimOrca
• Paper: https://arxiv.org/abs/2306.02707
• Description: Recorded interactions between a user and the chatbot ChatGPT, that can be used to
train a model to act like ChatGPT.
• Task: Fine-tune a chatbot to mimic ChatGPT.
