


# **California Housing Price Prediction using Linear Regression**

This project demonstrates an end-to-end machine learning pipeline for predicting California housing prices using **linear regression**, focusing on **multicollinearity reduction** and **performance enhancement** techniques. The project highlights how leveraging **Variance Inflation Factor (VIF)** and **outlier removal** significantly improved the model’s performance, making this a strong example of my data analysis and machine learning capabilities.

## **Key Highlights**

### **1. Multicollinearity Detection & Reduction**
By applying **Variance Inflation Factor (VIF)**, I identified and removed highly collinear features, which ensured that each remaining feature had a unique contribution to the model’s performance. Addressing multicollinearity led to a more stable and interpretable model.

- **VIF Analysis**: Through careful examination, I eliminated variables with high VIF scores, resulting in a more reliable model fit.

### **2. Impact of Outlier Removal**
A detailed outlier analysis helped identify data points that were skewing the model. Removing these outliers:
- **Before outlier removal**: The model's performance was inconsistent, with significant prediction errors.
- **After outlier removal**: The model’s **R-squared improved from 53% to 61.7%**, reflecting a more accurate fit and better predictive capabilities. This substantial increase underscores the importance of handling outliers in regression models.

### **3. Model Performance**
Key performance metrics after implementing **VIF-based feature selection** and **outlier removal**:
- **R-squared**: Increased from 53% to 61.7%, marking a significant improvement in the model's ability to explain the variance in housing prices.
- **Mean Squared Error (MSE)**: Reduced, reflecting better generalization and tighter predictions.

### **4. Data Visualization & Insights**
I used advanced data visualization techniques to explore relationships between features and target variables. These insights guided feature selection and model optimization, with key findings including:
- A strong positive correlation between **median income** and housing prices, reinforcing the importance of this feature in the prediction model.

---

## **Technical Skills Demonstrated**
- **Linear Regression**: Implemented using `scikit-learn` and `statsmodels` for building and interpreting regression models.
- **Variance Inflation Factor (VIF)**: Applied to detect multicollinearity, optimizing model performance.
- **Outlier Detection & Removal**: Enhanced model accuracy by removing influential outliers.
- **Data Visualization**: Used `seaborn` and `matplotlib` to generate insightful visualizations that informed decision-making.
- **Python Libraries**: Demonstrated expertise in `numpy`, `pandas`, `scikit-learn`, `statsmodels`, and `seaborn`.

---

## **Installation and Usage**

1. Clone the repository:
   ```
   git clone https://github.com/Isaac-Jim/California_Housing_Prediction.git
   ```
2. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter:
   ```
   jupyter notebook Linear_Regression.ipynb
   ```
4. Follow the workflow to preprocess data, visualize relationships, and train the linear regression model.



## **Concluding Remarks**
This project exemplifies how thoughtful data preprocessing, including multicollinearity reduction through **VIF** and targeted outlier removal, can significantly improve model performance. With an R-squared improvement from **53% to 61.7%**, this project showcases my ability to enhance model accuracy and apply machine learning techniques effectively. 

This work reflects my proficiency in data analysis, **model improvement**, and creating actionable insights—skills that are critical for success in **data science** and **machine learning roles**.

<img width="724" alt="Screenshot 2024-09-30 at 18 00 24" src="https://github.com/user-attachments/assets/e64c897b-14ca-437b-bba3-e7f7628b7145">
<img width="743" alt="Screenshot 2024-09-30 at 18 00 08" src="https://github.com/user-attachments/assets/6b5b6dc9-35bf-45d3-848c-1a37d24252de">
<img width="991" alt="Screenshot 2024-09-30 at 17 33 49" src="https://github.com/user-attachments/assets/ce52c595-6483-4e22-921d-641146902bae">
<img width="922" alt="Screenshot 2024-09-30 at 17 33 08" src="https://github.com/user-attachments/assets/cc688dcc-ebbb-410e-b14d-cd3a3571e3c8">
<img width="997" alt="Screenshot 2024-09-30 at 17 32 35" src="https://github.com/user-attachments/assets/96aa49d8-b7ac-44c0-a296-6fe4507e9a88">
<img width="1131" alt="Screenshot 2024-09-30 at 17 32 11" src="https://github.com/user-attachments/assets/dc810795-e4f1-4de9-ba4b-b6e7ed9efd38">
