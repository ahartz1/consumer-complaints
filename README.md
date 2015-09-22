# Analyzing Consumer Complaint Data

## Description

This IPython Notebook uses pandas to read and analyze data from the [CFPB Consumer Complaint
Database](http://www.consumerfinance.gov/complaintdatabase/). This database is
a collection of all complaints made by American consumers to the Consumer
Financial Protection Bureau.

## Normal Mode

Use Pandas to read in the included file, `complaints_dec_2014.csv`.

Calculate and chart:

* Number of complaints by product
* Number of complaints by company (top 10 companies only)
* Number of complaints by company response
* Mean number of complaints by day of week
* Any other insights you find interesting

Write up a summary of what you found from each chart you made.

<!-- ## Hard Mode

In addition to the requirements from **Normal Mode**:

* Combine the complaints data with US population by state data (find this
  yourself) and then chart the frequency of complaints by state per capita.
* Find statistically significant outliers of complaints by ZIP code. Look these
  up to see if there's a possible reason (military bases are often surrounded
  by predatory lending companies, for example.)

## Nightmare Mode

In addition to the requirements from **Hard Mode**:

* Take the frequency of complaints by state per capita and then make a chart
  of the US, with frequency of complaints matched to a scale of lighter color
  (low frequency) to darker color (high frequency), with a legend. -->

## To View This Notebook
Just click on the `consumer-complaints.ipynb` file above.

## To Run This Notebook
### System Requirements / Installation

* You will need to have **python&nbsp;3** installed on your machine. See [python's site](https://www.python.org/) for details.

* Clone this repo onto your machine.

* You will need to make sure that you have a virtual environment running in the folder that you intend to work from. [See this site for details if you're not familiar.](http://docs.python-guide.org/en/latest/dev/virtualenvs/) **Complete this step before attempting the below.**

* In your command-line program (such as Terminal on Mac&nbsp;OS&nbsp;X), navigate into the newly created repo. By default, this will be called `consumer-complaints`. Install the requirements file by runnning **`pip install -r requirements.txt`**.

#### Opening the Notebook
* Using a command-line program, navigate to the folder containing the downloaded file and run the following line: **`ipython notebook consumer-complaints.ipynb`**

* **Note:** This will open in a browser window and take over the command-line program's window until you close out of IPython Notebook. If you have closed your browser window, but your command line is still running the notebook, kill the process by pressing `Ctrl+C` or quitting the program entirely.

## Additional Resources

* [CFPB Consumer Complaint Database data and visualizations](http://www.consumerfinance.gov/complaintdatabase/)

* [US Census data](https://www.census.gov/popest/data/datasets.html) (Vintage 2014 State Population Datasets)

* [State Abbreviation csv](http://www.fonz.net/blog/archives/2008/04/06/csv-of-states-and-state-abbreviations/)

## Credit

The [Consumer Financial Protection Bureau](http://www.consumerfinance.gov/) is
pretty great! Thanks for making your data public.
