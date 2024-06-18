# Single IMU-based Multisegment Motion Analysis and Prediction

## Synopsis

Accurately estimating human gait and joint motion is crucial in the field of rehabilitation and motion analysis. Traditional methods of gait analysis, such as motion tracking systems, capture joint angles and provide insights into movement disorders. However, these methods are complex, expensive, and require extensive setup.

Abnormal gait results from injuries that affect joints in the body, disrupting the cyclic patterns of gait. There is a significant biomechanical relationship between the shank and thigh segments regarding the cyclic patterns of gait. This relationship in the kinematic chain of the shank and thigh will be investigated to estimate thigh angular velocities from data collected from the shank.

### Research Gap
There are minimal approaches that can provide accurate joint motion estimation while being minimally invasive and cost-effective.

### Novelty
This project collects subject data to estimate thigh angular velocities from shank angular velocity data to monitor the progression of injury.

## Contents

- `README.md`: Readme file for the project.
- `requirements.txt`: File listing dependencies.
- `gait_analysis.ipynb`: Jupyter Notebook for the project.
- `updated_my_dataset/`: Folder containing the dataset.
  - `Normal_Processed/`: Contains 10 Excel files for normal gait data collected (one for each subject).
  - `Weighted_Processed/`: Contains 10 Excel files for weighted gait data collected to simulate injury (one for each subject).
- `FYP-Presentation-Ibrahim.pdf`: Project presentation report.

## Instructions

1. Navigate to the project directory:
```bash
    cd imu-based-multisegment-gait-analysis
```
2. Install dependencies using pip:
```bash
    pip install -r requirements.txt
```
3. Open and run the Jupyter Notebook gait_analysis.ipynb to explore the project.
4. Ensure that the dataset files in the updated_my_dataset directory are correctly sourced in the notebook.
5. Experiment with the code, modify parameters, or integrate new functionalities as needed.
6. Refer to FYP-Presentation-Ibrahim.pdf for a detailed project presentation and analysis.