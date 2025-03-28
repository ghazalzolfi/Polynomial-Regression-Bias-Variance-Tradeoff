# Polynomial Regression and Bias-Variance Tradeoff Analysis
This project explores the fundamental concepts of polynomial regression, bias-variance tradeoff, and model generalization within the framework of supervised machine learning. It involves generating synthetic polynomial datasets, fitting polynomial regression models of varying degrees, and analyzing how the complexity of the model impacts its performance.

## Project Activities:
- ### Synthetic Data Generation:
A custom dataset was created based on a polynomial function with degrees up to six, incorporating random noise to simulate realistic conditions. This synthetic dataset facilitates clear observation of the model’s behavior across different complexities.

- ### Dataset Splitting:
Data was systematically divided into three subsets:

Training Set: Used for fitting polynomial models.

In-Range Test Set: For assessing generalization within the known domain.

Out-of-Range Test Set: For evaluating the model’s extrapolation capability.

- ### Polynomial Model Training:
Polynomial regression models with degrees from 1 to 10 were trained. This extensive modeling allowed for rigorous exploration of underfitting, optimal fitting, and overfitting behaviors, crucial for illustrating the bias-variance tradeoff.

- ### Performance Evaluation and Visualization:
Models were evaluated using Mean Squared Error (MSE), Mean Absolute Percentage Error (MAPE), and R² scores. Results were graphically represented to vividly illustrate how model complexity impacts both training and test performances, enabling clear identification of the optimal polynomial degree.

- ### Bias-Variance Tradeoff Analysis:
Through detailed visual and numerical analysis, the project demonstrates the essential concept of balancing bias and variance to achieve optimal generalization. Polynomial degrees that minimized error while maintaining generalizability were highlighted and discussed.

## Libraries and Tools:
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn (Regression, Cross-validation, Metrics)
