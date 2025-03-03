# 📌 Analyzing the Impact of Gaming on Academic Performance

## 📖 Overview  
This project explores how gaming habits affect students' grades using demographic factors like parental income and education. We perform **EDA, visualizations, and linear regression** to uncover trends, helping understand the balance between gaming and academic success.  

---

## 📂 Dataset Information  
The dataset includes the following columns:  

| Feature | Description |
|---------|------------|
| **Sex** | Student's gender (`Male` / `Female`) |
| **School Code** | Unique identifier for the school |
| **Playing Years** | Number of years the student has been gaming |
| **Playing Often** | Frequency of gaming (scale 1-5) |
| **Playing Hours** | Hours spent gaming per day |
| **Playing Games** | Number of game types played (`0`: No, `1`: Yes) |
| **Parent Revenue** | Annual family income |
| **Father Education** | Father's education level |
| **Mother Education** | Mother's education level |
| **Grade** | Student's academic grade |

---

## 📊 Methods & Approach  
1️⃣ **Data Preprocessing:**  
   - Handling missing values  
   - Encoding categorical variables  
   - Scaling numerical data  

2️⃣ **Exploratory Data Analysis (EDA):**  
   - Visualizing grade distributions  
   - Analyzing correlations (gaming hours vs. grades, parent income vs. grades)  

3️⃣ **Regression Modeling:**  
   - Applying **Linear Regression** to predict grades based on gaming habits and demographics  
   - Evaluating model performance  

---

## 📈 Key Visualizations  
✅ Correlation heatmap to explore relationships between features  
✅ Box plots to see trends (e.g., **gaming hours vs. grades**)  
✅ Pairplots to Show Relationships  

---

## 🖥️ How to Run the Project  

### 1️⃣ Install Dependencies  
Ensure you have the required libraries:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2️⃣ Run the Jupyter Notebook
``` bash
jupyter notebook
```
### 📌 Expected Outcomes
- Identify patterns between gaming habits and academic success
- Develop a predictive model to estimate grades
- Provide insights for parents and educators on the balance between gaming and studies

## 📜 Author
- 👨‍💻 Name : Senitha Gunathilaka
- 📧 Contact : senitha02@gmail.com
- 📅 Date of Completion : 2025/03/03





