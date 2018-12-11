# Precit the poverty of households in Costa Rica using automated feature engineering
<p style="margin:30px\">
    <img width=50% src="https://www.featuretools.com/wp-content/uploads/2017/12/FeatureLabs-Logo-Tangerine-800.png" alt="Featuretools" />
</p>

In this tutorial, we show how [Featuretools](https://www.featuretools.com) can be used to predict the poverty of household in Costa Rica using a [dataset](https://www.kaggle.com/c/costa-rican-household-poverty-prediction/data) from Kaggle.

*The Tutorial notebook from this repository exists [on Kaggle](https://www.kaggle.com/willkoehrsen/featuretools-for-good). If you would prefer to work in that environment, you can fork the existing kernel to use as a starting point.*

## Highlights

* We generate interesting aggregations by age and location automatically.
* We use a secondary time index to generate features from the no-show column without leaking invalid information.


## Notebook

Link to notebook: [Tutorial](Tutorial.ipynb)


## Running the tutorial
If you would like to work on Kaggle, the Tutorial notebook [has been uploaded](https://www.kaggle.com/sjrothsc/using-featuretools-for-missed-appointments) as a kernel. You can fork that notebook to use as a starting point. If you prefer to work locally:
1. Clone the repo

```
git clone https://github.com/Featuretools/predict-costa-rican-poverty.git
```

2. Install the requirements

```
pip install featuretools
pip install sklearn
pip install bokeh
```

3. Download the data

You can download the data from [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments) or create a kernel and use Featuretools there. After downloading, save the CSV to a directory called `data` in the root of this repository.


## Feature Labs
<a href="https://www.featurelabs.com/">
    <img src="http://www.featurelabs.com/wp-content/uploads/2017/12/logo.png" alt="Featuretools" />
</a>

Featuretools is an open source project created by [Feature Labs](https://www.featurelabs.com/). To see the other open source projects we're working on visit Feature Labs [Open Source](https://www.featurelabs.com/open). If building impactful data science pipelines is important to you or your business, please [get in touch](https://www.featurelabs.com/contact.html).

### Contact

Any questions can be directed to help@featurelabs.com
