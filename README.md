<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="300" alt="Skills Network Logo">
  </a>
</p>

# 💻 Hands-on Lab: Model Development Using Regression

**Estimated time to complete: 45 minutes**

This Jupyter-based lab helps you develop and evaluate various linear and polynomial regression models to predict laptop prices based on different features. The lab is designed for learners using **JupyterLite** or **local Jupyter environments**.

---

## 📌 Objectives

By the end of this lab, you will be able to:

- Apply Single Variable Linear Regression
- Apply Multiple Variable Linear Regression
- Fit Polynomial Regression models (1st, 3rd, and 5th degree)
- Create and use a regression pipeline with scaling and polynomial features
- Evaluate models using **R² score** and **Mean Squared Error (MSE)**

---

## 🧰 Libraries Used

This project utilizes the following Python libraries:

- [`pandas`](https://pandas.pydata.org/)
- [`numpy`](https://numpy.org/)
- [`matplotlib`](https://matplotlib.org/)
- [`seaborn`](https://seaborn.pydata.org/)
- [`scikit-learn`](https://scikit-learn.org/)

> Note: In **JupyterLite**, you may need to run this before importing seaborn:
```python
import piplite
await piplite.install('seaborn')
