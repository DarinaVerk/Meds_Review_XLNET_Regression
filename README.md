### **Medical Drug Reviews Regression with XLNet**

---

#### **Overview**
This project, **Meds_Review_XLNET_Regression**, demonstrates a **text regression task** for analyzing **medical drug reviews** using a Jupyter Notebook. Built with the powerful **XLNet** transformer model, the project tackles a dataset of **161,297 reviews** to predict quantitative scores for drug effectiveness and user satisfaction. With a focus on transfer learning and performance optimization, the pipeline achieves:
- **MAE:** 0.93  
- **R² Score:** 0.77  

---

#### **Key Highlights**
- **Repository Name:** `DarinaVerk/Meds_Review_XLNET_Regression`
- **Dataset Size:** 161,297 drug reviews.  
- **Methodology:** Transfer Learning with XLNet in a Jupyter Notebook.  
- **Performance Metrics:**  
  - Mean Absolute Error (MAE): **0.93**  
  - R² Score: **0.77**

---

#### **Project Workflow**
1. **Data Preprocessing**
   - Cleaning and normalization of review texts (e.g., removing special characters and noise).
   - Handling missing values and outliers.

2. **Tokenization**
   - XLNet tokenizer for subword tokenization.
   - Padding and truncating reviews to match model input requirements.

3. **Model Training**
   - Fine-tuning pre-trained XLNet for regression.
   - Added a dense regression layer for predicting scores.

4. **Evaluation**
   - Metrics: MAE and R² for performance evaluation.
   - Visualization of predicted vs. actual scores.

---

#### **Usage**
1. Clone the repository:
   ```
   git clone https://github.com/darinaverk/Meds-Review-XLNET-Regression.git
   cd Meds_Review_XLNET_Regression
   ```

2. Open the Jupyter Notebook:
   ```
   jupyter notebook Meds_Review_XLNET_Regression.ipynb
   ```

3. Run the notebook cells to preprocess the data, train the model, and evaluate its performance.

---

#### **Why This Project?**
This project provides a practical approach to applying XLNet for regression tasks in natural language processing, showcasing:
- High-performance metrics.
- End-to-end implementation in a single, user-friendly Jupyter Notebook.
- Insights into medical reviews, with potential applications in healthcare analytics.

---
