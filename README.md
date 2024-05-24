# Appartment-Complex-Reccomendation-System

Using data mining to make a recommendation system for choosing an apartment complex to stay in for a new resident given a city

Used [this dataset](https://www.kaggle.com/code/iamsouravbanerjee/there-s-no-place-like-home/input) for our data analysis

### Requirements
- Python 3.8
- required PIP packages (can be installed by `python3 -m pip install numpy pandas sklearn tensorflow torch`)

### Data Cleaning and Transformation


### KNN Clustering and recommendation engine


### KMeans clustering and recommendation engine


### Linear Regressor Pricer
Used the **cleaned** housing_dataset.csv (the output of the cleaning script) as the input to our script
- Keep the housing_dataset.csv in the same folder as the script / Upload it to the Google Colab Python Notebook
- Run the script to get the R Squared score of the actual and predicted price of the test dataset.
- Price any arbitrary vector having the following attributes: `['availability', 'size', 'total_sqft', 'bath', 'balcony']`
- Eg: Add the following code at the end, after adding a test_housing_data.csv with vectors having the above attributes:
```py
test_dataset = pd.read_csv('test_housing_data.csv')
print(model.predict(test_dataset))
```
