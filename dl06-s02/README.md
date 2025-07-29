 Final Project Analysis

 Part 1: Classical Perceptron for the AND Problem
-Objective: Evaluate the ability of a simple perceptron to solve the AND logic problem.
-Observation:Based on the decision boundary and model outputs, the perceptron successfully learned the correct behavior of the AND function.
-Reason for Success:The AND pattern is linearly separable, so a single-layer perceptron with a step activation function can effectively solve this problem.
-Key Insight:This model does **not** perform well on nonlinear patterns like XOR, highlighting the necessity of multilayer networks (MLPs) for more complex tasks.

---
Part 2: Machine Learning Model Analysis on Medical Dataset**
Objective:Compare multiple machine learning models for predicting mortality in patients with heart failure.

Conclusion:
- If the `classification_report` for **MLP with 200 neurons** yields the highest F1-score, it's likely the most suitable model for this task.
-F1-score is more important than accuracy in this context because medical data may be imbalanced and the cost of misclassification is high.
- Decision Trees offer fast performance but are less reliable for generalization unless carefully optimized.
- Logistic Regression is the simplest model, yet provides a strong baseline and performs respectably in many real-world scenarios.

---
