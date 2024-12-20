# ML_lab_project

# Random Vector Analysis Using Poisson and Gaussian Distributions

This project involves analyzing a random vector—a collection of random values in \( n \)-dimensions (\( n \geq 100 \))—and fitting Poisson and Gaussian distributions to the collected data. The aim is to explore the characteristics of the data and compare its alignment with these statistical models.

---

## Key Features:
1. **Random Vector Generation**: 
   - Generates an \( n \)-dimensional random vector where \( n \geq 100 \).
   - Utilizes a variety of random generation techniques to simulate realistic data.

2. **Poisson Distribution Fit**:
   - Calculates the parameters for the Poisson distribution.
   - Evaluates how well the random data aligns with the Poisson model.

3. **Gaussian Distribution Fit**:
   - Fits a Gaussian (Normal) distribution to the data.
   - Computes mean (\( \mu \)) and standard deviation (\( \sigma \)) for the dataset.

4. **Visualization**:
   - Provides visual representations for better understanding:
     - Histograms of the data.
     - Fitted Poisson and Gaussian curves.
   - Overlays both distributions to compare their fit.

5. **Statistical Analysis**:
   - Computes goodness-of-fit measures (e.g., Chi-square test, KS test).
   - Provides insights into which model best represents the data.

---

## Technologies Used:
- **Programming Language**: Python
- **Libraries**: NumPy, SciPy, Matplotlib, Seaborn, Pandas

---

## Usage Instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/random-vector-distribution-fit.git
   ```
2. Navigate to the project directory and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python fit_distributions.py
   ```

---

## Applications:
- Statistical modeling and simulation.
- Analysis of large-scale random data.
- Comparison of theoretical distributions to empirical data.

---
