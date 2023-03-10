University Rating
==============================
Finding chance of getting admission in university


AWS elstic beanstalk link: http://universityadmission-env.eba-pkhdpav5.ap-northeast-1.elasticbeanstalk.com/ </br>
Azure link: https://university-admission.azurewebsites.net/


Project Organization
------------

    ├── README.md          <- Documentation of the project
    ├── data
    │   ├── processed      <- Processed data
    │   └── raw            <- Input data
    │
    ├── models             <- Saved models, scalers and other saved states
    │
    ├── notebooks          <- Experimenting with data
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── tests               <- testing files
    │   ├── test_config.py  <- Tests for inputs and outputs
    │   │ 
    │   └── conftest.py     <- Fixtures for tests
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   └── models         <- Scripts to train models and then use trained models to make
    │       │                 predictions
    │       ├── predict_model.py
    │       └── train_model.py
    │   
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

UI:
main branch


<img width="581" alt="UI-flask" src="https://user-images.githubusercontent.com/68346310/209124452-f05d350b-cb43-4d1b-9fa3-f696212b3592.png">

UI:
gradio-ui branch

<img width="930" alt="UI-Gradio" src="https://user-images.githubusercontent.com/68346310/209124538-21289f3f-bbd6-4a0b-af41-87f0284f329b.png">



1. Add the storage files in data_given/*.csv</br>
2. Run the program using dvc repro
