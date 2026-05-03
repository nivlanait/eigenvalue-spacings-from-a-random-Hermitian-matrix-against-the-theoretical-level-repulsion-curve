# Eigenvalue Spacing Analysis (Random Matrix Theory)

This project explores the statistical behavior of eigenvalue spacings in random Hermitian matrices and compares empirical results against the theoretical **level repulsion curve** predicted by Random Matrix Theory.

---

## 📌 Overview

Random Matrix Theory predicts that eigenvalues of large random Hermitian matrices exhibit **repulsion**—meaning adjacent eigenvalues are less likely to be very close together. This project:

- Generates random Hermitian matrices
- Computes their eigenvalues
- Analyzes nearest-neighbor eigenvalue spacings
- Compares empirical distributions to theoretical models (e.g., Wigner surmise)

---

## 🧠 Key Concepts

- **Hermitian matrices** → Real eigenvalues, symmetric structure  
- **Eigenvalue spacing** → Differences between consecutive sorted eigenvalues  
- **Level repulsion** → Eigenvalues tend to avoid clustering  
- **Wigner distribution** → Theoretical model for spacing distribution  

---

## ⚙️ Methodology

1. **Matrix Generation**
   - Construct random Hermitian matrices (complex or real symmetric)

2. **Eigenvalue Computation**
   - Compute eigenvalues using numerical linear algebra

3. **Spacing Calculation**
   - Sort eigenvalues and compute nearest-neighbor gaps

4. **Normalization**
   - Normalize spacings to allow comparison across simulations

5. **Statistical Analysis**
   - Aggregate spacing data over many trials

6. **Visualization**
   - Plot histogram of empirical spacings
   - Overlay theoretical level repulsion curve

---

## 📊 Results

The simulation demonstrates that:

- Eigenvalue spacings follow a non-uniform distribution
- Small spacings are suppressed (repulsion effect)
- Empirical results converge toward the theoretical curve as sample size increases

---
