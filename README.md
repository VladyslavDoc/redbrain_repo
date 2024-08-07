## redbrain_repo
# Description of pipeline in notebook

1. Tokenization texts.
2. Preprocessing categorical data.
3. Training XGBoost model.
   
# Loading weights

loaded_model = xgb.XGBClassifier()

### Load the model weights from the file
loaded_model.load_model('model_weights.json')

### Now you can use the loaded model
y_pred = loaded_model.predict(X_test)
