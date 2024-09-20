# MINRO_EEG_analysis
**Overview**
Welcome to the Rest_Med dataset repository. This dataset is part of our research presented in the paper titled "Novel Dataflow Approach for Dynamic Feature Extraction and Significant Observation Selection in High-Dimensional EEG Analysis". The dataset contains raw EEG recordings used to analyze brain activity during rest and meditation states, focusing on dynamic feature extraction and observation selection in high-dimensional EEG data.

**Dataset Description**
The Rest_Med dataset includes EEG recordings from 10 participants, with recordings taken under two main conditions:
    Rest State: Each participant’s EEG was recorded for 5 minutes, resulting in continuous data(c_rest,m_rest).
    Meditation State: Recorded over 15-20 minutes, divided into 6 segments, with each segment paired with a 5-minute rest segment from the same                     participant(c_med,m_med).
    Note: The dataset provided here is the original, unsegmented EEG data. Segmentation details are not included in this repository.

**Data Collection Details**
    Participants: 10 individuals (5 novices, 5 experienced meditators)
    Electrodes: Placed according to the international 10-20 system
    Collection Device: 8-channel EEG device with accelerometer
    Device Class: ENOBIO
    Communication Type: USB
    Software Version: NIC 2.1.3.4
    Firmware Version: 3031

**Data Format**: 
    File Type: EDF (European Data Format)
    Columns: 8 EEG channels and 3 accelerometer channels
    Sample Size: 10 participants with EEG data recorded for both rest and meditation states. Total data includes 20 full sessions (rest and meditation).
    EEG device sampling rate: 500 Samples/second
    Accelerometer sampling rate: 100 Samples/second
    For detailed information on the data collection setup, refer to Appendix-1 of research paper.

**Channels**
The dataset includes data from the following:
    EEG channels:Fp1,Fp2,C3,C4,P3,P4,O1,O2.
    Accelerometer Channels (3 channels):X (X-axis),Y (Y-axis),Z (Z-axis).
    



**Acknowledgments**
We thank the participants for their contribution and the Minro Lab IKS for their support in data collection and analysis.

**Link to Dataset**

https://drive.google.com/drive/folders/18HNQBSg58WoEE4I-HHc9bliqegaMYHqp?usp=sharing

