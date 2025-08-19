# Drinkable Water Prediction 💧

This project uses **Machine Learning** and a **Streamlit dashboard** to determine whether water is safe for consumption based on key quality indicators.  
The model analyzes chemical and physical properties of water and classifies its potability with real-time results.

---

## 🔎 Parameters Considered

| Parameter          | Description                                |
|--------------------|--------------------------------------------|
| Hardness           | Calcium & Magnesium concentration          |
| Total Dissolved Solids | Overall dissolved salts (TDS) in water  |
| Chloramines        | Compound of chlorine & ammonia             |
| Sulfate            | Sulfate ion concentration                  |
| Conductivity       | Electrical conductivity of water           |
| Organic Carbon     | Presence of organic pollutants             |
| Trihalomethanes    | Byproducts of chlorination process          |
| Turbidity          | Water clarity and suspended particles      |

---

## ⚙️ Local Setup

```bash
# 1. Clone the repository
git clone https://github.com/Keer0423/drinkable-water-prediction.git
cd drinkable-water-prediction

# 2. Install Python dependencies
pip install -r requirements.txt

# 3. Launch the Streamlit app
streamlit run app.py
