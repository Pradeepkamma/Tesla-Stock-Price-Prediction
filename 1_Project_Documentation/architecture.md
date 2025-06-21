# 🏗️ System Architecture

The architecture of our stock prediction model follows a structured, modular approach that ensures clarity, reusability, and performance.

### 📊 Data Flow:
1. **Input Layer**  
   - Dataset containing Open, High, Low, Volume, and Close values of Tesla stock.

2. **Preprocessing**  
   - Handle missing values, normalize features, and split data into training and testing sets.

3. **Model Training**  
   - A linear regression model is trained on the historical data.

4. **Prediction**  
   - The model predicts closing prices based on input features.

5. **Evaluation**  
   - Metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) are used.

6. **Visualization**  
   - Bar charts and line plots show actual vs predicted prices.

This modular design allows easy upgrades — such as switching to a different regression model or integrating sentiment data — without breaking the entire pipeline.

