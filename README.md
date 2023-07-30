# Intrusion Detection using Machine Learning (ML)

This project was conducted during a 12-week BrainStation Data Science bootcamp. The main objective was to build an Intrusion Detection model using ML capable of adapting to new types of network attacks, not easily detectable by conventional IDS solutions on the market.

## Why an ML IDS?

With the increasing frequency of attacks on private networks, a simple ML model trained on synthetic data and deployed to analyze PCAP data for anomaly detection is highly relevant to today's commercial security needs. The advantage of this IDS lies in its ability to become robust through extensive training on various data sources.

## Phases of the project:

- [Data Loading and Cleaning](https://github.com/MDSV9/capstone/blob/a5fe55f857adb9b0bcd7ba43d08d54ab39bd78c6/Notebooks/Data%20Loading%20and%20Cleaning.ipynb): Notebook for loading the collected data and cleaning simple problems.
- [EDA and Data Split](https://github.com/MDSV9/capstone/blob/a5fe55f857adb9b0bcd7ba43d08d54ab39bd78c6/Notebooks/EDA%20and%20Train-Test%20Split.ipynb): Notebook for exploratory data analysis and data splitting.
- [Base Model Training](https://github.com/MDSV9/capstone/blob/a5fe55f857adb9b0bcd7ba43d08d54ab39bd78c6/Notebooks/Base%20Model.ipynb): Notebook for initial model training.
- [Advanced Model Training and Model Evaluation](https://github.com/MDSV9/capstone/blob/460c9f0f321827ecf8a28f52a9942484bdbb52de/Notebooks/Advanced%20modeling%20and%20Model%20Evaluation.ipynb): Notebook for improving model performance and it's evaluation (WARNING: This notebook takes considerable resouces and time to run).

## Resources:

- [Data Collection](https://drive.google.com/drive/folders/1z0_TUUPjnYUQ5X1e-gOQl3xVd3b7gquG?usp=sharing): Link to the original dataset used.
- [Data Dictionary](https://github.com/MDSV9/capstone/blob/a5fe55f857adb9b0bcd7ba43d08d54ab39bd78c6/data-dict.pdf): PDF document explaining the data attributes.
- [Final Capstone Presentation](https://drive.google.com/file/d/1MsTl-ni7F6vQhnJILQsl6QTOkjTfItjM/view?usp=drive_link): Google Drive link to the final project presentation.

## Directory Structure:

Ensure the following directories exist in the root of the project:

1. `data/`: Place the raw data files here.
2. `processed/`: The preprocessed data will be saved in this directory.
3. `visuals/`: Store any visualizations or plots generated by the notebooks here.
4. `temp/`: Temporary files or intermediate outputs can be stored here.

## Anaconda Environment:

An Anaconda environment file (`environment.yml`) is included in the repository. It contains all the necessary dependencies for running the Jupyter notebooks within this project. To set up the environment, use the following command:
`conda env create -f environment.yml`
After creating the environment, activate it before running the notebooks:
`conda activateCapstone_env`

## Contact Me: 

Thank you for showing interest in my Capstone project! If you'd like to discuss my findings, offer suggestions, or chat about related topics, feel free to [reach out to me via email](mailto:moisesdsvera+capstone@gmail.com).
