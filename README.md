# On the evaluation of BERT-based models for Italian Sentiment Analysis

This is the GitHub repo of the final project for the course NaturalLanguageUnderstanding @ UNITN 2020-2021.

## Task
The goal of this project was to test 2 BERT-based italian models on multiple italian datasets from different domain, in order to compare their performances and to assess their generalization capabilities, with and without finetuning.

## Models
- [AlBERTo-IT](https://github.com/marcopoli/AlBERTo-it)
- [FEEL-IT](https://github.com/MilaNLProc/feel-it)

## Data
To run the code, make sure to have all the datasets in `data/`:
- [SENTIPOLC16](http://www.di.unito.it/~tutreeb/sentipolc-evalita16/index.html): `data/Sentipolc16`
- [FEEL-IT](https://github.com/MilaNLProc/feel-it): `data/Feel-it`
- [MultiEmotions-IT](https://github.com/RacheleSprugnoli/Esercitazioni_SA/tree/master/dataset): `data/Multiemotions-it`
- Amazon reviews: Private datasets. `data/Amazon-reviews`
- Coadapt Valence: Private datasets. `data/Coadapt_valence`
- [AriEmozione 1.0](https://zenodo.org/record/4022318#.YRTaYYgzZPY): `data/Aria`
- [TRIP-MAML](https://github.com/diegma/trip-maml): `data/Trip-maml`

## Code
- AlBERTo reproduction.ipynb: code to reproduce the results presented in the AlBERTo's paper, with a utility to run multiple experiments with different random seeds, in order to collect evidence and compute statistics about convergence
- AlBERTo enhancements.ipynb: code to explore some minor architectural and hyper-params changes, in order to improve the AlBERTo's performances on polarity classification
- AlBERTo multiclass.ipynb: code to adapt AlBERTo to multi class predictions, along with some hyper-parameter tuning and train/validation split
- Error analysis.ipynb: code to train and test AlBERTo and Feel-IT on the various datasets, with and without fine-tuning
- report.pdf: report
- SOM.pdf: downloaded copy of the Support Online Material cited in the report
- Project presentation.pdf: slides used for the presentation of the project with prof. Riccardi and Gabriel Roccabruna (25-09-2021)

## Environment
The file environment.yml contains a Conda env to [automatically](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) install all the relevant packages

## Report
A more detailed description of this project is available in `report.pdf`. Supplementary online material is available [here](https://docs.google.com/presentation/d/1QatCNkoasTE8R3Huii7lO47lHLfqErN3E12LipOh07M/edit?usp=sharing).
