# NLU_final_project

This is the GitHub repo for the final project for the course NaturalLanguageUnderstanding @ UNITN 2020-2021.

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
- Coadapt Sentiment: Private datasets. `data/Coadapt`
- [AriEmozione 1.0](https://zenodo.org/record/4022318#.YRTaYYgzZPY): `data/Aria`
- [TRIP-MAML](https://github.com/diegma/trip-maml): `data/Trip-maml`

## Environment
The file environment.yml contains a Conda env to [automatically](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) install all the relevant packages

## Report
A more detailed description of this project is available in `report.pdf`
