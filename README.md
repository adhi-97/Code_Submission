# Meta-Learning Approaches for Overcoming Subject Variability, Limited Data Availability, and Challenges in EEG-Based Motor Imagery Classification

This repository is the official implementation of [Meta-Learning Approaches for Overcoming Subject
Variability, Limited Data Availability, and Challenges
in EEG-Based Motor Imagery Classification]

## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```
## Datasets Used
1. BCI Competition IV 2a
2. PhysionetMI

## Training

To train the model(s) in the paper, run this command:

```Run the model
python run.py
```
### Things to conside while running the code.

1. For BCI Competition IV 2a dataset:
  - current setting: 
      subject 2 to 9 (train)
      subject 1 (test)
      to change the subject for test please modify line 32, 33 (dataloader_BCI_Competition_IV.py)
      
2. For physionetMI dataset:
  - current setting:
      Train: subject 1 to 40
      Test: subject 41-50
      to change the subject for test please modify line 41, 42 accordingly
      channels: 64
      to change number of channels modify line 35 and 36 (dataloader_physionet_MI.py) and line 12,13 (learner.py)
      

<!-- ## Results

Our model achieves the following performance on : -->

