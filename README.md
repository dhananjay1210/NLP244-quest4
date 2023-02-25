# NLP244-quest4

This model translates the SNLI dataset to french and then performs NLI.

1) The environment variables are stored into .env file. Please update this file before running notebooks.

2) All the dependancies are listed in the 'reqiurements.txt' file. Please install them using pip or conda environment.

3) Run 'quest_4_data_analysis' notebook to generate French dataset. It will be stored locally in 'data' folder and also pushed to the huggingface. I have used 100000 datapoints from train file and translate them. The whole dataset takes time to run.

4) Run 'quest_4_model' to train 'distilcamembert-base' for NLI. Validation F1 score: 0.7465, Test F1 score: 0.7487