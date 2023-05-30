# BirdCLEF 2023 - Identify bird calls in soundscapes

## Description:

This repository contains my notebooks and code for the BirdCLEF 2023 challenge. The goal of the challenge is to identify bird calls in soundscapes. The dataset consists recordings made in Kenya. The recordings are labeled with the species present in the recording. The challenge is to identify the species present in the recording. You can check the competition on  Kaggle: https://www.kaggle.com/c/birdclef-2023/overview

## Usage:

* Download the dataset from Kaggle and place it in the `birdclef-2023` folder. The `birdclef-2023` folder should have the following structure:

    ```bash
    birdclef-2023
    ├── train_audio
    │   ├── species_name
    │   │   ├──XC12345.ogg
    │   │   ...
    ├──test_soundscapes
    │   ├── soundscapes.ogg
    ├──train_metadata.csv
    ├──sample_submission.csv
    ├──eBird_Taxonomy_v2021.csv
    ```
  
* Install the required packages using `pip install -r requirements.txt`
* Start the notebook server using `jupyter notebook`
* Open the notebook and run the cells

