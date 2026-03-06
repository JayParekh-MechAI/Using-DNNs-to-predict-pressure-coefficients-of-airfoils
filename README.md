# Using-DNNs-to-predict-pressure-coefficients-of-airfoils

# Using Deep Neural Networks to Predict Pressure Coefficients of Airfoils
**BEng (Hons) Mechanical Engineering Dissertation | Final Year Project**

## 📌 Project Overview
This dissertation investigates the application of Deep Neural Networks (DNN) to predict the pressure coefficients ($C_p$) of low Reynolds number airfoils. Traditionally, these values are obtained through computationally expensive CFD (Computational Fluid Dynamics) simulations. This project proves that a trained neural network can provide high-accuracy predictions in a fraction of the time.

## 🚀 Key Achievements
* **High Accuracy:** Developed a DNN model with an **accuracy of 97.58%**.
* **Performance Optimization:** Achieved a **50% improvement** in error margins compared to previous benchmark models (Zelong et al., 2018).
* **Innovation:** Successfully implemented **Exponential Linear Unit (ELU)** activation functions to outperform standard ReLU configurations in aerodynamic contexts.

## 🛠 Technical Stack
* **Physics Domain:** Fluid Dynamics, Airfoil Theory, Reynolds Numbers (50,000), Mach 0.1.
* **Machine Learning:** Deep Neural Networks (DNN), Multi-layer Perceptrons.
* **Tools:** Python, TensorFlow/Keras, XFoil (for data generation/validation).
* **Optimization:** Comparison of various hidden layer configurations (e.g., 256 to 128 neurons).

## 📊 Methodology & Logic
1. **Data Acquisition:** Generated pressure coefficient data for 2D airfoils at a 6.5° angle of attack using XFoil.
2. **Model Architecture:** Evaluated multiple architectures, finding that a 2-hidden layer model provided the optimal balance between speed and precision.
3. **Validation:** Compared DNN predictions against "True Values" to generate R² scores and error distribution histograms.



## 📄 Project Documentation
* [**Main Dissertation Report (PDF)**](Main%20Report.pdf) – Complete 100+ page thesis covering literature review, methodology, and results.
* [**Project Logbook (PDF)**](Logbook.pdf) – A chronological record of the 20+ week research and development process.
* [**Presentation & Viva (PDF/PPTX)**](Presentation%20and%20Viva.pdf) – Summary of the findings presented to the academic board.

---
**Core Skills:** Artificial Neural Networks (ANN), Fluid Mechanics, Python Programming, Aerodynamic Analysis, Data Pre-processing.
