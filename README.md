# Probability_density_functions_102313045
# Learn Probability Density Functions using Roll-Number-Parameterized Non-Linear Model

##  Project Description


The objectives are:

1. Apply a roll-number-based nonlinear transformation to NO₂ values.
2. Learn parameters of a Gaussian-type probability density function.
3. Estimate the parameters using Maximum Likelihood Estimation (MLE).

---

##  Dataset Used

**Dataset:** India Air Quality Data  
**Source:** Kaggle  

🔗 https://www.kaggle.com/datasets/shrutibhargava94/india-air-quality-data  


##  Methodology

### Step 1: Non-Linear Transformation

Each NO₂ value (x) is transformed using:

z = x + a_r sin(b_r x)

Where:

a_r = 0.05 × (r mod 7)  
b_r = 0.3 × ((r mod 5) + 1)  

r = University Roll Number

---

### Step 2: Probability Density Function

We estimate parameters of:

p̂(z) = c e^(−λ (z − μ)²)

Where:

- μ = Mean parameter  
- λ = Precision parameter  
- c = Normalization constant  

Parameters are learned using Maximum Likelihood Estimation (MLE).

---

##  Output

- Estimated λ  
- Estimated μ  
- Estimated c  
- Histogram of transformed data  
- Learned probability density curve  
<img width="618" height="510" alt="Screenshot 2026-02-19 at 2 53 35 AM" src="https://github.com/user-attachments/assets/a24e09f6-7b4e-4a21-9a13-8615ab653e48" />

---

##  Author

Name: SNEHA GUPTA  
Subject: Predictive Analytics (UCS654)
