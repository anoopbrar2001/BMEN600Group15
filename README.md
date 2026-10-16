# BMEN600 Project
## Team 15
## Team Members Present
Anoop Brar, Ella Watson, Noah Willfong, Aashir Ali
## Candidate Project 1
## Biomedical Problem
Wearable Sensors for Seizure Detection
## Possible Research Question:
Is there a way to develop a wearable sensor that utilizes non EEG & ECG data for early seizure prediction in pediatric epileptic patients?
## Data set
https://openneuro.org/datasets/ds005873/versions/1.1.0
## Biggest Uncertainty:
Our biggest uncertainty is the size of the dataset and if it will provide sufficient and relevant data for the project.
## Candidate Project 2
Impaired Gait Analysis for Rehabilitation of Concussion Patients
## Possible Research Question
Can gait analysis be used for rehabilitation for adult patients with traumatic brain injuries?
## Data set
https://zenodo.org/records/15729056
## Biggest Uncertainty:
Our biggest uncertainty is the need for multiple datasets to do a proper comparison of impaired & non-impaired patients.
## Current decision:
We are currently leaning towards Project 1, due to the availability of data related to seizure prediction, symptoms, and the variety of tracking methods (EEG, ECG, etc.)
## Project Decision
REVISE - The overall project works, but we need to assess the feasibility of our target population, what specific physiological data makes the most sense for us to measure, and the research gap our project fills.
## REVISED RESEARCH QUESTION
How accurately can non-convulsive focal seizures be detected from accelerometer, gyroscope and EMG technology? 
## Team plan

<img width="970" height="745" alt="image" src="https://github.com/user-attachments/assets/bb5f1824-e98f-4dfe-9162-229e7e270d3f" />

## Participant metadata table:
The participant-level metadata and recording summary are available below:

- [View participant metadata and recording summary](data/participant_metadata_and_recording_counts.csv)

## Dataset source and access
The project uses the SeizeIT2 dataset, available through OpenNeuro, ds005873, version 1.1.0. The dataset contains physiological recordings, including movement and EMG data, that will be investigated for non-convulsive focal seizure detection. The dataset can be found at: https://openneuro.org/datasets/ds005873/versions/1.1.0
The raw dataset is accessed from the original source and is not duplicated in this repository. The repository contains our analysis code and derived metadata outputs. Dataset access and use should follow the terms specified by the original source.

## Current Progress
We have developed a preliminary metadata analysis to summarize participant characteristics, identify available signal files, and compare dataset counts with figures used in our project report. The current outputs provide an initial assessment of data availability but do not establish seizure-detection accuracy. Event annotation validation, confirmation of sensor channels, and model evaluation remain outstanding.

## Repository Contents
README.md: Project background, research question, dataset source, and instructions.
SeizeIT2_Midterm_Notebook.ipynb: Jupyter notebook for preliminary metadata analysis and data-quality checks.
data/participant_metadata_and_recording_counts.csv: Participant-level metadata and recording summary.
outputs/: Generated metadata summaries, cleaned tables, file inventories, and consistency checks.
requirements.txt: Python packages required to run the notebook.

## Software & Setup
The preliminary analysis uses Python in Jupyter Notebook. The main packages include pandas and NumPy, alongside Python's standard libraries for retrieving dataset metadata.
Install the required packages using:
pip install pandas numpy ipython jupyter

## How to Run the Preliminary Analysis
1. Clone or download this repository.
2. Install the required Python packages.
3. Open Jupyter Notebook in the project directory.
4. Open SeizeIT2_Simple_Midterm_Notebook.ipynb.
5. Run the notebook cells in order.
6. Review the generated CSV files in the output directory.
An internet connection is required to retrieve metadata from the configured dataset sources.

## Limitations
The current analysis summarizes file availability rather than usable seizure events. The number of eligible non-convulsive focal seizures has not yet been established, and the required accelerometer, gyroscope, and EMG channels must be verified. Dataset version consistency must also be checked before the final analysis.
