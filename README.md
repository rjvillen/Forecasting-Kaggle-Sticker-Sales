# Forcasting Sticker Sales Kaggle Competition

This repository contains our models for the "Forecasting Sticker Sales" Kaggle Competition. Here, the Machine Learning task is to forecast sticker sales in different countries (At Kaggle, they take stickers seriously!).

The repository is organized into 4 main notebook:

1. Dataset Exploration: Contains exploratory data analysis (EDA) for the original dataset. 
2. Feature Engineering: Transforms features into a more explanatory space, producing `transformed_features.csv`
3. Model training: Uses `transformed_features.csv` to try a variety of ML models.
4. Evaluation: Uses `results.csv` to analyse the errors of different models proposed.

The final model submitted as a final submission was a 0.65-0.35 ensemble model of Linear Regression and an auxiliar model that predicts the residuals, achieving the 32nd place (top 1%) in the private leaderboard.

![image](https://github.com/user-attachments/assets/62ae56a1-c2ec-4f2d-879e-6c7de0593d8e)

```bibtex
@misc{playground-series-s5e1,
    author = {Walter Reade and Elizabeth Park},
    title = {Forecasting Sticker Sales},
    year = {2025},
    howpublished = {\url{https://kaggle.com/competitions/playground-series-s5e1}},
    note = {Kaggle}
}
