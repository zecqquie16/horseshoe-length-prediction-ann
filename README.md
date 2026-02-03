# horseshoe-length-prediction-ann
Shallow neural network project in MATLAB to predict horse shoe external length.
# Predicting Horse Shoe External Length using a Shallow Neural Network

This project presents a **shallow artificial neural network (ANN)** implemented in **MATLAB** to predict the **external curve length of horse shoes** based on four geometric measurements.

The work was completed as part of an academic coursework at **De Montfort University**.

---

## Project Overview
The objective of this project was to design, train, and evaluate a neural network capable of making accurate predictions on a real-world geometric problem.

**Inputs:**
- Internal curve length  
- Width length  
- Cord length  
- Curve length  

**Output:**
- External curve length of the horse shoe

---

## Technologies
- MATLAB
- Artificial Neural Networks
- Data normalisation and preprocessing
- Experimental evaluation and visualisation
- 
---

## Methodology
- Dataset of 219 horse shoes
- Input normalisation to [0,1] range
- Data split:
  - 70% training
  - 20% validation
  - 10% testing
- Shallow neural network topology
- Hyperparameter optimisation
- Performance evaluation using:
  - Mean Absolute Percentage Error (MAPE)
  - Root Mean Squared Error (RMSE)

---

## Results
- Achieved a **MAPE of approximately 2.76%** on test data
- RMSE around **0.538 cm**
- Optimal validation performance obtained with a small hidden-layer topology
- Demonstrated strong correlation between predicted and real values

---

## Visual Outputs
The project includes:
- Predicted vs real value plots
- Training and validation performance curves
- Input distribution histograms
- Neural network training illustrations

---

## Documentation
- Academic poster available in `/docs/poster`
- Presentation slides available in `/docs/presentation`

---

## Author
**Zakaria Boutarfa**  
De Montfort University  

---

## Notes
The dataset may not be publicly available due to academic constraints.  
The code and documentation are provided for educational purposes.




