# titanic-eda

Python-based EDA on the Titanic dataset using Pandas, NumPy, Matplotlib, and Seaborn.

##  Insight Summary
- **Sex** -> Female passengers had a significantly higher survival rate compared to males.
- **Fare** -> Survival increased with higher fare, indicating wealthier passengers had better access to safety.
- **Pclass** -> 1st-class passengers survived the most; 3rd-class had the lowest survival rate.
- **Age** -> Children showed the highest survival after grouping ages into categories (supports "women and children first").
- **FamilySize** -> Most passengers were travelling alone; survival was lower for those alone compared to small families.

##  Engineered Features
- **Title** -> Extracted from names (e.g., Mr, Mrs) to capture social status.
- **FareGroup** -> Binned fare into categories to capture wealth tiers.
- **IsAlone** -> Flag indicating if passenger travelled alone.
- Features encoded using `LabelEncoder` where needed for modeling/readiness.

##  Files
- `titanic_eda.ipynb` -> Jupyter notebook containing the full EDA and visualizations.
- `Titanic-Dataset.csv` -> Raw dataset used for analysis.
- `README.md` -> This file.

##  Tools Used
Python -> Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook