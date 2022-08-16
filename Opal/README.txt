1. BART_model is the best model fine-tuned on drug reviews restricted to osteoporosis (2 labels: 
["effectiveness", "side effects"].

2. Folder Data contains all the preprocessed and original data for fine-tuning.

3. Folder Results contains all the output plots.

4. Inside the folder Scripts:
	two EDA files for initial data exploratory analysis
	fine_tune_BART.ipynb contains the tutorial for fine-tuning BART on drug reviews with two labels
	fine_tune_BART_prob.ipynb reloads the best fine-tuned BART model and output probabilities instead of labels
	fine-tune-tutorial.ipynb contains the implementation pipeline for fine-tuning any models from Huggingface
	fine_tune_BART_prob_m.ipynb contains the tutorial for fine-tuning BART on drug reviews with 10 labels.
