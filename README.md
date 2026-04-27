🚦 Multimodal Traffic Congestion Prediction

This repository contains the implementation of a traffic congestion prediction system that integrates multiple data sources, including traffic, weather, and social media sentiment. The project explores both multimodal fusion and sequential modeling approaches to improve prediction performance.

📁 Repository Structure
.
├── Datasets/
├── data preprocessing/
├── Multimodal Fusion Model/
├── Sequential Pipeline Model/
📊 Datasets/

Contains all datasets used in the project, including:

Traffic data
Weather data
Social media (tweet) data
Processed and merged datasets for training
⚙️ data preprocessing/

Includes scripts for:

Data cleaning and normalization
Feature engineering
Sentiment extraction from text data
Final dataset construction for modeling
🧠 Multimodal Fusion Model/

Implements deep learning models that combine multiple data modalities:

LSTM for temporal traffic patterns
Neural networks for weather features
Transformer-based models (e.g., BERT) for text sentiment
Fusion strategies:
Feature concatenation
Attention-based fusion
🔄 Sequential Pipeline Model/

Implements a pipeline-based approach:

Text data processed using transformer models
Extracted features fed into a machine learning model (e.g., CatBoost)
