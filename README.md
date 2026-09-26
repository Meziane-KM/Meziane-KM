<h1 align="center">Meziane Kacidem</h1>

<p align="center">
  <b>MSc student in Control, Signal & Image Processing (M2 ATSI) · Université Paris-Saclay</b><br>
  Computer Vision · Inverse Problems & Imaging · Deep Learning · Real-time Control
</p>

<p align="center">
  <a href="https://linkedin.com/in/meziane-kacidem"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:m.meziane.kacidem@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/Meziane-KM/TER-deconvolution-wiener-hunt-dps"><img src="https://img.shields.io/badge/Research_project-TER-6f42c1?style=for-the-badge"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🔎_Open_to-6--month_end--of--studies_internship_·_from_March_2027-2ea44f?style=flat-square">
  <img src="https://img.shields.io/badge/📍-Paris_area,_France-555?style=flat-square">
</p>

---

### 👋 About me

I design algorithms that turn **raw measurements into reliable decisions**: reconstructing images from blurred, noisy data, detecting and classifying objects, and controlling physical systems in real time.

- 🎓 **M2 ATSI** (Automatique, Traitement du Signal et des Images), Université Paris-Saclay, with CentraleSupélec, IOGS and ENS Paris-Saclay
- 🔬 **Research project at L2S**: Bayesian image deconvolution with automatic hyperparameter estimation, compared with **Diffusion Posterior Sampling** (diffusion-model priors)
- 🎯 **Looking for** a 6-month internship (March → September 2027) in **computer vision, medical imaging, perception / ADAS or signal processing**, ideally on real data rather than toy datasets
- 🌍 French (fluent) · English (professional working proficiency)

---

### 🔬 Featured project

#### [Bayesian deconvolution: Wiener-Hunt filter vs. diffusion models (DPS)](https://github.com/Meziane-KM/TER-deconvolution-wiener-hunt-dps)
*Research project (TER), L2S lab, Université Paris-Saclay · supervised by François Orieux · 50-page report*

- Recover a sharp image from a blurred, noisy observation $z = Hx + b$ (an **ill-posed inverse problem**)
- **Wiener-Hunt** quadratic regularization solved in closed form with FFT (circulant approximation, $O(N \log N)$)
- **Unsupervised hyperparameter estimation** by marginal likelihood: the likelihood minimum matches the MSE minimum, so no manual tuning is needed
- **Diffusion Posterior Sampling** (Chung et al., 2023) reproduced in PyTorch: DDPM + U-Net prior, 1000-step guided sampling
- Result: Wiener-Hunt **25.68 dB** vs DPS **24.46 dB** PSNR (degraded input: 23.51 dB). DPS gives sharper edges, but a model-based method still wins when the learned prior has seen a single image

`Python` `PyTorch` `NumPy` `SciPy` `FFT` `Bayesian inference`

---

### 🛠️ Other projects

| Project | What I did | Stack |
|---|---|---|
| **Sliding-mode control of a 3-DOF robotic arm** | Dynamic model, SMC law design, **real-time implementation on dSPACE**; lower tracking error than a PID baseline | MATLAB/Simulink, dSPACE, IMU |
| **Vision pipeline** | Real-time object detection and image processing | YOLOv8, OpenCV |
| **Predictive maintenance of an electric motor** | Sensor data acquisition, failure prediction, LSTM vs Random Forest comparison, real-time monitoring | Python, LSTM, Random Forest, Raspberry Pi |
| **Image processing & machine learning** | Filtering, edge detection, thresholding; image classification with SVM and CNN | Python, OpenCV, scikit-learn |
| **Advanced signal processing** | Matched filtering and detection in noise, time-delay estimation, AR modelling (Yule-Walker), source localization (MUSIC, maximum likelihood) | MATLAB |
| **Gesture-controlled robotic arm** | Hand-gesture recognition to drive a pick-and-place arm | Python, OpenCV |
| **DC motor speed & position control** | Modelling and controller design | MATLAB/Simulink |

---

### 🧰 Tech stack

**Languages** <br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white"> <img src="https://img.shields.io/badge/MATLAB%2FSimulink-0076A8?style=flat&logo=mathworks&logoColor=white"> <img src="https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white">

**Computer vision & deep learning** <br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"> <img src="https://img.shields.io/badge/YOLOv8-111111?style=flat"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white">

**Control & embedded** <br>
<img src="https://img.shields.io/badge/dSPACE-005A9C?style=flat"> <img src="https://img.shields.io/badge/Siemens_TIA_Portal-009999?style=flat&logo=siemens&logoColor=white"> <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white"> <img src="https://img.shields.io/badge/FPGA-555555?style=flat"> <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black">

**Methods**
- *Signal & image*: filtering, detection, spectral estimation, restoration, segmentation, Markov random fields
- *Inverse problems*: deconvolution, variational & Bayesian regularization, proximal algorithms, diffusion priors
- *Estimation*: Kalman filtering, maximum likelihood, Cramér-Rao bound, system identification
- *Control*: PID, RST, state feedback, LQR/LQG, H∞, MPC, sliding-mode control

---

### 💼 Experience

**FTTH engineering intern** · KABTELECOM (partner of SOGETREL for Orange) · Normandy · *May–Jul 2025*
Fiber installation, splicing and commissioning; OTDR and power-meter testing, RSSI/throughput diagnostics; support for telecom project planning.

**Electronics / automation maintenance intern** · Sarl Ibrahim & Fils (Ifri) · Béjaïa, Algeria · *Jun–Jul 2024*
Production-line analysis, Siemens S7-1200 PLCs with TIA Portal, preventive-maintenance diagnostics.

**Organizing member & mentor** · IEEE Student Branch, University of Boumerdès · *2021–2022*

---

### 🎓 Education

| | Degree | Institution |
|---|---|---|
| 2026–2027 | **M2 ATSI**: Control, Signal & Image Processing | Université Paris-Saclay |
| 2025–2026 | **M1 E3A, ASDS track**: Control, Data Science, Signal | Université Paris-Saclay |
| 2024–2025 | Licence SPI: Electronics, Signal & Networks | Université Sorbonne Paris Nord |
| 2023–2024 | M1 Electrical Engineering | IGEE (ex-INELEC), Algeria |
| 2020–2023 | Licence (BSc) Electrical & Electronics Engineering | IGEE (ex-INELEC), Algeria |

<details>
<summary><b>Key M2 courses</b></summary>

Scientific Computing in Python · Estimation & Identification (Kalman, ML, Cramér-Rao) · Optimization (duality, proximal algorithms) · Statistical & Reinforcement Learning · Multivariable Control (LQR, LQG, H∞, μ-analysis) · Signal Processing for Imaging Systems · Machine & Deep Learning · Model Predictive Control · Advanced Image Processing (restoration, segmentation, MRF) · Inverse Problems (variational & Bayesian)
</details>

---

<details>
<summary>🇫🇷 <b>En français</b></summary>

Étudiant en **Master 2 ATSI** (Automatique, Traitement du Signal et des Images) à l'Université Paris-Saclay. Je recherche un **stage de fin d'études de 6 mois à partir de mars 2027** en **vision par ordinateur, imagerie, perception ou traitement du signal**.

Mon TER au laboratoire L2S porte sur la **déconvolution d'images** : régularisation de Wiener-Hunt avec estimation automatique des hyperparamètres par inférence bayésienne, comparée à un a priori appris par **modèle de diffusion (DPS)**. J'ai aussi implémenté une commande par modes glissants en temps réel sur dSPACE, un pipeline de vision YOLOv8/OpenCV et un système de maintenance prédictive (LSTM / Random Forest).

N'hésitez pas à me contacter sur [LinkedIn](https://linkedin.com/in/meziane-kacidem) ou par [email](mailto:m.meziane.kacidem@gmail.com).
</details>

<p align="center"><i>♟️ Chess (1800 Elo) · ⚽ Football & running · ✈️ Travel</i></p>
