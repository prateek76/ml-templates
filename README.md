# ml-templates

Basic machine learning templates for regression and classification algorithms.  

## Getting Started
Use git clone https://github.com/prateek76/ml-templates.git to clone the repository into your local machine

## Prerequisites
If you already have a working installation of numpy and scipy, the easiest way to install scikit-learn is using pip

```
pip install -U scikit-learn
pip install pandas
pip install -U matplotlib
```
or conda:

```
conda install scikit-learn
conda install pandas
```

### Installing
* Change the path of dataset
```
df = pd.read_csv(PATH)

```
* select the rows required to make the model
```
X = dataset.iloc[:, m:n].values
y = dataset.iloc[:, 2].values
```
### change m:n to required number of columns( X is the feature set and y is the label )

* Use different Classes of scikit learn to make different models  
* change the label and title of the plot
* open terminal and execute the program by python3 filename.py

## Authors

* **Prateek** 
