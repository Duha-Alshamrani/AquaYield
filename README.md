# AquaYield

we built this project to explore how machine learning can help farmers make smarter decisions about irrigation without wasting water or harming crops.

The model takes in environmental data like soil moisture, temperature, and humidity, and predicts three things at once: whether a crop needs irrigation, how efficiently water is being used, and whether the plant is under stress.

---

## What it does

- Should this crop be irrigated right now?
- Is water being used efficiently?
- Is the plant stressed?

---

## Results

| Target | Accuracy |
|--------|----------|
| Irrigation Decision | 98% |
| Water Efficiency | 100% |
| Plant Stress | 100% |

---

## Built with

$$\text{Python} \quad \text{Pandas} \quad \text{NumPy} \quad \text{Scikit-learn} \quad \text{Matplotlib} \quad \text{Seaborn}$$

---

## Model

The core of AquaYield is a \textbf{Multi-Output Random Forest} that predicts all three targets simultaneously. Given input features $\mathbf{x} = [\text{moisture, temp, humidity, soil, crop, stage}]$, the model outputs:

$$\hat{y} = f(\mathbf{x}) = (\hat{y}_{\text{irrigation}},\ \hat{y}_{\text{water efficiency}},\ \hat{y}_{\text{plant stress}})$$

---

## Dataset

Smart Agriculture Dataset from Kaggle — contains soil moisture, temperature, humidity, and crop data.

---

## How to run

1. Clone the repo
2. Run:
$$\texttt{pip install pandas numpy scikit-learn matplotlib seaborn kagglehub}$$
3. Open \texttt{projectAi.ipynb} and run all cells

---

## About me

I'm Dhuha, an AI student at Umm Al-Qura University. This was a team university project that I genuinely enjoyed working on.
