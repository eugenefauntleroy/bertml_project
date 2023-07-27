# bertml_project

# Hate Speech Multi-Label Classifier
This Python script is a machine learning model that identifies and categorizes hate speech in a given text. The categories include race, religion, origin, gender, sexuality, age, and disability. The script uses the DistilBert model for sequence classification from HuggingFace's Transformers library. The base code for this script was inspired by Wesley A. Chung.

# Requirements
The script requires the following Python libraries:

## numpy
## torch
## transformers
## atasets
## matplotlib
## sklearn
## tqdm 

You can install these libraries using pip:

pip install numpy torch transformers datasets matplotlib sklearn tqdm

# Usage
The script does not take any direct input parameters. It uses a pre-defined hate speech dataset from HuggingFace's Datasets library.

You can run the script using Python:

python hate_speech_multilabel_classifier.py

# Outputs
The script will output a trained model that can classify hate speech into specific categories. It also provides a pipeline for classifying new text.

The script also outputs visualizations of the count and percentage of hate speech types in the dataset.
<img width="629" alt="bertresult2" src="https://github.com/eugenefauntleroy/bertml_project/assets/51951486/99c370e5-a1e2-41bd-8bf1-8ed1d6bdde68">
<img width="626" alt="bertresult3" src="https://github.com/eugenefauntleroy/bertml_project/assets/51951486/a9f6ccde-e446-4790-a2b7-945b8ce9b40a">


# Important Details
This script uses a multi-label classification approach, meaning each text can belong to multiple categories of hate speech. The model is trained for one epoch, but this can be adjusted.

The trained model's state is saved after each epoch. The path to the saved model should be updated according to your environment.

# Credits
This script was inspired and is a modified version of a work by Wesley A. Chung.

