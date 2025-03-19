# **Obesity Factor Analysis** 📊  

### **📌 Overview**  
This project analyzes key factors associated with **obesity risk**, including:  
✔ **Demographics** – Age, Gender, Weight  
✔ **Family History** – Genetic predisposition to obesity  
✔ **Lifestyle Choices** – Smoking, Exercise Frequency, Eating Habits  
✔ **Daily Activity** – Use of public transport vs. sedentary behavior  

Using **R**, we explore trends, correlations, and build models to understand obesity-related risks.  

---

### **🛠 Technologies & Dependencies**  
- **RStudio** (Development environment)  
- **Libraries:**  
  - `tidyverse` (Data wrangling & visualization)  
  - `MASS` (Statistical modeling, including Ordinal Logistic Regression)  
  - `ggplot2` (Data visualization)  

To install dependencies, run:  
```r
install.packages(c("tidyverse", "MASS", "ggplot2"))
```

---

### **📊 Analysis & Methodology**  
- **Exploratory Data Analysis (EDA)** – Data cleaning, feature engineering, visualization  
- **Statistical Modeling** – Ordinal Logistic Regression (`polr` from MASS)  
- **Visualization** – Trend analysis using `ggplot2`  

---

### **🚀 How to Run**  
1️⃣ Clone the repository:  
   ```sh
   git clone https://github.com/Kalp25740/obesity-factors-R.git
   cd obesity-factors-R
   ```
2️⃣ Open **RStudio** and load the script:  
   ```r
   source("analysis_script.R")
   ```
3️⃣ Run the models and explore visualizations.  

---

### **📌 Results & Insights**  
📊 **Top factors linked to obesity risk:**  
1. **Dietary Habits** – High correlation between poor eating patterns and obesity.  
2. **Exercise Frequency** – Regular physical activity significantly lowers risk.  
3. **Family History** – Genetic predisposition plays a role.  

---

### **📄 Future Improvements**  
🔹 Expand dataset with more demographic diversity.  
🔹 Improve predictive modeling with ML approaches.  
🔹 Develop an interactive **Shiny app** for obesity risk assessment.  

---

📢 **Contributions are welcome!** Fork the repo, make changes, and submit a pull request. 🚀  

📌 **Check out the repo:** https://github.com/Kalp25740/obesity-factors-R 
