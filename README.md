# DeltaCropNet: Advanced Time-Series Prediction of Rice Crop Yields

## 📖 Overview
DeltaCropNet is a deep learning-based framework designed for accurate prediction of rice crop yields in delta regions. By integrating time-series data on weather, NDVI (Normalized Difference Vegetation Index), and historical yield, the model employs Gated Recurrent Unit (GRU), Long Short-Term Memory (LSTM), and Simple Recurrent Neural Network (RNN) architectures to forecast future yields with high precision.

**Key Achievements:**
- **97.2% Accuracy** in Crop Yield Prediction
- Comparative analysis of GRU, LSTM, and RNN performances
- Integration of multi-source remote sensing and meteorological data

## 🏗️ Project Structure
The project is organized into three sequential phases, where the output of one phase serves as the input for the next:

- **Phase 1:** Weather Parameter Prediction
- **Phase 2:** NDVI Prediction using forecasted weather data
- **Phase 3:** Crop Yield & Production Prediction using forecasted weather and NDVI data
