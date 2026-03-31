# ***Real-Time Detection and Prediction of Epileptic Seizures using EEG Signals***

<img width="850" height="650" alt="image" src="https://github.com/user-attachments/assets/542206a2-ad2a-4bb6-a485-24e0940080bb" />
## ***The aim of this project is to develop an AI/ML-based system that detects and predicts epileptic seizures from EEG recordings, using real-world patient data from the CHB-MIT Scalp EEG and the Bonn Database.***

---
## Problem Statement
- Epilepsy is a long-term, noncommunicable brain disease that affects people of all ages. 
- According to the World Health Organization, about 50 million people around the world have epilepsy.
- It is estimated that up to 70% of those living with epilepsy could be free of seizures if they receive the right diagnosis and treatment.
- The latest global data from 2021 suggests that idiopathic epilepsy caused around 140,000 deaths worldwide that year. 
- The Neurology Center for Epilepsy and Seizures reports that the costs specifically related to epilepsy range from $1,022 to $19,749 per year for general epilepsy populations.
- Interpreting EEG data is difficult and lacks real-time seizure prediction, which makes it hard for patients to trust the results. It also takes neurologists a long time to make immediate interpretations.
- Our inspiration for this project came from a conversation with a faculty member whose son faces severe epilepsy; the need for real-time monitoring became personally important to us.

### **Existing EEG Prediction Accuracy vs Our accuracy (NeuroPulse):**
<img width="2027" height="645" alt="image" src="https://github.com/user-attachments/assets/ce0f1a01-99f0-428a-a908-6740194633b6" />




##  How our solution helps tackle current problems-
- The current epilepsy management system faces challenges due to expensive EEG tests, a shortage of neurologists, and insufficient continuous monitoring. Our device addresses these issues with a portable, AI-powered EEG device that allows for real-time seizure detection and prediction at a much lower cost than traditional methods.
- Through its cloud-based dashboard, our device connects patients and neurologists for easy communication and quick prescriptions. This enables remote EEG tracking, timely interventions, and improved medication adherence. It makes neurological care affordable, accessible, and ongoing, especially in underserved areas.
- The lightweight, rechargeable headband has a flexible polymer frame that fits different head shapes and uses eight electrodes for nearly perfect signal accuracy. An embedded audio chip provides real-time voice prompts like "Breathe deeply" when it detects abnormal spikes, helping patients stay calm and react quickly.
- If any abnormality in spikes is detected, an immediate alert signal will be sent to nearby doctors and the loved ones.
- Our device will detect live seizures in different timeframes. A user can set up his/her EEG device for a specific time range. For example, an individual can set his/her EEG device for 30/60 minutes or more. Meanwhile, he/she can go to sleep or can do another activity.

### **Published Research Paper Link**- [Research Paper](https://ieeexplore.ieee.org/document/11378780)
### **UK Patent Link**- [EEG Portable Headband](https://www.registered-design.service.gov.uk/find/reu1b8gk/93286159/designsbyowner)

## **Links for Accessing our system:**
Streamlit App:
1. FFT Visualization: [**FFT_Visualization**](https://fft-visualization.streamlit.app/)
2. STFT Visualization: [**STFT Visualization**](https://stft-visualization.streamlit.app/)
3. Seizure Predictor: [**Seizure Predictor**](https://seizure-predictor.streamlit.app/)
   
**Note- At the current stage, please refer to [EEG_Epilepsy_Prediction/notebooks/data] and use one of the Z/O/N/F/S files in the streamlit applications**
- 
##  Technologies Used
1. Hardware & Signal Acquisition-
   - EEG Headband: 8 dry electrodes for real-time data acquisition
   - Microcontroller: ESP32 / Arduino Nano for signal processing
   - Amplifier Module: ADS1299 (Texas Instruments) for biopotential signals
   - Wireless Transmission: Wi-Fi / Bluetooth (BLE) for cloud connectivity

2. Machine Learning & Signal Processing
   - Languages: Python (NumPy, Pandas, SciPy, Scikit-learn, TensorFlow/Keras)
   - Algorithms: FFT, STFT, Wavelet Transform, Lyapunov Exponents, fine-tuning using statistical methods.
   - Models: Ensemble ML Model Learning for seizure detection & prediction
   - Performance: 97%+ accuracy on real patient data

3. Visualization & Dashboard
   - Platform: Microsoft Power BI / Streamlit (prototype testing)
   - Libraries: Matplotlib, Plotly for EEG signal graphs and heatmaps
   - Visualization: Frequency bands (α, β, γ, δ), STFT heatmaps, real-time brain region mapping
   - Output: Doctor–Patient dashboard for tracking signals, medications, and alerts

3. Visualization & Dashboard
   - Frontend: React.js / HTML5 / CSS3 (Responsive UI for portal)
   - Backend: Node.js / Flask API for data handling
   - Database: Firebase / MongoDB for patient and doctor records
   - Cloud Hosting: Azure / AWS for real-time EEG data streaming & alert management

---

## Web-Page Structure-
![web-page](https://github.com/user-attachments/assets/cc6700af-7c23-4cf0-96a1-089e61b38a3c)


##  Credits

- Patient data used from the open-source
- 1. **CHB-MIT Scalp EEG Database** on [**PhysioNet**](https://physionet.org/).
  2. **Bonn Dataset** on [**Bonn**](https://www.upf.edu/web/ntsa/downloads/-/asset_publisher/xvT6E4pczrBw/content/2001-indications-of-nonlinear-deterministic-and-finite-dimensional-structures-in-time-series-of-brain-electrical-activity-dependence-on-recording-regi)

---

##  Contact

For questions, collaborations, or contributions:
- Pranit Gore Email: pranitgore05@gmail.com
- Aditya Mane Email: adityamane1402@gmail.com
