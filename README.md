# A kaggle data analysis

## Running the notebook:

* The requirements are in `requirements.txt`
  * Install with `pip install -r requirements.txt`
  * NOTE: Python 3.6+ only
* The dataset is [the two sigma connect rental](https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries/data)
  * Download it with the [kaggle api](https://github.com/Kaggle/kaggle-api)


Run the following after activating your python environment: 
```bash
kaggle competitions download -c two-sigma-connect-rental-listing-inquiries

unzip two-sigma-connect-rental-listing-inquiries.zip
unzip train.json.zip
unzip test.json.zip
# unzip images_sample.zip

# Optionally remove zip files
rm *.zip
```

Files:
 * [exploratory-data-analysis.ipynb](exploratory-data-analysis.ipynb) - Data exploration notebook.
 * [XGboosting.ipynb](XGboosting.ipynb) - Data mining using various versions of XGboosting.
 * [Random Forest](Milestone3codeRandomForest.ipynb) - Data mining using random forests
