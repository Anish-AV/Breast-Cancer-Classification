# Breast cancer prediction 

## Predicting if the cancer diagnosis is benign or malignant based on several observations/features
30 features are used, examples:

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry 
  - fractal dimension ("coastline approximation" - 1)
Datasets are linearly separable using all 30 input features

Number of Instances: 569
Class Distribution: 212 Malignant, 357 Benign
Target class:
   - Malignant
   - Benign


## Dataset
##### This dataset can be download from 
##### https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
## Model


### Support Vector Machine
```python
from sklearn.svm import SVC
```

## Libraries installation
scikit Learn
```bash
pip install scikit-learn
```
Seaborn 
```bash
pip install seaborn
```
Pandas
```bash
pip install pandas
```
Numpy
```bash
pip install numpy
```
## License
[MIT](https://choosealicense.com/licenses/mit/)

