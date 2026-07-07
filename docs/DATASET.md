Name : water_potability.csv
source : data->raw->water_potability.csv
Number of rows : 3276
Number of columns : 10
Target variable : portable
missing values : shulfate 781,ph 491, trihalomethanes 162


## Data Preprocessing

### Missing Values

- ph → Median
- Sulfate → Median
- Trihalomethanes → Median

### Scaling

StandardScaler

Reason:
To prevent features with larger numerical ranges from dominating distance-based algorithms.

Artifacts Generated

- water_potability_clean.csv
- standard_scaler.pkl