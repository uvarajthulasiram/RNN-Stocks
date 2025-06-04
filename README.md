# RNN-Stock
This project applies Recurrent Neural Networks (RNN) to analyze and predict stock price trends over time. Developed as part of the Master's in Artificial Intelligence and Machine Learning program at IIIT Bangalore (via Upgrad).

## Model Architecture

The model was built with the following layers:

- RNN Layer (LSTM or GRU with tunable units)
- Dropout Layer for regularization
- Dense Output Layer with softmax activation (for classification)

Hyperparameters were tuned using `Keras Tuner` with `RandomSearch`, including:
- `rnn_units`
- `dropout_rate`
- `dense_units`
- `model_type` (LSTM/GRU)

---

## 🧪 Model Performance

After hyperparameter tuning and retraining the final model using the best configuration:

- ✅ **Test Accuracy**: 100%
- ✅ **Precision**: 1.00
- ✅ **Recall**: 1.00
- ✅ **F1-Score**: 1.00

All predictions were accurate for the test set. The model demonstrated exceptional performance.
